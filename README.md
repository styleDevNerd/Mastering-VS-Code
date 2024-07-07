# Mastering-VS-Code

## Section 1 : VSCode Shortcuts, Views and Emmets

1. **VSCode Cheatsheet**
    For detailed shortcuts refer to this [vscode-cheat-sheet-page](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf).
2. **Sidebar**
    - zoom in (cmd + + / cmd + -)
    - create files and folders
    - collapse folder in explorer
    - expoler -> right click -> move primary sidebar left and right
    - outlines
    - adding extensions
3. **Activity bar (the left most one)**
    - it has explorer (cmt+shift+E),  - hide sidebar (cmd + B)
    - search (cmt+shift+F)
    - git, debug(cmt+shift+D)
    - extensions (cmt+shift+X)
    - setup github profile
    - we can change the activity bar  extensions (fluent icons)
4. **Basic Shortcuts**
    - ctrl/cmd + c = copy
    - ctrl/cmd + v = paste
    - ctrl/cmd + x = cut
    - ctrl/cmd + z = cut
    - alt/option + up/down => to move something selected
    - ctrl + ` => open terminal

5. **Advanced Shortcuts**
    - command pallete -> cmd + shift + p => open setting.
    - access file -> cmd + p (handy when you are in zin mode which means can not see explorer)
    - remove breadcrumbs (file path at the top) (cmd/crl + , => enabale breadcrumb)
    - remove minimap (right side small map) (cmd/crl + , => enabale breadcrumb)
    - open zen mode => view -> apperance -> zen mode (cmd+k then z)
    - expanding and collapsing code
    - navigating - tab => cmd+shift+]/[ - cmd + p => try :linenumber => enter or ctrl + G (mac/windows) - cmd + p => try @title => enter
    - search and replace - Find (cmd + F) - Replace (cmd + H) - Alt+Enter Select all occurences of Find match - cmd + shift + H => paste the search value => replace with a text => replace all
    - text navigating shortcuts - option + right arrow => navigate one word to the right - option + left arrow => navigate one word to the left - cmd + right arrow => cursor to the end of the line - cmd + left arrow => cursor to the start of the line
    - multi cursor selection => option + select anywhere
6. **Emmets**

   > Emmet is a web-developer’s toolkit that can greatly improve your HTML & CSS workflow.

   Example : if you type `nav>li*3`

   It will be expand for you like this:

   ```html
   <nav>
     <li></li>
     <li></li>
     <li></li>
   </nav>
   ```

    - nested => hdr>nav>ul>li*4>a
    - h1{hello}*5
    - mn>sect>art.love>hdr>ul>(li>a)*3^^sect>h1{welcome}*2+p{lala}
    - css emmet: p1rem, m1rem, bgimg, bgc,c,df (display flex),dg (display grid), db, di

   For more shortcuts refer to this [emmet-cheat-sheet-page](https://docs.emmet.io/cheat-sheet/).

7. **Show/Hide**
    - cmd + shift + p => focus/hide activity bar
    - show and hide status bar

## Section 2 : General, HTML, CSS, JS, Theme-based Extensions

1. **Live Server**
   > Launch a development local Server with live reload feature for static & dynamic pages
2. **Live Preview**
   > An extension that hosts a local server for you to preview your web projects on!
3. **vscode-pets**
   > Puts a small, bored cat, an enthusiastic dog, a feisty snake, a rubber duck, or Clippy 📎 in your code editor to boost productivity.
4. **Prettier - Code formatter**
   > Prettier is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.
5. **Auto Rename Tag**
   > Auto rename paired HTML/XML tag
6. **HTML End Tag Labels**
   > Labels HTML end tags in VSCode
7. **indent-rainbow**
   > This extension colorizes the indentation in front of your text, alternating four different colors on each step.
8. **CodeSnap**
   > Take beautiful screenshots of your code in VS Code!
9. **CodeSnap-plus**
   > Take beautiful screenshots of your code in VS Code! And you can hightlight the line just by click.
10. **Image preview**
    > Shows image preview in the gutter and on hover
11. **GitHub Theme**
    > GitHub theme for VS Code with different styles
12. **Material Icon Theme**
    > Material Design Icons for Visual Studio
13. **Better Comments**
    > The Better Comments extension will help you create more human-friendly comments in your code.
14. **Excalidraw**
    > To draw or plan anything without leaving the VSCode
15. **Live Share**
    > Real-time collaborative development from the comfort of your favorite tools.

## Section 3 : Extensions Mainly for HTML & CSS

1. **Color Highlight**
    > This extension styles css/web colors found in your document.
2. **axe Accessibility Linter**
    > Check code files for common accessibility defects. Checks React (JSX), React Native, Angular, Vue, HTML, and Markdown.
3. **HTML to CSS autocompletion**
    > Provides completion suggestions for classes and ids from markup documents to stylesheets.
4. **BEM Helper**
    > Improve writing html using BEM naming conventions.
5. **CSS Flexbox Cheatsheet**
    > Open a flexbox cheatsheet directly in VS Code.
6. **CSS Navigation**
    > Allows Go to Definition from HTML to CSS / Sass / Less, provides Completion and Workspace Symbols for class & id name, and supports Find References from CSS to HTML.

## Section 4 : Extensions for JavaScript Developers

1. **JavaScript (ES6) code snippets**
    > This extension contains code snippets for JavaScript in ES6 syntax for Vs Code editor (supports both JavaScript and TypeScript).
2. **DOM Code Snippets**
    > This extension contains a set of code snippets for getting / creating DOM elements.
3. **Error Lens**
    > Improve highlighting of errors, warnings and other language diagnostics.
4. **ESLint**
    > Integrates ESLint JavaScript into VS Code.
5. **npm Intellisense**
    > Visual Studio Code plugin that autocompletes npm modules in import statements
6. **Import Cost**
    > This extension will display inline in the editor the size of the imported package.

## Section 5 : Extensions for API Testing

1. **REST Client**
    > REST Client allows you to send HTTP request and view the response in Visual Studio Code directly.
2. **Thunder Client**
    > Thunder Client is a lightweight Rest API Client Extension for VS Code.

## Section 6 : Extensions for Typescript and Markdown

1. **JSON to TS**
    > Convert JSON object to typescript interfaces
2. **Pretty TypeScript Errors**
    > Make TypeScript errors prettier and more human-readable in VSCode
3. **Markdown Preview Enhanced**
    > Markdown Preview Enhanced ported to vscode
4. **markdownlint**
    >Markdown linting and style checking for Visual Studio Code

## Section 7 : Extensions for Themes

1. **Fluent Icons**
    > Fluent product icons for Visual Studio Code
2. **Andromeda**
    > Dark theme with a taste of the universe
3. **Cyberpunk**
    > A crazy cyberpunk theme
4. **Pro hacker theme**
    > VS Code Theme made for pro hackers. But no really, simple black and green theme to make you feel like hacker while you wirte poor code.

## Section 8 : Extensions for React.js, Data Modelling and Git

1. **ES7 React/Redux/GraphQL/React-Native snippets**
    > This extension provides you JavaScript and React/Redux snippets in ES7 with Babel plugin features for VS Code
2. **ERD Editor**
    > Entity-Relationship Diagram Editor VSCode Extension
3. **Code Spell Checker**
    > A basic spell checker that works well with code and documents.
4. **DotENV**
    > Support for dotenv file syntax
5. **Git Graph**
    > View a Git Graph of your repository, and perform Git actions from the graph.
