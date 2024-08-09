---
dg-publish: dg-publish
---
Nedávno byly v oblasti zpracování řečových signálů uvedeny nové metody založené na [[empirická modální dekompozice|empirické modální dekompozici]] EMD (Empirical Mode Decomposition). Pomocí EMD je možné rozložit jakýkoliv nelineární a časově proměnný signál na omezený, a většinou nízký, počet vlastních funkcí IMF (Intrinsic Mode Functions). Tyto funkce jsou frekvenčně a amplitudově modulované a jejich součtem je opět původní signál. Tsanas et al. navrhli několik metod měření SNR a NSR (Noise-to-Signal ratio) založených na IMF . Složky signálu ležící na vysokých frekvencích jsou obsaženy v prvních několika IMF. Proto mohou být tyto vlastní funkce použity k reprezen taci šumu a zbylé IMF k reprezentaci užitečné informace. Na tomto principu byly navrženy parametry IMF-SNR<sub>TKEO</sub> (založeno na Teagerově-Kaiserově energetickém operátoru), IMF-SNR<sub>SEO</sub> (založeno na energii signálu), IMF-SNR<sub>SE</sub> (založeno na Shannonově entropii), IMF-NSR<sub>TKEO</sub>, IMF-NSR<sub>SEO</sub> a IMF-NSR<sub>SE</sub>.

+
