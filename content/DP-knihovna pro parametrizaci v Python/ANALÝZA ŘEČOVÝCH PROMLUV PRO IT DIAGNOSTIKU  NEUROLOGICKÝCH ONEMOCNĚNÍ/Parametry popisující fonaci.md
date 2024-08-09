---
dg-publish: dg-publish
---
+Pravděpodobně nejpoužívanějšími parametry popisujícími patologický hlas jsou frek vence základního tónu F<sub>0</sub> a parametry vyjadřující její variabilitu v čase ([[Jitter|jitter]]): PPQ5 (five-point Pitch Perturbation Quotient), RAP (Relative Average Pertur bation), jitt<sub>loc</sub> (průměrná absolutní odchylka mezi následujícími periodami dělená průměrnou periodou), jitt<sub>abs</sub> (průměrná absolutní odchylka mezi následujícími peri odami), jitt<sub>ddp</sub> (průměrná absolutní odchylka mezi následujícími odchylkami soused ních glotálních period dělená průměrnou periodou).
Tyto para metry jsou dobrými kandidáty především pro kvantifikaci [[Klidový tremor|vokálního tremoru]]

Tieto medtódy však ovplyvňuje pohlavie rečníka.

Preto bolo vyvinuté PPE (Pitch Period Entropy) pri výpočte je uvažovaná logaritmická poltónová škála, inverzná filtrácia a odhad entropie.

Ďalšia metóda -> meranie smerodatnej odchýlky po, po ktorú sú hlasivky otvorené a zatvorené.

K efektivnímu popisu hypofonie či odchylek intenzity hlasu je možno použít krátkodobou energii E nebo změny úrovně hlasivkových pulzů ([[Shimmer]])

V tejto [[Abstrakt - Mykéska dizertačná práca|práci]] je uvedených 6 druhov [[Jitter|jitteru]] 
- APQ3
- APQ5
- APQ11
- shimm<sub>loc</sub>
- shimm<sub>ddp</sub>
- shimm<sub>dB</sub>
Ďalšie parametre:
- TKEO (Teager-Kaiser Energy Operator)
  Výhodou tohoto příznaku oproti E je to, že bere v úvahu také frekvenci signálu.
- ME (Modulation Energy)
  byla vybrána jako pa rametr, který úzce souvisí s rozložením energie ve výkonovém spektru.
- MPSD (Median of Power Spectral Density)
   Podobně je využíván medián výkonové spektrální hustoty
- LSTER (Low Short-Time Energy Ratio)
  LSTER se používá k diferenciaci mezi řečí a hudebním signá lem, jelikož řeč vykazuje větší odchylky v energii během úseků dlouhých 10–30ms. Nicméně tento parametr byl v práci zařazen i do analýzy patologického hlasu, jelikož se uvažuje, že v případě nemocných řečníků bude dosahovat vyšších hodnot.

+