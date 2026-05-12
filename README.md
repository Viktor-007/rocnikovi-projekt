# Rocnikovi-projekt

## Zapojení RGBW led pásku  
   - Cílem tohoto projektu je návrh a realizace **zpojení led pásku**, včetně výběru odpovídajícího napájecího zdroje a ověření jeho správné a bezpečné funkce. Projekt se zaměřuje na pochopení funkce LED pásků.   
   1. Návrh zapojení.
   2. Zapojení led pásku tak aby **spolehlivě a bezzávadně** svítil.
   3. Odskoušení funkce pod **dohledem odborného dozoru**.
   4. Závěrečné zkontralování práce.

### seznam součástek
   - led pásek-24V 16W na 1 metru COB LED pásek RGBW-WW 24V 16W 
   - zdroj-24V 75W LED zdroj 24V 75W NPZ-24-75 vnitřní
   - spojovací vodiče
   - ovaladač Ovladač dimLED OVS RGBW 4KR
   - regulátor/přijímač SMART přijímač dimLED ZIGBEE PR 5K 5v1
   - konektory
   - hliníkovy profil pro led pásek
   - montážní materiály jako jsou šrouby, oboustraná lepící páska protože u každého LED pásku 

### výpočet výkonu zdroje 
   - Při výpočtu zdroje se musí počítat s tím jakou spotřebu bude mít zdroj na 1. metru LED pásku. Musíme taky počítat s tím jaké bude mít zdroj maximální dlouhodobé zatížení. Univerzálně se uvádí 20% až 30% z maximálního zatížení zdroje.
   - Výpočet tedy musí být: odběr pásku na jednom metru * délka pásku (v metrech) + 20% až 30% (podle výrobce zdroje)
   - Je taky potřeba uvážit v potaz jestli bude pásek svítit 6 až 8 hodin v kuse.
   - Pro tyto zapojení je potřeba počítat s rezervou 30% až 40% výkonu zdroje. V této situaci je dobré počítat s tím že ne všechny zdroje budou plně funkční.

### dimenzováni zdroje
   - Dimenzování napájecího zdroje je důležitá část návrhu každého elektrického nebo elektronického zařízení. Když je zdroj správně zvolený, zařízení funguje spolehlivě, součástky se zbytečně neničí a snižuje se riziko poruch nebo poškození celého obvodu.
   - Prvním krokem je stanovení požadovaného napětí. Napětí zdroje musí odpovídat napětí, které vyžaduje napájené zařízení
   - Překročení jmenovitého napětí může vést k poškození zařízení, naopak nižší napětí může způsobit jeho nesprávnou funkci například žě bude led pásek slaběji svítit.
   - Dalším krokem je výpočet celkového proudu, který budou všechny připojené spotřebiče odebírat. Proud jednotlivých zařízení se sečte. Výsledná hodnota proudů je minimální a musí se počítat s vyším odběrem proudu.  
   - S tím se také váže to že by se zdroje neměli vybírat ne jen podle toho aby byli levné za cenu toho že bodou na hranici výkonu a nebo také že budou nekvalitně vyrobené. Nicméně je to na každém pro jaku možnost se rozhodne.

### výběr zdroje
   - Zdroje se vybírají podle toho v jakém prostředí jou používány.
   - V interiéru se nejčastěji používají krabičkové zdroje nebo přímo adaptéry. Ve venkovním prostředí se používají zdroje vyššího stupně IP ochrany. V průmyslu se používají nejčastěji zdoje na din lištu.
   - V potaz se také musí brát že ne všechny stejně vypadající zdroje s rozdílnou cenou budou stejně spolehlivé. 
   - Ve všech případech je potřeba vybírat zdroje podle výše napsaných parametrů.
     
### výpočet mého zdroje:
   - I =P/U =16/24 =0,67A na metr na 3. metrech 2A
   - P =P1 . počet metrů =3 . 16 =48W 

   
### schéma zapojení 
   -<img width="728" height="487" alt="image" src="https://github.com/user-attachments/assets/ecaafa04-e84e-46dc-bca9-6c52c512cd64" /> 

### vysledné fotky
   -<img width="3264" height="1472" alt="IMG20260511164008" src="https://github.com/user-attachments/assets/9c6a3344-e568-4a79-bde4-c42beff298b0" />
   -<img width="3264" height="1472" alt="IMG20260511164025" src="https://github.com/user-attachments/assets/a02bc4d3-6dc5-459e-bb0a-c76b7e8a4eaf" />
   -<img width="1235" height="644" alt="image" src="https://github.com/user-attachments/assets/449fccda-d8cc-4080-a9d8-56f6e0b172ce" />
   -<img width="1240" height="289" alt="image" src="https://github.com/user-attachments/assets/5fe4a998-a75b-491d-afbe-e2b6e5b1b926" />









### citace
   - Obecný zdroj informací. Online. Dostupné z: https://elektroschema.com/schema-zapojeni-led-pasku/. [cit. 2025-12-11].
   - Video informace. Online. 2025. Dostupné z: https://www.youtube.com/watch?v=A-nCv4oWz54. [cit. 2025-12-12].
   - Informace o zapojení led pásku. Online. 2025. Dostupné z: https://www.ledsviti.cz/jak-instalovat/prakticky-pruvodce-instalaci-led-pasku/. [cit. 2025-12-14].
   - Informace o led pásku. Online. 2025. Dostupné z: https://cs.wikipedia.org/wiki/LED_p%C3%A1sek. [cit. 2025-12-14].
   - Informace o zapojení 12V led pásku. Online. 2025. Dostupné z: https://elektroschema.com/schema-zapojeni-led-pasku-na-12v/. [cit. 2025-12-14].
   - Informace o chlazení led pásku. Online. 2025. Dostupné z: https://cs.wikipedia.org/wiki/LED_p%C3%A1sek#Chlazen%C3%AD. [cit. 2025-12-14].
   - Informace o zatížitelnosti zdroje. Online. Dostupné z: https://mardomdecor.com/cs/blog/jaky-zdroj-led-bych-mel-zvolit-technicke-rady-a-tipy/. [cit. 2026-01-08].

### poděkování 
   - Chtěl bych tímto poděkovat tátovi za vysvětlení všeho za mě potřebného k tomuto tématu. Byly to věci které jsem nikde nemohl dohledat. 

# Druhá část ročníkového projektu

## oprava vrtačky

### bezpečnost práce 
   -nejdůležitější je bezpečnost práce aby se nikomu nic nestalo.
#### opatřění 
   - je potreba aby byla vapojená z elektriky nebo aby byla bez akumulátoru 
   - je potřeba pracovat v suchém prostředí když se to týká elektrických věcí
   - je potřeba také používat ochrané pomůcky a správné nářadí

### diagnostaka závady
   - Kontrola napájení proběhla ještě před rozděláním celé vrtačky. Proběhla kontrlou přívodního kabelu.
   - Po rozdělání vrtačky jsem zkontroloval spínač, ložiska, převodovku. Při kontrole dílů jsem  zjistil, že spínač je vadný
   - Zjistil jsem to že problém byl v přívodovém kabelu který byl přerušen až v těle vrtačky.

### oprava
   - celou vrtačku jsem vyčistil
   - vyměnil jsem spínač a nově připájel přívod
   - promazal jsem převodovku

### cenová výhodnost
   - výměna uhlíků u komutátorových vrtaček, není to nákladná věc takže se vyplácí.
   - výměna ložisek je už trochu nákladnější ,ale pořád se to vyplácí.
   - výměna spínačěe se taky vyplatí.
   - výměna převodovky se podle mě vyplácí podle stáří vrtačky. když je starší 8 let tak je to už podle mě nevíhodné.
   - Při stáří do 5 let se to asi vyplácí, když je to mezi tak je to otáka na osobním názoru. 
   - výměna motoru je hodně nákladná a tím pádem se se neviplácí a to nemluvně že se vše vyndá ven z obalu vrtačky a potom se to musí dát vše zpět a někdy potom už tem plastový obal už nemusí moc držet pohromadě.
   - oprava a přepájení přerušených drátků se podle mě vyplatí vždy. 
       

### obrázky
   - <img width="612" height="407" alt="rozdělaná vrtačka 1" src="https://github.com/user-attachments/assets/acc83c2b-20f5-4098-98ee-129972cc5f3c" />
   
### citace
   - Informace o opravě vrtačky. Online. Dostupné z: https://www.youtube.com/watch?v=efS3i1gvVVQ. [cit. 2026-05-03].
   - Video návod. Online. Dostupné z: https://www.bing.com/videos/riverview/relatedvideo?q=oprava+vrta%c4%8dky&mid=BB0BE622CC7432E536D0BB0BE622CC7432E536D0&churl=https%3a%2f%2fwww.youtube.com%2fchannel%2fUC5EsWL7Xvudh4dsDVvarD_A&FORM=VIRE. [cit. 2026-05-03].
   - Informace o hledání závad. Online. [cit. 2026-05-11].

### poděkování
   - tímto bych chtěl poděkovat tátovi za rady jak bezpečnostní tak i ty praktické a pomoc při práci s opravou.
