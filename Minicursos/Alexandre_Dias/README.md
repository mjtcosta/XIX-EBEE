
# Excitonic effects using WanTiBEXOS: a MLWF‑TB + BSE approach  
**Palestrante:** Prof. **Alexandre C. Dias** (IF‑UnB) · **Evento:** XIX Escola Brasileira de Estrutura Eletrônica (EBEE) · **Ano:** 2025

## Introdução
Este minicurso apresenta o **WanTiBEXOS**, um pacote baseado em **tight‑binding de funções de Wannier maximamente localizadas (MLWF‑TB)** acoplado à **Equação de Bethe–Salpeter (BSE)** para estudar **propriedades eletrônicas e óticas com efeitos excitônicos** em materiais periódicos. A estrutura do curso cobre: (i) geração do Hamiltoniano MLWF‑TB (via interfaces com VASP/Quantum‑ESPRESSO/SIESTA/FHI‑aims ou *Extended Hückel*), (ii) pós‑processamentos eletrônicos (bandas, DOS, massa efetiva, curvatura de Berry, texturas de spin), (iii) **propriedades ópticas no regime IPA** e, sobretudo, (iv) **cálculo de excitons via BSE** com diferentes modelos para a interação el‑h (Coulomb 3D, Keldysh/Rytova 2D e variantes truncadas/Ohno) incluindo **efeitos de temperatura**. Também são discutidos **termelétricos (CRTA)** e métricas de desempenho fotovoltaico (absorvância, **PCE/SLME**). A parte prática guia desde a **instalação** (compilador Intel/`make all`) até *hands‑on* para bandas, DOS, ótica, BSE (densidade de probabilidade e bandas excitônicas) e estimativas de **eficiência fotovoltaica**.

## Referências (com links)
- **Documentação WanTiBEXOS:** https://wantibexos.readthedocs.io  
- **Repositório WanTiBEXOS (GitHub):** https://github.com/ac-dias/wantibexos  
- **Artigo do código (CPC, 2022/2023):** *WanTiBEXOS: a Wannier‑based Tight‑Binding code for electronic band structure, excitonic and optoelectronic properties of solids* — https://doi.org/10.1016/j.cpc.2022.108636  
- **Wannier90 (MLWFs):** Pizzi *et al.*, *J. Phys.: Condens. Matter* **32**, 165902 (2020) — https://doi.org/10.1088/1361-648X/ab51ff  
- **Revisão BSE/MBPT:** Onida, Reining & Rubio, *Rev. Mod. Phys.* **74**, 601 (2002) — https://link.aps.org/doi/10.1103/RevModPhys.74.601  
- **Potencial 2D (screening):** Cudazzo, Tokatly & Rubio, *Phys. Rev. B* **84**, 085406 (2011) — https://link.aps.org/doi/10.1103/PhysRevB.84.085406 ;  
  Berkelbach, Hybertsen & Reichman, *Phys. Rev. B* **88**, 045318 (2013) — https://link.aps.org/doi/10.1103/PhysRevB.88.045318 ;  
  Rytova (1967) — versão moderna: https://arxiv.org/abs/1806.00976 ; Keldysh, *JETP Lett.* **29**, 658 (1979) — https://ui.adsabs.harvard.edu/abs/1979JETPL..29..658K/abstract  
- **Curvatura de Berry (fundamentos):** Xiao, Chang & Niu, *Rev. Mod. Phys.* **82**, 1959 (2010) — https://link.aps.org/doi/10.1103/RevModPhys.82.1959  
- **SLME (eficiência espectroscópica):** Yu & Zunger, *Phys. Rev. Lett.* **108**, 068701 (2012) — https://link.aps.org/doi/10.1103/PhysRevLett.108.068701  

## Perfis
- **Google Scholar:** https://scholar.google.com/citations?user=0Pe4TDQAAAAJ  
- **Lattes:** http://lattes.cnpq.br/6101630210269302

## GITHUB

** https://github.com/ac-dias/wantibexos-recipes
