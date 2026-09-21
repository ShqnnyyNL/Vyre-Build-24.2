# Upload Guide

## Important privacy rule

Create or recover a **private** GitHub repository before uploading this package. The existing `ShqnnyyNL/Vyre-Build-24.2` repository was still public when this package was prepared.

## Upload

1. Extract `Vyre-GitHub-3.9.7.15-PRIVATE-DOCS.zip`.
2. Open the private repository on GitHub.
3. Upload the contents of the extracted `Vyre-GitHub-3.9.7.15` folder, including `.github`, `assets` and `docs`.
4. Commit with: `Update documentation for Vyre 3.9.7.15`
5. Confirm the repository visibility still says **Private**.

## Do not add

- Vyre source code;
- plugin JAR or private release ZIP;
- server or player data;
- production configuration;
- logs containing private data;
- passwords, tokens, database credentials or API keys.

The included `.gitignore` adds another layer of protection, but it does not replace checking every upload before committing.
