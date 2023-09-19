# CriativAI

Bem-vindo ao CriativAI, um aplicativo React alimentado por IA para geração de texto criativo a partir de prompts. Este repositório contém o código-fonte do aplicativo.

## Visão Geral

O CriativAI é uma ferramenta que combina a facilidade de uso do React com a potência da inteligência artificial. Com nosso aplicativo, você pode criar texto gerado automaticamente a partir de prompts, personalizando o nível de criatividade desejado.

## Principais Recursos

- Interface amigável construída com React.
- Integração com uma API de IA para geração de texto.
- Personalização da temperatura para controle da criatividade.
- Upload de vídeos para obter transcrições automáticas.

## Como Usar

1. Clone este repositório em sua máquina local.
2. Instale as dependências do projeto com `npm install`.
3. Execute o aplicativo com `npm start`.

Certifique-se de configurar corretamente a URL da API de IA no arquivo `App.js`.

## Configuração

Você pode configurar a URL da API de IA no arquivo `App.js`:

```javascript
const {
  input,
  setInput,
  handleInputChange,
  handleSubmit,
  completion,
  isLoading,
} = useCompletion({
  api: 'http://localhost:3333/ai/complete', // <--- Substitua pela URL da sua API
  // ...
});
