# [DEPRECATED] - modul již není udržován/no longer actively maintained

<h1>Modul pro Opencart 2</h1>
<h2>Instalace</h2>
<ol style="color: black; ">
  <li>
    <ul>
      <li><a href="https://github.com/Zasilkovna/opencart2/archive/opencart2.3.zip">Stáhnout soubor modulu pro Opencart 2.3.x &raquo;</a>
      	<ul>
      		<li><a href="https://github.com/Zasilkovna/opencart2/archive/AJAX-quick-checkout-opencart2.3.zip">Stáhnout upravenou verzi pro modul AJAX quick checkout (Opencart 2.3) &raquo;</a></li> 
      	</ul>
      </li>
      <li><a href="https://github.com/Zasilkovna/opencart2/archive/master.zip">Stáhnout soubor modulu pro Opencart 2.0-2.2.x &raquo;</a>
      	<ul>
      		<li><a href="https://github.com/Zasilkovna/opencart2/archive/AJAX-quick-checkout.zip">Stáhnout upravenou verzi pro modul AJAX quick checkout (Opencart 2.0-2.2.x) &raquo;</a></li> 
      	</ul>
      </li>
    </ul>
  </li>
  <li>
    Obsah adresáře <code>opencart2-master</code> nakopírujte do kořenového adresáře vašeho obchodu opencart.<br>
  </li>
  <li>
    Přihlašte se do administrace, přejděte na stránku Extensions » Shipping a modul nainstalujte.<br>
    <a href="https://cloud.githubusercontent.com/assets/11771520/8772625/045ed8cc-2ece-11e5-9f01-bb90e556e2a1.png"><img width=200 height=200 src="https://cloud.githubusercontent.com/assets/11771520/8772625/045ed8cc-2ece-11e5-9f01-bb90e556e2a1.png"></a><br><br>
    <a href="https://cloud.githubusercontent.com/assets/11771520/8772624/03292192-2ece-11e5-8612-c09330155585.png"><img width=600 height=46 src="https://cloud.githubusercontent.com/assets/11771520/8772624/03292192-2ece-11e5-8612-c09330155585.png"></a><br><br>
  </li>
  <li>
    Po nainstalování modulu (zelené +) klikněte na modré tlačítko <i><strong>edit</strong></i><br><br>
  </li>
  <li>
    Na stránce editace zadejte název dopravy, cenu, vyberte zemi, ze které mají být nabízeny pobočky a danou dopravní metodu povolte.
    Dále zadejte klíč api a povolte celý modul. Navíc můžete zadat daň dopravy.<br><br>
    <a href="https://cloud.githubusercontent.com/assets/11771520/8772621/00d3b164-2ece-11e5-8172-eaff1100ec6f.png"><img width=400 height=250 src="https://cloud.githubusercontent.com/assets/11771520/8772621/00d3b164-2ece-11e5-8172-eaff1100ec6f.png"></a><br><br>
  </li>
  <li>
    Nyní je doprava přes zásilkovnu nabízena vašim zákazníkům. Cílová pobočka bude uvedena vždy v <strong>poznámce objednávky</strong>.
  </li>
  <li>
    <strong style="color: red">Možný problém: </strong> pokud v košíku OpenCart po volbě dopravy Zásilkovnou tvrdí, že není vybrána doprava, zkontrolujte, zda nemáte v názvu způsobu dopravy tečku, např. <code>Zásilkovna.cz</code>. Pokud ano, odstraňte ji, OpenCart používá tečku pro oddělování položek a špatně pak název rozpozná.
    </li>
</ol>
<h2>Informace o modulu</h2>
<p>Podporované jazyky:</p>
<ul>
  <li>čeština</li>
  <li>angličtina</li>
</ul>
<h3>Podporované verze:</h3>
<ul>
  <li>Opencart 2.0.0 a novější</li>
  <li>Při problému s použitím v jiné verzi nás kontaktujte na adrese <a href="mailto:technicka.podpora@zasilkovna.cz">technicka.podpora@zasilkovna.cz</a></li>
</ul>
<h3>Poskytované funkce:</h3>
<ul>
  <li>Nastavení různé ceny pro různé cílové země</li>
  <li>Nastavení daně dopravy a GEO zóny</li>
  <li>Doprava zdarma od zadané ceny objednávky</li>
  <li>Cílová pobočka je uvedena v poznámce objednávky</li>
</ul>
<p>Pro provázání dopravy a platby doporučujeme použít modul, který naleznete <a targer='_blank' href="http://www.opencart.com/index.php?route=extension/extension/info&amp;extension_id=11301&amp;filter_search=gop">na této stránce</a></p>
