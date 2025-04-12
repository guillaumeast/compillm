# compillm · GACLI LLM Compiler Module

This module adds the `gacli compillm` command to your GACLI CLI.

It generates `llm_ressources/` files from the current project structure for use with large language models (LLMs).

---

## ✨ Features

- Generates a clean `.txt` version of your codebase
- Merges and ignores files based on `.gitignore`
- Outputs a `structure.md` and a `codebase.txt`
- Cross-platform (`macOS` & `Linux`)

---

## 🚀 Installation

```bash
gacli add-mod https://github.com/guillaumeast/gacli_compillm
```

This command will:
- Clone the repo into `~/.gacli/modules/user_modules/`
- Register the module in your `GACLI` registry
- Make the command `gacli compillm` available

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
See the [LICENSE](./LICENSE) file for details.
