<html lang="pt-BR"> 

<head> 

    <meta charset="UTF-8"> 

    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 

    <title>Questionário Neuropsicológico</title> 

    <script src="https://cdn.tailwindcss.com"></script> 

    <style> 

        textarea { 

            resize: both; 

            min-height: 100px; 

            width: 100%; 

        } 

        .checkbox-group label { 

            margin-right: 1rem; 

        } 

        .section { 

            margin-bottom: 2rem; 

        } 

        .question { 

            margin-bottom: 1rem; 

        } 

    </style> 

</head> 

<body class="p-6 max-w-4xl mx-auto bg-gray-100"> 

    <h1 class="text-2xl font-bold text-center mb-6">Questionário para Coleta de Dados sobre o/a Avaliado(a)</h1> 

    <p class="mb-4"><strong>Instruções:</strong> Por favor, ao responder as perguntas, caso sejam abertas, escreva o máximo de informações, pois isso contribuirá para dados mais fidedignos do que está sendo investigado. Algumas perguntas podem parecer repetitivas, mas isso é intencional, pois uma pergunta mais fechada ou de marcar pode necessitar de mais detalhes, caso o respondente consiga se lembrar.</p> 

 

    <div class="section"> 

        <label class="block mb-2"><strong>Nome da pessoa que responde o questionário:</strong></label> 

        <input type="text" class="w-full p-2 border rounded" id="nome_responsavel"> 

        <label class="block mb-2 mt-4"><strong>Idade:</strong></label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="idade"> 

        <label class="block mb-2 mt-4"><strong>Grau de parentesco:</strong></label> 

        <input type="text" class="w-full p-2 border rounded" id="parentesco"> 

    </div> 

 

    <h2 class="text-xl font-semibold mb-4">1. Em relação à fase gestacional</h2> 

    <p class="mb-4">Quais condições da mãe durante a gravidez (o que você souber):</p> 

    <div class="question"> 

        <label class="block mb-2">a) 1 a 3 meses:</label> 

        <textarea class="p-2 border rounded" id="gestacao_1_3"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">b) 4 a 6 meses:</label> 

        <textarea class="p-2 border rounded" id="gestacao_4_6"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">c) 7 a 9 meses:</label> 

        <textarea class="p-2 border rounded" id="gestacao_7_9"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">a) Nasceu:</label> 

        <div class="checkbox-group"> 

            <label><input type="checkbox" id="nasceu_prematuro"> Prematuro</label> 

            <label><input type="checkbox" id="nasceu_termo"> A termo</label> 

            <label><input type="checkbox" id="nasceu_pos"> Pós-termo</label> 

        </div> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">b) Tipo de parto:</label> 

        <input type="text" class="w-full p-2 border rounded" id="tipo_parto"> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">c) Houve problemas associados ao nascimento (falta de O2, posição de parto, eclâmpsia, inércia, etc.) ou após o nascimento (precisou de O2, UTI, incubadora, etc.)?</label> 

        <textarea class="p-2 border rounded" id="problemas_nascimento"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">d) Coisas que aconteceram com a mãe durante a gestação (acidente, desnutrição, uso de álcool, cigarro, drogas, problemas emocionais/psicológicos)?</label> 

        <textarea class="p-2 border rounded" id="problemas_mae"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">e) Teve doenças, morbidades ou comorbidades durante a gravidez e amamentação?</label> 

        <textarea class="p-2 border rounded" id="doencas_gravidez"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">f) Fez uso de medicamentos durante a gravidez/amamentação? Se sim, quais?</label> 

        <textarea class="p-2 border rounded" id="medicamentos"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">g) Bebê mamou no peito?</label> 

        <input type="text" class="w-full p-2 border rounded" id="amamentacao"> 

    </div> 

 

    <h2 class="text-xl font-semibold mb-4">2. Em relação ao progresso do desenvolvimento</h2> 

    <p class="mb-4">(Caso se lembre):</p> 

    <div class="question"> 

        <label class="block mb-2">a) Com quantos meses começou a engatinhar?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="engatinhar"> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">b) Com quantos meses começou a balbuciar?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="balbuciar"> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">c) Com quantos meses começou a sentar?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="sentar"> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">d) Com quantos meses começou a sustentar a cabeça?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="sustentar_cabeca"> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">e) Marque com um X os itens abaixo (se tiver informações relevantes, acrescente na linha abaixo):</label> 

        <div class="checkbox-group"> 

            <p>Andar:</p> 

            <label><input type="checkbox" id="andar_precoce"> Precoce</label> 

            <label><input type="checkbox" id="andar_normal"> Normal</label> 

            <label><input type="checkbox" id="andar_atrasado"> Atrasado</label> 

        </div> 

        <div class="checkbox-group"> 

            <p>Linguagem (fala):</p> 

            <label><input type="checkbox" id="fala_precoce"> Precoce</label> 

            <label><input type="checkbox" id="fala_normal"> Normal</label> 

            <label><input type="checkbox" id="fala_atrasado"> Atrasado</label> 

        </div> 

        <div class="checkbox-group"> 

            <p>Treino para o banheiro:</p> 

            <label><input type="checkbox" id="banheiro_precoce"> Precoce</label> 

            <label><input type.Html 

 

            <label><input type="checkbox" id="banheiro_normal"> Normal</label> 

            <label><input type="checkbox" id="banheiro_atrasado"> Atrasado</label> 

        </div> 

        <div class="checkbox-group"> 

            <p>Proporção do desenvolvimento:</p> 

            <label><input type="checkbox" id="desenv_precoce"> Precoce</label> 

            <label><input type="checkbox" id="desenv_normal"> Normal</label> 

            <label><input type="checkbox" id="desenv_atrasado"> Atrasado</label> 

        </div> 

        <label class="block mb-2 mt-2">Informações adicionais:</label> 

        <textarea class="p-2 border rounded" id="desenv_adicional"></textarea> 

    </div> 

 

    <h3 class="text-lg font-semibold mb-4">Enquanto criança, passou por alguma dessas condições?</h3> 

    <p class="mb-4">(Preencher com "sim" ou "não", e caso tenha informações relevantes, acrescente na linha abaixo):</p> 

    <div class="question"> 

        <label class="block mb-2">Problema de atenção?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="atencao"> 

        <textarea class="p-2 border rounded mt-2" id="atencao_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Desajeitado/desastrado?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="desajeitado"> 

        <textarea class="p-2 border rounded mt-2" id="desajeitado_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Hiperatividade?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="hiperatividade"> 

        <textarea class="p-2 border rounded mt-2" id="hiperatividade_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Dificuldade de aprendizagem?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="aprendizagem"> 

        <textarea class="p-2 border rounded mt-2" id="aprendizagem_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Dificuldade na fala/discurso?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="fala_dificuldade"> 

        <textarea class="p-2 border rounded mt-2" id="fala_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Fraqueza muscular?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="fraqueza_muscular"> 

        <textarea class="p-2 border rounded mt-2" id="fraqueza_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Problemas auditivos?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="auditivos"> 

        <textarea class="p-2 border rounded mt-2" id="auditivos_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Infecções no ouvido, com que frequência?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="infeccoes_ouvido"> 

        <textarea class="p-2 border rounded mt-2" id="infeccoes_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Problemas visuais?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="visuais"> 

        <textarea class="p-2 border rounded mt-2" id="visuais_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Enurese noturna (fazer xixi na cama)?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="enurese"> 

        <textarea class="p-2 border rounded mt-2" id="enurese_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Estereotipias ou tiques (movimentos repetitivos com mãos, pés, corpo)?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="tiques"> 

        <textarea class="p-2 border rounded mt-2" id="tiques_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Dificuldade em brincar, com brinquedos ou outras crianças?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="brincar"> 

        <textarea class="p-2 border rounded mt-2" id="brincar_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Como descreveria o sono da criança?</label> 

        <textarea class="p-2 border rounded" id="sono"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">Como foi a introdução alimentar? Teve alguma dificuldade?</label> 

        <textarea class="p-2 border rounded" id="alimentacao"></textarea> 

    </div> 

 

    <h2 class="text-xl font-semibold mb-4">3. Em relação ao início da fase escolar</h2> 

    <div class="question"> 

        <label class="block mb-2">a) Com quantos anos foi para a escola/creche? E quando iniciou, já tinha algum conhecimento prévio (escrever, ler, contar)?</label> 

        <textarea class="p-2 border rounded" id="escola_idade"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">b) Já repetiu série? Se sim, quantas? E o motivo?</label> 

        <textarea class="p-2 border rounded" id="repetiu_serie"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">c) Apresentava dificuldade para completar as tarefas dentro de um tempo razoável?</label> 

        <textarea class="p-2 border rounded" id="tarefas_tempo"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">d) Dificuldade em realizar atividades por etapas, já que se perdia no meio delas?</label> 

        <textarea class="p-2 border rounded" id="atividades_etapas"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">e) Desorganizado mais que o esperado para a faixa etária?</label> 

        <textarea class="p-2 border rounded" id="desorganizado"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">f) Dificuldade para expressar o pensamento? Colocar ideias no papel, escrever textos?</label> 

        <textarea class="p-2 border rounded" id="expressar_pensamento"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">g) Dificuldade em seguir instruções? Ou parecer não entender o que os outros diziam?</label> 

        <textarea class="p-2 border rounded" id="seguir_instrucoes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">h) Dificuldade para ler? Ou compreender, interpretar o que está lendo?</label> 

        <textarea class="p-2 border rounded" id="leitura"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">i) Dificuldade com pronúncia de palavras? Ou de confundir frequentemente d e b, q e p?</label> 

        <textarea class="p-2 border rounded" id="pronuncia"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">j) Dificuldade em fazer contas de cabeça? Até as mais simples?</label> 

        <textarea class="p-2 border rounded" id="contas_cabeca"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">k) Dificuldade na área de exatas (matemática, raciocínio lógico)?</label> 

        <textarea class="p-2 border rounded" id="exatas"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">l) Dificuldade em distinguir esquerda e direita?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="esquerda_direita"> 

        <textarea class="p-2 border rounded mt-2" id="esquerda_direita_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">m) Como os professores descreviam a criança como aluno?</label> 

        <textarea class="p-2 border rounded" id="professores_descricao"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">n) Como descreveria o humor e personalidade da criança?</label> 

        <textarea class="p-2 border rounded" id="humor_personalidade"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">o) Teve dificuldade em fazer amigos?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="fazer_amigos"> 

        <textarea class="p-2 border rounded mt-2" id="fazer_amigos_detalhes"></textarea> 

    </div> 

 

    <h2 class="text-xl font-semibold mb-4">4. Em relação à sensibilidade sensorial</h2> 

    <p class="mb-4">(Se a resposta for sim, lembrar que os comportamentos devem ser manifestados a ponto de ocorrer sofrimento ou de interferir na qualidade de vida da criança, ou seja, uma queixa recorrente):</p> 

    <div class="question"> 

        <label class="block mb-2">a) Possui sensibilidade a luz?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="sensibilidade_luz"> 

        <textarea class="p-2 border rounded mt-2" id="sensibilidade_luz_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">b) Possui sensibilidade a sons/ruídos?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="sensibilidade_sons"> 

        <textarea class="p-2 border rounded mt-2" id="sensibilidade_sons_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">c) Possui sensibilidade na pele (toque, roupa, objeto)?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="sensibilidade_pele"> 

        <textarea class="p-2 border rounded mt-2" id="sensibilidade_pele_detalhes"></textarea> 

    </div> 

    <div class="question"> 

        <label class="block mb-2">d) Possui sensibilidade gustativa (seletividade alimentar)?</label> 

        <input type="text" class="w-1/4 p-2 border rounded" id="sensibilidade_gustativa"> 

        <textarea class="p-2 border rounded mt-2" id="sensibilidade_gustativa_detalhes"></textarea> 

    </div> 

 

    <button onclick="window.print()" class="mt-6 bg-blue-500 text-white p-2 rounded hover:bg-blue-600">Imprimir/Salvar como PDF</button> 

 

    <script> 

        // Ensure only one checkbox is selected per group 

        const checkboxGroups = [ 

            ['nasceu_prematuro', 'nasceu_termo', 'nasceu_pos'], 

            ['andar_precoce', 'andar_normal', 'andar_atrasado'], 

            ['fala_precoce', 'fala_normal', 'fala_atrasado'], 

            ['banheiro_precoce', 'banheiro_normal', 'banheiro_atrasado'], 

            ['desenv_precoce', 'desenv_normal', 'desenv_atrasado'] 

        ]; 

 

        checkboxGroups.forEach(group => { 

            group.forEach(id => { 

                document.getElementById(id).addEventListener('change', () => { 

                    if (document.getElementById(id).checked) { 

                        group.forEach(otherId => { 

                            if (otherId !== id) { 

                                document.getElementById(otherId).checked = false; 

                            } 

                        }); 

                    } 

                }); 

            }); 

        }); 

    </script> 

</body> 

</html> 

 
