# To_whom

## ZIP delivery policy for large generated projects

This repository follows a strict accuracy rule:

- Do **not** claim to provide a ZIP file unless it has actually been generated.
- Do **not** fabricate “downloadable ZIP” links or attachments.

If a user requests a full multi-file project as a ZIP, the correct behavior is:

1. Clearly state that a ZIP cannot be provided unless the files are truly generated.
2. Offer to generate the project file-by-file (or module-by-module) until complete.
3. Provide practical packaging instructions to create a ZIP locally, or use an environment that supports multi-file artifact generation.

Recommended implementation order for large PHP app requests:

1. Setup (structure, config, database)
2. Core forms + AJAX/search
3. Printing/certificate layout
4. Supporting assets, docs, samples
5. Final verification + packaging steps

This ensures transparent, honest delivery without misrepresenting outputs.
