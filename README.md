# Example Brand (static probe)

A Simply Static export of the local WordPress probe running the CDS theme. Example Brand is the placeholder identity. The walk in the header is the system: Start, Color, Type, Layout, Sections, then The site.

Live: https://roots-and-fruit.github.io/rf-static-probe/

The kit itself (HTML reference + theme source) lives in [design-system-template](https://github.com/Roots-and-Fruit/design-system-template). This repo is only the exported files. Not rootsandfruit.com.

## Loop

1. Studio site `rf-static-probe` at http://localhost:8893
2. `node scripts/sync-theme.mjs --dest "C:/Users/reach/Studio/rf-static-probe/wp-content/themes/cds"`
3. `studio wp --path ... eval-file wordpress/probe-seed-showcase.php`
4. Simply Static → `static-export`
5. Copy that folder here, commit, push
