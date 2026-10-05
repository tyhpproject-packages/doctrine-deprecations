<!-- tyhp-readme:start -->
# tyhpdef/doctrine-deprecations

Tyhp type definitions for `doctrine/deprecations` `1.1.6`.

```bash
composer require --dev tyhpdef/doctrine-deprecations:1.1.6
```

This is a metapackage. Composer also installs `tyhpdef/doctrine-deprecations-impl` (type files).
Require **this** name, not `tyhpdef/doctrine-deprecations-impl`.

See https://tyhplang.com.

## Maintain `doctrine/deprecations`? Ship the types yourself

If you are a Packagist maintainer of `doctrine/deprecations`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/doctrine-deprecations-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `doctrine/deprecations` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/doctrine-deprecations": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `doctrine/deprecations` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `doctrine/deprecations` with a real constraint,
   `"replace": { "tyhpdef/doctrine-deprecations": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `doctrine/deprecations` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/doctrine-deprecations` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
