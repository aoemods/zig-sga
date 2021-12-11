# zig-sga

Low-level minimal allocation implementation of Relic's funky archive format in Zig with comments and clearly named variables.

## Getting sgatool

You can grab a copy of `sgatool`, the actually executable portion of `zig-sga`, from the latest successful CI run, the latest release (soon), or by compiling the program yourself.

### Compiling

First, install [Zig](https://ziglang.org/). Then:
```bash
git clone https://github.com/aoemods/zig-sga
cd zig-sga
zig build
# Output in ./zig-out/bin!

# Or to run it right away (useful for developers)
zig build sgatool -- [args]
```

## Using as a Library

See `tools/sgatool.zig` and `build.zig` for an example of how `zig-sga` can be used as a library in Zig!

## Prior Art

Credit where credit's due!

Thanks Janne for the [awesome blog post](https://janne252.dev/content/2021/coh3-pre-alpha-extract-sga) as well as the [SGA viewer tooling](https://github.com/Janne252/essence-archive-viewer) that inspired this effort. A dozen lines of documentation are based off of a table in Janne's blog post. \<3
