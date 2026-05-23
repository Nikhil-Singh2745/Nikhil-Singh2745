# i make things.

mostly because i'm bored, occasionally just to see if i can. i am absolutely not looking for work, so please don't reach out with job opportunities. 

i build whacky full-stack apps (usually unnecessarily over-engineered browser games using Next.js and TypeScript) and sometimes i write things from scratch in Go or C when i feel like punishing myself. Most of these are private because i don't want to manage issues or pull requests. 

---

## the things (they work, click the links)

### 📚 reading room 
* **what it is:** a blog. for text. i built this as a satire of the generic, template-cloned blog apps people build when they first learn web dev. except mine is violently over-engineered. there is no cms, no mdx, and no content pipeline. every single post is a hand-written react component. it has custom per-post color palettes, hard box shadows, a debug hud, and a 0.3° tilt on the html tag persisted in localstorage. why? because i could.
* **built with:** Next.js 16 (Turbopack), React 19, Tailwind CSS v4, Motion v12, TypeScript
* **link:** https://blog-nine-phi-25.vercel.app/
* **the only two articles worth reading on the internet right now:**
  * *i keep writing trpc for no reason:* where i figure out a reason anyway by calling trpc procedures from inside server actions via `createCaller`. nobody does this. i do.
  * *i don't backprop through softmax:* wrote an mlp in numpy. the textbook backward pass for the last layer is slow and numerically terrible. fixed it with two lines of basic algebra cancellation. 

### 🗄️ rawth (open source)
* **what it is:** a key-value database built entirely from scratch. it features a custom b+tree, a custom binary file format, a custom query language, and its own websocket server/web ui. zero external dependencies. no postgres, no sqlite, not even gorilla/websocket. it wasn't the wise choice, but that was entirely the point. 
* **built with:** Go
* **link:** https://rawth-production.up.railway.app/ *(stays up as long as my railway credits don't run out)*
* **Github link :** https://github.com/Nikhil-Singh2745/rawth

### 🏰 crypt (open source)
* **what it is:** a turn-based dungeon crawler that lives entirely on a server. no game engine, no js framework, no runtime. just one binary and ~1100 lines of pure code. the entire frontend is literally just a `<pre>` tag in a fake terminal window. every keypress triggers a `fetch()`, and every frame is a server-sent event. sessions are stored as a cookie pointing to a struct in a fixed-size array. if the server reboots, your character dies permanently. that's roguelike-correct. 
* **built with:** C & HTML (just a bit)
* **link:** https://crypt-f7ji.onrender.com/ 
* **note:** it is hosted on render's free tier. it *will* go down after 15 minutes of inactivity. you are going to have to stare at a blank screen for 15-20 seconds while the container wakes up. do not complain to me, it is not my fault. read the repository readme if you want to see the animations/gifs immediately.
* **Github link :** https://github.com/Nikhil-Singh2745/crypt *(Read the README, its there for a reason)*

### 🌐 threshold 
* **what it is:** a single-page webgl experience i built for a hackathon to see what would break first—the gpu, the browser, or me. the answer was me, twice. there is no game engine here. i used three.js for basic scene graph management, but the postprocessing pipeline, custom shaders, easing math, and audio scheduling are all completely handwritten. the entire application code is a stupidly small 9kb.
* **built with:** Three.js, WebGL, Vanilla JS
* **link:** [https://threshold-navy.vercel.app/](https://threshold-navy.vercel.app/)

### 🦖 dino supreme
* **what it is:** a satire of the chrome offline dinosaur game. the original game is supposed to be a low-effort distraction for when your internet dies. i decided to over-engineer it to an unnecessary degree just to see if i could keep the canvas performance stable while piling on useless features. 
* **built with:** Next.js, React, TypeScript, HTML5 Canvas API
* **link:** [https://dino-supreme.vercel.app/](https://dino-supreme.vercel.app/)

### 📦 ecopack select v2
* **what it is:** a 3D sustainable packaging configurator. this started as a basic college project, but i accidentally put way too much effort into it because i didn't know when to stop. it features a full blender-inspired ui and real-time eco-material visualization. one of my better three.js projects, even if it was for a grade.
* **built with:** React, Three.js, Tailwind CSS
* **link:** [https://ecopack-select-v2.vercel.app/](https://ecopack-select-v2.vercel.app/)

### 🧮 calculator
* **what it is:** a totally normal web calculator. it definitely does math, and definitely doesn't do anything weird when you start clicking the numbers. do not expect a standard grid; just click around and watch it break standard layout logic. 
* **built with:** Next.js, TypeScript, Tailwind CSS
* **link:** [https://calculator-khaki-eta-90.vercel.app/](https://calculator-khaki-eta-90.vercel.app/)
