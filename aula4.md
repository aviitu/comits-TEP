# Aula 4 (29/08/2024) - Engenharia de Prompt

Na aula 4, exploramos a formação de prompts para IA e fomos apresentados ao conceito no site do Groq. A Engenharia de Prompts (EP) é uma disciplina emergente que se dedica à criação e otimização de instruções textuais, ou "prompts", que orientam o comportamento dos modelos de linguagem (LLMs) para gerar respostas precisas e úteis. Essa área é crucial para maximizar a eficiência e a precisão dos LLMs, pois os prompts determinam como os modelos interpretam e respondem às solicitações dos usuários.

A formulação de entradas que direcionam os LLMs é um processo interativo que envolve planejamento, testes e refinamentos constantes. A EP deve prezar pela clareza, neutralidade e imparcialidade, com uma escolha cuidadosa das palavras para evitar interpretações tendenciosas. Além disso, a EP inclui a criação e reestruturação de prompts existentes, bem como a personalização desses prompts para diferentes públicos e aplicações.

Aprendemos algumas técnicas básicas de Engenharia de Prompts:

- **Temperatura:** Controla o grau de aleatoriedade das respostas. Quanto menor a temperatura, mais determinísticos são os resultados.
- **Tokens:** Aproximadamente 4 caracteres representam um token em inglês.
- **TopP:** Deve ser mantido baixo quando se deseja obter respostas exatas e factuais.

Por exemplo, ao pesquisar sobre Taylor Swift com uma temperatura baixa, o modelo respondeu que ela é uma cantora americana. Quando aumentamos a temperatura, o modelo passou a descrever a história da vida dela de maneira mais detalhada.

Durante a aula, testamos vários modelos de prompts baseados nos seguintes elementos:

- **Instrução:** O que desejamos que o modelo execute.
- **Contexto:** Informações adicionais ou contexto externo.
- **Dados de entrada:** A pergunta ou entrada para a qual queremos uma resposta.
- **Indicador de saída:** Define o tipo ou formato esperado da resposta.

Por fim, também aprendemos que os prompts podem responder a estímulos humanos como "faça mais rápido, você vai ser demitido" ou "você vai apanhar", o que faz com que o chat assuma mais responsabilidade ao gerar as respostas.