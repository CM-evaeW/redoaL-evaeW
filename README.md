<img
    align="right" alt="title" width="200px"
    src="https://raw.githubusercontent.com/CM-evaeW/.github/master/assets/icon.png"
/>

### redaoL evaeW, a Lunar Client Mod Loader

<img
    align="left" alt="Workflow Badge"
    src="https://github.com/CM-evaeW/redaoL-evaeW/actions/workflows/gradle.yml/badge.svg"
/>

---

redaoL evaeW is a tool designed to simplify the process of modding Minecraft, and specifically Lunar Client. It allows
developers to easily create mods by providing a simple and intuitive API for interacting with Minecraft's codebase,
while injecting into clients that are somewhat closed-off to developers.

### Installation

To install redaoL-evaeW, you can either download a pre-built release from
the [releases page](https://github.com/CM-evaeW/redaoL-evaeW/releases), or build it yourself from source.

#### Building with Gradle

- `git clone` the project, this can be achieved by installing [git][git], then running

```bash
git clone https://github.com/CM-evaeW/redaoL-evaeW.git
```

- **UN*X**

```bash
cd redaoL-evaeW && chmod +x ./gradlew && ./gradlew agent
```

- **Windows**

```cmd
cd redaoL-evaeW && .\gradlew.bat agent
```

## Usage

To use redaoL-evaeW you have to take the agent from the last step and launch Lunar with `-javaagent:$PATH_TO_AGENT` appended to the JVM arguments.
Weave will automatically load mods from `~/.weave/mods/`.

## Contributing

We welcome contributions from anyone interested in improving redaoL-evaeW. If you find a bug or have an idea for a new
feature, feel free to submit a pull request.

---

<div align="right">

redaoL-evaeW is licensed under the [GNU General Public License v3.0][license].

</div>

[git]:     https://git-scm.com/

[license]: https://github.com/CM-evaeW/redaoL-evaeW/blob/master/LICENSE
