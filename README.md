# mdl-recipes

Recipe catalogue for [mudev](https://github.com/mutms/mudev): Moodle site definitions
(core + optional patches + a selection of plugins), grouped at
`<vendor>/<stream>/<version>.yaml` (identifier `vendor/stream/version`) — e.g.
`mutms/dev/5.2` (rolling dev workspace) or `mutms/release/5.2.2.01` (pinned release). See
mudev's `docs/recipe-format.md` for the format and the embedded JSON Schema.

## License & contributing

The recipe data is dedicated to the public domain under **CC0 1.0** ([LICENSE](LICENSE)) —
copy, adapt and use it for anything, commercially or not, with no attribution required. Each
recipe's `contributed_by` value records who wrote it; keeping that credit when you reuse a
recipe is appreciated, but it is a courtesy, not a license condition. Contributions are
welcome under the same terms: by adding a recipe you dedicate it to the public domain too
(add your `contributed_by` so the courtesy credit can travel with it).

Data imported from external databases keeps its own license; any such import lives in a
clearly marked location with its source and license stated.

## Trademarks

Moodle™ is a registered trademark of Moodle Pty Ltd. This project is independent and is not
affiliated with, endorsed by, or sponsored by Moodle Pty Ltd. "Moodle" is used here only to
refer to the genuine Moodle software (e.g. an unmodified stable branch with additional
plugins). The `moodle` recipe edition denotes MuTMS running on unmodified Moodle core.
