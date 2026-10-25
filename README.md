<div align="center">
  <img 
    width="100%" 
    src="https://github.com/AmmaarBakshi/AmmaarBakshi/raw/main/TrajectoriesInGravity.webp"
    alt="Trajectories of Gravity — physics equations and galaxy illustration"
  />
</div>

<br/>

<div align="center">

# Ammaar Bakshi

<a href="https://github.com/AmmaarBakshi">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=900&color=4A9EFF&center=true&vCenter=true&width=560&lines=Pure+C+%C2%B7+Rust+%C2%B7+x86+Assembly+%C2%B7+Python;input+%E2%86%92+Lexer+%E2%86%92+Parser+%E2%86%92+AST+%E2%86%92+exec;Shipping+to+winget%2C+APT%2C+npm+%26+PyPI;Build+until+you+understand+everything." alt="Typing intro" />
</a>

*"I don't wait to understand everything before I build — I build until I understand everything."*

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-AmmaarBakshi-181717?style=flat-square&logo=github)](https://github.com/AmmaarBakshi)
[![PyPI](https://img.shields.io/badge/PyPI-letx-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/letx)
[![winget](https://img.shields.io/badge/winget-git--recall-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/microsoft/winget-pkgs)
[![Profile Views](https://komarev.com/ghpvc/?username=AmmaarBakshi&style=flat-square&color=4a9eff&label=profile+views)](https://github.com/AmmaarBakshi)
[![committers.top badge](https://user-badge.committers.top/india/AmmaarBakshi.svg)](https://user-badge.committers.top/india/AmmaarBakshi)

</div>

---

Every trajectory has equations behind it. Mine runs through pure C, a hand-rolled Rust shell with its own lexer and AST, x86 Assembly written register-by-register, and Python tooling that ships to real package managers. I don't wait for permission to explore a new layer of the stack — if it compiles (or doesn't), I want to know exactly why.

---

## 🛰️ Projects

### [⚗️ oxide](https://github.com/AmmaarBakshi/oxide) &nbsp;`Rust`

A custom, high-performance shell written entirely in Rust — not a wrapper around existing system calls, but a full pipeline built from scratch.

```text
  raw input ──▶ Lexer ──▶ Parser ──▶ AST ──▶ Execution Engine ──▶ output
```

Architected as a Cargo Workspace to keep every layer strictly decoupled:

| Crate | Role |
|---|---|
| `oxide-cli` | Entry point and terminal UI |
| `oxide-core` | REPL loop and state manager |
| `oxide-parser` | Lexer, grammar, and AST generation |
| `oxide-builtins` | Native shell commands (`cd`, `echo`, etc.) |

**Features:** custom lexing & parsing · process execution · output redirection (`>`) · dynamic prompt · built-in command interception

```bash
git clone https://github.com/AmmaarBakshi/oxide.git
cd oxide
cargo run -p oxide-cli
```

<br/>

<table>
<tr>
<td width="50%" valign="top">

### [📅 git-recall](https://github.com/AmmaarBakshi/git-recall) &nbsp;`C`

Personal git standup tool in pure C — no dependencies, just git. See exactly what you committed by day, week, month, or year.

```bash
$ git-recall --week
$ git-recall --month -2   # two months back
$ git-recall --day > recap.txt
```

[![winget](https://img.shields.io/badge/winget-Ammaar.git--recall-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/microsoft/winget-pkgs)
[![APT PPA](https://img.shields.io/badge/PPA-ammaar--apt%2Fgit--recall-E95420?style=flat-square&logo=ubuntu&logoColor=white)](https://launchpad.net/~ammaar-apt/+archive/ubuntu/git-recall)

</td>
<td width="50%" valign="top">

### [🗡️ paimon](https://github.com/AmmaarBakshi/paimon) &nbsp;`Rust` `JS`

Keyboard-driven Rust TUI that injects code snippets and project structures into your working directory. Snippets are embedded in the binary at compile time — no internet, no Python, nothing extra.

```bash
$ paimon --code -ls
# ↑↓ navigate  ENTER select  ← back  q quit
```

[![winget](https://img.shields.io/badge/winget-Ammaar.Paimon-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/microsoft/winget-pkgs)
[![npm](https://img.shields.io/badge/npm-paimon--npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/paimon-npm)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🔧 letx](https://github.com/AmmaarBakshi/letx) &nbsp;`Python`

Modular Python CLI toolkit. Plain-English error explanations, fix suggestions, and codebase cleanup — all from the terminal.

```bash
$ letxDebug -a my_script.py  # run + explain + fix
$ letxFix -rm -cmt src/      # strip all comments
```

[![PyPI](https://img.shields.io/badge/PyPI-letx-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/letx/)

</td>
<td width="50%" valign="top">

### [🖥️ ASSAMBLY](https://github.com/AmmaarBakshi/ASSAMBLY) &nbsp;`x86 Asm`

63 Assembly programs written register-by-register — animated ASCII bouncing balls, a desktop-lite shell, quadratic equation graphs, GCD, Hamming weight.

```nasm
mov  ax, [velocity]   ; most devs skip this layer
int  21h              ; I didn't.
```

</td>
</tr>
</table>

---

## 🧪 Stack

**Languages**

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Assembly](https://img.shields.io/badge/x86_Assembly-6E4C13?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML%2FCSS%2FJS-E34F26?style=flat-square&logo=html5&logoColor=white)

**Tooling & distribution**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Cargo](https://img.shields.io/badge/Cargo-000000?style=flat-square&logo=rust&logoColor=white)
![winget](https://img.shields.io/badge/winget-0078D4?style=flat-square&logo=windows&logoColor=white)
![Ubuntu PPA](https://img.shields.io/badge/Ubuntu_PPA-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white)

---

## 📈 Stats

<div align="center">
  <img src="https://streak-stats.demolab.com?user=AmmaarBakshi&theme=dark&background=0D1117&ring=4A9EFF&fire=4A9EFF&currStreakLabel=4A9EFF&sideLabels=C9D1D9&dates=8B949E&hide_border=true" height="160" alt="GitHub streak" />
  <br/><br/>
  <img width="100%" src="https://ghchart.rshah.org/4A9EFF/AmmaarBakshi" alt="Contribution chart" />
</div>

---

<div align="center">

<sub><code>D = (v₀² / g) · sin 2θ</code> — every trajectory has equations behind it.</sub>

<sub>If something here saves you time, a ⭐ goes a long way.</sub>

</div>
