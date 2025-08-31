# Site de Solicitação de Troca de Plantão

Este repositório contém um site estático simples para hospedar um formulário de solicitação de troca de plantão e uma página de perguntas frequentes (FAQ). O objetivo é permitir que os colaboradores enviem pedidos de troca sem necessidade de login e ao mesmo tempo disponibilizar informações úteis sobre o processo, em conformidade com a LGPD.

## Estrutura

- **index.html** – Página inicial. Apresenta o propósito do site, incorpora o formulário Google usado para solicitar a troca (substitua o `EXAMPLE_FORM_ID` pelo ID real do seu formulário) e fornece um breve aviso sobre coleta de dados.
- **faq.html** – Lista de perguntas frequentes e respostas relacionadas à troca de plantão.
- **privacy.html** – Política de privacidade simplificada, explicando como os dados são coletados, utilizados e protegidos.
- **README.md** – Este arquivo com instruções.

## Como usar

1. **Clone ou crie o repositório no GitHub**
   - Crie um novo repositório no GitHub com um nome apropriado (por exemplo, `troca-plantao-site`).
   - Clone o repositório em sua máquina local ou simplesmente faça upload dos arquivos presentes nesta pasta.

2. **Edite o link do formulário**
   - No arquivo `index.html`, substitua `EXAMPLE_FORM_ID` pelo ID do seu Google Form. O link de incorporação normalmente segue o formato:

        https://docs.google.com/forms/d/e/<ID_DO_FORMULÁRIO>/viewform?embedded=1

   - Para encontrar esse link, abra seu formulário no Google Forms, clique em **Enviar**, escolha o ícone de incorporação (`< >`) e copie o link do iframe.

3. **Commit e push**
   - Faça o commit das alterações e dê push para o GitHub:

        git add .
        git commit -m "Publicar site de troca de plantão"
        git push origin main

4. **Ativar o GitHub Pages**
   - No repositório, acesse **Settings → Pages**.
   - Em **Source**, selecione a branch (geralmente `main`) e a pasta `/ (root)` onde estão os arquivos. Salve as alterações.
   - O GitHub Pages gerará uma URL (por exemplo, `https://seu-usuario.github.io/nome-do-repositorio`) onde o site ficará disponível publicamente.

5. **Compartilhar o link**
   - Após a publicação, compartilhe a URL do GitHub Pages com a equipe. O formulário ficará integrado à página e não exigirá login para ser preenchido (desde que você tenha configurado o formulário para aceitar respostas de qualquer usuário).

## LGPD

Lembre-se de adaptar a política de privacidade conforme as necessidades de sua organização, descrevendo claramente como os dados serão coletados, usados e protegidos. É importante que os colaboradores sejam informados sobre seus direitos e que seja solicitado consentimento explícito para o processamento de seus dados.