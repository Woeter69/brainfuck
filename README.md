# Brainfuck Projects

This repository contains Brainfuck programs and examples.  
Brainfuck is an esoteric programming language with only 8 commands, designed to challenge and entertain programmers.

---

## Getting Started

You can run Brainfuck programs locally using an interpreter.

### Option 1: Install `bf` via apt (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install bf
```

### Option 2: Install `rust-bf` via snap

```bash
sudo snap install rust-bf
echo 'export PATH=$PATH:/snap/bin' >> ~/.bashrc
source ~/.bashrc
```

## Running the Code

```bash
bf hello.bf
rust-bf -f hello.bf
cat hello.bf | rust-bf
```

---

## Repository Contents

- Sample Brainfuck programs (`.bf` files)
- Example: `hello.bf` prints "Hello World!"

---

## About Brainfuck

Brainfuck uses the following 8 commands: `+`, `-`, `>`, `<`, `[`, `]`, `.`, `,`  
For more about the language: [Wikipedia - Brainfuck](https://en.wikipedia.org/wiki/Brainfuck)

---

## Suggestions

- Add example outputs for your sample programs.
- Include a LICENSE file if you want to specify usage permissions.
- Add contribution guidelines if you want others to contribute.

