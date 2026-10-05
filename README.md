<!-- tyhp-readme:start -->
# tyhpdef/webmozart-assert

Tyhp type definitions for `webmozart/assert` `2.4.1`.

```bash
composer require --dev tyhpdef/webmozart-assert:2.4.1
```

This is a metapackage. Composer also installs `tyhpdef/webmozart-assert-impl` (type files).
Require **this** name, not `tyhpdef/webmozart-assert-impl`.

See https://tyhplang.com.

## Maintain `webmozart/assert`? Ship the types yourself

If you are a Packagist maintainer of `webmozart/assert`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/webmozart-assert-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `webmozart/assert` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/webmozart-assert": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `webmozart/assert` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `webmozart/assert` with a real constraint,
   `"replace": { "tyhpdef/webmozart-assert": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `webmozart/assert` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/webmozart-assert` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
