The issue appears when using `pnpm biome check .` or the included script `pnpm check`

`files.include` with nested subdirs doesn't work at all.

`files.ignore` doesn't work as documented. It causes `include` to be ignored entirely.

Only thing that works is by not using `include` and excluding everything explicitly with `ignore`.
