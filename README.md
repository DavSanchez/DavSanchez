### Hi there 👋

Software engineer at [New Relic](https://newrelic.com), building production Rust for agent fleet management and control. Based in Las Palmas de Gran Canaria, Spain.

My work and interests follow a single thread: **the purely functional model, applied at every layer**. In software design, that means algebraic data types, parametric polymorphism, and referential transparency — using the type system to make illegal states unrepresentable and enable equational reasoning. Haskell is the sharpest expression of this: type classes, type inference, and purity enforced at the type level make entire families of bugs impossible by construction. Rust brings the same discipline to systems programming: ownership and borrowing statically eliminate data races and memory safety violations, and the newtype pattern and trait system let you encode invariants the compiler verifies — a pattern you reach for reflexively once you've debugged your first parameter swap that compiled fine. In software distribution and system configuration, the same model means Nix: every package is a derivation — a pure function from a set of hashed inputs to a content-addressed output — built in a hermetic sandbox with no implicit dependencies or ambient state. The purely functional model goes all the way down.

**How software gets built and shipped** deserves the same rigour as how it is designed. A build that is not reproducible is a bug you have not hit yet. I've contributed packages to nixpkgs, built Nix modules for distributing observability tooling, and managed all my machines declaratively for years. In production Rust, that extends to performance: allocations that look harmless can become a bottleneck at scale, which is when heap profilers, flamegraphs, and properly configured build profiles earn their keep.

**Open source contributions:**
- [**NixOS/nixpkgs**](https://github.com/NixOS/nixpkgs) — packaged several tools over the years: `opentelemetry-collector-builder`, `infrastructure-agent`, `kontroll`, `basalt`, `prism-cli`, and others
- [**nix-community/home-manager**](https://github.com/nix-community/home-manager) — darwin support for various modules

**Projects:**
- [**Nix-Relic**](https://github.com/DavSanchez/Nix-Relic) — New Relic infra observability tools packaged as Nix flakes and modules
- [**richenv**](https://github.com/DavSanchez/richenv) — rich environment variable configuration library for Haskell
- [**nix-dotfiles**](https://github.com/DavSanchez/nix-dotfiles) — fully declarative, reproducible system config (NixOS + nix-darwin)
- Learning by building: [HNS](https://github.com/DavSanchez/HNS) (toy DNS resolver in Haskell), [hox](https://github.com/DavSanchez/hox) / [rox](https://github.com/DavSanchez/rox) (the Lox interpreter, in Haskell and Rust)

---

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" height="165" src="https://github-readme-stats.vercel.app/api?username=DavSanchez&theme=transparent&show_icons=true&layout=compact&rank_icon=github" />
</a>
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DavSanchez&theme=transparent&hide=TeX,HTML,Swift,Verilog,Nu,Emacs%20Lisp&langs_count=5&layout=compact" />
</a>

<!--
**DavSanchez/DavSanchez** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
