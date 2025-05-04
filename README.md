#Daisy UI + Tailwind + Confetti Integration Demo

1. Created a new angular project with CSS
2. Added Tailwind 4 to Project
```bash
npm install tailwindcss @tailwindcss/postcss postcss --force
```
3. Create a `.postcssrc.json` and add following code to it
```bash
{
    "plugins": {
      "@tailwindcss/postcss": {}
    }
}
```
4. Install DaisyUI
```bash
npm i -D daisyui@latest
```
5. Install Confetti
```bash
npm i canvas-confetti @types/canvas-confetti
```