# Built-in features for inkforge-os

Purpose: long-form writing

1. **prepare a creative project** — run inkforge-os-workspace. It creates ~/Documents/inkforge-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run inkforge-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/inkforge-os-session-plans/.
3. **check project and export readiness** — run inkforge-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/inkforge-os-workspace features/inkforge-os-plan features/inkforge-os-check "$HOME/.local/bin/"
