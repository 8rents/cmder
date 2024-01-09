**[Cmder Docs](README.md)**

---

**previous:** [Configuring Bash](04-configuring-bash.md)

# Pacman Package manager

*Part 5*

> ***This guide will cover using the Arch Linux package manager `pacman`.*** 

---

## Pacman is for bash in msys2 and provides package management for bash only

Just to be clear we are using several different environments and several different package managers. 

- **Scoop** - A Windows program installer. Installs both GUI and CLI apps for Windows. **All scoop apps are portable **
- **Chocolatey** - Another Windows package manager
- **NPM** - Node Package manager. Whether node is installed through *Scoop*, *Choco* or *Pacman*, NPM installs only node packages.
- **Pacman** - The package manager for msys2 bash and arch Linux.

### Comparing Cygwin & MSYS

- **Cygwin** is an operating system wrapper
  The goal of Cygwin is to provide a Linux Programming API.
- **Msys** is a command shell substitute
  The goal of Msys is to provide a POSIX scripting environment.

When **comparing that to scoop:**

Scoop is an installer (plain and simple)

> *[The goal of Scoop is to let you use Unix-y programs in a normal Windows environment](https://github.com/ScoopInstaller/Scoop/wiki/Cygwin-and-MSYS-Comparison)*

Using Scoop lets you achieve similar things to Cygwin and MSYS, but without having to learn about and use a separate environment.

You can just keep doing what you're already doing but easily access the cross-platform tools you need.

---

**🤍 2023 [Brenton Holiday](https://brenton.holiday)**
