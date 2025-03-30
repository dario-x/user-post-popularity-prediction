<div align="center">

  <h3>Explainable Prediction of User Post Popularity: An Analysis of the One Million Posts Corpus</h3>
    
  <p>
    <br />
    <a href=">Paper</a>
    ·
    <a href="https://ofai.github.io/million-post-corpus/">Data</a>
    ·
    <a href="mailto:dariobogenreiter@rocketmail.com">Contact</a>
  </p>
    <br />
    <br />
    <br />
</div>


## Paper Abstract
Discussions in newspaper comment sections significantly influence public opinion. The
methods used to sort and display user posts impact these discussions and can propagate
certain opinions. However, sorting is often partially done by forum moderators, which
is time-consuming and prone to bias. Machine learning models trained on user voting
statistics offer a potential solution by automatically identifying engaging posts based on
the documented opinion of the community. Prior research in this domain has primarily
focused on improving predictive accuracy using deep learning approaches, often neglecting
the critical aspect of explainability. This study explores a range of explainable methods
to algorithmically identify valuable user posts in the One Million Posts corpus, sourced
from Austrian newspaper forum DerStandard. It introduces explainable features and
evaluates explainable and interpretable models, comparing their performance against
deep learning approaches. Results show that interpretable models trained on explainable
features outperform popular baselines in this domain. However, they fall short of the
predictive power of deep learning approaches. Despite their lower predictive power, these
interpretable approaches provide valuable insights into algorithmic decision-making and
its potential pitfalls. In addition to the model results, this work presents a comprehensive
analysis of the importance of the explainable features and proposes a novel labeling
approach for engaging posts designed to accommodate both small and large datasets.

## About This Repo
This repository holds the source code for the following 
* The source code applied to preprocess the data, generate the features and provide predictions
* A link to access the datasets employed in this research
* A Usage guide to re-run the experiments

## Data
* The experiments of this work rely on the dataset 'One Million Posts Corpus' - https://ofai.github.io/million-post-corpus/ - which contains ofter 1 million user posts written on the website of the Austrian newspaper 'derStandard.at'



## Contact
In case you have any questions or inquiries, feel free to send an email to, me, <a href="mailto:dariobogenreiter@rocketmail.com">Dario</a> 

## Link to the thesis

https://repositum.tuwien.at/handle/20.500.12708/213422

## Citation
<pre>
@MISC{Bogenreiter2025-fa,
  title        = "Explainable prediction of user post popularity: An analysis
                  of the One Million Posts corpus",
  author       = "Bogenreiter, Dario",
  journal      = "undefined [NLP]",
  publisher    = "TU Wien",
  year         =  2025,
  primaryClass = "NLP"
}
</pre>

## License
This work is licensed under The MIT License (MIT).
