# Dominguinhos — Site em HTML puro

Avaliação sobre o sanfoneiro pernambucano **Dominguinhos** (José Domingos de
Morais, 1941–2013), desenvolvido em **HTML5 semântico, sem nenhum CSS**.

Prova entregue em: **25/08/2026**.

## Estrutura de pastas

```
dominguinhos-site/
├── html/
│   ├── index.html      -> Página inicial: biografia do artista
│   ├── carreira.html   -> Carreira, parcerias e tabela de prêmios
│   └── legado.html     -> Legado, áudio ilustrativo e formulário de homenagem
├── img/
│   ├── cordel-dominguinhos.jpg   -> Capa de cordel sobre Dominguinhos (Jorge Henrique Vieira Santos)
│   └── dominguinhos-sanfona.webp -> Fotografia de Dominguinhos tocando sanfona
├── audio/
│   └── dominguinhos-sala-de-reboco.mp3 -> Gravação real de Dominguinhos, "Sala de Reboco"
├── video/               -> Pasta reservada, mantida vazia (nenhum vídeo é usado
│                           nesta entrega; o requisito de mídia foi cumprido com áudio local)
└── README.md
```

## Sobre o conteúdo

O site é dividido em três páginas, todas com o mesmo menu de navegação:

1. **Início (`index.html`)** — biografia de Dominguinhos: nascimento em Garanhuns
   (PE), infância com o trio "Os Três Pinguins", encontro com Luiz Gonzaga e
   falecimento.
2. **Carreira (`carreira.html`)** — trajetória artística, parcerias musicais
   (Anastácia, Nando Cordel, Gilberto Gil, Chico Buarque) e uma tabela com
   prêmios recebidos (Grammy Latino, Prêmio TIM, Prêmio Shell de Música).
3. **Legado (`legado.html`)** — um áudio instrumental ilustrativo (autoral,
   criado especialmente para este trabalho, já que não há autorização para uso
   de gravações originais), uma citação sobre HTML ouvida em aula, e um
   formulário para o visitante deixar sua homenagem.

## Sobre as imagens e o áudio

- `cordel-dominguinhos.jpg` — capa do cordel *"Dominguinhos: na sanfona, os
  acordes da inclusão"*, de Jorge Henrique Vieira Santos, usada em
  `index.html`.
- `dominguinhos-sanfona.webp` — fotografia de Dominguinhos tocando sanfona,
  usada em `carreira.html`.
- `dominguinhos-sala-de-reboco.mp3` — gravação real de Dominguinhos,
  "Sala de Reboco", usada em `legado.html`.

## Requisitos técnicos atendidos

- 3 páginas HTML com navegação fluida por menu presente em todas elas;
- Estrutura semântica completa: `header`, `nav`, `main`, `section`, `article`,
  `aside`, `footer` em todas as páginas;
- Tabela 3x3 com dados reais sobre prêmios, usando `colspan` em
  `carreira.html`;
- Formulário avançado em `legado.html`, com `type="date"`, `type="file"`,
  `type="range"`, `datalist`, `required` e `placeholder`;
- `details`/`summary` em mais de uma página;
- `figure`/`figcaption` em mais de uma página;
- Marcação avançada: `abbr`, `mark`, `del`, `ins`, `blockquote`, `cite`,
  `progress`, `meter`;
- Áudio local real (`audio/trecho-forro.mp3`) embutido com a tag `<audio>`;
- `<time datetime="2026-08-25">` na página inicial, com a data da prova;
- `<blockquote>` com uma frase sobre HTML ouvida do professor durante as
  aulas, em `legado.html`;
- Comentário HTML `<!-- -->` em `carreira.html` e `legado.html`, explicando
  dificuldades encontradas durante o desenvolvimento;
- Nenhum CSS: sem `style=`, `<style>`, `<center>`, `cellpadding` ou `align`.

## Como visualizar

Basta abrir `html/index.html` em qualquer navegador. Os links do menu levam
às demais páginas, e as imagens/áudio são carregados a partir das pastas
`img/` e `audio/` na raiz do projeto.
