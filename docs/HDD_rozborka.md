# Rozebraný pevný disk (HDD) – části a jejich funkce
Třída: T4A | Autor: Josef Černý | Datum: 03.12.2025

## Úvod
Cílem je stručně popsat hlavní části pevného disku (HDD), ukázat jejich umístění na fotografiích a vysvětlit základní funkci každé části.

---

## Obrázek 1: Flex kabel a konektor hlav (HSA flex)
![Obrázek 1: Flex kabel a konektor hlav – přenos signálu z hlav do PCB](img/1.jpg)
- Přenáší signály z čtecích/zapisovacích hlav do hlavní elektroniky (PCB) a napájení pro hlasovou cívku. U některých modelů bývá na flexu i předzesilovač (preamp).

## Obrázek 2: Stator vřetenového motoru (spindle stator)
![Obrázek 2: Stator vřetene – cívky roztočí plotny](img/2.jpg)
- Kruhový stator s měděnými cívkami vytváří rotující magnetické pole, které roztáčí rotor vřetene s plotnami (typicky 5 400–7 200 ot./min).

## Obrázek 3: Plotna disku na základně HDA
![Obrázek 3: Plotna – magnetické médium pro uložení dat](img/3.jpg)
- Lesklá magnetická plotna uchycená na náboji vřetene ukládá data ve stopách a sektorech. Pozn.: dotyk/šmouhy mohou disk znehodnotit.

## Obrázek 4: Raménko aktuátoru
![Obrázek 4: Raménko – polohuje čtecí/zapisovací hlavy](img/4.jpg)
- Lehký hliníkový nosník s ložiskem; nese hlavy a přesně je polohuje nad stopu pomocí hlasové cívky a permanentních magnetů.

## Obrázek 5: Permanentní magnety aktuátoru
![Obrázek 5: Magnety – pole pro pohyb raménka](img/5.jpg)
- Silné neodymové magnety vytváří magnetické pole, proti kterému působí hlasová cívka; zajišťují rychlé a přesné natáčení raménka.

## Obrázek 6: PCB řadiče a izolační/EMI podložka
![Obrázek 6: PCB – řadič, cache, napájecí obvody](img/6.jpg)
- Řadič (SoC), paměť cache (DRAM), napájecí/ochranné obvody a driver motoru. Řídí motor, aktuátor, zpracování signálu z hlav a komunikaci (SATA/PATA). Podložka brání zkratům a tlumí rušení.

## Obrázek 7: Horní kryt HDA (vnitřní strana)
![Obrázek 7: Kryt – těsnění a vyrovnání tlaku](img/7.jpg)
- Utěsňuje čisté prostředí uvnitř disku; vedení vzduchu kolem recirkulačního filtru a „breather“ pro vyrovnání tlaku.

---

## Závěr
Pevný disk kombinuje přesnou mechaniku a elektroniku; čisté prostředí a přesné polohování hlav umožňují spolehlivé uložení dat.

## Poznámky
- Při manipulaci s otevřeným HDD hrozí kontaminace prachem a poškození hlav/ploten.
- Nezakrývejte dýchací otvor. Vyvarujte se statické elektřiny (ESD).