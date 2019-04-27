# get-started-web-design

### system requirement
- NodeJS v10.15.3
- NPM 6.4.1
- Gulp cli v.3.9.1

### how to install
- [How to Install](https://nodejs.org/en/download/)
- npm i -g gulp@3.9.1

### start develop
- yarn or npm install
- gulp
- (open http://localhost:8080 in browser)

### how to add page
- add [login/what_ever].html in root directory

### how to include all bootstrap styles
- cd styles
- vi main.scss
- (comment like this)
```css
// @import "../node_modules/bootstrap/scss/utilities/flex";
// @import "../node_modules/bootstrap/scss/utilities/spacing";
// @import "../node_modules/bootstrap/scss/utilities/display";
// @import "../node_modules/bootstrap/scss/mixins/grid-framework";
// @import "../node_modules/bootstrap/scss/mixins/grid";
// @import "../node_modules/bootstrap/scss/grid";
@import '../node_modules/bootstrap/scss/bootstrap';
```
