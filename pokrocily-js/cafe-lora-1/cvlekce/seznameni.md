---
title: Seznámení s projektem a úprava menu
demand: 2
---

Seznamte se se zdrojovým kódem, který je pro vás v projektu připraven. Postupujte dle následujících kroků.

1. Prohlédněte si HTML a CSS projektu.
1. Všimněte si, že ikonka pro zobrazení navigace (hamburger menu) se zobrazuje i v případě, že jsme na širokém monitoru. Upravte CSS v souboru `style.css` tak, aby se ikonka na široké obrazovce nezobrazovala. Breakpoint zjistíte při prohlížení různých šířek stránky v devtools nebo v CSS. Po úpravě CSS proveďte commit vašich změn s nějakou dobře popisnou zprávou.
1. Položky navigace v hlavičce stránky nefungují. Doplňte tedy v `index.html` atributy `id` pro jednotlivé sekce a pozměňte odkazy v nabídce tak, abychom se vždy po kliknutí na odkaz přesunuli na správnou část stránky. Commitněte vaše změny se smysluplnou commit zprávou.
1. Sekce s názvem galerie je momentálně jen jeden velký obrázek. My budeme chtít, aby přes obrázek byl text popisující kavárnu. Doplňte do sekce odstaveček textu popisující interiér kavárny a nastylujte ho tak, aby byl přes obrázek čitelný – přidejte například poloprůhledné pozadí textu (pomůže zadání barvy s průhledností pomocí `rgba()`) nebo rozmazání stránky pod textem (najděte si CSS vlastnost `backdrop-filter`). Někdy pomůže také stínování textu – CSS vlastnost `text-shadow`.
1. Opět proveďte commit vašich změn s odpovídající commit zprávou. Pushněte do repozitáře na GitHubu.
