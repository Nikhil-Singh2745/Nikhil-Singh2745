<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=69f58e&height=90&section=header">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=454BFF&height=90&section=header">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=21262d&height=90&section=header" width="100%" />
</picture>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=32&duration=4000&pause=2000&color=a855f7&vCenter=true&center=true&width=600&lines=I+build+things.;Usually+closer+to+the+metal.;to+answer+a+question+nobody+asked.">
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=32&duration=4000&pause=2000&color=a855f7&vCenter=true&center=true&width=600&lines=I+build+things.;Usually+closer+to+the+metal.;to+answer+a+question+nobody+asked.">
    <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=32&duration=4000&pause=2000&color=F8FAFC&vCenter=true&center=true&width=600&lines=I+build+things.;Usually+closer+to+the+metal.;to+answer+a+question+nobody+asked." alt="Typing Banner" />
  </picture>
  
  <p><b>I build whacky full-stack apps, WebGL experiences, and low-level software.</b></p>
  <p>I focus on pushing the browser to its absolute limits, or breaking away from frameworks entirely to write things from scratch in C or Go or Rust when I feel like punishing myself. Not looking for work.</p>

  <br>

  <img src="https://skillicons.dev/icons?i=c,cpp,go,rust,php,js,react,nextjs,laravel,vue&theme=dark" alt="Tech stack" />
</div>

<br>

## ─── ✦ Coredump ───

<div align="center">
  <br>
  <i>Documenting the exact mechanisms by which systems programming silently punishes optimism.</i>
  <br><br>
</div>

* 🧠 **[a personal search engine on the Neural Engine](https://nikhil-singh2745.github.io/dumps/003-local-semantic-search-ane/)** — Forcing unused Apple Silicon to do semantic text vectorization, mostly because the hardware was just sitting there.
* ⏱️ **[the userspace spinlock is a bet against the scheduler](https://nikhil-singh2745.github.io/dumps/002-userspace-spinlock-scheduler-bet/)** — A 128× performance cliff decided entirely by whether you actually own the core. 
* 💥 **[the bimodal cost of `std::vector` reallocation](https://nikhil-singh2745.github.io/dumps/001-bimodal-vector-reallocation/)** — How forgetting a single `noexcept` keyword triggers a 40× slowdown on memory reallocation.

<br>

## ─── ✦ Featured Experiments ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>📚 Reading Room</h3>
      <p>A violently over-engineered blog, now permanently abandoned because maintaining it was a nightmare. Built as a satire of generic templates, there is no CMS and no MDX, every post is a handwritten React component with custom per-post palettes and a 0.3° HTML layout tilt. It became so weirdly exhausting to write a simple post that I just stopped. A fitting monument to why I moved on from full-stack and MLOps.</p>
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
      <br><br>
      <a href="https://blog-nine-phi-25.vercel.app/"><b>[ Live Site ]</b></a> • 
      <a href="https://blog-nine-phi-25.vercel.app/posts/trpc-for-no-reason">Read: <i>I keep writing tRPC for no reason</i></a>
    </td>
    <td width="50%" valign="top">
      <h3>🛸 Cyber-City</h3>
      <p>An infinite cyberpunk drone-flying game. Pilot through a procedurally generated neon metropolis. Features a brutal "Deathwish Mode" where speed is permanently locked at maximum and buildings collapse directly into your flight path.</p>
      <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" />
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <br><br>
      <a href="https://cyber-city-blush.vercel.app/"><b>[ Play Game ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏰 Crypt</h3>
      <p>A turn-based dungeon crawler living entirely on a server. No game engine, no JS framework. The frontend is literally a <code>&lt;pre&gt;</code> tag in a fake terminal. Every keypress is a fetch(). If the server reboots, you die permanently. Roguelike-correct.</p>
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
      <br><br>
      <a href="https://crypt-f7ji.onrender.com/"><b>[ Enter Dungeon ]</b></a> • 
      <a href="https://github.com/Nikhil-Singh2745/crypt"><b>[ Source & Gifs ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🗄️ Rawth</h3>
      <p>A key-value database built entirely from scratch. Features a custom B+Tree, custom binary file format, query language, and its own WebSocket server. Zero external dependencies. No Postgres, no SQLite. Not the wise choice, but that was the point.</p>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/rawth"><b>[ Source Code ]</b></a>
    </td>
  </tr>
</table>

<br>

## ─── ✦ Latency Chasing & Quant-Adjacent Systems ───
<div align="center">
  <br>
  <i>Building pre-built infrastructure catering to HFT spaces or multi-strategy quantitative funds like D.E. Shaw. Where microseconds are a personal insult.</i>
  <br><br>
</div>

<table width="100%">
  <tr>
    <td width="100%" valign="top">
      <h3>⚡ NanoMQ</h3>
      <p>A lock-free SPSC inter-process message queue operating over POSIX shared memory (<code>shm_open</code>/<code>mmap</code>), written entirely from scratch in C++20. It completely evicts the operating system kernel from the messaging hot path—zero syscalls, zero locks, and absolutely no data copying beyond the slot write.</p>
      <p>Features explicit cache-line isolation to eliminate false sharing, strict acquire/release memory ordering (where <code>seq_cst</code> is legally banned to prevent pointless fences), and inline <code>rdtsc</code> instruction monitoring. </p>
      <img src="https://img.shields.io/badge/C%2B%2B-20-blue.svg?style=for-the-badge&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/Memory_Ordering-Acquire%2FRelease-orange?style=for-the-badge" />
      <img src="https://img.shields.io/badge/Min_Latency-44_ns-brightgreen?style=for-the-badge" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/nanomq"><b>[ Source Code & Architecture ]</b></a>
    </td>
  </tr>
</table>

<br>

## ─── ✦ The WebGL and Canvas Sandbox ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Threshold</h3>
      <p>A single-page WebGL experience built to see what would break first: the GPU, the browser, or me. Zero abstractions beyond Three.js scene graphs. Shaders and audio math are handwritten. The application logic is a microscopic 9kb.</p>
      <a href="https://threshold-navy.vercel.app/"><b>[ Launch Experience ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>✂️ Offcut</h3>
      <p>A premium design portfolio for a studio that does not exist. Pure vanilla HTML, CSS, and JS pushed past sanity. Features zero libraries, an interactive paint canvas for scribbling virtual ink, and client case studies where the copywriter clearly gave up halfway through. Hand-rolled in less than 24 hours because I didn't want to invest actual time into it.</p>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <br><br>
      <a href="https://offcut-chi.vercel.app/"><b>[ Visit Studio ]</b></a> • <a href="https://github.com/Nikhil-Singh2745/offcut"><b>[ Source Code ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🚀 Deadframe</h3>
      <p>A fast-paced 2D space shooter with a roguelite perk system. Bypassed standard game engines entirely to build a custom rendering loop from scratch using the raw HTML5 Canvas API.</p>
      <a href="https://deadframe.vercel.app/"><b>[ Play Game ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>📦 Ecopack Select v2</h3>
      <p>A 3D packaging configurator with a Blender-inspired UI. Started as a basic college project, but I accidentally put way too much effort into it because I didn't know when to stop.</p>
      <a href="https://ecopack-select-v2.vercel.app/"><b>[ View Configurator ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💻 Glass-OS</h3>
      <p>A cyberpunk web desktop simulator. Features draggable windows, a local-storage note editor, and a functional terminal running classic tropes like <code>cowsay</code> and <code>matrix</code>.</p>
      <a href="https://glass-os.vercel.app/"><b>[ Boot OS ]</b></a>
    </td>
    <td width="50%" valign="top">
      </td>
  </tr>
</table>

<br>

## ─── ✦ PHP (I Know, I Know) ───

<div align="center">
  <br>
  <i>I don't particularly enjoy PHP. I am, unfortunately, quite good at it.</i>
  <br><br>
</div>

<table width="100%">
  <tr>
    <td width="100%" valign="top">
      <h3>🎵 WaveCraft</h3>
      <p>A web-based audio synthesizer with its own domain-specific language. You write music notation in the browser; the server lexes and parses it into an AST, walks it to generate raw PCM samples via oscillator math, applies ADSR envelopes, and encodes the result as a binary WAV file. No audio libraries. The entire synthesis pipeline is implemented in PHP, which was nobody's first recommendation.</p>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
      <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
      <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <br><br>
      <a href="https://wavecraft-s13f.onrender.com/"><b>[ Live Demo ]</b></a> • 
      <a href="https://github.com/Nikhil-Singh2745/Wavecraft"><b>[ Source Code ]</b></a>
    </td>
  </tr>
</table>

<br>

## ─── ✦ PHP Backend Autopsies ───
*A series of projects I built to understand how specific backend subsystems actually work. No frontends. No deploy links. No point pretending otherwise. Recently open-sourced because they were just sitting there.*

<table width="100%">
  <tr>
    <td width="100%" valign="top">
      <h3>💳 VaultLedger</h3>
      <p>A Stripe-inspired payment orchestration engine built to map the underlying complexity of money movement. Includes an append-only event-sourced state machine, a rigorous double-entry accounting ledger that bans floating-point numbers, a local SQLite-friendly idempotency layer, and an asynchronous webhook delivery framework complete with HMAC payload verification and automated circuit breakers. It doesn't handle real credit cards, which is probably for the best.</p>
      <img src="https://img.shields.io/badge/Laravel_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/vaultledger"><b>[ Source Code ]</b></a>
    </td>
  </tr>
</table>

<br>

## ─── ✦ Honorable Mentions ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🦖 Dino Supreme</h3>
      <p>A satire of the Chrome dinosaur game. Over-engineered to an unnecessary degree just to see if I could keep canvas rendering stable while piling on useless features.</p>
      <a href="https://dino-supreme.vercel.app/"><b>[ Play ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🧮 Calculator</h3>
      <p>A totally normal web calculator. Definitely does math, and definitely doesn't do anything weird when you click the numbers. Watch it break standard layout logic.</p>
      <a href="https://calculator-khaki-eta-90.vercel.app/"><b>[ Calculate ]</b></a>
    </td>
  </tr>
</table>

<br>

<details>
<summary><b>▸ Open Source Archives (Older Projects)</b></summary>
<br>

*I made these back when I was still figuring things out. They don't have live deployment links, but the source code is public. Read the repos to run them locally.*

* 🔍 **[personal-search-engine](https://github.com/Nikhil-Singh2745/personal-search-engine)** `[ C ]` — A tiny CLI tool that indexes text/markdown directories and ranks results using term-frequency. 
* 🛑 **[rate-limiter](https://github.com/Nikhil-Singh2745/rate-limiter)** `[ Rust / Redis / Lua ]` — An HTTP service running a token-bucket rate limiter. Executes Lua scripts to handle atomic updates.
* 📉 **[lag-sim](https://github.com/Nikhil-Singh2745/lag-sim)** `[ Rust / Vue.js ]` — A local internet lag simulator. Spins up a TCP proxy to intentionally drop packets, throttle traffic, and add delays.

</details>

<br>

<div align="center">
  <i>If it runs in the browser, it can probably be pushed further.</i>
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=69f58e&height=90&section=footer">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=454BFF&height=90&section=footer">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=21262d&height=90&section=footer" width="100%" />
</picture>
