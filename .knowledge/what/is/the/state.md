---
status: "green"
revised_at: "2026-09-22T11:07:34+10:00"
---

The Website's Field Notes table on the homepage and `field-notes/index.html` uses reverse chronology. Its three 21 September 2026 entries appear as PetaLinux 101, the Jev correction, then the first Jev experiment. The PetaLinux note remains the accepted Field Notes style reference.

`field-notes/jev-jacobian.html` reads as David's contemporaneous first account: after building a TypeSafe Jev Yes/No/Maybe CLI with a `where` context option, he saw Maybe for the bare conjecture question, No with the Alpöge counterexample, and Maybe with a bijection, then asked Codex for a 500-map experiment. The original terminal PNG is centered and linked at full size. The page reports the original 420/500 (84.0%) intended response pattern and refers to the later correction only in its top banner. `field-notes/jev-jacobian-correction.html` contains David's hand-edited account of discovering the determinant confound, a short terminal-styled Codex/David transcript, and the matched 244/500 (48.8%) result. The pilot and both 500-map JSON files remain available for download.

Commit `769642a` on `main` contains the finished Jev pages, screenshot, shared styling, and the Website `.knowledge/` tree; `origin/main` received it on 2026-09-22. GitHub Pages built that exact commit successfully. The two live Jev pages returned HTTP 200 with their expected text, and the live PNG returned HTTP 200 with bytes matching the committed source. Local links and images resolved, `git diff --check` passed, and desktop/mobile Chromium renders were inspected. The sibling `jev-jacobian-bench` project's current knowledge treats the matched run as its result; its benchmark files were not changed for the site publication.
