# i make things.

mostly because i'm bored, occasionally just to see if i can. i am absolutely not looking for work, so please don't reach out with job opportunities. 

i build whacky full-stack apps (usually unnecessarily over-engineered browser games using Next.js and TypeScript) and sometimes i write things from scratch in Go or C when i feel like punishing myself. Most of these are private because i don't want to manage issues or pull requests. 

---

## the things (they work, click the links)

### 📚 reading room 
* **what it is:** a blog. for text. i built this as a satire of the generic, template-cloned blog apps people build when they first learn web dev. except mine is violently over-engineered. there is no cms, no mdx, and no content pipeline. every single post is a hand-written react component. it has custom per-post color palettes, hard box shadows, a debug hud, and a 0.3° tilt on the html tag persisted in localstorage. why? because i could.
* **built with:** Next.js 16 (Turbopack), React 19, Tailwind CSS v4, Motion v12, TypeScript
* **link:** [https://blog-nine-phi-25.vercel.app/]
* **the only two articles worth reading on the internet right now:**
  * *i keep writing trpc for no reason:* where i figure out a reason anyway by calling trpc procedures from inside server actions via `createCaller`. nobody does this. i do.
  * *i don't backprop through softmax:* wrote an mlp in numpy. the textbook backward pass for the last layer is slow and numerically terrible. fixed it with two lines of basic algebra cancellation. 

### 🗄️ rawth (open source)
* **what it is:** a key-value database built entirely from scratch. it features a custom b+tree, a custom binary file format, a custom query language, and its own websocket server/web ui. zero external dependencies. no postgres, no sqlite, not even gorilla/websocket. it wasn't the wise choice, but that was entirely the point. 
* **built with:** Go
* **link:** [https://rawth-production.up.railway.app/] *(stays up as long as my railway credits don't run out)*
* **Github link :** [https://github.com/Nikhil-Singh2745/rawth]

### 🏰 crypt (open source)
* **what it is:** a turn-based dungeon crawler that lives entirely on a server. no game engine, no js framework, no runtime. just one binary and ~1100 lines of pure code. the entire frontend is literally just a `<pre>` tag in a fake terminal window. every keypress triggers a `fetch()`, and every frame is a server-sent event. sessions are stored as a cookie pointing to a struct in a fixed-size array. if the server reboots, your character dies permanently. that's roguelike-correct. 
* **built with:** C & HTML (just a bit)
* **link:** [https://crypt-f7ji.onrender.com/] 
* **note:** it is hosted on render's free tier. it *will* go down after 15 minutes of inactivity. you are going to have to stare at a blank screen for 15-20 seconds while the container wakes up. do not complain to me, it is not my fault. read the repository readme if you want to see the animations/gifs immediately.
* **Github link :** [https://github.com/Nikhil-Singh2745/crypt] *(Read the README, its there for a reason)*
