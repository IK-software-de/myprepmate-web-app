# Offline app fonts

These are the unmodified normal font variants used by MyPrepMate. The
font files come from the official Google Fonts URLs declared by
`google_fonts` 6.3.3. Every download was checked against the package's
SHA-256 digest and expected size; `sources.json` records both.

The Google button's Roboto Regular/Medium files are the unmodified Flutter
SDK Material font assets. Their Apache license is `Roboto-LICENSE.txt`.

Each family is distributed under its included SIL Open Font License.
The application registers these licenses in Flutter's license registry.
`google_fonts` discovers the assets by filename; runtime fetching is disabled.

When changing the font package or adding a variant, update the matching
asset and confirm that light and dark themes load with runtime fetching off.
