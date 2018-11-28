# DiphtheriaRohingya2017

Code listing for a paper: [Matsuyama R, Akhmetzhanov AR, Endo A, Lee H, Yamaguchi T, Tsuzuki S, Nishiura H 2018 Uncertainty and sensitivity analysis of the basic reproduction number of diphtheria: A case study of Rohingya refugee camp in Bangladesh, November-December 2017. *PeerJ*](https://peerj.com/articles/4583/)

**Background** A Rohingya refugee camp in Cox’s Bazar, Bangladesh experienced a large-scale diphtheria epidemic in 2017. The background information of previously immune fraction among refugees cannot be explicitly estimated, and thus, we conducted an uncertainty analysis of the basic reproduction number, *R*<sub>0</sub>.

**Methods** A renewal process model was devised to estimate the *R*<sub>0</sub> and ascertainment rate of cases, and loss of susceptible individuals was modeled as one minus the sum of initially immune fraction and the fraction naturally infected during the epidemic. To account for the uncertainty of initially immune fraction, we employed a Latin Hypercube sampling method.

**Results** *R*<sub>0</sub> ranged from 4.7 to 14.8 with the median estimate at 7.2. *R*<sub>0</sub> was positively correlated with ascertainment rates. Sensitivity analysis indicated that *R*<sub>0</sub> would become smaller with greater variance of the generation time.

**Discussion** Estimated *R*<sub>0</sub> was broadly consistent with published estimate from endemic data, indicating that the vaccination coverage of 86% has to be satisfied to prevent the epidemic by means of mass vaccination. LHS was particularly useful in the setting of refugee camp in which the background health status is poorly quantified.

---

Code scripts consists of two notebooks:
* "[*A. Outbreak Analysis in Julia*](https://nbviewer.jupyter.org/github/aakhmetz/DiphtheriaRohingya2017/blob/master/A-Outbreak_Analysis_in_Julia.ipynb)" presents the code that was used to run simulations and generate all results in the paper,
* "[*B. Plotting in R*](B-Plotting_in_R.ipynb)" shows the code that was used to generate all figures in the paper.

Additionally, there is data-file "Data.xlsx" with reported diphtheria incidence in a Rohingya refugee camp, and three files *output_Julia_XX.csv" with the output of simulations used in the second notebook.
