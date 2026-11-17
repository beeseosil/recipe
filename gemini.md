# Agent Execution Rules for Recipe Repository

## 1. Documentation Reflection Rule
- Any recipe modifications, additions, or tips discussed and agreed upon with the user must be immediately reflected in the corresponding markdown files under `./recipe` (e.g., `risotto.md`, `pilaf.md`).
- **Required Section**: Every recipe markdown must include a **'미리 전처리 가능한 것'** (Pre-preparable items / Advance preparation guide) section detailing items that can be prepped in advance versus items that should be prepped immediately before cooking.

## 2. Git Commit & Push Rule
- Repository: `https://github.com/beeseosil/recipe.git`
- Whenever changes are made to markdown files in `./recipe`, automatically commit and push the updates directly to the remote repository without waiting for explicit git instructions.
- Ensure commit messages clearly describe the reflected recipe changes.
