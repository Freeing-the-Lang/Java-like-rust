# ☕ Java-like-rust

**A lightweight experimental language combining Java syntax with Rust’s safety and ownership model**

---

## 🎯 Project Goal

**Java-like-rust** aims to merge the familiar, readable syntax of Java with Rust’s modern safety, performance, and memory ownership principles.

- 🚀 Java-like syntax, Rust-level performance  
- 🧠 Ownership and borrowing without garbage collector  
- 🦾 Thread safety and deterministic execution  
- 🔒 ProofLedger-ready build system (for reproducibility and hash verification)

---

## 🧱 Directory Structure




Java-like-rust/
├─ src/             # Core transpiler and runtime
├─ examples/        # Java → Rust example code
├─ tests/           # Parser and translation tests
├─ proofledger/     # Build proofs and hash logs
├─ LICENSE
└─ README.md



---

## ⚙️ Build & Run

```bash
# Example (if using a Rust-based compiler)
cargo build --release
./target/release/java_like_rust input.java




🧪 Example


Input (Java-like)


class Hello {
    public static void main() {
        System.out.println("Hello, world!");
    }
}



Output (Generated Rust)


fn main() {
    println!("Hello, world!");
}




🧩 Vision




“Write like Java, execute like Rust.”




This project explores:




Static typing with ownership and lifetimes


Rust’s borrow checker in a Java-like context


Deterministic, proof-verifiable build pipelines




Future directions may include:




LLVM-free backend (Pure Rust)


Integrated ProofLedger log on each build


WebAssembly compilation support





🪶 License


This project is licensed under the MIT License.



---


