BCNLayer3D - Sitemap externo para Google Search Console

Archivo incluido:
- bcnlayer3d-sitemap.xml

Objetivo:
Alojar este sitemap en un sitio web que controles (por ejemplo GitHub Pages),
verificar tanto BCNLayer3D como el sitio que aloja el sitemap en Google Search Console,
y enviar el sitemap desde la propiedad del sitio que lo aloja.

Pasos recomendados con GitHub Pages:
1. Crea un repositorio público, por ejemplo: bcnlayer3d-sitemap
2. Sube bcnlayer3d-sitemap.xml a la raíz del repositorio.
3. En GitHub: Settings > Pages > Deploy from a branch > main > /(root).
4. Espera a que GitHub Pages publique el sitio.
5. En Google Search Console añade como propiedad de prefijo de URL:
   https://TU_USUARIO.github.io/bcnlayer3d-sitemap/
6. Search Console te dará un archivo HTML de verificación.
   Súbelo también a la raíz del repositorio y espera a que Pages se actualice.
7. Verifica esa propiedad en Search Console.
8. Comprueba que la propiedad de BCNLayer3D sigue verificada:
   https://sites.google.com/view/bcnlayer3d/
9. En la propiedad de GitHub Pages, abre Sitemaps y envía:
   bcnlayer3d-sitemap.xml

Nota:
Un sitemap ayuda a Google a descubrir URLs, pero no garantiza que se indexen.
