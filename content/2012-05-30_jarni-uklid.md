Title: Jarní úklid
Date: 2012-05-30 14:28:07

Jak jsem [avizoval]({filename}2012-01-20_uz-jsi-s-tim-saskovanim-kolem-blogu-trapny.md), tak se stalo. Vymetl jsem na blogu pavučiny, dal jsem mu nová střívka, nový kabátek. V odkazovaném článku jsem sice psal, že to udělám večer před státnicemi, ale nakonec jsem to stihl dřív :-) Pracoval jsem na tom po malých kousíčkách několik měsíců, vždy ve volné chvilce mezi učením.

Co je nového?

- Blog je kompletně [na GitHubu](https://github.com/honzajavorek/blog). Nejen zdrojový kód, ale i [samotné HTML stránky](https://github.com/honzajavorek/blog/tree/gh-pages) (využívá tedy [GitHub Pages](http://pages.github.com/)). Můžete mi opravovat chyby v článcích posíláním *pull requestů* ;-) Taky to samozřejmě funguje i jako nezničitelná [záloha]({filename}2011-12-11_jak-jsem-ublizil-svemu-denicku.md).
- Adresy na RSS/Atom vedou nyní přímo na služby, které je poskytují. Tedy [Disqus](http://disqus.com) a [Feedburner](http://feedburner.com). Myslím, že umístění blogu měním o dost častěji, než tyhle služby, takže jsou pro čtenáře nakonec jistějším opěrným bodem :-) Zatím by mělo fungovat přesměrování, ale nevím jak dlouho - lepší bude, když si adresy změníte ve svých čtečkách.
- Deníček je generován do statického HTML pomocí skvělého nástroje [Pelican](http://pelican.notmyidea.org) (Python). To znamená, že veškerou interakci na webu obstarává JavaScript (moc jí není, jen komentáře) a že by se všechny stránky měly načítat superrychle.
- Vše je na nové doméně `honzajavorek.cz`. Na `blog.javorek.net` ani `honza.javorek.net` nic už nikdy nebude. Ostatně, v blízké době nejspíš zanikne celé `javorek.net`, ale to je jiná pohádka.
- Všechny články jsou nyní ve značkovacím jazyce [Markdown](daringfireball.net/projects/markdown/). Mám [Texy!](http://www.texy.info) moc rád, ale nejsem si jistý jeho budoucností (vývoj tak nějak stojí) a jeho podpora ve světě je zcela minimální. Použít jej v Pythonu je obtížné (neříkám nemožné!) a chtít blog zmigrovat někam jinam, je to vždy velká překážka. Připravuji malý Python filtr [tipi](https://github.com/honzajavorek/tipi), který bude vylepšovat typografii výstupu z Markdownu podle českých pravidel.
- Blog je ještě jednodušší. Snažil jsem se, aby měl úplné minimum nutných funkcí. Některé jsou celkem skryté (třeba [archiv](http://honzajavorek.cz/archives)), ale kdo hledá, najde. A kdo nehledá, tomu nepřekáží. Soustředil jsem se na *obsah sdělení*.
- Při stylování blogu jsem si hrál. Např. to zelené logo nahoře je v SVG. Tvořil jsem to všechno hlavně pro své potěšení. Protože mi vůbec nečiní potěšení optimalizovat pro Internet Explorer, nezobrazí se styly žádnému pod verzi 9. Kruté, ale co. Článek si návštěvník přečíst může, HTML šablona je napsána, řekl bych, sémanticky a přehledně. Stejně jako [se to kdysi dělávalo s Netscape Navigátorem](http://www.pixy.cz/pixylophone/2004_12_archiv.html#1103239648)... Jednou se možná hecnu a pro IE to odladím. Nechtěl jsem však, aby to zdržovalo spuštění blogu. Stejně tak s tiskovými styly - tiskne si někdo mé články? Dejte mi vědět, třeba ty styly dodělám.
- No a narovinu říkám, že mě moc nebaví testovat mobilní zobrazení. Takže se nepřidávám do současného trendu *mobile first* nebo *mobile only*, spíš jsem se web prostě jen pocitově snažil udělat tak, abych snad kladl co nejméně klacků pod nohy. V Opeře Mini, [kterou mám já](http://localhost/blog/output/blog/proc-si-koupim-jednoduchy-telefon), to není *tak strašný*. Klidně napište doporučení na úpravy, jež by vám čtení na mobilu usnadnily.
- Komentáře mají rozhraní pořád v angličtině, protože za to polovičaté české bych se fakt styděl. Napsal jsem Disqusu, že jim tu českou verzi klidně vylepším. Uvidíme, co napíšou.

Nu a to je asi tak vše. Těšte se na nové články, mám při tom učení hrozný tvůrčí a myšlenkový přetlak.

## Aktualizace

Na základě připomínek jsem udělal následující úpravy:

- Logo v SVG jsem nahradil jeho verzí v PNG. Svět očividně na SVG v CSS není stále připraven, nechytal se ani Chrome (vivat Firefox!).
- Zkusil jsem opravit fonty tak, aby se lépe zobrazovaly na Windows. Pomůže to? Nevím.
- Povolil jsem styly pro Internet Explorer 7 a vyšší. Prý bylo zobrazování, až na menší chybky, v pohodě.
