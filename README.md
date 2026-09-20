# 🌿 Brunnin da Massa

Site informativo sobre cannabis medicinal — benefícios com respaldo científico, mitos x fatos, regulamentação no Brasil e um artigo completo com fontes citadas.

Feito em **HTML, CSS e JavaScript puros** (sem frameworks, sem build step), pronto para publicar no **GitHub Pages**.

## 🎨 Conceito de design

- **Paleta:** verdes botânicos (floresta, musgo, sálvia) + âmbar quente, usando psicologia das cores — verde transmite equilíbrio, crescimento e confiança; o âmbar traz clareza e calor humano aos pontos de ação.
- **Tipografia:** `Fraunces` (serifada, orgânica) nos títulos + `Work Sans` no corpo do texto, carregadas via Google Fonts.
- **Tom:** informativo e honesto — o conteúdo separa claramente o que a ciência já confirma do que ainda é promessa, com fontes reais linkadas.

## 📁 Estrutura de pastas

```
brunnin-da-massa/
├── index.html          → página inicial
├── artigo.html          → artigo completo sobre cannabis medicinal
├── css/
│   └── style.css        → todo o design do site (tokens de cor, tipografia, layout)
├── js/
│   └── script.js         → menu mobile, animações leves, botão "voltar ao topo"
├── assets/               → pasta reservada para imagens/ícones adicionais
├── README.md
└── .gitignore
```

## ✏️ Como participar / editar o conteúdo

Tudo é editável direto nos arquivos `.html` (texto) e `css/style.css` (visual):

- **Trocar cores:** edite as variáveis no topo de `css/style.css`, dentro de `:root { ... }` (ex.: `--forest`, `--amber`, `--sage`).
- **Trocar textos:** edite diretamente o HTML de `index.html` e `artigo.html` — o conteúdo está em português, em blocos fáceis de localizar (hero, benefícios, mitos, regulamentação, artigo).
- **Adicionar uma imagem real:** salve o arquivo em `assets/` e referencie com `<img src="assets/nome-do-arquivo.jpg" alt="descrição">`.
- **Adicionar uma nova seção:** copie um bloco `<section class="section ...">` existente em `index.html` e ajuste.

Não há processo de build — qualquer editor de texto (VS Code, por exemplo) e um navegador já bastam para ver o resultado (`abrir index.html`).

## 🚀 Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `brunnin-da-massa`).
2. No seu terminal, dentro desta pasta:

   ```bash
   git init
   git add .
   git commit -m "Primeira versão do site Brunnin da Massa"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/brunnin-da-massa.git
   git push -u origin main
   ```

3. No GitHub, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
5. Salve. Em alguns minutos o site estará no ar em:
   `https://SEU-USUARIO.github.io/brunnin-da-massa/`

Depois disso, qualquer novo `git add . && git commit -m "..." && git push` atualiza o site publicado automaticamente.

## ℹ️ Nota sobre o Lovable

Você mencionou o Lovable — vale um esclarecimento: o Lovable gera projetos em React/Vite, hospedados na infraestrutura dele. Como você pediu especificamente **HTML/CSS/JS puro, pronto para Git local e GitHub Pages**, optei por esse formato, que é 100% portátil e não depende de nenhuma plataforma paga. Se no futuro você quiser migrar para o Lovable, este mesmo conteúdo (textos, estrutura de seções, paleta de cores) serve como briefing pronto para colar lá.

## ⚠️ Aviso importante

Este site tem finalidade **informativa e educacional**. Não substitui consulta, diagnóstico ou prescrição médica. Toda pessoa interessada em tratamento com cannabis medicinal deve procurar orientação de um profissional de saúde habilitado.

[acesse brunnin da massa](https://mkl0pes.github.io/brunnin_da_massa/)