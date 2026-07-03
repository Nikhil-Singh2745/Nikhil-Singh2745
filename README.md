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

## ─── ✦ Low-Latency & Quant Systems ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ NanoMQ</h3>
      <p>A lock-free SPSC inter-process queue over POSIX shared memory, written from scratch in C++20. The hot path uses zero syscalls and zero locks, with cache-line isolation, acquire/release ordering, and inline <code>rdtsc</code> instrumentation.</p>
      <img src="https://img.shields.io/badge/C%2B%2B-20-blue.svg?style=for-the-badge&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/Memory_Ordering-Acquire%2FRelease-orange?style=for-the-badge" />
      <img src="https://img.shields.io/badge/Min_Latency-44_ns-brightgreen?style=for-the-badge" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/nanomq"><b>[ Source Code & Architecture ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>📈 Stoikov Micro-Price Estimator</h3>
      <p>A dependency-free C++17 implementation of the Stoikov micro-price framework, modeling L1 order-book snapshots as an absorbing Markov chain and solving the fair-value adjustment directly.</p>
      <img src="https://img.shields.io/badge/C%2B%2B-17-blue.svg?style=for-the-badge&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/Math-Markov_Chains-blueviolet?style=for-the-badge" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/stoikov-micro-price-estimator"><b>[ Source Code ]</b></a>
    </td>
  </tr>
</table>

<br>

## ─── ✦ Backend Systems ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 Admit</h3>
      <p>An admission-controlled Go cache comparing W-TinyLFU against LRU and LFU. Includes a packed Count-Min Sketch, self-aging frequency estimates, segmented LRU, and reproducible benchmarks for skew, scans, and concept drift.</p>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
      <img src="https://img.shields.io/badge/Cache-W--TinyLFU-brightgreen?style=for-the-badge" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/Admit"><b>[ Source Code & Benchmarks ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 authz-engine</h3>
      <p>A Zanzibar-inspired relationship-based authorization engine with rewrite-rule evaluation, cycle detection, memoization, depth limits, and zookie-versioned caching.</p>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
      <img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white" />
      <img src="https://img.shields.io/badge/Authorization-ReBAC-blueviolet?style=for-the-badge" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/authz-engine"><b>[ Source Code & Architecture ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 VaultLedger</h3>
      <p>A payment orchestration engine with event-sourced state, double-entry accounting, idempotency, signed webhook delivery, and circuit breakers.</p>
      <img src="https://img.shields.io/badge/Laravel_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/vaultledger"><b>[ Source Code ]</b></a>
    </td>
    <td width="50%" valign="top"></td>
  </tr>
</table>

<br>

## ─── ✦ Full-Stack Systems ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🗄️ Rawth</h3>
      <p>A zero-dependency key-value database built from scratch in Go, including a B+Tree, binary file format, query language, and WebSocket server.</p>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
      <br><br>
      <a href="https://github.com/Nikhil-Singh2745/rawth"><b>[ Source Code ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🏰 Crypt</h3>
      <p>A server-resident turn-based dungeon crawler written in C. The frontend is a <code>&lt;pre&gt;</code> tag, every keypress is a request, and a server restart means permanent death.</p>
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
      <br><br>
      <a href="https://crypt-f7ji.onrender.com/"><b>[ Enter Dungeon ]</b></a> •
      <a href="https://github.com/Nikhil-Singh2745/crypt"><b>[ Source & Gifs ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎵 WaveCraft</h3>
      <p>A browser-based music DSL whose PHP backend lexes notation into an AST, synthesizes raw PCM with oscillators and ADSR envelopes, and encodes the result as a WAV file—with no audio libraries.</p>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
      <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
      <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <br><br>
      <a href="https://wavecraft-s13f.onrender.com/"><b>[ Live Demo ]</b></a> •
      <a href="https://github.com/Nikhil-Singh2745/Wavecraft"><b>[ Source Code ]</b></a>
    </td>
    <td width="50%" valign="top"></td>
  </tr>
</table>

<br>

## ─── ✦ Frontend & Browser Experiments ───

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Threshold</h3>
      <p>A compact WebGL experience with handwritten shaders, audio math, and roughly 9 KB of application logic.</p>
      <a href="https://threshold-navy.vercel.app/"><b>[ Launch Experience ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🛸 Cyber-City</h3>
      <p>An infinite drone-flying game set in a procedurally generated neon city, including a maximum-speed Deathwish Mode.</p>
      <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" />
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <br><br>
      <a href="https://cyber-city-blush.vercel.app/"><b>[ Play Game ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>✂️ Offcut</h3>
      <p>A fictional design-studio portfolio built with vanilla HTML, CSS, and JavaScript, including an interactive paint canvas.</p>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <br><br>
      <a href="https://offcut-chi.vercel.app/"><b>[ Visit Studio ]</b></a> •
      <a href="https://github.com/Nikhil-Singh2745/offcut"><b>[ Source Code ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🚀 Deadframe</h3>
      <p>A fast-paced 2D space shooter with a roguelite perk system and a custom raw-Canvas rendering loop.</p>
      <a href="https://deadframe.vercel.app/"><b>[ Play Game ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📦 Ecopack Select v2</h3>
      <p>A 3D packaging configurator with a Blender-inspired interface.</p>
      <a href="https://ecopack-select-v2.vercel.app/"><b>[ View Configurator ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>💻 Glass-OS</h3>
      <p>A cyberpunk web desktop with draggable windows, persistent notes, and a functional novelty terminal.</p>
      <a href="https://glass-os.vercel.app/"><b>[ Boot OS ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📚 Reading Room</h3>
      <p>An intentionally over-engineered blog where every post is a custom React component with its own palette and layout.</p>
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
      <br><br>
      <a href="https://blog-nine-phi-25.vercel.app/"><b>[ Live Site ]</b></a> •
      <a href="https://blog-nine-phi-25.vercel.app/posts/trpc-for-no-reason"><b>[ Read Post ]</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🦖 Dino Supreme</h3>
      <p>An aggressively over-engineered satire of the Chrome dinosaur game.</p>
      <a href="https://dino-supreme.vercel.app/"><b>[ Play ]</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧮 Calculator</h3>
      <p>A deliberately uncooperative calculator that breaks standard layout behavior as you use it.</p>
      <a href="https://calculator-khaki-eta-90.vercel.app/"><b>[ Calculate ]</b></a>
    </td>
    <td width="50%" valign="top"></td>
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
