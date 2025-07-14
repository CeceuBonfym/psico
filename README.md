<!-- 1. Dados Pessoais -->
    <div class="section">
        <h2 class="text-xl font-semibold mb-4">1. Dados Pessoais</h2>
        <div class="question">
            <label for="nome" class="block font-medium required">Nome completo:</label>
            <textarea id="nome" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="idade" class="block font-medium required">Idade:</label>
            <textarea id="idade" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="escolaridade" class="block font-medium required">Escolaridade (nível de ensino e anos de estudo):</label>
            <textarea id="escolaridade" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="profissao" class="block font-medium">Profissão atual ou anterior:</label>
            <textarea id="profissao" class="mt-1"></textarea>
        </div>
        <div class="question radio-group">
            <p class="font-medium required">Lateralidade:</p>
            <label><input type="radio" name="lateralidade" value="destro"> Destro</label>
            <label><input type="radio" name="lateralidade" value="canhoto"> Canhoto</label>
            <label><input type="radio" name="lateralidade" value="ambidestro"> Ambidestro</label>
        </div>
    </div>

    <!-- 2. Histórico Médico -->
    <div class="section">
        <h2 class="text-xl font-semibold mb-4">2. Histórico Médico</h2>
        <div class="question">
            <label for="diagnosticos" class="block font-medium">Diagnósticos médicos prévios (ex.: diabetes, hipertensão, epilepsia):</label>
            <textarea id="diagnosticos" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="medicacoes" class="block font-medium">Medicações em uso (nome, dose e frequência):</label>
            <textarea id="medicacoes" class="mt-1"></textarea>
        </div>
        <div class="question checkbox-group">
            <p class="font-medium">Histórico de traumas cranianos?</p>
            <label><input type="checkbox" name="trauma" value="sim"> Sim</label>
            <label><input type="checkbox" name="trauma" value="nao"> Não</label>
            <div class="question mt-2" id="trauma-detalhes" style="display: none;">
                <label for="trauma_detalhes" class="block font-medium">Se sim, descreva (quando, gravidade, sequelas):</label>
                <textarea id="trauma_detalhes" class="mt-1"></textarea>
            </div>
        </div>
        <div class="question">
            <label for="cirurgias" class="block font-medium">Cirurgias realizadas (incluindo neurológicas):</label>
            <textarea id="cirurgias" class="mt-1"></textarea>
        </div>
        <div class="question checkbox-group">
            <p class="font-medium">Histórico de doenças neurológicas ou psiquiátricas?</p>
            <label><input type="checkbox" name="doencas_neuro" value="sim"> Sim</label>
            <label><input type="checkbox" name="doencas_neuro" value="nao"> Não</label>
            <div class="question mt-2" id="doencas-neuro-detalhes" style="display: none;">
                <label for="doencas_neuro_detalhes" class="block font-medium">Se sim, descreva:</label>
                <textarea id="doencas_neuro_detalhes" class="mt-1"></textarea>
            </div>
        </div>
    </div>

    <!-- 3. Queixas Cognitivas -->
    <div class="section">
        <h2 class="text-xl font-semibold mb-4">3. Queixas Cognitivas</h2>
        <div class="question">
            <label for="memoria" class="block font-medium">Dificuldades de memória (ex.: esquecer nomes, eventos recentes):</label>
            <textarea id="memoria" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="atencao" class="block font-medium">Dificuldades de atenção ou concentração:</label>
            <textarea id="atencao" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="linguagem" class="block font-medium">Dificuldades de linguagem (ex.: encontrar palavras, compreensão):</label>
            <textarea id="linguagem" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="executiva" class="block font-medium">Dificuldades em funções executivas (ex.: planejamento, organização):</label>
            <textarea id="executiva" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="visuoespacial" class="block font-medium">Dificuldades visuoespaciais (ex.: orientação, reconhecimento de objetos):</label>
            <textarea id="visuoespacial" class="mt-1"></textarea>
        </div>
    </div>

    <!-- 4. Comportamento e Humor -->
    <div class="section">
        <h2 class="text-xl font-semibold mb-4">4. Comportamento e Humor</h2>
        <div class="question">
            <label for="humor" class="block font-medium">Alterações de humor (ex.: ansiedade, depressão, irritabilidade):</label>
            <textarea id="humor" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="comportamento" class="block font-medium">Alterações comportamentais (ex.: impulsividade, apatia):</label>
            <textarea id="comportamento" class="mt-1"></textarea>
        </div>
        <div class="question checkbox-group">
            <p class="font-medium">Mudanças recentes na personalidade?</p>
            <label><input type="checkbox" name="personalidade" value="sim"> Sim</label>
            <label><input type="checkbox" name="personalidade" value="nao"> Não</label>
            <div class="question mt-2" id="personalidade-detalhes" style="display: none;">
                <label for="personalidade_detalhes" class="block font-medium">Se sim, descreva:</label>
                <textarea id="personalidade_detalhes" class="mt-1"></textarea>
            </div>
        </div>
    </div>

    <!-- 5. Impacto Funcional -->
    <div class="section">
        <h2 class="text-xl font-semibold mb-4">5. Impacto Funcional</h2>
        <div class="question">
            <label for="atividades_diarias" class="block font-medium">Dificuldades em atividades diárias (ex.: cozinhar, gerenciar finanças):</label>
            <textarea id="atividades_diarias" class="mt-1"></textarea>
        </div>
        <div class="question">
            <label for="trabalho" class="block font-medium">Impacto no trabalho ou estudos:</label>
            <textarea id="trabalho"<iostream>
            <div class="question">
                <label for="social" class="block font-medium">Impacto nas relações sociais ou familiares:</label>
                <textarea id="social" class="mt-1"></textarea>
            </div>
            <div class="question">
                <label for="outros" class="block font-medium">Outras observações relevantes:</label>
                <textarea id="outros" class="mt-1"></textarea>
            </div>
        </div>

        <div class="no-print text-center mt-6">
            <button onclick="window.print()" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700 transition">Imprimir Questionário</button>
        </div>
    </div>

    <script>
        // Auto-resize textareas based on content
        function autoResizeTextarea(textarea) {
            textarea.style.height = 'auto';
            textarea.style.height = ${Math.max(textarea.scrollHeight, 80)}px;
        }

        document.querySelectorAll('textarea').forEach(textarea => {
            textarea.addEventListener('input', () => autoResizeTextarea(textarea));
            if (textarea.value) autoResizeTextarea(textarea);
        });

        // Checkbox group logic (exclusive selection)
        function handleCheckboxGroup(name, detailsId) {
            const checkboxes = document.querySelectorAll(input[name="${name}"]);
            const detailsSection = document.getElementById(detailsId);
            checkboxes.forEach(checkbox => {
                checkbox.addEventListener('change', function () {
                    if (this.checked) {
                        checkboxes.forEach(cb => {
                            if (cb !== this) cb.checked = false;
                        });
                        if (this.value === 'sim') {
                            detailsSection.style.display = 'block';
                        } else {
                            detailsSection.style.display = 'none';
                            const detailsTextarea = detailsSection.querySelector('textarea');
                            detailsTextarea.value = '';
                            autoResizeTextarea(detailsTextarea);
                        }
                    }
                });
            });
        }

        // Radio group logic
        document.querySelectorAll('.radio-group input[type="radio"]').forEach(radio => {
            radio.addEventListener('change', function () {
                const group = this.name;
                document.querySelectorAll(input[name="${group}"]).forEach(rb => {
                    if (rb !== this) rb.checked = false;
                });
            });
        });

        // Initialize checkbox groups with conditional details
        handleCheckboxGroup('trauma', 'trauma-detalhes');
        handleCheckboxGroup('doencas_neuro', 'doencas-neuro-detalhes');
        handleCheckboxGroup('personalidade', 'personalidade-detalhes');

        // Ensure proper textarea sizing on print
        window.addEventListener('beforeprint', () => {
            document.querySelectorAll('textarea').forEach(textarea => {
                textarea.style.height = 'auto';
                textarea.style.height = ${textarea.scrollHeight}px;
            });
        });
    </script>
</body>
