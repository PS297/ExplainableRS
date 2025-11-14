# Feature Importance Aware Deep Neural Network Model for Explainable Recommender Systems
An interpretable decision-making process is vital for developing
recommender systems. It should identify key items and relevant
information to improve the recommendations. Deep learning models have
shown promising performance, but simultaneously achieving explainability
and efficiency is challenging. Existing explainable recommender systems
interpret feature importance after training, which may not be able
to determine crucial feature importance for enhancing performance. Additionally,
the model’s learning paradigm depends on a single-objective
function that ignores the captured information of user-item interaction.
This study aims to develop a feature importance aware deep neural
network model for explainable recommender systems, which facilitates
improved predictive performance by considering the feature importance
within the training procedure and generates a recommendation list based
on the user’s preference. The proposed method minimizes the combination
of model losses and introduces a penalty term that specifically targets
and diminishes the detrimental impact of a particular feature on
the solution’s efficacy. This strategy ensures the determination of the
optimal solution by satisfying the explainable conditions imposed during
the training framework. Extensive experiments on publicly accessible
FilmTrust and MovieLens-100K datasets show notable recommendation
performance.
<img width="1703" height="620" alt="Fig 3" src="https://github.com/user-attachments/assets/c673675d-4c96-4d50-aafe-522995f73556" />




## Citation
@InProceedings{10.1007/978-3-032-10489-2_10,
author="Gupta, Pragya
and Aishwaryaprajna
and Guha, Debashree
and Chakraborty, Debjani",
editor="Mart{\'i}nez, Luis
and Camacho, David
and Yin, Hujun
and Dutta, Bapi
and Yera, Raciel
and Rodr{\'i}guez Dom{\'i}nguez, Rosa M.
and Tall{\'o}n-Ballesteros, Antonio",
title="Feature-Importance Aware Deep Neural Network Model for Explainable Recommender Systems",
booktitle="Intelligent Data Engineering and Automated Learning -- IDEAL 2025",
year="2026",
publisher="Springer Nature Switzerland",
address="Cham",
pages="109--120",
}
