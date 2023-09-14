# upload.ai - Criação de informações de vídeos com IA

Bem-vindo ao **upload.ai**, uma aplicação construída no NLW que utiliza TypeScript e Inteligência Artificial para transcrever vídeos automaticamente e criar o que você desejar. Com esta aplicação, você pode fazer o upload de vídeos em formato .mp4 e obter transcrições precisas em texto, economizando tempo e esforço.

## Tecnologias Utilizadas

- React
- Vite
- Node.js
- Fastify
- API da OpenAI
- shadcn-ui
- Web Assembly
- FFmpeg

## Como Funciona

1. Faça o upload de um vídeo no formato .mp4 para a aplicação.
2. A aplicação converterá o vídeo em um arquivo de áudio .mp3 usando Web Assembly e a biblioteca FFmpeg.
3. O arquivo de áudio é enviado para a API da OpenAI, que utiliza IA para transcrever o áudio.
4. Você pode selecionar um prompt para a IA criar um título ou descrição para o vídeo do YouTube.
5. O prompt é enviado juntamente com a transcrição para a IA, que cria o título ou descrição com base na transcrição gerada.

## Como Usar

1. Clone este repositório em sua máquina local.
2. Instale as dependências do projeto com `npm install`.
3. Configure suas credenciais da API da OpenAI no arquivo `.env`:

   ```env
   OPENAI_KEY=SuaChaveDaAPIAqui
   ```
4. Inicie o servidor com `npm start`.
5. Acesse a aplicação em `http://localhost:3000` em seu navegador.

## Contribuição
Contribuições são bem-vindas! Se você deseja melhorar ou adicionar recursos à aplicação, sinta-se à vontade para abrir uma issue ou enviar um pull request.
