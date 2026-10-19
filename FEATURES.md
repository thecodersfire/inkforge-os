# Built-in features for inkforge-os

Purpose: long-form writing

1. **prepare a creative project** — run inkforge-os-workspace. It creates ~/Documents/inkforge-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run inkforge-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/inkforge-os-session-plans/.
3. **check project and export readiness** — run inkforge-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/inkforge-os-workspace features/inkforge-os-plan features/inkforge-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for long-form writing:

1. **GIMP** — org.gimp.GIMP
2. **Inkscape** — org.inkscape.Inkscape
3. **Krita** — org.kde.krita

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for long-form writing:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
3. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
4. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
5. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
6. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
7. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
8. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
9. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
