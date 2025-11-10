# Site do Festival de Ciências (GitHub Pages)

Este pacote contém um arquivo `index.html` pronto para ser publicado no GitHub Pages.

## Publicar via interface web (sem Git)
1. Crie um repositório novo no GitHub (ex.: `festival-de-ciencias`), público.
2. Faça upload do arquivo `index.html` (arraste e solte na página do repositório).
3. Vá em **Settings → Pages**.
4. Em **Build and Deployment**, selecione **Source = Deploy from a branch**.
5. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
6. Aguarde alguns segundos e volte em **Settings → Pages** para copiar a URL gerada (algo como `https://seu-usuario.github.io/festival-de-ciencias/`).

## Publicar via Git (opcional)
```bash
git init
git add .
git commit -m "Publicar site"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/festival-de-ciencias.git
git push -u origin main
```
Depois ative o Pages em **Settings → Pages** como acima.
