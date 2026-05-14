# Do Zero ao site no ar com Quarto - Apostila

**Material de apoio da Playlist - Café com R**  
**Autora:** Jennifer Luz Lopes


## Sobre este repositório

Este é o **repositório da apostila** da playlist **"Do Zero ao site no ar com Quarto"**, disponível gratuitamente no YouTube.
Apostila HTML: https://projetoportifolio-nor.netlify.app/

Aqui você encontra o arquivo `.qmd` da apostila, o CSS de estilo e todas as imagens utilizadas no material. É o repositório que você precisa clonar para acompanhar e renderizar a apostila localmente no RStudio.

> Este repositório contém exclusivamente o material de apoio desta playlist.  
> O repositório central com todos os projetos e códigos do canal está em:  
> [github.com/JenniferLopes/projetos_YouTube](https://github.com/JenniferLopes/projetos_YouTube)


## Estrutura do repositório

```
projeto1_portifolio/
├── apostila_quarto.qmd    ← apostila principal
├── estilo_book.css        ← estilo customizado
├── imgs/                  ← imagens utilizadas na apostila
├── _publish.yml           ← configuração de publicação
├── .gitignore
└── renv/                  ← ambiente R reproduzível
```


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


## Materiais desta playlist

| Material | Link |
|---|---|
| Apostila do Projeto | [projetoportifolio-nor.netlify.app](https://projetoportifolio-nor.netlify.app/) |
| Blog Café com R | [jenniferlopes.quarto.pub/portifolio](https://jenniferlopes.quarto.pub/portifolio/) |
| Canal YouTube | [youtube.com/@jennifercafecomr](https://www.youtube.com/@jennifercafecomr) |
| Cadastro para materiais | [cafecomr-conteudos.lovable.app](https://cafecomr-conteudos.lovable.app/) |


## Como usar este material

1. Clone este repositório
2. Abra o arquivo `projeto1_portifolio.Rproj` no RStudio
3. Certifique-se de ter R, RStudio e Quarto instalados
4. Renderize a apostila com o botão **Render** ou via terminal:

```bash
quarto render apostila_quarto.qmd
```

Para visualizar localmente antes de publicar:

```bash
quarto preview apostila_quarto.qmd
```



## Pré-requisitos

- [R](https://cran.r-project.org) - versão 4.1 ou superior
- [RStudio](https://posit.co/download/rstudio-desktop) ou [Positron](https://github.com/posit-dev/positron/releases)
- [Quarto CLI](https://quarto.org/docs/get-started) - versão 1.4 ou superior



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

*Todo o material é open-source e gratuito. Se este repositório foi útil para você, considere deixar uma estrela e compartilhar com outros profissionais.*
