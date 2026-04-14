# LORE Salla Theme

This folder is the GitHub-ready version of the LORE Salla theme.

## Put only these files at the repository root

- `twilight.json`
- `src/views`
- `src/assets`
- `src/locales`

## Why this folder exists

The earlier GitHub repository mixed the Salla theme with builder files and a separate Next.js prototype. Salla theme import should point to a repository whose root is the theme itself.

## Recommended upload flow

1. Create a new empty GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Make sure `twilight.json` is visible on the first page of the repo.
4. In Salla Partners, connect that repository and create the theme again.

## Important

Do not upload the surrounding app files, `node_modules`, builder folders, or nested copies of the theme when creating the GitHub repo for Salla.
