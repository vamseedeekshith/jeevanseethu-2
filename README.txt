JeevanSetu GitHub Pages deployment fix

IMPORTANT: Upload index.html to the ROOT of the repository named jeevanseethu, on the branch and folder selected in Settings > Pages.

This index.html is the standalone JeevanSetu page. GitHub Pages serves index.html as the site homepage; if it is missing, visitors may see the README instead.

Steps:
1. Open https://github.com/vamseedeekshith/jeevanseethu
2. Add file > Upload files.
3. Upload index.html from this package into the repository root (not inside a subfolder).
4. Commit changes to main.
5. In Settings > Pages, ensure deployment source is main branch and /(root), or select the matching root folder if already configured.
6. Wait for the Pages deployment to finish, then open https://vamseedeekshith.github.io/jeevanseethu/ and hard-refresh with Ctrl+F5.

Note: This fixes the homepage entry-point issue. It does not by itself prove that live maps, GPS permissions, nearby facility lookup, or cross-device emergency synchronization work; those need separate testing. Cross-device synchronization requires a shared backend.
