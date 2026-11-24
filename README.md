# ChatGPT-Pro

ChatGPT-Pro is an advanced application that combines the power of ChatGPT and DALL.E. With this app, you have the flexibility to switch between ChatGPT versions. One of the standout features of ChatGPT-Pro is its ability to generate images using DALL.E.

## Android / installable app

This project is a Progressive Web App (PWA): deploy it to a site served over HTTPS, open the site in Chrome on Android, then choose **Install app** (or **Add to Home screen**) from the browser menu. It opens in a standalone app window. The chat needs an internet connection and a valid OpenAI API key; the interface shell is cached for reopening, but AI requests are not available offline.

For local development, run `npm install` and `npm run dev`. To test the production PWA locally, run `npm run build` and `npm run preview`; service worker registration is enabled only in production builds.

> Note: this creates an installable web app, not an APK. A native Android package would require a separate wrapper/build step (for example, Capacitor).

## One-Click Deploy

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/EyuCoder/chatgpt-clone)

### Deploy to Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/EyuCoder/chatgpt-clone&project-name=chatgpt-and-dalle&repo-name=chatgpt-clone)

_you can checkout the app [here](https://chatgpt.eyucoder.com/)_

> a demo of the App

<!-- https://user-images.githubusercontent.com/26358650/212903093-08c58f9b-25b5-440d-89e7-7a4b1f36df5a.mp4 -->
<img src="demo/demo.gif" width="800px" alt="android icon"/>

**Give it a ⭐ if you liked it 😜**

### Features

- [x] gpt 3.5 and 4
- [x] dall.e image generator
- [x] save chat to localstorage
- [x] chat context

## If you find this project helpful, you can buy me a coffee here

<a href="https://www.buymeacoffee.com/eyuel" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 150px !important;" /></a>

## install

```bash
npm install
```

## start app

```bash
npm run dev
```

**_Tech used_**

- openai API
- Langchain
- React with Vite
- TailwindCSS with DaisyUI
- react-icons
- react-markdown

## 📝 License © [Eyuel](https://linkedin.com/in/eyuel-daniel)

> This project is released under the Apache License 2.0 license. See [LICENSE](./LICENSE) for details.
