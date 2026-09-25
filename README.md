# Tuottovaateiden kartta

Mikä selittää Inderesin seuraamien yhtiöiden tuottovaatimusta (WACC 2026)? Koko, riski vai toimiala?

**Avaa sivu:** https://tommisaarinen28-dotcom.github.io/inderes-wacc-kartta/

- 171 Inderesin seuraamaa yhtiötä, tilanne 25.9.2026
- WACC: Inderesin rankinglista (WACC 2026)
- Sektori, toimiala (ICB), markkina-arvo ja riskipisteet: inderes.fi GraphQL (tuorein ennustetransaktio)
- SEK-markkina-arvot on muunnettu euroiksi EKP:n viitekurssilla. Multituden ja Spotifyn sektori on luokiteltu käsin, koska se puuttuu lähteestä.

Sivulla: WACC vs. markkina-arvo (log), WACC riskipisteittäin, WACC toimialoittain, kokoluokka × sektori -lämpökartta ja yhtiötaulukko, jossa näkyy poikkeama koko + riski -sovitteesta. Sektorisuodatin rajaa kaikki kaaviot kerralla.

`wacc_landscape.csv` sisältää sivun lähdedatan.
