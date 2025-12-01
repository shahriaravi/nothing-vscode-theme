# Nothing OS Theme for VS Code

[![Get it on VS Code Marketplace](https://img.shields.io/badge/Get%20it%20on-VS%20Code%20Marketplace-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=xexefe.nothing-os-theme)

**Nothing OS Theme** is a minimal, high-contrast extension inspired by the unique design language of Nothing Technology. It features a monochromatic palette, dot-matrix aesthetics, and the signature **Nothing Red (#D71921)** accents.

Designed to reduce eye strain while keeping important syntax highly visible.

## 🎨 Theme Variants

This extension comes with **5 distinct variants**:

### 1. Nothing OS Dark
The definitive Nothing experience. Pure black (`#000000`) background, perfect for OLED screens, with high-contrast white text and red accents.

![Nothing OS Dark Screenshot](https://github.com/shahriaravi/nothing-vscode-theme/raw/main/images/dark.png)

### 2. Nothing OS Gray
A softer, slate-gray (`#14151F`) background for those who find pure black too harsh. Balanced contrast with the same signature red highlights.

![Nothing OS Gray Screenshot](https://github.com/shahriaravi/nothing-vscode-theme/raw/main/images/gray.png)

### 3. Nothing OS Light
A clean, paper-white workspace that maintains the Nothing aesthetic in bright environments.

![Nothing OS Light Screenshot](https://github.com/shahriaravi/nothing-vscode-theme/raw/main/images/light.png)

### 4. Nothing OS Dark (Glyph)
A strict monochromatic version. Pure black and white only, mimicking the Glyph Interface. Color is used *extremely* sparingly, only for critical errors.

![Nothing OS Glyph Screenshot](https://github.com/shahriaravi/nothing-vscode-theme/raw/main/images/glyph.png)

### 5. Nothing OS Special
A special variant with enhanced color coding. Features the signature Nothing black background with vibrant yellow (#ffc703) accents and red highlights for better syntax differentiation.

---

## ⚙️ Recommended Settings

For the best experience, add these settings to your `settings.json`:

```json
{
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "editor.fontLigatures": true,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.guides.bracketPairs": true,
  "editor.bracketPairColorization.enabled": true,
  "workbench.colorTheme": "Nothing OS Gray"
}