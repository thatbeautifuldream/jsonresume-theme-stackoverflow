# How to Test Your Theme Locally

## Install dependencies

If you haven’t already, install the dependencies:

```bash
pnpm install
```

## Install the JSON Resume CLI

If you don’t have it globally:

```bash
pnpm install -g resume-cli
```

## Link your theme for local development

In your theme directory, run:

```bash
pnpm link
```

Then, in the directory with your resume.json, run:

```bash
pnpm link jsonresume-theme-stackoverflow
```
