# pluralsight-js-dev-env
Pluralsight JS Development Environment setup

1. Select text editor prefarably with inbuilt terminal
2. create ".editorconfig" in project_root
3. create "package.json"
4. create "srcServer.js" in the project_root/buildScripts
  - development web server with express
  - sharing work in progress using localtunnel
5. script automation in "package.json"
  - concurrent command using "npm-run-all --parallel"
6. create ".barbelrc" in project_root for transpiling configuration
7. create "webpack.config.js" in project-root for bundling
  - configure "srcServer.js" to work with webpack
  - create inddex.js in src folder
  - use source-map to debug
8. create ".eslintrc.json" in project_root for linting ie enforce rules in project.


