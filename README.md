# Chatbot com Assistente Virtual

Este projeto é um chatbot simples com assistente virtual, desenvolvido em HTML e JavaScript.
Ele utiliza a API `Phi-3-mini-4k-instruct` da Hugging Face para fornecer respostas inteligentes e amigáveis.
O design é simples, responsivo e oferece uma experiência de conversa fluida. Você pode experimentar aqui: igorbkz.github.io/chatbot/
## Recursos

- **Assistente Virtual Inteligente:** Responde perguntas e fornece informações úteis.
- **Interface Responsiva:** Design simples e responsivo para uma experiência agradável.
- **Histórico de Conversa:** Armazena mensagens previamente enviadas para contexto.

## Pré-requisitos

- Navegador Web moderno (Chrome, Firefox, Safari, etc.)
- Conta na [Hugging Face](https://huggingface.co/) com uma chave de API válida.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/igorbkz/chatbot.git
    ```
2. Abra o arquivo `index.html` em um navegador web.
3. Substitua a variável `API_KEY` em `index.html` pela sua chave de API da Hugging Face:
    ```javascript
    const API_KEY = 'sua-chave-aqui'; // Substitua pela sua chave de API real
    ```
4. Comece a conversar com o assistente virtual!

## Personalização

Você pode personalizar o projeto alterando:
- **Estilos:** Edite a seção `<style>` no arquivo `index.html`.
- **Parâmetros da API:** Ajuste a temperatura e outros parâmetros na variável `requestData` em `index.html`.

## Estrutura do Projeto

```
chatbot-assistente-virtual/
│
├── index.html   # Código HTML principal com toda a lógica do chatbot
└── README.md    # Este arquivo
```

## Sugestões e Melhorias

Sugestões e melhorias são bem-vindas! Por favor, abra uma [issue](https://github.com/igorbkz/chatbot/issues) ou envie um [pull request](https://github.com/igorbkz/chatbot/pulls).

## Licença

Este projeto está licenciado sob a licença MIT.
