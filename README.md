# Repozitář pro testovací katalogizační záznamy
Repozitář obsahuje následující větve:
- větev `main` by měla zůstat prázdná, záznamy z ní se objeví v produkčním NKOD https://data.gov.cz
- větev `test` obsahuje záznamy, které se objeví v testovacím NKOD https://pod-test.dia.gov.cz navíc k těm došlým testovací datovou schránkou
- větev `develop` obsahuje záznamy, které se objeví ve vývojové instanci NKOD

Každá větev pak obsahuje adresáře
- `záznamy` - pro soubory reprezentující zprávy došlé datovou schránkou a vyzvednuté [NKOD-ISDS](https://github.com/datagov-cz/nkod-isds)
- `přílohy` - pro soubory z příloh datových zpráv - registrační záznamy pro NKOD tvořitelné [formulářem pro registraci lokálního katalogu](https://data.gov.cz/formulář/registrace-lokálního-katalogu) nebo [formulářem pro registraci datové sady](https://data.gov.cz/formulář/registrace-datové-sady).