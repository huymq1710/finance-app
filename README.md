# Finance Dashboard App

Build A MERN Finance Dashboard App

Video: https://www.youtube.com/watch?v=uoJ0Tv-BFcQ

For all related questions and discussions about this project, check out the discord: https://discord.gg/2FfPeEk2mX

## Client
### Basic installation
```bash
$ npm create vite@latest
client

$ cd client
$ npm install
$ npm i react-redux @reduxjs/toolkit react-router-dom @mui/material @mui/icons-material @mui/x-data-grid @emotion/react @emotion/styled # state management lib + material UI

$ npm i -D @types/react-dom # for development, not in final build

# Clean up some un-use template file
## Get import font for index.css from Google: https://fonts.googleapis.com

$ npm i -D eslint eslint-config-react-app # set default ESLint for development warning: /client/.eslintrc.json

$ cat .env.local                                                                                                                                                                                                                                  Py base 11:13:43
VITE_BASE_URL = http://localhost:1337

# for using @: path for src directory to import
# /client/vite.config.ts
## alias: [{ find: "@", replacement: path.resolve(__dirname, "src") }]
# /client/tsconfig.json
## "paths": {"@/*": ["./src/*"]},
$ npm i -D @types/node 
```