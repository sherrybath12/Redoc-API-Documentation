# Redoc-API-Documentation

## Quick Start Guide ##

1. Build an Open API specification yaml file for your API collection.
   
2. Bundle the docs into a zero-dependency HTML file.
   ```javascript 
   npx redoc-cli bundle <path to open api spec file>
   ```
3. You shuould see the below message:
   Bundled successfully in: redoc-static.html
   
4. This will generate a single html file called redoc-static.html, which is a static, fully-functional version of your built documentation. 
  
5. You can rename it manually, or just run:
   ```javascript
   mv redoc-static.html index.html
   ```
6. The file generated in the previous step is all we need to publish our API Docs on GitHub Pages.🎉 
