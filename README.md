# compillm · GACLI LLM Compiler Module

### 🚧 **WORK IN PROGRESS** 🚧

This module adds the `gacli compillm` command to your [GACLI CLI](https://github.com/guillaumeast/gacli).

It compiles all files in the target directory into a `llm_ressources/` folder for easy use with large language models (LLMs).

---

## ✨ Features

- Outputs a `structure.md` and a `codebase.txt`
- Generates a clean, structured `.txt` version of your codebase
- Merges and ignores files based on `.gitignore`
- Cross-platform (`macOS` & `Linux`)

---

## 🚀 Installation

```bash
gacli add-mod https://github.com/guillaumeast/gacli_compillm
```

This command will:
- Clone the `repo` into `~/.gacli/modules/user_modules/`
- Register the `module` in your `GACLI` registry
- Make the `command` `gacli compillm` available

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
See the [LICENSE](./LICENSE) file for details.
