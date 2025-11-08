# Como analisar empresas - Book Website

This project uses [MkDocs](https://www.mkdocs.org/) to generate a static website from Markdown files.

## Getting Started

### 1. Install Python (if not already installed)

On macOS, you can use Homebrew:

```sh
brew install python
```

Or download the official installer from [python.org](https://www.python.org/downloads/).

### 2. Create and activate a virtual environment (recommended)

This avoids permission errors and keeps dependencies isolated:

```sh
python3 -m venv venv
source venv/bin/activate
```

You should see (venv) at the start of your terminal prompt.

### 3. Install dependencies

```sh
pip install -r requirements.txt
```

This will install MkDocs and any other requirements into your virtual environment.

### 4. Serve locally

```sh
mkdocs serve
```

Or, if the above fails:

```sh
python -m mkdocs serve
```

### 5. Build static site

```sh
mkdocs build
```

Or:

```sh
python -m mkdocs build
```

The main content is in `src/index.md`.

---

#### Troubleshooting

- If you see `command not found: pip`, make sure you have activated your virtual environment and that Python is installed.
- If you see `externally-managed-environment` or permission errors, always use a virtual environment as shown above.
- If you see `command not found: mkdocs`, make sure you installed dependencies after activating the virtual environment, or use `python -m mkdocs ...`.
# documentsInvesting
