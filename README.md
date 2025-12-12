# Catthode for Superfile

> **From CRT to OLED.** Bringing warmth back to a world of cold themes.

Catthode is a high-contrast, retro-futuristic theme designed for prolonged coding sessions. It blends the crushed blacks of modern OLED displays with the comforting, warm glow of analog tungsten filaments.

## 🎨 Color Palette

### Surface
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Base** | `#000000` | Editor background, pure void |
| **Sidebar** | `#141414` | Sidebars, panels, widgets |
| **Selection** | `#2d2d2d` | Text selection, hover states, buttons |
| **Border** | `#636363` | Borders, subtle dividers |

### Phosphor
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Text** | `#ffffff` | Standard text |
| **Variable** | `#e8e8e8` | Variables, identifiers |
| **Comment** | `#b3b3b3` | Comments, docstrings |
| **Ignored** | `#757575` | Ignored files, disabled elements |

### Glow
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Wheat** | `#fae2c8` | Types, classes, bright glow |
| **Tan** | `#d9b98c` | Secondary glow |
| **Gold** | `#ffb86c` | Keywords, storage, headers |
| **Amber** | `#ff9e3b` | Functions, accents, active states |
| **Clay** | `#f08d49` | Operators, punctuation |

### Accents
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Red** | `#ff6b6b` | Errors, deletions, dangerous actions |
| **Green** | `#b9d665` | Strings, insertions, success |
| **Cyan** | `#aee6d6` | Regex, escapes, information |
| **Blue** | `#9cd9e6` | Links, properties, secondary info |
| **Purple** | `#eba4be` | Constants, numbers, booleans |

## 📦 Installation

1.  **Locate your Superfile configuration directory.**
    Usually `~/.config/superfile/`.

2.  **Create a `theme` directory** if it doesn't exist.
    ```bash
    mkdir -p ~/.config/superfile/theme
    ```

3.  **Download** `catthode.toml` and place it in the `theme` directory.
    ```bash
    cp catthode.toml ~/.config/superfile/theme/
    ```

4.  **Edit your `config.toml`**.
    Open `~/.config/superfile/config.toml` and find the `theme` setting. Change it to `catthode`.

    ```toml
    # ... inside config.toml
    theme = "catthode"
    ```

5.  **Restart Superfile**.
