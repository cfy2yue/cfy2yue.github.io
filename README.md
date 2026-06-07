# Feiying Chen CV Site

Personal academic CV website built with the HugoBlox Academic CV template.

## Local Preview

Use the local Hugo, Go, and Node binaries downloaded into ignored tool folders:

```bash
PATH="$PWD/.tools/node-v24.16.0-linux-x64/bin:$PWD/bin:$PWD/.tools/go/bin:$PATH" pnpm run build
PATH="$PWD/.tools/node-v24.16.0-linux-x64/bin:$PWD/bin:$PWD/.tools/go/bin:$PATH" hugo server --disableFastRender
```

The site content lives mainly in:

- `data/authors/me.yaml`
- `content/_index.md`
- `content/experience.md`
- `content/publications/`
- `content/projects/`

Original source materials such as `CV_eng.pdf` are intentionally ignored because they may contain non-public contact information.
