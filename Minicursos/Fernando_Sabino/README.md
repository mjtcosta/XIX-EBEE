# Minicurso: Introdução à Teoria do Funcional da Densidade (DFT)

**Palestrante:** Fernando Pereira Sabino (EESC–USP)  
**Evento:** EBEE XIX — Escola Brasileira de Estrutura Eletrônica

## Introdução
Este minicurso apresenta os fundamentos da Teoria do Funcional da Densidade (DFT) e sua aplicação em ciência de materiais. Partimos dos teoremas de Hohenberg–Kohn, que estabelecem a densidade eletrônica como variável fundamental do estado fundamental, e do formalismo de Kohn–Sham, que mapeia o sistema interagente para um sistema de elétrons não interagentes que reproduz a mesma densidade. Em seguida, discutimos a aproximação de troca‑correlação — o “coração” da DFT — organizando‑a ao longo da *escada de Jacó* (LDA → GGA → meta‑GGA → híbridos), com ênfase em escolhas práticas de funcionais, critérios de convergência e validação.

Na parte aplicada, o foco recai sobre cálculo de estruturas eletrônicas e propriedades ópticas/energéticas em sólidos: seleção de pseudopotenciais/PAW, bases (ondas planas vs. orbitais localizados), tratamento de interações de van der Waals (D3/TS/vdW‑DF), efeitos de correlação local (DFT+U) e recomendações para estimativa de *band gaps*, defeitos e estabilidade estrutural. O minicurso fecha com boas práticas de reprodutibilidade (parâmetros de *k‑mesh*, cortes de energia, testes de convergência) e um roteiro mínimo para projetos em códigos *ab initio* populares.

## Referências principais (com links)
- Hohenberg, P.; Kohn, W. **Inhomogeneous Electron Gas**. *Phys. Rev.* **136**, B864 (1964). DOI: 10.1103/PhysRev.136.B864.  
  <https://link.aps.org/doi/10.1103/PhysRev.136.B864>
- Kohn, W.; Sham, L. J. **Self‑Consistent Equations Including Exchange and Correlation Effects**. *Phys. Rev.* **140**, A1133 (1965). DOI: 10.1103/PhysRev.140.A1133.  
  <https://link.aps.org/doi/10.1103/PhysRev.140.A1133>
- Perdew, J. P.; Burke, K.; Ernzerhof, M. **PBE GGA**. *Phys. Rev. Lett.* **77**, 3865 (1996).  
  <https://doi.org/10.1103/PhysRevLett.77.3865>
- Perdew, J. P. **et al.** **PBEsol**. *Phys. Rev. Lett.* **100**, 136406 (2008).  
  <https://doi.org/10.1103/PhysRevLett.100.136406>
- Sun, J.; Ruzsinszky, A.; Perdew, J. P. **SCAN meta‑GGA**. *Phys. Rev. Lett.* **115**, 036402 (2015).  
  <https://doi.org/10.1103/PhysRevLett.115.036402>
- Furness, J. W. **et al.** **r2SCAN**. *Phys. Rev. B* **102**, 100102(R) (2020).  
  <https://doi.org/10.1103/PhysRevB.102.100102>
- Adamo, C.; Barone, V. **PBE0 híbrido**. *J. Chem. Phys.* **110**, 6158 (1999).  
  <https://doi.org/10.1063/1.478522>
- Heyd, J.; Scuseria, G. E.; Ernzerhof, M. **HSE (2003/2006)**. *J. Chem. Phys.* **118**, 8207 (2003); Krukau **et al.**, *J. Chem. Phys.* **125**, 224106 (2006).  
  <https://doi.org/10.1063/1.1564060> • <https://doi.org/10.1063/1.2404663>
- Perdew, J. P.; Zunger, A. **LDA (PZ81)**. *Phys. Rev. B* **23**, 5048 (1981).  
  <https://doi.org/10.1103/PhysRevB.23.5048>
- Ceperley, D. M.; Alder, B. J. **Gás de elétrons QMC**. *Phys. Rev. Lett.* **45**, 566 (1980).  
  <https://doi.org/10.1103/PhysRevLett.45.566>
- Grimme, S. **Dispersion D3 / D3(BJ)**. *J. Chem. Phys.* **132**, 154104 (2010); *J. Comput. Chem.* **32**, 1456 (2011).  
  <https://doi.org/10.1063/1.3382344> • <https://doi.org/10.1002/jcc.21759>
- Tkatchenko, A.; Scheffler, M. **TS-vdW**. *Phys. Rev. Lett.* **102**, 073005 (2009).  
  <https://doi.org/10.1103/PhysRevLett.102.073005>
- Dion, M. **et al.** **vdW‑DF**. *Phys. Rev. Lett.* **92**, 246401 (2004).  
  <https://doi.org/10.1103/PhysRevLett.92.246401>
- Lee, K. **et al.** **vdW‑DF2**. *Phys. Rev. B* **82**, 081101(R) (2010).  
  <https://doi.org/10.1103/PhysRevB.82.081101>
- Dudarev, S. L. **et al.** **DFT+U (Dudarev)**. *Phys. Rev. B* **57**, 1505 (1998).  
  <https://doi.org/10.1103/PhysRevB.57.1505>
- Blöchl, P. E. **PAW**. *Phys. Rev. B* **50**, 17953 (1994).  
  <https://doi.org/10.1103/PhysRevB.50.17953>
- Vanderbilt, D. **Ultrasoft pseudopotentials**. *Phys. Rev. B* **41**, 7892 (1990).  
  <https://doi.org/10.1103/PhysRevB.41.7892>
- Troullier, N.; Martins, J. L. **Pseudopotenciais TM**. *Phys. Rev. B* **43**, 1993 (1991).  
  <https://doi.org/10.1103/PhysRevB.43.1993>
- Perdew, J. P.; Schmidt, K. **Jacob's Ladder**. *AIP Conf. Proc.* **577**, 1–20 (2001).  
  <https://doi.org/10.1063/1.1390175>
- **Livros didáticos úteis**
  - Parr, R. G.; Yang, W. *Density-Functional Theory of Atoms and Molecules*. Oxford (1989).  
    <https://global.oup.com/academic/product/density-functional-theory-of-atoms-and-molecules-9780195092769>
  - Martin, R. M. *Electronic Structure: Basic Theory and Practical Methods*. Cambridge (2004/2008).  
    <https://doi.org/10.1017/CBO9780511805769>
  - Giustino, F. *Materials Modelling using DFT*. Oxford (2014).  
    <https://global.oup.com/academic/product/materials-modelling-using-density-functional-theory-9780199662432>

## Perfis
- Google Scholar: <https://scholar.google.com/citations?user=Y9SK0n4AAAAJ>
- Lattes (CNPq): <https://lattes.cnpq.br/K4204095D6>
