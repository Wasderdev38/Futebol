[README.md](https://github.com/user-attachments/files/32964021/README.md)
# Tudo Sobre Futebol

Site informativo sobre futebol desenvolvido para o projeto da Unidade I de
HTML — disciplina de Desenvolvimento Front-End para Web (UNIPÊ), aula de
HTML Avançado.

## Sobre o projeto

O site reúne conteúdo sobre história, regras, posições, seleções, jogadores,
Copa do Mundo e curiosidades do futebol, aplicando os recursos de HTML5
vistos em sala de aula. **Não foi utilizado CSS nem JavaScript** — o foco é
100% estrutural, em HTML puro.

## Estrutura de pastas

```
futebol-tudo-sobre/
├── index.html          → página inicial (fora da pasta html/ para fácil acesso)
├── html/                → demais páginas do site
│   ├── historia.html
│   ├── regras.html
│   ├── posicoes.html
│   ├── selecoes.html
│   ├── jogadores.html
│   ├── copa-do-mundo.html
│   ├── curiosidades.html
│   ├── video.html
│   ├── galeria.html
│   ├── cadastro.html
│   ├── estatisticas.html
│   ├── contato.html
│   └── sobre.html
├── img/                 → imagens usadas no site
├── audio/                → arquivo de áudio (hino.mp3)
├── video/                → arquivo de vídeo (melhores-momentos.mp4)
└── README.md
```

Total de páginas HTML: **14** (mais de 10, conforme exigido).

## Requisitos atendidos

- **Tags semânticas** em todas as páginas: `header`, `nav`, `main`,
  `section`, `article`, `aside`, `footer`.
- **Áudio** com `controls` — página `sobre.html`.
- **Vídeo local** com `controls` — página `video.html`.
- **Figure + figcaption** — páginas `index.html`, `posicoes.html`,
  `selecoes.html`, `jogadores.html`, `copa-do-mundo.html`, `galeria.html`,
  `video.html`.
- **Formulário avançado** (`date`, `file`, `color`, `range`) — página
  `cadastro.html`.
- **Campos `required` e `placeholder`** — páginas `cadastro.html` e
  `contato.html`.
- **Datalist** — campo "Time do coração" na página `cadastro.html`.
- **Details e summary** — páginas `index.html`, `curiosidades.html` e
  `sobre.html`.
- **Marcação avançada de texto** (mais de 3 tags): `mark`, `del`/`ins`,
  `abbr`, `blockquote`, `progress`, `meter` — distribuídas entre as páginas
  `historia.html`, `regras.html`, `copa-do-mundo.html`,
  `curiosidades.html` e `estatisticas.html`.
- **Navegação fluida**: menu completo presente em todas as páginas,
  com links relativos entre `index.html` e a pasta `html/`.
- **Organização em pastas**: `html/`, `img/`, `audio/`, `video/`.

## Sobre os arquivos de mídia

As imagens em `img/` e os arquivos em `audio/` e `video/` desta entrega são
**placeholders gerados automaticamente** (imagens com cor sólida e texto
identificador, um tom de áudio e um vídeo de teste), apenas para que a
estrutura do projeto e as tags HTML funcionem corretamente ao abrir as
páginas no navegador. Recomenda-se substituí-los por fotos, um áudio e um
vídeo reais antes da entrega final, mantendo os mesmos nomes de arquivo
(ou atualizando os caminhos `src` correspondentes nos arquivos `.html`).

## Como visualizar

Basta abrir o arquivo `index.html` em qualquer navegador. A navegação entre
as páginas é feita inteiramente por links relativos, sem necessidade de
servidor.

## Autor

Projeto acadêmico — Desenvolvimento Front-End para Web — UNIPÊ.
Baseado no material do Prof. Israel Cunha (HTML Avançado).
