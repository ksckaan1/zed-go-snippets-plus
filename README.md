# Go Snippets Plus for Zed IDE

![Version](https://img.shields.io/github/v/release/ksckaan1/zed-go-snippets-plus?style=flat-square)
![License](https://img.shields.io/github/license/ksckaan1/zed-go-snippets-plus?style=flat-square)
[![Zed](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zed-industries/zed/main/assets/badge/v0.json)](https://zed.dev)

A comprehensive collection of Go snippets for the [Zed IDE](https://zed.dev), designed to match the familiarity and productivity of standard VS Code Go snippets.

🚀 **Boost your productivity with shortcuts for common patterns like `if err != nil`, loops, HTTP handlers, and testing structures.**

## ✨ Features

- **VS Code Familiarity:** Uses the same prefixes you are used to (`iferr`, `forr`, `tyf`, etc.).
- **Comprehensive:** Covers everything from basic syntax to concurrency and HTTP.
- **Productivity Focused:** Includes complex blocks like Table-Driven Tests (`tdt`) and Handler functions.

## 📦 Installation

1. Open **Zed**.
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux/Windows) to open the command palette.
3. Type `zed: extensions` and select it.
4. Search for **"Go Snippets Plus"**.
5. Click **Install**.

## 📝 Snippets Reference

### Essentials & Declarations
| Prefix | Description |
|--------|-------------|
| `pkgm` | Package main with main function |
| `im` | Single import statement |
| `ims` | Multiple import block |
| `var` | Single variable declaration |
| `vars` | Multiple variables block |
| `co` | Single constant |
| `cos` | Multiple constants block |
| `make` | make() statement |
| `new` | new() statement |

### Types & Functions
| Prefix | Description |
|--------|-------------|
| `tyf` | Type function declaration |
| `tyi` | Type interface declaration |
| `tys` | Type struct declaration |
| `func` | Function declaration |
| `meth` | Method declaration |
| `in` | Empty interface `interface{}` |
| `map` | Map declaration |
| `finit` | init function |
| `fmain` | main function |

### Control Flow & Error Handling
| Prefix | Description |
|--------|-------------|
| `if` | If statement |
| `el` | Else branch |
| `ie` | If-else statement |
| `iferr` | **If error check** (`if err != nil { ... }`) |
| `switch` | Switch statement |
| `sel` | Select statement |
| `cs` | Case clause |
| `for` | For loop |
| `forr` | For range loop |
| `pn` | panic() |
| `df` | Defer statement |

### Concurrency
| Prefix | Description |
|--------|-------------|
| `go` | Anonymous goroutine |
| `gf` | Goroutine function call |
| `ch` | Channel declaration |

### Logging & Formatting
| Prefix | Description |
|--------|-------------|
| `fp` | fmt.Println() |
| `ff` | fmt.Printf() |
| `lp` | log.Println() |
| `lf` | log.Printf() |
| `lv` | Log variable content |

### HTTP / Web
| Prefix | Description |
|--------|-------------|
| `helloweb`| complete Hello World web app |
| `hand` | HTTP handler declaration |
| `hf` | http.HandleFunc() |
| `wr` | HTTP handler parameters (`w http.ResponseWriter, r *http.Request`) |
| `rd` | http.Redirect() |
| `herr` | http.Error() |
| `las` | http.ListenAndServe() |
| `sv` | http.Serve() |

### Testing
| Prefix | Description |
|--------|-------------|
| `tf` | Test function |
| `tm` | TestMain function |
| `tdt` | **Table-driven test** boilerplate |
| `bf` | Benchmark function |
| `ef` | Example function |
| `tl` | t.Log() |
| `tlf` | t.Logf() |
| `tlv` | Log variable in tests |

### Utils
| Prefix | Description |
|--------|-------------|
| `sort` | Sort implementation |

## 🤝 Contributing

Contributions are welcome! If you feel a snippet is missing or could be improved:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/amazing-snippet`).
3. Commit your changes.
4. Open a Pull Request.

## 📄 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Kaan Kuscu**
- Email: [me@kaanksc.com](mailto:me@kaanksc.com)
- GitHub: [@ksckaan1](https://github.com/ksckaan1)

## 🔗 Repository

[https://github.com/ksckaan1/zed-go-snippets-plus](https://github.com/ksckaan1/zed-go-snippets-plus)
