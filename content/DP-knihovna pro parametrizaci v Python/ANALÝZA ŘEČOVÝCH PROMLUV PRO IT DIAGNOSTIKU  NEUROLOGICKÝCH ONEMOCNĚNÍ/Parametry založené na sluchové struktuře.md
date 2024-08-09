---
dg-publish: dg-publish
---
Použitím ICC koeficientů je možné získat frekvenční spektrum modulačních obálek aplikovaných na různá pásma sluchového podnětu. Podobně jako v případě modulačního spektra zahrnuje výpočet ICC na začátku STFT a následně extrakci výkonového spektra $|S[k,m]|^2$. Nicméně v dalším kroku už není použita filtrace bankou trojúhelníkových filtrů, ale bankou P gammatónových filtrů rovnoměrně rozložených na melovské škále. Tyto filtry jsou definovány následovně:

![[Pasted image 20240808153203.png]]
Kde je f_c střední frekvence v Hz, o řád filtru (v případě této práce byl volen o = 4) a fvz vzorkovací frekvence v Hz.

Nakonec je modulové spektrum každé obálky $|T[p,l]|$ filtrováno bankou Q = 13 rezonančních filtrů exponenciálně rozdělených od 12 do 107Hz.


Takto na konci procesu vznikne matice $Ξ[p,q]$  (q = 1,2,...,Q) ICC koeficientů pro vstupní řečový signál s[n]. Nově navržené parametry jsou založeny na funkci $ξ[p]$, která je vypočítána z $Ξ[p,q]$ dle vztahu:

![[Pasted image 20240808153438.png]]

+