# Denní sběr a ukládání měnových kurzů z ČNB

## Úvod

V rámci tohoto úkolu budete mít za úkol vytvořit automatizovaný ETL proces, který bude denně stahovat měnové kurzy **hlavních i ostatních měn** z webových stránek České národní banky (ČNB) a ukládat je ve formátu Parquet.

## Zadání

1. **Denní stahování kurzů:**
   - **Webové stránky ČNB**: [Kurzy měn](https://www.cnb.cz/cs/financni-trhy/devizovy-trh/)
   - Implementujte Python skript, který bude denně stahovat všechny dostupné kurzy měn z webových stránek ČNB.
  
2. **Uložení dat:**
   - Uložte data do formátu Parquet.
   - Data by měla být ukládána způsobem, který umožňuje zpětnou analýzu historických kurzů.

## Požadavky na technologie

- **Programovací jazyk**: Python
- **Výstupní formát**: Parquet

## Odevzdání
- Odevzdejte v podobě Github repozitáře. Link na repozitář prosím odešlete na e-mail jakub.skapik@fidoo.com
