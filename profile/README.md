# Welcome to the Rust Dune Project 👋

🚀 **Reimagining the Stanford Dune Project in Rust**  
Our project aims to rewrite the [Stanford Dune Project](https://dune.scs.stanford.edu/) using the Rust programming language. By reimplementing Dune framework for Intel VT-x and AMD SEV-SNP platforms, we enable both guest and host processes to execute in the Ring-0 privilege level of virtual machines with enhanced safety and performance guarantees provided by Rust. Meanwhile, the untrusted processes can be scheduled to the user-space of a lower VMPL under AMD SEV-SNP platform.

## 🏗️ What We're Building

- **Kernel Module in Rust**: A robust and secure reimplementation of the original kernel module.
- **libdune Library**: A library OS, rewritten in Rust, to interface with the kernel module and the user applications.
- **dune-sys Crate**: A user-friendly Rust crate providing an interface for interacting with the Dune environment.

This project blends cutting-edge virtualization concepts with Rust's safety and performance, making it a fresh take on the Dune framework.

---

## 🌈 How to Contribute

We warmly welcome contributors who share an interest in systems programming, Rust, and virtualization! Here's how you can get involved:

1. **Check out the codebase**: Clone the repository and familiarize yourself with the project structure.
2. **Read the contribution guide**: (Coming soon!) This will provide coding standards, issue filing procedures, and PR submission guidelines.
3. **Pick an issue**: Look for issues labeled as `good first issue` or `help wanted` to get started.
4. **Join the discussion**: Engage with the community on GitHub Issues or Discussions.

Whether you're an expert in virtualization or just diving into Rust, there's a place for you here!

---

## 📚 Resources

Here are some resources to help you get up to speed:

- **Original Dune Project**: [Stanford Dune Paper](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/belay)  
  Learn about the foundational work behind our Rust-based reimplementation.
- **Rust Programming Language**: [The Rust Book](https://doc.rust-lang.org/book/)  
  Ideal for contributors who are new to Rust.
- **Virtualization Basics**: [Hardware and Software Support for Virtualization](https://kartikgopalan.github.io/680v/books/HSSV.pdf)  
  A primer for understanding the concepts behind this project.

---

## 🍿 Fun Facts About Our Project

- **Why Rust?** Its safety features and modern language ergonomics make it perfect for systems programming.
- **Virtualization Meets Safety**: With Rust, we're bringing a new level of security to Dune's virtualization paradigm.
- **Community First**: We're building this for everyone who loves systems programming and virtualization tech.

---

We believe in the power of collaboration to achieve mighty things. Join us in redefining what's possible with Rust and virtualization!

🧙 With Rust, safety is not an option—it's built-in.  
Happy coding! 💻  
