# Malacopa
Checklist de reglas para no ser el malacopa de la peda. HTML estático, sin build, funciona offline (PWA).
Los datos se guardan en el celular (localStorage).

## Probar local
    python3 -m http.server 8000

## Subir a Git
    git init && git add . && git commit -m "Malacopa"
    git branch -M main
    git remote add origin https://github.com/TU_USUARIO/malacopa.git
    git push -u origin main

## Cloudflare Pages
Workers & Pages → Create → Pages → Connect to Git → elige el repo.
Framework: None. Build command: (vacío). Output directory: /
