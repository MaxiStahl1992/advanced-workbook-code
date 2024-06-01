This codebase is part of the Advanced Workbook for the course DLMAIIAC01 – Inference and Causality. It contains implementations and analyses for various tasks related to Bayesian statistics, Granger causality, confounders in AI, the front-door criterion, handling missing data, and collider bias. The aim is to apply theoretical concepts to practical examples and demonstrate their real-world implications.

All sources used to complete the tasks are listed under 2.Sources. This list is comprehensive and includes all journal entries, articels, webpages and books used (besides some code libraries and the course book) used to complete the tasks. The list includes sources not used in the final version of the paper, but I still found them useful to gain a deeper understanding of the topics.

## 1.Tasks
1. Task 1: Bayesian Statistics: Comparison of Conjugate and Jeffery Prior Distributions
Description: Scrutinize and compare the practical applications of a conjugate prior distribution with those of a Jeffreys prior distribution. Examine how the selection of a prior influences posterior computation and its implications in a real-world scenario.
2. Task 2: Granger Causality on a Stock Market Example
Description: Explain the concept of Granger causality in the context of time series data using an example of stock market analysis. Demonstrate the implications of finding a Granger-causal relationship.
3. Task 3: Confounders in the Context of Artificial Intelligence
Description: Describe the concept of confounders in AI and elaborate on how addressing confounders can aid in machine learning model interpretation and reliability. Discuss a technique used in AI for adjusting for confounders.
4. Task 4: Educational Platform and the Front Door Criterion
Description: Explain how to use the front-door criterion to determine the causal effect of motivational messages on student engagement in an educational platform. Describe the variables, mediator, necessary controls, and conditions for the front-door criterion.
5. Task 5: The Impact of Missing Data on the Example of Weight Loss and Diet
Description: Analyze the effect of diet on weight loss using observational data. Discuss how missing values might affect the analysis and propose a causal approach to handle missing data, emphasizing its importance in yielding consistent estimates.
6. Task 6: Collider Bias in a Hypothetical Study on Stress, Smoking, and Heart Disease
Description: Discuss the concept of collider bias in a hypothetical study examining the relationship between stress, smoking, and heart disease. Explain why controlling for smoking might lead to incorrect causal inferences and outline how collider bias can be identified and mitigated.

## 2.Sources
### Task 1:
* Ghaderinezhad, F., & Ley, C. (2020). On the Impact of the Choice of the Prior in Bayesian Statistics. In N. Tang (Ed.), Bayesian Inference on Complicated Data. IntechOpen. https://doi.org/10.5772/intechopen.88994
* Gutiérrez‐Peña, E., & Muliere, P. (2004). Conjugate Priors Represent Strong Pre‐Experimental Assumptions. Scandinavian Journal of Statistics, 31(2), 235–246. https://doi.org/10.1111/j.1467-9469.2004.02-019.x
* Hornik, K., & Grün, B. (2013). On conjugate families and Jeffreys priors for von Mises–Fisher distributions. Journal of Statistical Planning and Inference, 143(5), 992–999. https://doi.org/10.1016/j.jspi.2012.11.003
* Tokdar, S. (2014). Choosing a Prior Distribution. https://www2.stat.duke.edu/~st118/sta732/Prior.pdf

### Task 2:
* Cornwall, G. J., Mills, J. A., Sauley, B. A., & Weng, H. (2019). Topics in identification, limited dependent variables, partial observability, experimentation, and flexible modelling. Part A (First edition). Emerald Publishing.
* Fisher, R. A. (1928). Statistical methods for research workers (2nd ed.). Oliver and Boyd.
* Guo, Z. (2023). Research on the Augmented Dickey-Fuller Test for Predicting Stock Prices and Returns. Advances in Economics, Management and Political Sciences, 44(1), 101–106. https://doi.org/10.54254/2754-1169/44/20232198
* Mittnik, S., & Otter, P. W. (1990). DETERMINATION OF LINEAR FEEDBACK BETWEEN MULTIPLE TIME SERIES. In Dynamic Modelling and Control of National Economies 1989 (pp. 329–334). Elsevier. https://doi.org/10.1016/B978-0-08-037538-0.50054-X
* Papana, A., Kyrtsou, C., Kugiumtzis, D., & Diks, C. (2017). Financial networks based on Granger causality: A case study. Physica A: Statistical Mechanics and Its Applications, 482, 65–73. https://doi.org/10.1016/j.physa.2017.04.046
* Peia, O., & Roszbach, K. (2015). Finance and growth: Time series evidence on causality. Journal of Financial Stability, 19, 105–118. https://doi.org/10.1016/j.jfs.2014.11.005
* Shojaie, A., & Fox, E. B. (2022). Granger Causality: A Review and Recent Advances. Annual Review of Statistics and Its Application, 9(1), 289–319. https://doi.org/10.1146/annurev-statistics-040120-010930
* Siggiridou, E., Koutlis, C., Tsimpiris, A., & Kugiumtzis, D. (2019). Evaluation of Granger Causality Measures for Constructing Networks from Multivariate Time Series. Entropy, 21(11), 1080. https://doi.org/10.3390/e21111080

### Task 3:
* Arbogast, P. G., & VanderWeele, T. J. (2013). Considerations for Statistical Analysis. In Developing a Protocol for Observational Comparative Effectiveness Research: A User’s Guide. Rockville (MD): Agency for Healthcare Research and Quality (US). https://www.ncbi.nlm.nih.gov/books/NBK126192/
* Beery, S., van Horn, G., & Perona, P. (2018). Recognition in Terra Incognita (arXiv:1807.04975). arXiv. http://arxiv.org/abs/1807.04975
* Bellman, R. E. (2010). Dynamic Programming. Princeton University Press. https://doi.org/10.1515/9781400835386
* Blöbaum, P., Götz, P., Budhathoki, K., Mastakouri, A. A., & Janzing, D. (2022). DoWhy-GCM: An extension of DoWhy for causal inference in graphical causal models (arXiv:2206.06821). arXiv. http://arxiv.org/abs/2206.06821
* Duffy, G., Clarke, S. L., Christensen, M., He, B., Yuan, N., Cheng, S., & Ouyang, D. (2022). Confounders mediate AI prediction of demographics in medical imaging. Npj Digital Medicine, 5(1), 188. https://doi.org/10.1038/s41746-022-00720-8
* Ferrari, E., Bosco, P., Calderoni, S., Oliva, P., Palumbo, L., Spera, G., Fantacci, M. E., & Retico, A. (2020). Dealing with confounders and outliers in classification medical studies: The Autism Spectrum Disorders case study. Artificial Intelligence in Medicine, 108, 101926. https://doi.org/10.1016/j.artmed.2020.101926
* Ferrari, E., Retico, A., & Bacciu, D. (2020). Measuring the effects of confounders in medical supervised classification problems: The Confounding Index (CI). Artificial Intelligence in Medicine, 103, 101804. https://doi.org/10.1016/j.artmed.2020.101804
* Rueckel, J., Huemmer, C., Fieselmann, A., Ghesu, F.-C., Mansoor, A., Schachtner, B., Wesp, P., Trappmann, L., Munawwar, B., Ricke, J., Ingrisch, M., & * * Sabel, B. O. (2021). Pneumothorax detection in chest radiographs: Optimizing artificial intelligence system for accuracy and confounding bias reduction using in-image annotations in algorithm training. European Radiology, 31(10), 7888–7900. https://doi.org/10.1007/s00330-021-07833-w
* Sharma, A., & Kiciman, E. (2020). DoWhy: An End-to-End Library for Causal Inference (arXiv:2011.04216). arXiv. http://arxiv.org/abs/2011.04216
* Zeng, J., Gensheimer, M. F., Rubin, D. L., Athey, S., & Shachter, R. D. (2022). Uncovering interpretable potential confounders in electronic medical records. Nature Communications, 13(1), 1014. https://doi.org/10.1038/s41467-022-28546-8

### Task 4:
* Bhattacharya, R., & Nabi, R. (2022). On Testability of the Front-Door Model via Verma Constraints (Version 2). arXiv. https://doi.org/10.48550/ARXIV.2203.00161
* Fulcher, I. R., Shpitser, I., Marealle, S., & Tchetgen Tchetgen, E. J. (2020). Robust Inference on Population Indirect Causal Effects: The Generalized Front Door Criterion. Journal of the Royal Statistical Society Series B: Statistical Methodology, 82(1), 199–214. https://doi.org/10.1111/rssb.12345
* Luo, H., Zhuang, F., Xie, R., Zhu, H., Wang, D., An, Z., & Xu, Y. (2024). A survey on causal inference for recommendation. The Innovation, 5(2), 100590. https://doi.org/10.1016/j.xinn.2024.100590
* Matthay, E. C., & Glymour, M. M. (2022). Causal Inference Challenges and New Directions for Epidemiologic Research on the Health Effects of Social Policies. Current Epidemiology Reports, 9(1), 22–37. https://doi.org/10.1007/s40471-022-00288-7
* Pearl, J. (2009). Causal inference in statistics: An overview. Statistics Surveys, 3(none). https://doi.org/10.1214/09-SS057

### Task 5:
* Chen, Y., Wang, X., & Xu, G. (2023). GATGPT: A Pre-trained Large Language Model with Graph Attention Network for Spatiotemporal Imputation (arXiv:2311.14332). arXiv. http://arxiv.org/abs/2311.14332
* Ding, P., & Li, F. (2018). Causal Inference: A Missing Data Perspective. Statistical Science, 33(2). https://doi.org/10.1214/18-STS645
* Mainzer, R., Moreno-Betancur, M., Nguyen, C., Simpson, J., Carlin, J., & Lee, K. (2023). Handling of missing data with multiple imputation in observational studies that address causal questions: Protocol for a scoping review. BMJ Open, 13(2), e065576. https://doi.org/10.1136/bmjopen-2022-065576
* Mohan, K., Pearl, J., & Jin, T. (2013, June 5). Missing Data as a Causal Inference Problem. Proceedings of the Neural Information Processing Systems Conference (NIPS). https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2343794
* Nazir, A., Cheeema, M. N., & Wang, Z. (2023). ChatGPT-based biological and psychological data imputation. Meta-Radiology, 1(3), 100034. https://doi.org/10.1016/j.metrad.2023.100034
* Pedersen, A., Mikkelsen, E., Cronin-Fenton, D., Kristensen, N., Pham, T. M., Pedersen, L., & Petersen, I. (2017). Missing data and multiple imputation in clinical epidemiological research. Clinical Epidemiology, Volume 9, 157–166. https://doi.org/10.2147/CLEP.S129785
* Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., * * Passos, A., Cournapeau, D., Brucher, M., Perrot, M., & Duchesnay, E. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825–2830.
* Rodrigues, D., Kreif, N., Lawrence-Jones, A., Barahona, M., & Mayer, E. (2022). Reflection on modern methods: Constructing directed acyclic graphs (DAGs) with domain experts for health services research. International Journal of Epidemiology, 51(4), 1339–1348. https://doi.org/10.1093/ije/dyac135
* Wang, T., Smith, D. A., Campbell, C., Freeman, O., Moysova, Z., Noble, T., Várnai, K. A., Harris, S., Salih, H., Roadknight, G., Little, S., Glampson, B., Mercuri, L., Papadimitriou, D., Jones, C. R., Taylor, V., Chaudhry, A., Phan, H., Borca, F., … Matthews, P. C. (2023). Cohort Profile: The National Institute for Health Research Health Informatics Collaborative: Hepatitis B Virus (NIHR HIC HBV) research dataset. International Journal of Epidemiology, 52(1), e27–e37. https://doi.org/10.1093/ije/dyac127

### Task 6:
* Digitale, J. C., Martin, J. N., Glidden, D. V., & Glymour, M. M. (2023). Key concepts in clinical epidemiology: Collider-conditioning bias. Journal of Clinical Epidemiology, 161, 152–156. https://doi.org/10.1016/j.jclinepi.2023.07.004
* Lee, H., Aronson, J., & Nunan, D. (2019). Catalogue of bias collaboration. Collider Bias. In Catalogue Of Bias. https://catalogofbias.org/biases/collider-bias/
* Rodrigues, D., Kreif, N., Lawrence-Jones, A., Barahona, M., & Mayer, E. (2022). Reflection on modern methods: Constructing directed acyclic graphs (DAGs) with domain experts for health services research. International Journal of Epidemiology, 51(4), 1339–1348. https://doi.org/10.1093/ije/dyac135
* Rohrer, J. M. (2018). Thinking Clearly About Correlations and Causation: Graphical Causal Models for Observational Data. Advances in Methods and Practices in Psychological Science, 1(1), 27–42. https://doi.org/10.1177/2515245917745629
* Tönnies, T., Kahl, S., & Kuss, O. (2022). Collider bias in observational studies: Consequences for medical research. Part 30 of a series on evaluation of scientific publications. Deutsches Ärzteblatt International. https://doi.org/10.3238/arztebl.m2022.0076
* Turney, S. (2022). Chi-Square (Χ²) Tests | Types, Formula & Examples. Statistics. https://www.scribbr.com/statistics/chi-square-tests/
* Weiskopf, N. G., Dorr, D. A., Jackson, C., Lehmann, H. P., & Thompson, C. A. (2023). Healthcare utilization is a collider: An introduction to collider bias in EHR data reuse. Journal of the American Medical Informatics Association, 30(5), 971–977. https://doi.org/10.1093/jamia/ocad013

## 3.Paper
The corresponding paper elaborates on the theoretical background and provides a more detailed and comprehensive analyses of the tasks than just the codebase. The paper can be found in the folder PDF, as well as the task description.