<h1 align="center">
  <img alt="" title="logo" src="public/logo.svg" />
</h1>

<p>
  Shorts Summary é uma aplicação web para criar resumo de vídeos shorts do Youtube utilizando Inteligência Artificial para transcrever o conteúdo do vídeo e realizar o resumo do conteúdo.
</p>

## Construído com
- [Vite](https://vitejs.dev/)
- [express](https://expressjs.com/pt-br/)
- [Axios](https://axios-http.com/ptbr/docs/intro)
- [ytdl-core](https://github.com/fent/node-ytdl) -> Para baixar vídeos do Youtube.
- [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) -> Para converter .mp4 para .wav
- [node-wav](https://github.com/andreasgal/node-wav) -> Para manipular dados de áudio em formato WAV.
- [@xenova/transformers](https://github.com/xenova/transformers.js) -> Para usar os modelos de [IA's](https://huggingface.co/models?sort=trending&search=xenova).

## Primeiro Acesso

Clone o projeto

```bash
  git clone https://github.com/matheusfd3/shorts-summary.git
```

Entre no diretório do projeto

```bash
  cd shorts-summary
```

Instale as dependências

```bash
  npm install
```

Inicie o front-end

```bash
  npm run web
```

Inicie o servidor

```bash
  npm run server
```

## Screenshots
