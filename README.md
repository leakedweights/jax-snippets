# JAX Snippets

Welcome to the JAX Snippets repository! This repository contains custom Visual Studio Code snippets to help you quickly import common JAX and Flax components into your Python projects.

## Directory Structure

```
jax-snippets/
├── jax-snippets/
│   ├── utils.json
│   ├── modules.json
│   └── imports.json
├── .gitignore
├── LICENSE
├── README.md
```

## How to Import Snippets into VS Code

Follow the steps below to import the snippets into Visual Studio Code:

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/leakedweights/jax-snippets.git
```

### 2. Open User Snippets in VS Code

1. Open Visual Studio Code.
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the Command Palette.
3. Type `Preferences: Configure User Snippets` and select it.
4. Select `New Global Snippets file...`.

### 3. Copy Snippet Content

1. Open the corresponding snippet file in the `jax-snippets/jax-snippets` directory. For example, open `imports.json` for import snippets.
2. Copy the entire content of the file.

### 4. Paste into VS Code Snippet File

1. In the snippet file that VS Code opened, paste the copied content.
2. Save the file.

### 5. Use the Snippets

Now, you can use the snippets in your code. For example, type `jaxflax` and press `Tab` or `Enter` to insert the snippet.

## Example Snippet

Here is an example snippet from `imports.json`:

```json
{
  "Import JAX and Flax": {
    "prefix": "jaxflax",
    "body": [
      "import jax",
      "import jax.numpy as jnp",
      "from jax import random",
      "from flax import linen as nn",
      "from flax.training import train_state",
      "import optax",
      "",
      "# Your code starts here"
    ],
    "description": "Import common JAX and Flax components"
  }
}
```

### Description

- **prefix**: `jaxflax` - This is the trigger word for the snippet.
- **body**: The lines of code that will be inserted.
- **description**: A brief description of the snippet.
