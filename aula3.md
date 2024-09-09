# Aula 3 (22/08/2024) - Modelos LLM, Hugging Face e Ollama

Nesta aula, aprendemos sobre várias ferramentas e tecnologias que são fundamentais para o desenvolvimento moderno.

Primeiramente, discutimos o DuckDuckGo, um mecanismo de busca que prioriza a privacidade dos usuários. Diferente de outros mecanismos de busca, o DuckDuckGo não rastreia o histórico de pesquisa dos usuários, o que significa que ele não cria ou mantém perfis pessoais. Durante a aula, realizei uma pesquisa sobre a cantora Taylor Swift e encontrei uma notícia recente sobre o cancelamento de seus shows devido a um ataque terrorista.

Também instalamos o Python e a biblioteca Langchain, que permite realizar pesquisas automatizadas. Importamos códigos do script e testamos a integração com o DuckDuckGo. Além disso, o professor abordou o uso de ferramentas como Wikipedia e YouTube, que podem ser implementadas por meio de bibliotecas, ampliando as funcionalidades do DuckDuckGo.

A aula também incluiu uma introdução ao Docker, uma plataforma open source que facilita o empacotamento de aplicações dentro de containers. Com o Docker, é possível rodar uma aplicação em qualquer máquina que tenha essa tecnologia instalada. Isso torna o desenvolvimento mais ágil e independente da plataforma.

Falamos sobre o uso do Docker no Windows, especificamente com o WSL 2 (Windows Subsystem for Linux). O Docker, integrado ao WSL 2, melhora a configuração de ambientes de desenvolvimento no Windows, que historicamente é burocrática e tem desempenho inferior em algumas ferramentas. Com o Docker, podemos criar ambientes baseados em Unix de forma unificada e com maior desempenho. Optamos por utilizar o Docker Desktop com WSL2, que roda sobre a Virtual Machine Platform e se integra com o WSL2, sem a necessidade de adquirir a licença PRO do Windows 10/11. Entre as vantagens, destacam-se a ferramenta visual para administração do Docker, a instalação de extensões e a possibilidade de rodar clusters Kubernetes localmente. Contudo, ele pode consumir bastante memória, e, em algumas situações, é necessário reiniciar o Docker Desktop para que funcione corretamente.

Por fim, fizemos a instalação do Ubuntu como parte da configuração do ambiente de desenvolvimento. Também baixamos algumas ferramentas essenciais para o trabalho com LLMs (Large Language Models), como o LLM Studio, Anything LLM, e Ollama.