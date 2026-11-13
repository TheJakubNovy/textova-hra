# Nebezpečí na Mezinárodní vesmírné stanici

Textová hra v Pythonu o útěku z porouchané Mezinárodní vesmírné stanice (ISS).

Probudíš se na zemi po nárazu a skoro nic si nepamatuješ. Stanici zasáhl roj asteroidů a ze stěny uniká vzduch. Musíš přežít, projít místnosti stanice, posbírat předměty a připravit únikový modul. Před odletem je potřeba **opravit elektřinu, doplnit palivo a opravit padák**. Cestou tě čeká souboj a některá rozhodnutí mohou skončit smrtí.

## Jak hru spustit

1. Otevři soubor s hrou ve **VS Code** jako Jupyter notebook: `TODO: název souboru .ipynb`
2. Klikni na tlačítko **start (▶)** u buňky s hrou.
3. Hra se zeptá: „napiš 1 pro začátek hry“. Napiš `1` a stiskni **Enter**.

**Potřebuješ:**
- VS Code s podporou Jupyter notebooků,
- Python verze `3.12.14`.

Hra nepotřebuje žádné další knihovny, používá jen vestavěný modul `random`.

## Jak se hra ovládá

- Hra ti vždy nabídne očíslované možnosti. Vybereš napsáním čísla (`1`, `2`, `3`…) a stiskem **Enter**.
- Místo čísla můžeš kdykoliv napsat příkaz:
  - `inventář`: vypíše, co máš u sebe,
  - `životy`: vypíše, kolik máš životů.
- Když zadáš něco jiného, hra tě upozorní a zeptá se znovu.
- U dveří s panelem můžeš místo čísla zadat čtyřmístný kód.

### Souboj

Na začátku souboje máš 15 energie. V každém kole si vybereš:

1. **útok**: stojí 5 energie,
2. **odpočinek**: doplní 5–7 energie,
3. **doplnění životů**: vypiješ džus (+50 životů), pokud ho máš v inventáři.

## Autor

[TheJakubNovy](https://github.com/TheJakubNovy)
