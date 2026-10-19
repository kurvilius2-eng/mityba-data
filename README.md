# Mityba – food database

The optional full food database for the **Mityba** nutrition app, downloaded from inside the app
(Settings → Food database). Nothing about the user is sent when it is downloaded.

| File | What |
|---|---|
| `foods-full.db.gz` | SQLite database, gzip-compressed (~370 000 foods) |
| `foods-full.json` | Manifest: version, size and MD5 checksum the app checks after downloading |
| `privacy-policy.md` | The app's privacy policy (Lithuanian and English) |

## Sources and licences

The database combines these sources. Each food in the app shows where it comes from.

- **Open Food Facts** – packaged products. © Open Food Facts contributors,
  [openfoodfacts.org](https://world.openfoodfacts.org). The database is available under the
  [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/); individual
  contents under the [Database Contents License](https://opendatacommons.org/licenses/dbcl/1-0/);
  product images (shown in the app, not included here) under CC BY-SA.
- **USDA FoodData Central** – U.S. Department of Agriculture, Agricultural Research Service.
  Public domain.
- **Livsmedelsverket** (Swedish Food Agency) – Livsmedelsdatabasen,
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **ANSES Ciqual** (France) – Ciqual table de composition nutritionnelle des aliments,
  [Licence Ouverte / Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence).

## Licence of this database

Because it contains data from Open Food Facts, **this database as a whole is made available under
the Open Database License (ODbL) 1.0**: you may use, share and adapt it, provided you attribute the
sources above and share any adapted database under the same licence. This applies to the data only,
not to the Mityba app.
