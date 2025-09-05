# Excel-Case study-Analýza e-shopových dat
Analýza e-shopových dat v Excelu

Tento projekt byl zaměřen na analýzu dat z e-shopu, kde jsem pracoval se dvěma tabulkami – Transactions a Products. Tabulka Transactions obsahovala jednotlivé objednávky, zatímco tabulka Products sloužila jako databáze produktů s jejich kategorií a cenou. Cílem bylo odpovědět na několik analytických otázek a přitom ukázat postup řešení, použití konkrétních funkcí a práci s kontingenčními tabulkami.

Na začátku jsem obě tabulky propojil pomocí funkce XLOOKUP, díky čemuž jsem mohl do tabulky transakcí doplnit ceny produktů a spočítat celkovou tržbu pro každou objednávku. Následně jsem vytvořil kontingenční tabulku, která ukázala, že nejvyšší obrat má kategorie Televize. Díky seřazení kategorií podle tržeb jsem snadno identifikoval, že tato kategorie generuje největší část příjmů.

Dále jsem zkoumal, jak se obrat vyvíjí v čase. Pomocí kontingenční tabulky jsem rozdělil tržby i počty prodaných kusů podle měsíců a produktových kategorií. Z toho bylo patrné, že jednotlivé měsíce se od sebe liší a prodeje mají kolísavý vývoj. Tento krok mi ukázal, jak lze využít časové členění dat k odhalení trendů.

Poté jsem analyzoval, který den v týdnu je nejsilnější z pohledu počtu objednávek. Pomocí funkcí DENTÝDNE a ZVOLIT jsem si vytvořil pomocné sloupce s číselným a textovým označením dne. Ty jsem pak použil v kontingenční tabulce, kde se ukázalo, že nejvíce objednávek přichází v sobotu.

Další úkol se zaměřil na to, které kategorie produktů se nejčastěji prodávají společně s televizemi. K tomu jsem si vytvořil pomocný sloupec s kategoriemi zakoupenými spolu s televizí a následně využil funkce UNIQUE a COUNTIF. Analýza ukázala, že s televizí se nejčastěji prodává kategorie Audio, která se objevila v kombinaci s televizí celkem desetkrát.

V další části jsem hodnotil, zda navýšení marketingového rozpočtu vedlo ke změně tržeb. Rozdělil jsem data na období před a po stanoveném datu, vypočítal průměrné tržby pomocí funkce PRŮMĚR a pak je porovnal. Výsledky ukázaly, že po zvýšení rozpočtu došlo k růstu průměrného obratu o 3,9 %. Uvědomil jsem si ale, že korelace nemusí nutně znamenat příčinnou souvislost, protože výsledek může být ovlivněn i dalšími faktory, například sezónností nebo změnami v chování zákazníků.

Nakonec jsem řešil otázku, zda má pořadí produktů na stránkách e-shopu vliv na chování zákazníků. Připravil jsem návrh metod, jak tento vliv ověřit. Zaměřil jsem se zejména na A/B testování, sledování heatmap pomocí nástrojů jako Hotjar nebo využití Google Analytics. Kromě toho jsem navrhl i zákaznické dotazníky a průzkumy, které by mohly poskytnout cennou zpětnou vazbu. Díky tomu jsem si uvědomil, že defaultní pořadí produktů může mít vliv na zákazníky a je důležité jej testovat a analyzovat.

Celý projekt mi umožnil propojit teoretické znalosti s praktickou prací v Excelu. Naučil jsem se efektivně používat funkce jako XLOOKUP, COUNTIF, DENTÝDNE, ZVOLIT a PRŮMĚR, pracovat s kontingenčními tabulkami a vytvářet pomocné výpočty. Zároveň jsem se naučil přemýšlet nad daty v širším kontextu a formulovat doporučení, která by mohla mít praktické využití pro řízení e-shopu.
