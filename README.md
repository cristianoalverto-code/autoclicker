# BlackJack Esports

A responsive recruiting site for BlackJack Esports, an upcoming RLCS team looking for dedicated Rocket League players.

## Run locally

```bash
npm install
npm run dev
```

Open the local Vite URL shown in the terminal. Build the production bundle with `npm run build`.

## Speed AutoClicker for Windows

Run the desktop app during development with `npm run desktop:dev`. Create a Windows installer with `npm run dist:windows`; the setup executable is written to `release/Speed-AutoClicker-Setup-0.0.0.exe`.

The activation binding can be set to a keyboard key or either side mouse button (XButton1 / XButton2). Click rate, click button, timing, limits, and activation settings are saved on the current PC. Share the installer with another person; their settings are stored separately on their PC.

## Publish publicly

1. Upload this project to a GitHub repository. Do not upload `node_modules` or `dist`.
2. Import the repository at [vercel.com](https://vercel.com).
3. Use `npm run build` as the build command and `dist` as the output directory.
4. Deploy. Vercel will provide a public URL.
5. To use `blackjackesports.com`, add the domain in Vercel and follow the DNS records it provides.

Applications are delivered through FormSubmit to `cristianoalverto@gmail.com`. Confirm FormSubmit's activation email before testing submissions.
