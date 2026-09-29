# Constante Odontologia

Site institucional responsivo da Constante Odontologia, clínica odontológica em Divinópolis, MG.

## Tecnologias

- HTML5
- CSS3
- JavaScript, sem framework
- DM Sans, carregada do Google Fonts

O site é estático e não possui dependências de projeto nem `package.json`.

## Instalação

Não é necessário instalar dependências. Baixe ou clone o repositório e mantenha o `index.html` junto dos arquivos de mídia referenciados por ele.

## Desenvolvimento

Abra `index.html` no navegador. Para servir os arquivos por HTTP com Python instalado, execute nesta pasta:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Build

Não há etapa de build configurada. O próprio `index.html` e os arquivos de mídia formam a versão publicada.

## Estrutura

- `index.html` — conteúdo, estilos e JavaScript do site.
- `constante-logo.png` — logotipo usado na navegação e no rodapé.
- `clinic-procedimento.png` — imagem da seção da clínica.
- `dr-marcelo.jpeg` — retrato do profissional.
- `gallery-clinica.png`, `gallery-detalhe.png`, `gallery-experiencia.png` e `gallery-divinopolis.png` — imagens da galeria.
- `hero-video.mp4` — vídeo de fundo da abertura.

Os arquivos de mídia ficam na mesma pasta do HTML para preservar os caminhos relativos já usados pelo site. Não há componentes, rotas, utilitários ou hooks separados porque este projeto não usa framework.
