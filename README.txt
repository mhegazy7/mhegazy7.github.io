ICDI website — GitHub Pages build

Upload the CONTENTS of this folder to the root of your repository:
  index.html
  support.js
  .nojekyll
  assets/   (whole folder, keep the name lowercase)

Repo Settings > Pages > Source: Deploy from a branch > main > / (root).
For the custom domain icdieg.com, add it under Settings > Pages > Custom domain,
then in GoDaddy DNS create:
  A    @  185.199.108.153
  A    @  185.199.109.153
  A    @  185.199.110.153
  A    @  185.199.111.153
  CNAME www  <your-github-username>.github.io
