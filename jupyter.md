# ⚡ Keyboard Shortcuts
## 🧭 Command Mode (press Esc to enter)
| Shortcut          | Action                              |
| ----------------- | ----------------------------------- |
| `A`               | Insert new cell **above**           |
| `B`               | Insert new cell **below**           |
| `X`               | Cut selected cell                   |
| `C`               | Copy selected cell                  |
| `V`               | Paste cell below                    |
| `Shift + V`       | Paste cell above                    |
| `D + D`           | Delete selected cell                |
| `Z`               | Undo cell deletion                  |
| `M`               | Change cell to **Markdown**         |
| `Y`               | Change cell to **Code**             |
| `Shift + Enter`   | Run cell and move to next           |
| `Ctrl + Enter`    | Run cell, stay on same cell         |
| `Alt + Enter`     | Run cell and insert a new one below |
| `Up / Down Arrow` | Move between cells                  |
| `0 + 0`           | Restart the kernel                  |

## 🧠 Edit Mode (press Enter to enter)
| Shortcut           | Action                     |
| ------------------ | -------------------------- |
| `Ctrl + /`         | Comment/uncomment lines    |
| `Shift + Tab`      | Show documentation tooltip |
| `Ctrl + Shift + -` | Split cell at cursor       |
| `Ctrl + A`         | Select all text            |
| `Tab`              | Auto-complete code         |
| `Ctrl + Shift + P` | Command palette            |

# ✨ Magic Commands
Magic commands are special Jupyter commands starting with % (line magics) or %% (cell magics).

## 🔹 Line Magics
| Command              | Description                                  |
| -------------------- | -------------------------------------------- |
| `%pwd`               | Show current working directory               |
| `%cd path`           | Change working directory                     |
| `%ls`                | List files in current directory              |
| `%who`               | List all variables in the workspace          |
| `%whos`              | Detailed variable info                       |
| `%time code`         | Time execution of a single line              |
| `%timeit code`       | Run code multiple times and get average time |
| `%history`           | Show command history                         |
| `%reset`             | Clear all variables                          |
| `%matplotlib inline` | Display plots inline                         |
| `%run script.py`     | Run a Python script inside the notebook      |

## 🔸 Cell Magics
| Command                             | Description                                                    |
| ----------------------------------- | -------------------------------------------------------------- |
| `%%time`                            | Time execution of the whole cell                               |
| `%%timeit`                          | Benchmark entire cell                                          |
| `%%writefile filename.py`           | Save cell content to a file                                    |
| `%%capture`                         | Suppress cell output                                           |
| `%%bash`                            | Run shell commands in a Bash environment                       |
| `%%html`, `%%latex`, `%%javascript` | Render respective content types                                |
| `%%python`                          | Run cell in Python interpreter (useful if using other kernels) |

## 🧩 Other Useful Tricks
`!command` → Run shell command (e.g., !ls, !pip install numpy)

`?object` → Show help for an object (e.g., ?list)

`object??` → Show source code if available

`Shift + L` → Toggle line numbers in a cell

`Ctrl + S` → Save notebook

