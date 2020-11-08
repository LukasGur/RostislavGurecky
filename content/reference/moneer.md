---
title: Moneer
translationKey: reference/moneer
type: reference
date: 2019-09-30T00:00:00+02:00
comingSoon: true
seo:
  title: Moneer – hodnota vašich investic v reálném čase
  description: Jste investor? Pak by vás jistě uchvátilo vidět hodnotu vlastního portfolia v reálném čase, nyní. Snili jsme o tom také. A proto vyvíjíme Moneer.
  type: website
listdata:
  heading: Moneer.
  text: Náš vlastní projekt. Webová aplikace a služba pro správu a vedení investic menších i větších investorů. Podpora různých měn a investic jako fiat, kryptoměny, P2P, drahé kovy, nemovitosti a další.
  buttonText: Řeknete mi víc?
  image: blogger
landing:
  heading: Moneer – hodnota vašich investic v reálném čase.
floatingbox:
  id: about
  heading: Všechny vaše investice pohromadě v reálném čase.
  text: '<p>Moneer vám umožní na pár kliknutí sledovat aktuální zisk či ztrátu vašeho celého investičního portfolia. Sleduje ceny kurzů a automaticky přepočítává hodnotu vašeho portfolia. Můžete si navíc přepínat mezi kategoriemi, takže víte přesně, co vám nejvíce vynáší a co ne.</p>'
  buttons:
    - text: Investujete? Omrkněte Moneer.
      url: https://moneer.app
      type: primary
    - text: Jak jsme Moneer vyvíjeli
      url: '#moneer'
      type: primary-outline
sections:
  - id: moneer
    heading: Data. Automaticky. Aktuálně.
    text: '<p>Abychom zajistili, že bude hodnota portfolia každého investora zobrazena v reálném čase, musíme <strong>neustále analyzovat</strong> změny kurzů a aktuální hodnoty různých aktiv a ty si ukládat.</p><p>K tomuto jsme nasadili několik API, některá data pak čerpáme přímo z webů, které jsou na danou problematiku zaměřeny. Samozřejmě z několika různých zdrojů.</p><p><strong>Tato data následně uchováváme v Moneeru. U každé hodnoty máme také uloženo, kdy byla platná. Z těchto dat se potom dopočítají pohyby v hodnotě portfolií v čase.</strong></p>'
    image: data
    buttons:
      - text: Více o API a stabilitě
        url: '#api-stability'
        type: primary
  - id: lot-of-data
    heading: Spousta dat.
    text: '<p>Ceny drahých kovů, resp. zlata, stříbra, platiny a palladia, ukládáme každých 15 sekund. To vychází na 8 409 600 kovových záznamů v databázi každý rok. S tím pak musíme pracovat.</p><p>Pro práci s touto spoustou dat nám skvěle slouží MongoDB se svými <a href="https://docs.mongodb.com/manual/aggregation/">agregačními funkcemi</a>. Ty nám umožní potřebná data vydolovat rychle a pak je rychle zobrazit uživateli.</p><p><strong>Od začátku jsme kladli důraz na řádnou přípravu vhodného modelu dat a efektivní algoritmus pro jejich získávání. Díky tomu aplikace požadavky odbavuje velice rychle.</strong></p>'
    image: factory
  - id: api-stability
    heading: API a stabilita.
    text: '<p>Pro získávání relevantních dat jsme museli zvolit vhodné API služby nebo jiné zdroje. Do Moneeru implementujeme přes <strong>10 různých API</strong> a postupně budeme přidávat další.</p><p>V případě výpadku některé z API se uživateli zobrazí upozornění a hodnota jeho investic v daném segmentu bude zobrazena pro poslední platné uložené hodnoty. Později se Moneer pokusí chybějící data <strong>zpětně získat</strong>.</p><p><strong>Uživatel tak stále uvidí hodnotu svých investic co nejblíže současné situaci. Je navíc informován, že jde o několik momentů starší data. O nápravu se nemusí starat.</strong></p>'
    image: memorystorage
    buttons: 
      - text: Prohlédněte si Moneer
        url: https://moneer.app/
        type: primary
      - text: Prohlédněte si další reference
        url: /cs/reference/
        type: primary-outline
---
