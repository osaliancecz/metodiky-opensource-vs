Open-source Aliance

# Vzorové požadavky na ICT zakázky - otevřenost řešení

- Předmět: Sada vzorových požadavků pro zadávací dokumentaci a požadavky na předmět u veřejných zakázekk otevřenosti
- Verze: [%Version], [%Date]
- Autoři: Pracovní výbor pro architekturu a eGovernment Open-source Aliance a partneři
- Určeno pro: veřejné zadavatele, orgány veřejné moci a subjekty připravující dokumentaci veřejných zakázek, Open-source Aliance
- Důvod předložení: dílčí cíl 2.8 Informační koncepce ČR a potřeba definovat sadu požadavků pro splnění zásad 16 a 17 IKČR a souvisejících architek
- Poznámky: [%Comment]

## Úvod

Vzorové požadavky na ICT zakázky - otevřenost řešení má za cíl připravit a dát k dispozici tu část vzorových požadavků na veřejné zakázky ICT, která se týká otevřenosti a zabránění závislost. Materiál je určen pro veřejné zadavatele, orgány veřejné moci a subjekty připravující dokumentaci veřejných zakázek, důvodem zpracování a předložení je dílčí cíl 2.8 Informační koncepce ČR a potřeba definovat sadu požadavků pro splnění zásad 16 a 17 IKČR a souvisejících architek

Sada vzorových požadavků pro zadávací dokumentaci a požadavky na předmět u veřejných zakázekk otevřenosti je základem pro sestavení požadavků na předmět veřejné zakázky do zadávací dokumentace, aby poptávané řešení a dodávka v rámci této veřejné zakázky splňovaly povinnosti primárně nasazovat otevřený software a otevřená řešení. Zadavatel je může použít tak, jak jsou připravené, ale vhodné je si je pečlivě prostudovat a přizpůsobit potřebám konkrétní veřejné zakázky. Vždy je ale nutné dodržet základní principy těchto požadavků, a tak v maximální možné míře požadovat po uchazečích a následně po dodavatelích při plnění veřejné zakázky otevřenost.

Jako další kroky se navrhuje zadavatelům adoptovat příslušné požadavky do zadávací dokumentace pro veřejné zakázky k ICT a používat je pro každou zakázku na.

Aktuální verzi dokumentu a především CSV soubor exportu z katalogu požadavků, který lze využít pro přímé zpracování dat, najdete na otevřeném GIT repozitáři na adrese 

[https://github.com/osaliancecz/metodiky-opensource-vs/tree/main/pozadavky-verejne-zakazky](https://github.com/osaliancecz/metodiky-opensource-vs/tree/main/pozadavky-verejne-zakazky) 

## Vyjasnění potřeby požadavků a jejich použití

Informační koncepce České republiky, jež je pro veřejnou správu závazná, přináší mnoho povinností a pravidel, které stanovují rámec pro výstavbu a dodání informačních systémů určených právě pro samotnou veřejnou správu.
IKČR Přináší kupříkladu povinnost využívání otevřeného software a otevřených standardů. Naproti tomu též pamatuje i na ty případy, kdy se otevřený software využít nedá a přesně stanovuje postup, který je nutné zvolit a který je závazný pro samotného zadavatele.

Stěžejními zásadamy, které přesně deklarují a popisují takové požadavky, jsou:

* Zásada řízení ICT Z16: Využívání otevřeného software a standardů
* Zásada řízení ICT Z17: Podpora vyváženého partnerství s dodavateli

Výše uvedené zásady kladou důraz na maximální otevřenost, na kvalitní vztahy všech zainteresovaných subjektů. Tyto faktory zakládají transparentní a do budoucna rovné prostředí pro všechny strany. Vzniká tak kvalitní platforma pro všestrannou spolupráci.

Důležitým základem kvalitní spolupráce mezi zadavatelem a dodavatelem  je také samotná veřejná zakázka, která musí splňovat všechny nutné náležitosti.

Nezbytnou součástí veřejné zakázky jsou požadavky na právní vztahy všech zainteresovaných subjektů tak, aby ty neumožňovaly budoucí nejasnosti vyplývající ze smlouvy či nezakládaly platformu pro budoucí závažné právní i finanční i jakékoliv jiné spory všech smluvních stran.

## Tři druhy požadavků k otevřeným řešením 

Související požadavky týkající se opensource lze rozdělit do tří skupin:

1. Právní požadavky a požadavky na vztah k dodávce a dodavateli 
2. Technické a funkční a nefunkční požadavky na technickou realizaci díla 
3. Znalostní požadavky na dokumentaci a zdroje 

### Právní požadavky a požadavky na vztah k dodávce a dodavateli 

Vzhledem k platné a závazné legislativě, také s ohledem k Informační koncepci České republiky, se předpokládá, že dodané dílo/systém zadavateli bude dodáno tak, aby ten měl vždy možnost nechat jej spravovat a rozvíjet třetí stranou, tedy naprosto nezávisle na samotném dodavateli díla. Výše popsaný fakt vychází právě ze závazné koncepce rozvoje informačních systémů veřejné správy, tedy z Informační koncepce České republiky, která závazný bod popisuje ve své zásadě - Zásada řízení ICT Z17: Podpora vyváženého partnerství s dodavateli a přináší povinnost jejího naplnění pro všechny subjekty veřejné správy.

Pro naplnění výše uvedeného je podstatné, aby byla již od počátku přesně stanovena zadávací dokumentace a veřejná zakázka na samotné dílo.
Z toho také vychází povinnost obou smluvních stran o správném nastavení zastřešující smlouvy.

Je nutné, aby součástí zadávací dokumentace a následně uzavřené smlouvy mezi zadavatelem a dodavatelem byla jasně definovaná dohoda o právech zadavatele a o licenčních podmínkách, které se vztahují k samotnému dodanému dílu tak, aby veškeré licence byly k dispozici právě zadavateli. Cílem toho všeho je možnost správy samotného díla právě jím.

Dalším, neméně důležitým, faktem vycházejícím ze správně nastaveného smluvního vztahu mezi zadavatelem a dodavatelem je, že ve vlastnictví zadavatele zůstává, a to i v případě rozluky těchto dvou subjektů, samotný obsah, kód díla i jeho kompletní dokumentace a také tzv. business inteligence, která popisuje vše, co systém/dílo vlastně dělá a jak funguje.

Z toho vyplývají požadavky související s autorským právem i rolí autorského práva. Jelikož, autorské právo vztahující se k samotnému dílu nesmí jakýmkoliv způsobem bránit zadavateli v možnosti přenesení samotné správy dodaného díla k třetímu subjektu či samotnému zadavateli.

### Technické a funkční a nefunkční požadavky na technickou realizaci díla 

Vzhledem k tomu, že platí povinnost využívat ve veřejné správě otevřený software a otevřené standardy pro webové služby a rozhraní, jež je právně ukotvena v Informační koncepci České republiky, konkrétně v požadavku - Zásada řízení ICT Z16: Využívání otevřeného software a standardů, předchází se právě tímto nařízením možným dlouhodobě vysokým nákladům a rizikům za dodané dílo, jenž by nebylo postaveno právě na opensource platformě.

Tedy, je důležité, aby bylo samotné požadované dílo vystavěno právě na platformě opensource nebo s použítím opensource technologií.

I zde platí princip správně nastaveného požadavku mezi zadavatelem a dodavatelem, který říká, že samotné dílo je možné provozovat kdekoliv, tedy technicky i jakkoliv jinak nezávisle na dodavateli. Tento požadavek by měl být opět součástí správně nastavené smlouvy mezi zadavatelem a dodavatelem.

V praxi se tedy požaduje, aby dílo bylo možné provozovat kdekoliv, tedy nezávisle na platformě dodavatele. Z toho vychází i požadavek zadavatele na možnost svobodného přenesení systému/díla prostřednictvím konteineru či virtualizační platformy tam, kam si zadavatel vlastní vůlí určí.

Z toho také vyplývá, že konkrétní technické požadavky musí naplňovat principy a zásady Informační koncepce ČR a Národního architektonického plánu.

Tato oblast obsahuje požadavky, které jsou ryze technickými požadavky na předmět veřejné zakázky a týkají se rozsahu a praktického využití otevřených řešení a standardů.

### Znalostní požadavky  a požadavky na dokumentaci a zdroje 

Jestliže se ve spolupráci mezi zadavatelem a dodavatelem nevyskytují žádné právní či licenční překážky, které by bránily tomu, aby mohl zadavatel předat správu a rozvoj systému/díla třetí straně, je nutné naplnit tu podmínku požadovanou zadavatelem, aby ten měl k dispozici všechny informace, které jsou důležité a nezbytné ke komplexní správě celého systému/díla. Tedy, je nezbytné, aby dodavatel díla předal zadavateli veškeré informace k dílu se vztahující.

Zadavatel musí v tomto ohledu obdržet veškeré informace, které budou přesně říkat, jak systém/dílo funguje, co systém/dílo přesně dělá, jaké jsou potřeby pro jeho správu.

Součástí požadavků zadavatele na dodavatele díla jsou požadavky na architektonickou dokumentaci, vývojovou dokumentaci, provozní dokumentaci. Požadavky kladou důraz i na definici konkrétní podoby samotné dokumentace. I zde by se měly v maximální míře využít otevřené a běžně využívané standardy pro formáty a obsah dokumentace.

Součástí požadavků zadavatele je též požadavek na komplexní dodání vývojového prostředí, ve kterém lze systém/dílo kompilovat a také požadavky na monitorování funkčnosti samotného systému/díla, a to kdykoliv.

## Sada vzorových požadavků pro zadávací dokumentaci a požadavky na předmět u veřejných zakázekk otevřenosti

V tabulce je seznam všech předpřipravených požadavků i s popisem požadavku. K dispozici je na repozitáři také CSV soubor, který se lépe hodí pro přizpůsobení a přípravu konkrétní zadávací dokumentace.


| Název | Popis |
|----------|----------|
| Díl : Vzorové požadavky na zakázky ICT v souvislosti s otevřeným řešením a open-source |  |
| Skupina 1: Právní požadavky a požadavky na vztah k dodávce a dodavateli  |  |
| Právní požadavek 1.1: Deklarace a popis otevřenosti řešení | Dodavatel již v nabídce smlouvy určené zadavateli, pak i při uzavírání smluvního vztahu se zadavatelem, přesně deklaruje, jaká je skutečná míra otevřenosti řešení dodávaného díla. Dodavatel ve smlouvě přesně říká, jestli je dílo postavené na open-source řešení a také uvádí to, jestli je součástí dodávky i zdrojový kód díla, či nikoliv. Dodavatel též ve smlouvě deklaruje, že dodané dílo/systém zadavateli bude dodáno tak, aby ten měl vždy možnost nechat jej spravovat a rozvíjet třetí stranou, tedy naprosto nezávisle na samotném dodavateli díla. |
| Právní požadavek 1.2: Práva na zajištění provozu třetí stranou | Dodavatel předá zadavateli veškerá práva vztahující se k dodávanému dílu tak, aby zadavatel měl možnost dílo plně provozovat či samotný provoz a správu díla a jeho rozvoj předat subjektu třetí strany. |
| Právní požadavek 1.3: Právo na zajištění podpory třetí stranou | Dodavatel předá zadavateli veškerá práva k dílu se vztahující tak, aby zadavatel měl plnou možnost zajistit technickou a uživatelskou podporu informačního systému přímo svými prostředky či, aby zadavatel měl možnost tuto technickou a uživatelskou podporu informačního systému delegovat na subjekt třetí strany. |
| Právní požadavek 1.4: Práva na zajištění rozvoje třetí stranou | Dodavatel předá zadavateli veškerá práva k dílu se vztahující tak, aby zadavatel měl maximální možnost zajistit rozvoj informačního systému přímo svými prostředky či, aby  zadavatel měl možnost rozvoj informačního systému delegovat na subjekt třetí strany. |
| Právní požadavek 1.5: Podrobné odůvodnění pro výjimky ze zásad IKČR č. 16 a 17, pokud jsou relevantní | Zadavatel, pro požadované dílo, je povinen naplnit soulad s Informační koncepcí ČR, hlavně se zásadami č. 16 a č. 17 této koncepce. Jestliže však není možné tyto zásady IKČR zadavatelem naplnit, je nezbytné, aby dodavatel poskytnul zadavateli podklady pro případné odůvodnění pro výjimku ze zásad č. 16 a 17 IKČR, a to kupříkladu tehdy, kdy dodavatel nemůže předat zadavateli autorská práva ke komponentám třetích stran. Na základě výše uvedeného je zadavatel schopen požádat o výjimku při plnění souladu se zásadami č. 16. a č. 17 IKČR. |
| Právní požadavek 1.6: Práva na obsah dodávky | Dodavatel předá zadavateli veškerá práva na všechny části dodávky včetně kompletní dokumentace, včetně analytických prací a návrhů řešení, také včetně samotné architektury dodávaného díla, a to proto, aby zadavatel měl tyto prostředky k dispozici i po případné rozluce obou stran. |
| Právní požadavek 1.7: Práva na zdrojové kódy a dokumentaci | Dodavatel předá zadavateli zdrojové kódy, a to včetně jejich popisu, ke všem komponentám díla. Pochopitelně  za předpokladu, že těmito kódy disponuje. V případě, že se jedná o zdrojové kódy open-source řešení, předá dodavatel zadavateli zdroj/odkaz, který na tyto veřejné kódy odkazuje. Kromě zdrojových kódů předává dodavatel zadavateli i kompletní vývojovou dokumentaci. Vývojová dokumentace a zdrojové kódy musejí být předány v takovém rozsahu a detailu, aby bylo možné na základě tohoto předání zajistit plnou podporu a rozvoj díla buď přímo zadavatelem či subjektem třetí strany. |
| Právní požadavek 1.8: Práva na BI v rámci dodávky | Dodavatel předá zadavateli veškerá práva byznys inteligence, prostřednictvím které se realizuje příslušný informační systém/dílo. Ve vlastnictví zadavatele tak zůstává, a to i v případě rozluky těchto dvou subjektů, samotný obsah, kód díla i jeho kompletní dokumentace a také právě tzv. byznys inteligence, která popisuje vše, co informační systém/dílo vlastně dělá a jak funguje. Zadavatel musí v tomto ohledu obdržet tedy veškeré informace popisující komplexní fungování systému/díla a také maximální penzum informací, jaké jsou potřeby pro jeho správu. |
| Právní požadavek 1.9: Práva na dílo zůstávají zadavateli i po ukončení vztahu s dodavatelem | Práva na samotné zdrojové kódy díla, práva na úpravu a rozvoj díla a práva na kompletní dokumentaci vztahující se k dodanému dílu se předávají zadavateli trvale. Tato práva zadavatele v žádném případě nezanikají v okamžiku ukončení smluvního vztahu zadavatele a dodavatele. |
| Právní požadavek 1.10: Návrh smlouvy musí respektovat možnost provozu a rozvoje třetí stranou | Dodavatel již v rámci nabídky předloží návrh smlouvy, která respektuje veškerá zde uvedená práva zadavatele a povinnosti dodavatele v právních a znalostních požadavcích. Dodavatel v rámci nabídky předloží dokument či přehled plnění jednotlivých požadavků s odkazem na konkrétní ustanovení v návrhu smlouvy. |
| Právní požadavek 1.11: Integrační rozhraní neomezené licencí či podmínkami využití | Dodavatel žádným způsobem nezpůsobí to, aby zadavatel nemohl využívat služby rozhraní integrace se systémem bez nutnosti dalších licenčních poplatků dodavateli nebo dalších nákladů na pořízení technologie potřebné pro fungování těchto služeb. Za to se nepovažuje nákup technologie určené jako integrační platforma, pokud zadavatel nevyužívá integrační platformu postavenou na open-source. |
| Skupina 2: Technické a funkční a nefunkční požadavky na technickou realizaci díla  |  |
| Technický požadavek : Poptávané řešení bude vystavěno na open-source platformách | Je-li k řádnému fungování softwarového řešení zapotřebí nějaká sdílená komponenta či platforma, bude pro vývoj a provoz využita platforma s otevřeným zdrojovým kódem, a to buď v bezplatné verzi, nebo v placené rozšířené verzi s odůvodněním takové potřeby. |
| Technický požadavek : Poptávané řešení bude postaveno na open-source produktech | Je-li k řádnému fungování softwarového řešení zapotřebí nějaký softwarový produkt, bude pro vývoj a provoz využit produkt s otevřeným zdrojovým kódem, a to buď v bezplatné verzi, nebo v placené rozšířené verzi s odůvodněním takové potřeby. |
| Technický požadavek : Tvorba a správa zdrojového kódu se řídí politikou NÚKIB Bezpečnostní doporučení pro vývoj otevřeného softwaru ve veřejné správě | Při tvorbě zdrojového kódu, jeho správě a přípravě a nasazování řešení, se dodrží opatření v metodice Bezpečnostní doporučení pro vývoj otevřeného softwaru ve veřejné správě alespoň ve skupinách D, CI. |
| Technický požadavek : Aplikace a knihovny jsou řádně v kódu deklarovány a používají určené závislosti | Jsou-li v řešení využity externí aplikace či knihovny třetích stran, jsou jejich závislosti v kódu správně deklarovány a je popsána jejich potřeba a účel knihovny. U knihoven dodavatele se veškeré zde uvedené požadavky na otevřenost uplatní vždy a bez výjimek, u knihoven třetích stran, jež nejsou otevřené, se uplatní požadavky v maximální možné míře. |
| Technický požadavek : Využívají se pouze aktuální, podporované a udržované verze knihoven a aplikací | Pokud je využita externí závislost, musí být použity pouze knihovny a jejich verze, které jsou udržované, aby bylo sníženo riziko použití knihovny, která obsahuje zranitelnosti, které nikdo nebude řešit. Pokud aplikace závisí na neudržované knihovně, měla by být nahrazena novější, podporovanou verzí nebo její udržovanou alternativou. |
| Skupina 3: Otevřená integrace |  |
| Funkční požadavek 3.1: Integrace součástí dodávky | Součástí dodávaného řešení či informačního systému je také vytvoření a dodání rozhraní pro jeho integraci s ostatními systémy. Toto rozhraní pro integraci musí splňovat zde uvedené požadavky na něj kladené. |
| Funkční požadavek 3.2: Systém musí mít otevřené a zdokumentované rozhraní pro integraci | Poptávaný systém musí mít jediné rozhraní pro integraci s ostatními informačními systémy podporující otevřené standardy pro integrační platformy. Rozhraní bude transparentně zdokumentováno a popsáno tak, aby zadavatel i ostatní dodavatelé jej mohli volat a využívat bez nutnosti další součinnosti s dodavatelem.  |
| Funkční požadavek 3.3: Rozhraní pro integraci se systémem musí umožňovat doplňování či úpravu služeb | Integrační rozhraní systému musí být koncipováno takovým způsobem, aby zadavatel či jím pověřená třetí strana byl schopen rozšiřovat integraci o nové služby. Z popisu rozhraní musí být jasný i postup, jak případně upravovat atributy či volání stávajících služeb, pokud to bude nutné. |
| Technický požadavek 3.4: Rozhraní pro integraci služeb musí být postaveno na transparentních službách | Rozhraní pro integraci musí být tvořeno jako standardizované rozhraní složené z volatelných služeb rozdělených pro synchronní a asynchronní komunikaci. Dodavatel postaví rozhraní buď na webových službách, nebo službách API, přičemž využije obecně známých otevřených standardů pro konstrukci takových služeb a jejich schémat. |
| Technický požadavek 3.5: Neomezené využití integračního rozhraní | Dodavatel nebude vyžadovat nákup licence na využívání integračního rozhraní a rozsah jeho využívání nebude podmiňovat licenčními či jinými poplatky. Dodavatel nebude vyžadovat ani žádné zvláštní poplatky za připojení jednotlivých informačních systémů k jím dodanému rozhraní pro integraci. Rozhraní smí zadavatel využívat pro neomezený počet systémů, neomezený počet služeb a neomezený počet jejich volání. |
| Technický požadavek 3.6: Připravenost řešení na rozšíření integrace | Dodávaný systém musí být koncipován a v dokumentaci popsán takovým způsobem, aby zadavatel či jím pověřená třetí strana byl schopen nad údaji a funkcionalitami budovat nové či rozšiřovat stávající služby rozhraní pro integraci. |
| Technický požadavek 3.7: Rozhraní koncipované dle principu technologické neutrality | Dodavatel splní povinnost podle architektonického principu IKČR č. 14 u rozhraní, a to tak, že rozhraní vybuduje na otevřených standardech a nebude jej omezovat pouze na uzavřenou technologii integrační platformy, ledaže by se se zadavatelem dohodl na přechodném období, po které bude zadavatel dále využívat uzavřenou technologii uzavřené platformy, která ještě není postavena na otevřeném řešení. |
| Skupina 4: Znalostní požadavky na dokumentaci a zdroje  |  |
| Požadavek na dokumentaci 4.1: Dodat přehled veškerých produktů a součástí, jež dodávka obsahuje | Dodavatel již v rámci nabídky, nebo nejpozději při schvalování detailního návrhu řešení, dodá seznam všech součástí, zejména však technologických platforem a prostředků pro dodávané řešení. Tento seznam musí obsahovat zejména technologické a aplikační platformy, na nichž je řešení vystavěno a na jejichž existenci je závislé, a to včetně označení jejich verzí nutných pro chod řešení a minimální požadované konfigurace pro správný chod řešení. Dodavatel dodá také seznam součástí a platforem pro vývojové prostředí, nebo rozvoj programového kódu. |
| Požadavek na dokumentaci 4.2: Dodat veškeré licenční smlouvy produktů a součástí, jež dodávka obsahuje | Dodavatel, nejpozději při akceptačním řízení, dodá veškeré licence a licenční podmínky nejen pro samotné řešení, ale také pro všechny jeho licencované současti a platformy. Dodá buď úplné znění licenční smlouvy a dalších smluvních dokumentů, jimiž je zadavatel povinen se řídit při provozu a rozvoji, nebo odkaz na aktuální verze takových dokumentů, pokud jsou veřejně k dispozici na internetu. |
| Požadavek na dokumentaci 4.3: Dodat veškeré zdrojové kódy včetně dokumentace | Dodavatel u otevřených produktů a součástí a u součástí, kde tomu nebrání autorské právo nezaviněné hlavním dodavatelem, dodá zdrojové kódy včetně dokumentace. Součástí dokumentace jsou i vazby na potřebné produkty a součásti třetích stran a způsob jejich využití ve zdrojovém kódu a při kompilaci. |
| Požadavek na dokumentaci 4.4: Datová architektura a dokumentace datového fondu řešení | Dodavatel v rámci dodávky řešení dodá model datové architektury v úrovni a podrobnosti podle hledisek datové architektury z Národního architektonického rámce, a to v úrovni všech skupin údajů, jednotlivých údajů a jejich evidencí a technických podrobnostech o údajích srovnatelných se způsobem a obsahem ohlášení údajů v rámci agend v RPP. |
| Požadavek na dokumentaci 4.5: Dokumentace a popis rozhraní k integraci | Dodavatel v rámci předané dokumentace předá také úplnou dokumentaci rozhraní systému určeného pro integraci s ostatními informačními systémy. Tato dokumentace bude obsahovat zejména technologický popis fungování rozhraní, rozdělení služeb na synchronní a asynchronní, popisy všech služeb rozhraní, schémata jednotlivých služeb a seznamů jejich atributů včetně příslušných omezení, seznam a popis všech vrácených chybových hlášení a zpráv včetně popisu odstranění příčiny chyby a datová schémata atributů pro volání služeb v rámci webových služeb nebo služeb API. |
| Požadavek na dokumentaci 4.6: Do seznamu technologií uvést potřebné technologie pro integraci | Dodavatel v rámci seznamu využitých technologií a technologií potřebných pro provoz a fungování systému uvede také, s jakými technologiemi integračních platforem a správy API služeb funguje jím dodané otevřené rozhraní. |
| Požadavek na dokumentaci 4.7: Dokumentace standardizace integračního rozhraní | Dodavatel v rámci předání dokumentace k využívaným technologiím doplní také seznam a případná licenční omezení u technologií využitých pro fungování rozhraní pro integraci se systémem. |



## Další postup a návrhy

V souvislosti s cílem připravit a dát k dispozici tu část vzorových požadavků na veřejné zakázky ICT, která se týká otevřenosti a zabránění závislost se navrhují následující kroky:

1. zadavatelům adoptovat příslušné požadavky do zadávací dokumentace pro veřejné zakázky k ICT a používat je pro každou zakázku na



----------

[%Comment]

Praha, [%Date], Pracovní výbor pro architekturu a eGovernment Open-source Aliance a partneři
