# codescope
Description : Local code verifier. Detects Python, JSON, YAML errors without sending your data. Visibility : Public Initialize : ✅ Add a README file .gitignore : Python License : MIT License ```
```markdown
# ⚡ CodeScope

> **Local code verifier.** Detects Python, JSON, YAML, HTML, CSS, SQL errors without sending your data anywhere.

[![License: MIT](https://img.shields.io/badge/License-MIT-00d4ff.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-a855f7.svg)](https://www.python.org/)
[![Zero dependencies](https://img.shields.io/badge/dependencies-0-4ade80.svg)]()
[![Offline](https://img.shields.io/badge/works-offline-c8a45c.svg)]()

---

## 🎯 The problem

You paste code. You don't know if it's valid. You don't want to install an IDE. You don't want your code sent to a random server.

**CodeScope fixes that.**

---

## ⚡ One command

```bash
python3 codescope.py
```

Open http://localhost:9099/ — done.

---

🚀 What it does

· 18+ languages detected automatically
· 6 real verifiers (Python, JSON, YAML, HTML, CSS, SQL)
· Real syntax errors with line + column
· Zero dependencies (Python stdlib only)
· Zero data sent (everything local)
· Works on iPhone (same WiFi)
· Works offline (no internet needed)

---

🧪 Real verifiers

Language Verifier How
Python ✅ Real Uses ast.parse()
JSON ✅ Real Uses json.loads()
YAML ✅ Basic Tabs + indentation
HTML ✅ Basic Tag balance
CSS ✅ Basic Brace balance
SQL ✅ Basic Parentheses + ;

Everything else: syntax highlighting only (honest, no fake scores).

---

📱 On iPhone

1. Run python3 codescope.py on your computer
2. Note the network IP (shown at startup)
3. On iPhone: open http://192.168.1.XX:9099/ in Safari
4. Share → Add to Home Screen

Works like a native app.

---

🖼️ Screenshot

screenshot.png

---

🛠️ Stack

· Python 3.8+ (stdlib only)
· HTTP server (built-in)
· CodeMirror 5 (CDN)
· Zero npm, zero pip, zero install

---

📄 License

MIT — see LICENSE

---

🧬 Built by

Aissa Mohammedi (DGK) — System Builder

⭐ If this helps you, star the repo.

---

🔗 Other projects

· Nexus System — Distributed multi-process runtime
· Nexus QuickHub — Visual editor + MCP
· Nexus SMI — System monitor without NVIDIA

```

### 📄 `LICENSE` (racine)
→ Copie ceci :

```

MIT License

Copyright (c) 2026 Aissa Mohammedi (DGK)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

### 📄 `.gitignore` (racine)
→ Copie ceci :

```

pycache/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
*.egg-info/
.installed.cfg
*.egg
.env
.venv
env/
venv/
ENV/
.idea/
.vscode/
*.swp
*.swo
.DS_Store
Thumbs.db

```

---

# 📌 ÉTAPE 3 — CONFIGURER LE REPO GITHUB

## 3.1 Settings → About (en haut à droite du repo)

**Description** (copie-colle exact) :
```

Local code verifier. Detects Python, JSON, YAML, HTML, CSS, SQL errors without sending your data. Zero dependencies. Works offline.

```

**Website** :
```

http://localhost:9099

```

**Topics** (ajoute ces 15) :
```

python
code-verifier
syntax-checker
linter
developer-tools
local-first
privacy
offline
codemirror
python3
json
yaml
no-dependencies
open-source
self-hosted

```

## 3.2 Settings → Social preview
Upload une image **1280×640** avec :
- Logo `{}` en grand
- "CodeScope" en titre
- "Local code verifier" en sous-titre
- Couleurs : `#02040a` fond, `#00d4ff` → `#a855f7` dégradé

---

# 📌 ÉTAPE 4 — PUSH LE CODE

## 4.1 Sur ton PC :

```bash
cd ~/Documents
git clone https://github.com/TON-PSEUDO/codescope.git
cd codescope

# Copie codescope.py à la racine
cp /chemin/vers/codescope.py .

# Remplace le README
nano README.md
# Colle le contenu ci-dessus

# Remplace LICENSE
nano LICENSE
# Colle le contenu ci-dessus

# Remplace .gitignore
nano .gitignore
# Colle le contenu ci-dessus

# Push
git add .
git commit -m "Initial release: CodeScope v1.0.0"
git push origin main
```

4.2 Vérifie sur GitHub

```
https://github.com/TON-PSEUDO/codescope
```

Tu dois voir :

· ✅ Le README qui s'affiche
· ✅ Les badges
· ✅ Les topics en bas
· ✅ Le code Python

---

```
https://github.com/Aissamohammedi88/codescope/


6.5 Site web
