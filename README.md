# ShopDashboard-Exercise
這是一個練習 React 前端的網頁。  
參考影片：https://www.youtube.com/playlist?list=PLwHsNjmBZ-MJnVNyiaVYHW_dDA5n3mbVk

## Dev Evn：
- yarn v1.22.21
- react v18.2.0
- node.js v16.20.2
- tailwindcss v3.3.6

## Start Command
```
# first install packege
yarn
# Run Webs
yarn start
```

## Setting Dev Env
安裝 nvm 管理包：https://github.com/nvm-sh/nvm

安裝 yarn 管理包：`npm install --global yarn`

Env：使用 node.js : 16.20.2

安裝 [reactor router](https://reactrouter.com/en/main/start/tutorial) ：`yarn add -D react-router-dom`

1. 創建 React Project：
`npx create-react-app <project_name>`
2. 安裝 [tailwindcss](https://www.tailwindcss.cn/docs/installation)

    `yarn add -D tailwindcss`

3. 初始化 tailwindcss

    `npx tailwindcss init -p`

4. 設定 `tailwind.config.js`

    ```jsx
    /** @type {import('tailwindcss').Config} */
    module.exports = {
      content: [
        "./src/**/*.{js,jsx,ts,tsx}",
      ],
      theme: {
        extend: {},
      },
      plugins: [],
    }
    ```

5. (Option) 安裝 prettier

    `yarn add -D prettier`

6. (Option) 建立 `.prettierrc` 設定程式碼編寫時格式

    在最外層建立 prettier 設定檔 ：`.prettierrc`

    ```
    {
        "trailingComma": "none",
        "tabWidth": 4,
        "semi": false,
        "singleQuote": true,
        "bracketSpacing": true,
        "printWidth": 120
    }
    ```

7. 修改 project/src/index.css 添加

    ```jsx
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
