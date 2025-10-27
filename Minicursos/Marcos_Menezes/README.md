# Optical Properties of Nanomaterials from ab-initio Calculations 

## Introdução
Este minicurso da **XIX Escola Brasileira de Estrutura Eletrônica** apresenta um roteiro prático e conceitual para o cálculo de **propriedades ópticas de nanomateriais a partir de primeiros princípios**. Partimos da **Teoria do Funcional da Densidade (DFT)** para descrever o estado fundamental e discutimos suas limitações na predição de gaps e espectros. A partir daí, motivamos a **Teoria de Perturbações de Muitos Corpos (MBPT)**: a aproximação **GW** para correções de quase-partículas e a **Equação de Bethe–Salpeter (BSE)** para incluir **excitons** na resposta óptica. Ao longo do caminho, exploramos exemplos que vão desde a correção do gap em semicondutores à renormalização da velocidade de Fermi em grafeno, destacando por que **efeitos excitônicos são particularmente fortes em sistemas 2D**.

Além dos fundamentos, o minicurso enfatiza **boas práticas numéricas e de convergência**, essenciais para resultados confiáveis: escolha e densidade de malhas k, número de bandas vazias, tratamentos do potencial de Coulomb em 2D e critérios de parada. Mostramos estratégias específicas para materiais bidimensionais e discutimos como **respostas ópticas não lineares** (p.ex., *second harmonic generation* e *shift current*) podem ser tratadas de forma consistente com excitons. O objetivo é fornecer ao participante um mapa claro que conecte teoria, implementação e interpretação física, com ênfase em resultados recentes e aplicações relevantes.

## Referências (com links)

### Fundamentos (DFT e ótica linear)
- P. Hohenberg; W. Kohn. *Phys. Rev.* **136**, B864 (1964). [doi:10.1103/PhysRev.136.B864](https://doi.org/10.1103/PhysRev.136.B864)
- W. Kohn; L. J. Sham. *Phys. Rev.* **140**, A1133 (1965). [doi:10.1103/PhysRev.140.A1133](https://doi.org/10.1103/PhysRev.140.A1133)
- M. L. Cohen; S. G. Louie. *Fundamentals of Condensed Matter Physics*. Cambridge (2016). [Página da editora](https://www.cambridge.org/highereducation/books/fundamentals-of-condensed-matter-physics/446148D4DABEFCF80363F14A0230056E)
- L. Hedin; S. O. Lundqvist. *Solid State Physics* **23**, 1–181 (1969). [doi:10.1016/S0081-1947(08)60615-3](https://doi.org/10.1016/S0081-1947(08)60615-3)

### MBPT / GW
- M. S. Hybertsen; S. G. Louie. *Phys. Rev. B* **34**, 5390 (1986). [doi:10.1103/PhysRevB.34.5390](https://doi.org/10.1103/PhysRevB.34.5390)
- J. Deslippe *et al.* *Comput. Phys. Commun.* **183**, 1269 (2012). [doi:10.1016/j.cpc.2011.12.006](https://doi.org/10.1016/j.cpc.2011.12.006) · [arXiv](https://arxiv.org/abs/1111.4429)
- M. van Schilfgaarde; T. Kotani; S. V. Faleev. *Phys. Rev. Lett.* **96**, 226402 (2006). [doi:10.1103/PhysRevLett.96.226402](https://doi.org/10.1103/PhysRevLett.96.226402)
- W. Chen; A. Pasquarello. *Phys. Rev. B* **86**, 035134 (2012). [doi:10.1103/PhysRevB.86.035134](https://doi.org/10.1103/PhysRevB.86.035134)

### Excítons / BSE
- M. Rohlfing; S. G. Louie. *Phys. Rev. B* **62**, 4927 (2000). [doi:10.1103/PhysRevB.62.4927](https://doi.org/10.1103/PhysRevB.62.4927)
- G. Strinati. *Rivista del Nuovo Cimento* **11**, 1–86 (1988). [doi:10.1007/BF02725962](https://doi.org/10.1007/BF02725962)

### Convergência e algoritmos (2D / supercélulas)
- D. Y. Qiu; F. H. da Jornada; S. G. Louie. *Phys. Rev. B* **93**, 235435 (2016). [doi:10.1103/PhysRevB.93.235435](https://doi.org/10.1103/PhysRevB.93.235435) · [arXiv](https://arxiv.org/abs/1605.08733)
- F. H. da Jornada; D. Y. Qiu; S. G. Louie. *Phys. Rev. B* **95**, 035109 (2017). [doi:10.1103/PhysRevB.95.035109](https://doi.org/10.1103/PhysRevB.95.035109) · [arXiv](https://arxiv.org/abs/1610.06641)
- J. B. Haber; D. Y. Qiu; F. H. da Jornada; J. B. Neaton. *Phys. Rev. B* **108**, 125118 (2023). [doi:10.1103/PhysRevB.108.125118](https://doi.org/10.1103/PhysRevB.108.125118)
- A. R. Altman; S. Kundu; F. H. da Jornada. *Phys. Rev. Lett.* **132**, 086401 (2024). [doi:10.1103/PhysRevLett.132.086401](https://doi.org/10.1103/PhysRevLett.132.086401)

### Resultados e aplicações citadas
- P. E. Trevisanutto *et al.* *Phys. Rev. Lett.* **101**, 226405 (2008). [doi:10.1103/PhysRevLett.101.226405](https://doi.org/10.1103/PhysRevLett.101.226405)
- C. Attaccalite; A. Rubio. *Phys. Status Solidi B* **246**, 2523–2526 (2009). [doi:10.1002/pssb.200982335](https://doi.org/10.1002/pssb.200982335)

### Óptica não linear com excítons
- Y.-H. Chan; D. Y. Qiu; F. H. da Jornada; S. G. Louie. *PNAS* **118**, e1906938118 (2021). [doi:10.1073/pnas.1906938118](https://doi.org/10.1073/pnas.1906938118)
- J. Ruan; Y.-H. Chan; S. G. Louie. *Nano Lett.* **24**, 15533–15539 (2024). [doi:10.1021/acs.nanolett.4c03434](https://doi.org/10.1021/acs.nanolett.4c03434)

### Trabalhos do grupo
- M. G. Menezes; R. B. Capaz; S. G. Louie. *Phys. Rev. B* **89**, 035431 (2014). [doi:10.1103/PhysRevB.89.035431](https://doi.org/10.1103/PhysRevB.89.035431)
- W. S. Paz *et al.* *Nano Lett.* **21**, 7781–7788 (2021). [doi:10.1021/acs.nanolett.1c02742](https://doi.org/10.1021/acs.nanolett.1c02742)
- J. E. Silveira *et al.* *J. Environ. Chem. Eng.* **12**, 111998 (2024). [doi:10.1016/j.jece.2024.111998](https://doi.org/10.1016/j.jece.2024.111998)
- V. G. Garcia *et al.* *FlatChem* **48**, 100753 (2024). [doi:10.1016/j.flatc.2024.100753](https://doi.org/10.1016/j.flatc.2024.100753)


## Perfis do Prof. Marcos G. Menezes
- **Google Scholar:** https://scholar.google.com/citations?user=t38NLLwAAAAJ
- **Currículo Lattes:** https://lattes.cnpq.br/5945425658332294
