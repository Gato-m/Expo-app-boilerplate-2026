# Expo HAS CHANGED

Read the exact versioned docs at https://docs.expo.dev/versions/v57.0.0/ before writing any code.

# Expo Project Instructions

## Package management

- Use `npx expo install <package>` for Expo-compatible packages.
- Do not use `npm install` for packages that Expo manages or provides compatibility guidance for.
- Do not manually guess Expo package versions.
- Preserve compatibility with the project's installed Expo SDK.

## Expo workflow

- Use Expo Skills when they are relevant.
- Use Expo MCP tools when they provide relevant information or actions.
- Before significant dependency changes, inspect the current Expo SDK and package versions.
- Run `npx expo-doctor` after dependency or Expo configuration changes.

## Code changes

- Inspect existing project patterns before introducing new architecture.
- Prefer the project's existing libraries and conventions.
- Do not add dependencies unless they are necessary.

## Validation

After making changes:
1. Run the appropriate TypeScript check.
2. Run lint if configured.
3. Run relevant tests if available.
4. Run `npx expo-doctor` for Expo/dependency changes.
5. Review `git diff`.

## Git safety

- Never run `git push` automatically.
- Ask before creating a commit.
- Never reset, checkout, clean, or otherwise discard user changes without explicit approval.