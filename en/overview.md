---
title: Hacking zkSync Era for Fun and (hopefully) Profit
image: "https://era.zksync.io/docs/era-dark.svg"
level: 1
categories:
    - Hacking
    - zkSync
    - Bug Bounties
    - Etherium
duration: 640
---

zkSync Era is a layer 2 rollup that uses zero-knowledge proofs to scale Ethereum without compromising on security or decentralization. Since it's EVM compatible (Solidity/Vyper), 99% of Ethereum projects can redeploy without refactoring or re-auditing a single line of code. zkSync Era also uses an LLVM-based compiler that will eventually let developers write smart contracts in C++, Rust and other popular languages.

**And we're going to try and break it!**

<!--more-->

# Overview

::badge
$1,100,000
::
is up for grabs for anyone who can find vulnerabilities in zkSync Era. I'm going to attempt to keep some notes on what we're doing and how we're doing it. I'm not a security researcher, so I'm going to be learning as I go.

I figured I may as well kill two birds with one stone and write an ADA Hacker Space lesson so I can test building out that system as well. I'll try and keep it as beginner friendly as possible, but I'm going to assume some basic knowledge of Ethereum and Solidity. If you don't, I'd recommend checking out [Mastering Ethereum by Andreas Antonopoulos and Dr. Gavin Woods](https://github.com/ethereumbook/ethereumbook#readme). I'm also going to assume you have some basic knowledge of how to use the command line. If you don't, I'd recommend checking out [The Command Line Crash Course](https://learnpythonthehardway.org/book/appendixa.html) (mostly because GitHub CoPilot wrote that line).
