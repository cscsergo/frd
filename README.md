# FRD ütemező

Egyszerű webapp egy ismétlődő teendő (FRD) nyilvántartására.

- **Hány naponta** – beállítható intervallum (1–365 nap).
- **Elvégeztem** – rögzíti az elvégzés napját; a következő időpont az *elvégzés napjától* + intervallum. Ha ma kellett volna, de holnap végzed el, a következő is egy nappal később lesz.
- **Átütemezés** – +1 nap / +2 nap / +1 hét, vagy tetszőleges dátum.
- **Előzmények** – mikor végezted el, és hány nap késéssel.
- **Export / import** – JSON mentés, más eszközre átvitelhez.

Az adatok a böngésző `localStorage`-ában tárolódnak (eszközönként külön).
Telefonon „Hozzáadás a kezdőképernyőhöz” után appként használható.

Élő verzió: GitHub Pages.
