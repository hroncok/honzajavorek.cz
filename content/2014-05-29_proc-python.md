Title: Proč Python?
Date: 2014-05-29 01:56:30

Občas se mě někdo zeptá, proč vlastně "kopu za Python". Co že je na něm tak úžasného. Zkusím to nějak sepsat.

Můžete mít rádi svou zahradní sekačku, ale stejně ji nepoužijete, když budete potřebovat míchat těsto na bábovku nebo vrtat poličku. Ačkoliv můžeme polemizovat nad tím, že pokud je programovací jazyk [Turing-complete](https://cs.wikipedia.org/wiki/Turingovsk%C3%A1_%C3%BAplnost), tak v něm lze teoreticky napsat cokoliv, asi se pragmaticky shodneme na tom, že s programovacími jazyky je to v něčem spíše jako s tou sekačkou a vrtačkou. Aplikace pro iOS je nejlepší psát v Objective-C, skriptování v prohlížeči se nejsnadněji dělá v JavaScriptu, ovladač k tiskárně se píše v C, atd.

Jenže pak máme ještě hromadu aplikací, kde to tak vyhraněné není, nebo je to minimálně sporné. Potom většinou nastupují emoce a sympatie. Řekněme třeba web. Web můžete udělat v PHP, Ruby, Pythonu, JavaScriptu/Node.js, Haskellu, ... Kvalita ekosystému, rychlost vývoje a podobné argumenty tady moc nehrají roli, protože když se to sečte a podtrhne, tak jsou ty technologie prostě srovnatelné. Áno, Node.js může být asynchronnější a rychlejší než třeba zrovna ten Python, ale zase si u něj nabijete čumák v něčem jiném - všechno má svá pro a proti. Ekonomicky je to prostě jedno - pokud tedy nebudeme uvažovat i to, jak je snadné najít na tu kterou technologii vývojáře, atd.

Tak. A teď si říkáte - no jo, ale nechtěl jsi psát článek o tom, jak je Python nejlepší na světě? Zatím to vypadá, že je to programovací jazyk jako každý jiný. No tak vám teď něco prozradím: Je to tak! Python je, stejně jako každý jiný programovací jazyk, prostě nástroj. Nástroj, který máte použít tehdy, kdy se vám hodí. A nástroj, který má zůstat v šuplíku, pokud to s něčím jiným uděláte lépe nebo rychleji. Python není nejlepší na světě a pokud všechno přepíšete z PHP do Pythonu, tak to váš byznys rozhodně nijak zázračně nezachrání.

Takže... Proč Python? Důvody jsou osobní, subjektivní. Proč se mi Python zalíbil? No, přecházel jsem z PHP...

- Líbilo se mi, že je systematický a nemá takový bordel ve standardní knihovně apod. Dávalo to holt tak nějak všechno větší smysl a lépe to do sebe zapadalo. Já jsem přece jenom v určitých věcech detailista, takže toto mi dost imponovalo.
- Python je víceúčelový jazyk. Jasně, všichni dneska děláme webíky, je to free, cool a in, ale kdo ví co bude za pár let? Python tady [byl](https://twitter.com/spazef0rze/status/471316103793475584), je a nejspíš bude. PHP je "dobré" jen na jednu věc - na web. Se skřípěním zubů z něho vydojíte nějakou CLI aplikaci, ale tím to končí, není to víceúčelový jazyk. Ruby je na tom lépe - je navržené jako víceúčelový jazyk, ale realita je taková, že se proslavilo díky Rails, tzn. webovému frameworku, a jeho ekosystém AFAIK jen málokdy překročí hranici světa webů a CLI prográmků. V Pythonu je třetina Linuxu, celý Dropbox, je out-of-box přítomen na každém serveru (skriptování), napíšete v něm GUI aplikaci stejně dobře a rychle jako IRC bota nebo tu webovou stránku. Říkal jsem si, že když budu umět Python, může se svět ubírat kudy chce a já se neztratím. Mimochodem, znáte třeba [RapsberryPi](http://www.raspberrypi.org/tag/python/)? Co myslíte, bude se vám hodit spíš PHP, nebo spíš Python, až se sem přižene Internet of Things?
<blockquote class="twitter-tweet" lang="en"><p>taky umíte ovládat svou mikrovlnku pomocí pythonu? <a href="http://t.co/bEQDZvqtK4">pic.twitter.com/bEQDZvqtK4</a> od <a href="https://twitter.com/domix">@domix</a></p>&mdash; Michal Illich (@michalillich) <a href="https://twitter.com/michalillich/statuses/466676410178760704">May 14, 2014</a></blockquote>

- Ztotožnil jsem se s myšlenkama, které dělají Python Pythonem. Sedly mi. Říká se tomu [Zen of Python](http://legacy.python.org/dev/peps/pep-0020/) a mě se to prostě fakt hodně líbí. Každý jazyk má svůj způsob, jakým řeší problémy. Když to uděláte v souladu s těmi způsoby, píšete tzv. *idiomatic* kód. Typicky, když jste Java vývojář a napíšete něco v Ruby, nebude to *idiomatic*, protože sice píšete Ruby, ale přemýšlíte v Javě - pro Rubystu bude takový kód hrozně kostrbatý a nepřirozený, byť bude fungovat a bude vlastně správně. Abyste napsali *idiomatic* Ruby, musíte mu navyknout a přemýšlet v Ruby. No a takové "typické přemýšlení v Pythonu" někdo sepsal a pojmenoval to Zen of Python. Projděte si to, je to asi 20 krátkých vět ve stylu *simple is better than complex, complex is better than complicated...*
<blockquote class="twitter-tweet" lang="en"><p>Můj oblíbený způsob jak nabootovat do nového jazyka nebo ekosystému: vygooglit si &quot;idiomatic &lt;název jazyka&gt;&quot;</p>&mdash; Honza Javorek (@honzajavorek) <a href="https://twitter.com/honzajavorek/statuses/458983315778048000">April 23, 2014</a></blockquote>

Osobně mi opravdu vyhovuje řešení problémů ve stylu Zen of Python. Dalo by se říct, že věřím v Zen of Python :) Když píšu v jiném jazyce, dejme tomu v Ruby, dokážu se přizpůsobit a napsat *idiomatic* Ruby, ale netěší mě to tolik. Nenadchnu se pro to, protože věřím, že způsob, jakým by se to řešilo v Pythonu, mi vyhovuje víc.

<blockquote class="twitter-tweet" lang="en"><p>Az bude zase scitani lidu, muzu uvest do kolonky pro vyznani PEP20?</p>&mdash; Honza Javorek (@honzajavorek) <a href="https://twitter.com/honzajavorek/statuses/463299299091419136">May 5, 2014</a></blockquote>

Takže tak to je. Python mi prostě sedl a proto ho mám rád a spjal jsem s ním i kus svého života. Můžu se naučit nové jazyky, můžu se nechat třeba zaměstnat v [Apiary](http://apiary.io/), kde se (zatím! :-D ) v Pythonu třeba vůbec neprogramuje. Stejně se ale budu ztotožňovat se Zen of Python a věřit v to, že takhle se mají problémy řešit. To mi prostě nikdo nesebere, protože to souzní s tím, co jsem si myslel nebo co se mi líbilo dlouho před tím, než jsem vůbec o nějaký Python zakopnul.

<blockquote class="twitter-tweet" lang="en"><p>Otevřete si tuhle stránku a hledejte slovo Python ;) <a href="http://t.co/GbUY77FmN8">http://t.co/GbUY77FmN8</a></p>&mdash; Honza Javorek (@honzajavorek) <a href="https://twitter.com/honzajavorek/statuses/470947836251881472">May 26, 2014</a></blockquote>

A proč Python propaguju? Co mě motivuje k tomu, abych ho ukazoval jiným lidem a nabízel jako možné řešení jejich problémů?

No, jak už jsem naznačil, nedělám si iluze, že by byl Python řešením všech problémů světa. Ačkoliv je to víceúčelový jazyk, má svá pro a proti, tu se hodí více, tam méně. Přijde mi ale, že jsem v Pythonu objevil pěkný a silný nástroj, který přijde vhod často. Systematický. Snadný k naučení a přitom s obrovským ekosystémem. Přijde mi škoda, že se někde děcka učí programovat třeba v Pascalu nebo v C, když by se mohly stejně tak naučit rovnou Python, který má lidskou, čitelnou a rychle pochopitelnou syntaxi i pro začátečníka (na rozdíl od C), ale přitom se s ním (na rozdíl od Pascalu) píše produkční software, takže stačí prohloubit znalosti a hurá, je ze mě programátor s prakticky uplatnitelnou znalostí, kterého mohou hned někam zaměstnat.

A proč psát třeba weby v Pythonu a ne v PHP? Upřímně, tady z ekonomického hlediska nevidím nějakou zásadní konkurenční výhodu Pythonu. Je tam lepší integrace s dalším serverovým softwarem, pružnější deployment, atd., na světě je milion Django appek a web na míru si z nich poskládáte jak z LEGO stavebnice... ale tohle nejspíš bude v PHP taky ([Symfony](http://symfony.com/)?) masa programátorů a eroze většinu těch nejtrapnějších problémů v PHP časem plus mínus vyřešila a slušná aplikace se v tom asi nějak napsat dá. Trh s PHP programátory je obrovský, často jsou levní, komunita obrovská, hostingy všude, takže ekonomicky to určitě dává smysl. Kdo by si začal v Djangu psát na koleně CMS pro svůj blogísek, místo aby si někam naplácl WordPress, popřípadě Drupal, není z mého pohledu srdcař, ale někdo, kdo fakt neví co s časem. Takže proč psát weby v Pythonu? Nejspíš asi hlavně pro samotnou radost z onoho psaní. Všichni určitě známe [PHP: a fractal of bad design](http://eev.ee/blog/2012/04/09/php-a-fractal-of-bad-design/)... ;-) Psát PHP prostě není radost. Není. Ne. To už raději číst Perl. Pokud jste webový podnikatel, chcete PHP. Pokud jste programátor webových aplikací, chcete Ruby, Python, Node.js. (A samozřejmě, pokud jste banka, chcete Javu.)

No a o čem je tedy vlastně má mise v oblasti propagaci Pythonu? Jak chci dokázat, že si více lidí vybere Python, když tady zároveň tvrdím, že Python je jazyk jako každý jiný?

Chtěl bych zlepšovat ekosystém okolo Pythonu, jakožto mého oblíbeného jazyka. Vytvořit a podporovat komunitu, psát články, točit videa, připravovat přednášky, odpovídat na dotazy. Ukazovat firmám, jak hledat Pythonisty a spojovat Pythonisty s firmami. Vytvořit u nás prostředí, které když nováček uvidí, tak si řekne - "týjo, mohl bych sice programovat v Node.js nebo Javě, nebo třeba v Go, ale když se naučím Python, bude kolem mě hromada lidí, kteří mi mohou pomoci, se kterými můžu na pivo, je tu spousta videí v češtině a článků a návodů a materiálů... a přitom to vypadá, že je i relativně dost pracovních nabídek, tak se pak nejspíš nebudu muset bát, že bych nezakopl o práci!" A firmy si zase řeknou, že díky komunitě se vyplatí na Python vsadit, protože mají kde hledat lidi a kam jít pro podporu...

Takže tohle je moje mise a to bych chtěl :-) Aby komunita a ekosystém byli tím rozhodujícím závažím na vahách. Aby byl Python volbou pro víc a víc lidí ne proto, že si pár fanatiků myslí, že je to nejlepší jazyk na světě, ale proto, že spousta lidí od Aše po Karvinou má dojem, že programovat v Pythonu je zábava a tuto zábavu stojí za to sdílet mezi sebou.
