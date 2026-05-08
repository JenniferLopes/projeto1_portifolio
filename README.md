# Do Zero ao Blog no Ar com Quarto

**Material de apoio da Playlist — Café com R**  
**Autora:** Jennifer Luz Lopes

---

## Sobre este repositório

Este é o **repositório central** da playlist **"Do Zero ao Blog no Ar"**, disponível gratuitamente no YouTube.

Aqui você encontra todos os materiais, códigos e links dos projetos desenvolvidos ao longo da playlist. Conforme novos projetos forem publicados, este repositório será atualizado com os respectivos links e recursos.

> Repositório central de todos os projetos e códigos da playlist:  
> [github.com/JenniferLopes/projetos_YouTube](https://github.com/JenniferLopes/projetos_YouTube)

---

## O que você vai aprender

| Etapa | Conteúdo |
|---|---|
| V01 | Por que você precisa de um portfólio |
| V02 | Instalando R, RStudio e Quarto do zero |
| V03 | O que é o Quarto e os tipos de output |
| V04 | YAML: o cabeçalho que controla tudo |
| V05 | Chunks de código: opções essenciais |
| V06 | Markdown e formatação no Quarto |
| V07 | Temas e personalização visual |
| V08 | Criando o blog com Quarto |
| V09 | Posts e categorias |
| V10 | Personalizando navegação e aparência |
| V11 | Publicando no Quarto Pub |
| V12 | Publicando no Netlify |

---

## Materiais desta playlist

| Material | Link |
|---|---|
| Apostila do Projeto | [projetoportifolio-nor.netlify.app](https://projetoportifolio-nor.netlify.app/) |
| Blog Café com R | [jenniferlopes.quarto.pub/portifolio](https://jenniferlopes.quarto.pub/portifolio/) |
| Canal YouTube | [youtube.com/@jennifercafecomr](https://www.youtube.com/@jennifercafecomr) |
| Cadastro para materiais | [cafecomr-conteudos.lovable.app](https://cafecomr-conteudos.lovable.app/) |

---

## Estrutura do repositório

```
projetos_YouTube/
├── README.md                  ← você está aqui
├── playlist_01_blog_quarto/   ← materiais desta playlist
│   ├── apostila_quarto.qmd
│   ├── estilo_book.css
│   └── imgs/
└── playlist_02_primeiro_projeto/  ← em breve
```

---

## Como usar este material

1. Clone ou baixe o repositório
2. Abra o projeto no RStudio
3. Certifique-se de ter R, RStudio e Quarto instalados
4. Renderize o arquivo `apostila_quarto.qmd` com o botão **Render**

```bash
quarto render apostila_quarto.qmd
```

---

## Pré-requisitos

- [R](https://cran.r-project.org) — versão 4.1 ou superior
- [RStudio](https://posit.co/download/rstudio-desktop) ou [Positron](https://github.com/posit-dev/positron/releases)
- [Quarto CLI](https://quarto.org/docs/get-started) — versão 1.4 ou superior

---

## Sobre a autora

**Jennifer Luz Lopes**  
Doutora em Melhoramento Genético de Plantas pela UFPel. Analista de Dados SR na Suzano S.A. Consultora, instrutora e mentora em R. Criadora do Café com R e cofundadora da R-Ladies Goiânia.

| Canal | Link |
|---|---|
| Blog e portfólio | [jenniferlopes.quarto.pub/portifolio](https://jenniferlopes.quarto.pub/portifolio/) |
| YouTube | [youtube.com/@jennifercafecomr](https://www.youtube.com/@jennifercafecomr) |
| GitHub | [github.com/JenniferLopes](https://github.com/JenniferLopes) |
| LinkedIn | [linkedin.com/in/jennifer-luz-lopes](https://linkedin.com/in/jennifer-luz-lopes) |

---

<!-- BOTÕES HTML — funcionam no GitHub com suporte a HTML -->

<div style="display:flex; flex-direction:column; gap:12px; padding:1rem 0; max-width:420px;">

  <a href="https://jenniferlopes.quarto.pub/portifolio/" target="_blank" style="display:flex; align-items:center; gap:14px; background:#224573; padding:14px 22px; text-decoration:none; border-radius:8px;">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/></svg>
    <span style="font-size:15px; font-weight:600; color:#ffffff; flex:1;">Blog Café com R</span>
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
  </a>

  <a href="https://github.com/JenniferLopes" target="_blank" style="display:flex; align-items:center; gap:14px; background:#6B4F4F; padding:14px 22px; text-decoration:none; border-radius:8px;">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="#ffffff"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0 0 24 12c0-6.63-5.37-12-12-12z"/></svg>
    <span style="font-size:15px; font-weight:600; color:#ffffff; flex:1;">GitHub</span>
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
  </a>

  <a href="https://www.youtube.com/@jennifercafecomr" target="_blank" style="display:flex; align-items:center; gap:14px; background:#4A6FA5; padding:14px 22px; text-decoration:none; border-radius:8px;">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="#ffffff"><path d="M23.495 6.205a3.007 3.007 0 0 0-2.088-2.088c-1.87-.501-9.396-.501-9.396-.501s-7.507-.01-9.396.501A3.007 3.007 0 0 0 .527 6.205a31.247 31.247 0 0 0-.522 5.805 31.247 31.247 0 0 0 .522 5.783 3.007 3.007 0 0 0 2.088 2.088c1.868.502 9.396.502 9.396.502s7.506 0 9.396-.502a3.007 3.007 0 0 0 2.088-2.088 31.247 31.247 0 0 0 .5-5.783 31.247 31.247 0 0 0-.5-5.805zM9.609 15.601V8.408l6.264 3.602z"/></svg>
    <span style="font-size:15px; font-weight:600; color:#ffffff; flex:1;">YouTube</span>
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
  </a>

  <a href="https://projetoportifolio-nor.netlify.app/" target="_blank" style="display:flex; align-items:center; gap:14px; background:#2C7FB8; padding:14px 22px; text-decoration:none; border-radius:8px;">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/><polyline points="10 9 9 9 8 9"/></svg>
    <span style="font-size:15px; font-weight:600; color:#ffffff; flex:1;">Apostila do Projeto</span>
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/></svg>
  </a>

</div>

---

*Todo o material é open-source e gratuito. Se este repositório foi útil para você, considere deixar uma estrela e compartilhar com outros profissionais.*
