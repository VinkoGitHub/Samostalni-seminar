# Samostalni-seminar
Materijal vezan uz kolegij "Samostalni seminar iz istraživanja u fizici".

Cijeli seminar bazira se na radu

> S. H. Rudy, S. L. Brunton, J. L. Proctor, J. N. Kutz, Data-driven discovery of partial differential equations. Sci. Adv. 3, e1602614 (2017)

kojeg se može pronaći na [Science Advances](https://www.science.org/doi/10.1126/sciadv.1602614). Kodovi koji su priloženi u repozitoriju većinom su modificirane verzije onih iz navedenog rada.

## Datoteke
- **PDE_FIND_QM.py** je modul unutar kojeg se nalaze funkcije potreben za identifikaciju dinamike kvantnih sustava (jednadžbe oblika $u_t=N(u)$).
- **PDE_FIND_CM.py** je modul unutar kojeg se nalaze funkcije potreben za identifikaciju dinamike klasičnih sustava (jednadžbe oblika $u_{tt}=N(u)$).
- **Examples** je mapa unutar koje su razni primjeri za koje je uspješno identificirana dinamika.
- **Datasets** je mapa unutar koje se nalaze podatci i primjeri potrebni za treniranje koda.
