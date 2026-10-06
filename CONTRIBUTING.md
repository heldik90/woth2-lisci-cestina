# Contributing / Jak pomoci

## Hlášení chyby

Založte Issue a přidejte:

- český text, který je chybný, a navrhovanou opravu;
- místo ve hře: obrazovku, úkol nebo dialog;
- verzi hry a revizi češtiny, pokud je znáte;
- screenshot pro kontext, ideálně bez osobních údajů.

## Úprava překladu

V souboru `.po` upravujte příslušné `msgstr`. Zachovejte `msgid`, `msgctxt`, identifikátory a komentáře. Zachovejte zástupné proměnné, herní formátovací značky, význam odstavců a názvy, které mají zůstat v originále. Pokud je chybný samotný zdrojový text, vysvětlete to v Issue; nepřepisujte ho bez vysvětlení v katalogu.

Překlady v `runtime_string_overrides.json` mohou mít aktuálnější originál než katalogy `.po`. U nich porovnávejte české `translation` s odpovídajícím `source`. Identifikátory a kontrolní součty zachovejte. Totéž platí pro doplňkové položky v `supplemental_strings.json`.

Do popisu pull requestu napište důvod změny a případný kontext ze hry. Posílejte vlastní návrhy; při použití práce jiného překladatele uveďte původ a oprávnění k použití.

## English

Please report the exact Czech text, the suggested correction, its in-game context, and the game/translation version if known. Screenshots help resolve ambiguous wording.

When editing PO catalogs, change `msgstr` and preserve `msgid`, `msgctxt`, identifiers, placeholders and game markup. Runtime overrides may use more current English source text than the PO exports; review their `translation` against `source` and preserve the keys and hashes.

Explain each proposed change in a pull request. Submit your own suggestions and identify the origin and permission for any third-party translation material.
