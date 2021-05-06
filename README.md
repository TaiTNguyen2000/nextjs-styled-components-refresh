# A Fix for NextJS and Styled-Components Refresh Issue
When using NextJS with Styled-Components, upon refreshing the page, Styled-Components isn't fetched before the page is rendered, you can fix this by following these steps:

1. Create .babelrc file in **root** folder
2. Create _document.js  file in **pages** folder
3. Install **babel-plugin-styled-components** as a DevDependency
*npm install babel-plugin-styled-components --save-dev*
