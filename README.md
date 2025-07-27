#  Calculator Project – Rust (Shared)

![Ferris the Crab](https://www.rust-lang.org/static/images/ferris.gif)

👥 Shared with ALI CS Club

---

This is the **shared Rust calculator repository** for ALI CS Club members.  
It includes both:

- `cli/` – A terminal-based calculator written in idiomatic Rust.  
- `gui/` – A graphical calculator using a modern Rust GUI framework like `egui` or `iced`.

Each version is in its own folder and built using `cargo`.

---

## 📁 Project Structure

```
calculator-rust-shared/
├── cli/
│   └── calculator.rs             # CLI version – run with cargo
└── gui/
    └── calculator_gui.rs         # GUI version – built with egui or iced
```

---

## 🚀 How to Run

### CLI Version

```bash
cd cli
cargo run
```

### GUI Version

⚠️ Requires dependencies such as `egui` or `iced` to be installed in your `Cargo.toml`

```bash
cd gui
cargo run
```

---

## 🤝 Contribution Guidelines

- If you're working **independently**, please **fork** this repo or create a **branch**, and submit a **pull request** when your work is ready to merge.
- If you're working **together with a club member** (e.g., in a meeting), only **one person should edit and push at a time** to avoid conflicts.
- Keep code clean, well-documented, and placed in the appropriate folder (`cli/` or `gui/`).

---

## 🧠 Purpose

This project helps members strengthen:
- Ownership, pattern matching, and memory safety in Rust (CLI version)
- GUI development using modern Rust crates like `egui` or `iced` (GUI version)
- GitHub-based collaboration using branching, pull requests, and issue tracking

Happy coding in Rust!
