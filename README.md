# Brainfuck Projects

This repository contains Brainfuck programs and examples. Brainfuck is an esoteric programming language with only 8 commands, designed to challenge and entertain programmers.

---

## Getting Started

You can run Brainfuck programs locally using an interpreter.

### Option 1: Install `bf` via apt (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install bf

### Option 2: Install `rust-bf` via apt snap

```bash
sudo snap install rust-bf
echo 'export PATH=$PATH:/snap/bin' >> ~/.bashrc
source ~/.bashrc

### Running the code

```bash
bf hello.bf
rust-bf -f hello.bf
cat hello.bf | rust-bf
