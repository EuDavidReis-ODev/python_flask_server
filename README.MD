
# Projeto Python Flask Server

Este é um projeto Flask Server hospedado no GitHub, que oferece um servidor web Python utilizando a biblioteca Flask. O servidor oferece rotas básicas para renderizar páginas HTML e processar requisições POST e GET.

## Funcionalidades Principais

- **Roteamento de Páginas:** O servidor possui rotas definidas para renderizar páginas HTML e processar solicitações de acordo com o caminho da URL.
  
- **Renderização de Templates:** Utiliza a função `render_template` do Flask para renderizar modelos HTML dinâmicos, permitindo a passagem de parâmetros para os modelos.

- **Gestão de Requisições:** Capacidade de processar requisições tanto GET quanto POST.


## Estrutura do Projeto

O projeto está organizado de forma simples e intuitiva:

- **server.py:** O arquivo principal que contém a lógica do servidor Flask, incluindo a definição das rotas e a lógica de processamento das requisições.

- **templates/:** Diretório que contém os modelos HTML a serem renderizados pelo servidor.

## Uso

1. **Instalação das Dependências:**

```
    pip install Flask
```
2. **Execução do Servidor:**
```
    python server.py
```
3. **Acesso às Rotas:**

- **Página Inicial:** `http://localhost:5000/`
- **Rota de Saudação:** `http://localhost:5000/ola/` ou `http://localhost:5000/ola/<nome>`
- **Rota de Login:** `http://localhost:5000/logar`

## Como Contribuir

- Faça um fork do repositório.
- Clone o repositório forkado para sua máquina local.
- Implemente suas melhorias ou correções.
- Envie um pull request para revisão.

## Autor
    David Reis

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---
Este é um projeto inicial e pode ser expandido com mais funcionalidades e recursos conforme necessário. Qualquer contribuição é bem-vinda!
