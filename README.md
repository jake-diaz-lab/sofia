# Página de Sofía 🎡

Página estática (un solo `index.html` + `assets/sofia.jpg`) publicada con GitHub Pages:
https://jake-diaz-lab.github.io/sofia/

## Editar y volver a publicar
1. Edita `index.html` (HTML/CSS/JS en el mismo archivo, sin build).
2. `git add -A && git commit -m "cambios" && git push origin main`
3. El workflow `.github/workflows/pages.yml` publica solo en 1–2 minutos (pestaña *Actions*).

## Bajar la página
- Solo desactivar Pages: `gh api -X DELETE repos/jake-diaz-lab/sofia/pages`
- Borrar todo (repo + página): `gh repo delete jake-diaz-lab/sofia --yes`
  (requiere el scope `delete_repo`: `gh auth refresh -s delete_repo`)
