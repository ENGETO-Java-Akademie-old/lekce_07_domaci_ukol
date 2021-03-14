# lekce_07_domaci_ukol

V sedmé lekci jsme si ukázali jak použít `ArrayList` a `HashMap` jak pro ukládání Stringu, čísel, tak i vlastních objektů. Také jsme si ukázali, jak správně porovnávat objekty pomocí metod `equals()`.

Za domácí úkol vytvořte jednoduchou aplikaci reprezentující telefonní seznam. Nejprve si vytvořte několik záznamů typu `Kontakt`, který obsahuje:
- Telefonní číslo
- Jméno
- Příjmení
- Kategorii (RODINA, PRACE, OSTATNI)

| Telefonní číslo      | Jméno | Příjmení | Kategorie |
| ----------- | ----------- | ----------- | ----------- |
| +420602111222      | Jan       | Novak | PRACE |
| +420212342143      | Tomas       | Zeleny | PRACE |
| +420602222345      | Jana       | Novakova | OSTATNI |
| +420602553233      | Sef       |  | PRACE |
| +420612533434      | Rodice - pevna       |  | RODINA |

Vytvořte program, který bude mít následující metody:
- Na základě celého telefonního čísla vyhledá Kontakt
- Na základě jména nebo příjmení najde seznam záznamů
- Na základě části telefonního čísla najde seznam záznamů, které obsahuje onu část telefonního čísla


## Bonus
Jako bonus se zkuste zamyslet, jak řešit možnosti uživatelských úprav seznamu kontaktů a dopad na funkcionalitu. 
Umožníte dplicitní záznamy? 
Co budete považovat za duplicitní záznamy v případě, že `Kontakt` rozšíříte o další pole jako Adresa nebo druhé telefonní číslo?
Máte představu, jak to bude fungovat, když těch záznamů budete mít v několik tisíc? A co když celý veřejný telefonní seznam?
