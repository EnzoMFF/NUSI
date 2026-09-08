# Livreto do NUSI — UNIMONTES (versão em texto acessível)

Transcrição em HTML do livreto **NUSI (Núcleo de Sociedade Inclusiva) — Perspectivas de Acessibilidade e Inclusão no Ensino Superior**, com menu lateral fixo (Sumário) que leva direto a cada capítulo.

Projeto de **[seu nome]** e **EnzoMFF**.

## Arquivos

- `index.html` — a página principal: todo o texto do livreto, em HTML real, organizado por capítulo, com Sumário fixo e barra de acessibilidade.
- `livreto-nusi-unimontes.pdf` — o PDF original, no formato de impressão (livreto/spread). Disponível como download no topo da página.
- `livreto-nusi-leitura-online.pdf` — o mesmo conteúdo, com as páginas reorganizadas em ordem de leitura normal (1, 2, 3...), uma abaixo da outra, para quem preferir o PDF em vez do HTML.

## Por que HTML em vez de só o PDF

O PDF original foi exportado do InDesign como **imagem** (sem texto selecionável), então dentro dele Ctrl+F, VLibras e leitor de tela não funcionam. Por isso todo o conteúdo foi transcrito para HTML de verdade nesta página — o que garante:

- **Ctrl+F funciona** em qualquer navegador, em todo o texto da página.
- **VLibras funciona** e traduz o conteúdo para Libras, porque agora é texto real, não imagem.
- **Leitor de tela** consegue ler a página inteira, incluindo tabelas e listas.
- **Zoom de texto** (botões A−/A/A+ na barra de acessibilidade) e **alto contraste** funcionam em 100% do conteúdo.
- Botão **"Ouvir esta página"** lê o conteúdo em voz alta (usa a função de fala do próprio navegador).

Os dois PDFs continuam disponíveis para download, para quem quiser a versão visual/original do livreto (por exemplo, para imprimir).

## Recursos de acessibilidade incluídos

- Alto contraste (fundo preto / texto amarelo).
- Zoom de texto (A−, A, A+).
- Leitura em voz alta do conteúdo.
- Widget oficial **VLibras** (tradução para Libras).
- Sumário 100% navegável por teclado, com destaque automático da seção atual enquanto você rola a página.
- Skip link ("Pular para o conteúdo") para quem navega por teclado ou leitor de tela.

## Como publicar no GitHub Pages

1. Crie um repositório (ex.: `nusi-unimontes`) e adicione o **EnzoMFF** como colaborador em Settings → Collaborators.
2. Envie `index.html`, `livreto-nusi-unimontes.pdf` e `livreto-nusi-leitura-online.pdf` para a raiz do repositório.
3. Em Settings → Pages, selecione a branch `main` e a pasta `/(root)`.
4. O site fica em `https://SEU-USUARIO.github.io/nusi-unimontes/`.

> Os PDFs somados têm ~74 MB. Isso é normal para um repositório do GitHub (limite de 100 MB por arquivo), só deixa o clone/upload inicial um pouco mais lento.

## Ajustando o conteúdo

Todo o texto está direto no `index.html`, dividido em `<section>` (uma por capítulo, na mesma ordem do Sumário). Para corrigir ou completar algum trecho, procure pelo título do capítulo e edite o texto normalmente — é HTML puro, sem build nem dependências.

## Conferência de fidelidade

Este texto foi transcrito a partir das imagens do PDF original (o arquivo não tinha camada de texto para copiar diretamente). O conteúdo, os números de lei e os dados foram conferidos com cuidado, mas vale uma revisão final por alguém da equipe do NUSI antes de publicar oficialmente, especialmente números de lei, artigos e dados estatísticos.
