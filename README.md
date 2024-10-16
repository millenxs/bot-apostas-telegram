# Bot de Apostas para Telegram

Este projeto é um bot que monitora jogos de futebol ao vivo e envia informações sobre partidas em andamento para um canal do Telegram. O bot utiliza Selenium para navegar em uma página da web de scanner de futebol ao vivo e envia mensagens com base em determinados critérios de análise de jogo.

## Funcionalidades

- Acessa o site de scanner de futebol ao vivo.
- Monitora jogos em tempo real, capturando informações como tempo de jogo, placar, escanteios, cartões e outros detalhes relevantes.
- Envia atualizações para um grupo/canal do Telegram sempre que condições específicas de ataque e estatísticas de jogo são atendidas.

## Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Selenium**: Biblioteca usada para automatizar a interação com o navegador e coletar dados do site.
- **Jupyter Notebook**: Usado para executar e desenvolver o código.
- **Telegram Bot API**: Envia mensagens diretamente para um canal do Telegram utilizando a API de bots.
- **Firefox WebDriver**: Usado pelo Selenium para controlar o navegador Firefox.
- **WebDriver Manager**: Facilita a instalação e o gerenciamento do WebDriver do Firefox.

## Pré-requisitos

Antes de começar, certifique-se de ter os seguintes itens instalados:

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/install)
- [Selenium](https://pypi.org/project/selenium/)
- [WebDriver Manager](https://pypi.org/project/webdriver-manager/)
- Navegador Firefox

Você pode instalar as dependências necessárias executando o seguinte comando no terminal:

```bash
pip install selenium webdriver-manager
```
