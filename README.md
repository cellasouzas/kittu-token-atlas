# Atlas de Tokens Kittu

Referência dos design tokens do arquivo Figma **Kittu | Akad Design System** | coleções `theme`, `kittu`, `_primitives`, `_type` e `_values`.

🔗 **[Ver a página publicada](https://cellasouzas.github.io/kittu-token-atlas/)**

Página estática (`index.html`) gerada a partir do estado atual do arquivo Figma. Abra localmente no navegador ou publique via GitHub Pages (Settings → Pages → branch `main`, pasta `/`).

Sem processo de build, é um único arquivo HTML autocontido (CSS + JS inline, sem dependências além de fontes do Google Fonts).

## Usando o GitHub CLI (`gh`)

O jeito mais simples de clonar, atualizar e publicar este repositório é pelo [GitHub CLI](https://cli.github.com).

### Instalar

```bash
# Windows (winget)
winget install --id GitHub.cli

# macOS (Homebrew)
brew install gh

# Linux
# veja https://github.com/cli/cli/blob/trunk/docs/install_linux.md
```

### Autenticar

```bash
gh auth login --hostname github.com --git-protocol https --web
```

Isso abre o navegador pra você autorizar com a sua conta do GitHub. Depois de autenticado, o `git push`/`git pull` já funcionam sem pedir usuário e senha de novo (o `gh` configura o credential helper do git automaticamente).

### Clonar

```bash
gh repo clone cellasouzas/kittu-token-atlas
cd kittu-token-atlas
```

### Atualizar a página

Depois de editar o `index.html`:

```bash
git add index.html
git commit -m "Atualiza atlas de tokens"
git push
```

O GitHub Pages redeploya automaticamente a cada push na branch `main`.

### Comandos úteis

```bash
gh repo view cellasouzas/kittu-token-atlas --web   # abre o repo no navegador
gh auth status                                       # confirma se está logada e com qual conta
```
