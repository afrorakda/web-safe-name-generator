# #86 Web Safe Name Generator

A minimalist, high-performance tool for designers and developers to sanitize filenames for web-safe usage. It removes "impurities" that cause server errors or broken links.

## 1 Tool / 1 Action
- **Input:** Paste a list of "dirty" filenames (with spaces, accents, special characters, or non-English letters).
- **Action:** Click "Generate Web Safe Names."
- **Output:** Get a clean, URL-friendly list ready for production.

## Features
- **Lowercase Conversion:** Automatically converts all characters to lowercase.
- **Space & Symbol Handling:** Replaces spaces and forbidden symbols with a single hyphen `-`.
- **De-Accent Logic:** Converts Latin accented characters (e.g., `é`, `à`, `ñ`) to their plain English equivalents (e.g., `e`, `a`, `n`).
- **Strict Sanitization:** Removes non-alphanumeric characters (including Japanese/Unicode) to ensure 100% compatibility with any web server.
- **Smart Fallback:** Automatically assigns `filename` if the name becomes empty after stripping unsupported characters.
- **Privacy First:** Browser-only processing. No files are uploaded; no data is tracked.

## Design System
- **Background:** `#fff`
- **Main Color:** `#333`
- **Border Radius:** `15px` (Mandatory)
- **UI:** Optimized for both Desktop and Mobile (Safari/Chrome).

## Footer
No login / No tracking / No ads / Browser only Privacy Policy / afrorakda © 2026
