# Orders Automation

## Descrição

Esse projeto foi feito para automatizar o cadastro de pedidos de lentes Zeiss em uma plataforma de premiação. Utilizando webscraping, o script coleta os números de pedidos diretamente do site do fornecedor e os insere automaticamente em um segundo site, onde esses pedidos geram premiações. Assim, economizamos tempo e evitamos possíveis erros de inserção manual!

## Como Funciona

- **Coleta de Números de Pedidos**: O script faz webscraping no site do fornecedor para capturar os números dos pedidos de forma automática.
- **Cadastro dos Pedidos**: Em seguida, esses pedidos são cadastrados no site de premiação.
- **Automação de Ponta a Ponta**: Do início ao fim, o processo é todo automatizado, facilitando o cadastro em grande escala e reduzindo a carga de trabalho manual.

### Tecnologias Usadas

- **Python**: O coração do projeto.
- **Webscraping**:
  - `Selenium` para extração e inserção dos dados, tanto no site de pedidos como no site da premiação.

### Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/RenanBjj/Webscraping-Orders-Premiation.git
