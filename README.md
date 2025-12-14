# Goblin
GOBLIN (Graphical Output Builder for Language Integration & Narration) is a lightweight, portable SSML authoring utility that lets you paste plain text, highlight phrases, and apply speech markup through simple controls while showing the resulting SSML in a live output pane for copy/paste into other tools such an elevenlabs.

It includes a Pronunciation Manager for creating and reusing consistent pronunciations (e.g., phoneme, sub, and say-as entries), with search and filters, plus actions to apply to a selection, insert at the cursor, or apply to all occurrences (best-effort). A Tag Inspector allows you to click existing marked-up regions to review and edit attributes, unwrap tags, or save configurations for reuse. The app also supports undo/redo, a conservative Storyline-safe SSML subset view, and local, browser-only storage for saved pronunciations and snippets, with JSON import/export for portability.

How to run
1) Unzip
2) Open index.html in a browser (Chrome/Edge/Firefox)
3) Optional: open HELP.html for documentation

About
GOBLIN — Graphical Output Builder for Language Integration & Narration

New in v5
- Pronunciation Manager (structured library)
  - Save pronunciations with: Term, Method (phoneme/sub/say-as), parameters, Category/Tags, Notes
  - Search + filter by method
  - Apply to selection, insert at cursor, or apply to all occurrences (basic text-node walker)
  - Import/Export pronunciations (JSON) via clipboard prompts
  - "Send to Pronunciation Manager" from Tag Inspector for phoneme/sub/say-as tags

Also included (from v4)
- Undo / Redo
- Tag Inspector (edit attributes JSON, unwrap/remove)
- Saved Snippets (generic wrap-tag reuse)

Notes
- Output is SSML 1.1; engine support varies.
- "Apply to all occurrences" is a best-effort helper; review output for unintended matches.

Developed by ASR 2005
Licensed under GNU GPL v3.0 (GPLv3). See LICENSE.txt.
