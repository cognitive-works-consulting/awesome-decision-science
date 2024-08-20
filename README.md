# Awesome Decision Science [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Une liste de ressources triées sur le volet à propos de tout ce qui touche à la prise de décision : vidéos, tutoriels, livres, documents, thèses, articles, datasets et libs open source. Cliquez sur le menu hamburger 🍔 pour naviguer plus facilement.

👍 Vous aimez ? Un like, un partage aiderait grandement le projet ! Partageons les connaissances !

⚠️ Disclaimer : la quasi-totalité des ressources est dispo gratuitement et légalement. Je ne touche rien sur les ventes des rares ressources payantes, qui sont simplement référencées car j'estime que ce sont des ressources de valeur.

## Sommaire
- [Awesome Decision Science ](#awesome-decision-science-)
  - [🤖 Artificial Intelligence, Computational Intelligence, and Machine Learning](#-artificial-intelligence-computational-intelligence-and-machine-learning)
    - [Books](#books)
      - [Computational Intelligence](#computational-intelligence)
      - [Deep Learning](#deep-learning)
      - [Explainable AI](#explainable-ai)
      - [Machine Learning](#machine-learning)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts)
      - [Deep Learning](#deep-learning-1)
      - [Explainable AI](#explainable-ai-1)
      - [Machine Learning](#machine-learning-1)
      - [Reinforcement Learning and Control Theory](#reinforcement-learning-and-control-theory)
    - [Datasets](#datasets)
    - [Packages](#packages)
      - [Data loading](#data-loading)
      - [Explainable AI](#explainable-ai-2)
      - [Feature Engineering](#feature-engineering)
      - [Hyperparameter optimization](#hyperparameter-optimization)
      - [Machine Learning techniques](#machine-learning-techniques)
    - [Papers](#papers)
      - [Deep Learning](#deep-learning-2)
        - [Bayesian approaches](#bayesian-approaches)
        - [Generative aspects](#generative-aspects)
        - [Mathematical aspects: approximation and generalization](#mathematical-aspects-approximation-and-generalization)
        - [Mathematical aspects: optimization](#mathematical-aspects-optimization)
      - [Machine Learning](#machine-learning-2)
        - [Conformal Prediction](#conformal-prediction)
        - [Explainable AI](#explainable-ai-3)
        - [Fuzzy sets](#fuzzy-sets)
        - [Imbalanced data problems](#imbalanced-data-problems)
        - [Training ML models](#training-ml-models)
    - [Posts and threads](#posts-and-threads)
      - [Explainable AI (XAI)](#explainable-ai-xai)
      - [Imbalanced data problems](#imbalanced-data-problems-1)
    - [Talks, conferences, and videos](#talks-conferences-and-videos)
  - [📊 Business Intelligence, Data Visualization, Communicating and Reporting](#-business-intelligence-data-visualization-communicating-and-reporting)
    - [Books](#books-1)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts-1)
    - [Datasets](#datasets-1)
    - [Packages](#packages-1)
      - [Data structures](#data-structures)
        - [Python](#python)
      - [Data Visualization and Reporting](#data-visualization-and-reporting)
        - [Julia](#julia)
          - [Python](#python-1)
	- [Papers](#papers-1)
    - [Posts and threads](#posts-and-threads-1)
    - [Talks, conferences, and videos](#talks-conferences-and-videos-1)
  - [💻 Computer Science and Software Engineering](#-computer-science-and-software-engineering)
    - [Books](#books-2)
      - [Algorithmics, data structures, and programming languages](#algorithmics-data-structures-and-programming-languages)
      - [Scientific programming](#scientific-programming)
      - [Software development](#software-development)
      - [Databases](#databases)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts-2)
      - [Algorithms](#algorithms)
      - [Scientific programming](#scientific-programming-1)
      - [Software engineering](#software-engineering)
    - [Packages](#packages-2)
      - [Python](#python-2)
        - [Data processing](#data-processing)
        - [GUI](#gui)
    - [Papers](#papers-2)
    - [Posts and threads](#posts-and-threads-2)
    - [Talks, conferences, and videos](#talks-conferences-and-videos-2)
  - [🗺️ Geospatial Analysis](#️-geospatial-analysis)
    - [Books](#books-3)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts-3)
    - [Datasets](#datasets-2)
    - [Packages](#packages-3)
    - [Papers](#papers-3)
    - [Posts and threads](#posts-and-threads-3)
    - [Talks, conferences, and videos](#talks-conferences-and-videos-3)
  - [👩‍🔬 Mathematics, Operations Research, Game Theory, and Simulations](#-mathematics-operations-research-game-theory-and-simulations)
    - [Books](#books-4)
      - [Algebra](#algebra)
      - [Applied Mathematics](#applied-mathematics)
      - [Game Theory and Simulations](#game-theory-and-simulations)
      - [Graph Theory](#graph-theory)
      - [Optimization](#optimization)
      - [Sequential Problems](#sequential-problems)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts-4)
      - [Mathematical Finance](#mathematical-finance)
      - [Probability](#probability)
    - [Datasets](#datasets-3)
    - [Packages](#packages-4)
      - [Optimization](#optimization-1)
      - [Sensitivity analysis](#sensitivity-analysis)
    - [Papers](#papers-4)
    - [Posts and threads](#posts-and-threads-4)
      - [Optimization](#optimization-2)
    - [Talks, conferences, and videos](#talks-conferences-and-videos-4)
  - [🤯 Methodology, interactions, and philosophical aspects of Science](#-methodology-interactions-and-philosophical-aspects-of-science)
    - [Building theories](#building-theories)
    - [Computational Science](#computational-science)
    - [Machine Learning and Statistics](#machine-learning-and-statistics)
    - [Mathematics](#mathematics)
    - [Scientific approaches](#scientific-approaches)
  - [📈 Statistics, Econometrics, and Data Mining](#-statistics-econometrics-and-data-mining)
    - [Books](#books-5)
      - [Clustering](#clustering)
      - [Econometrics](#econometrics)
      - [Statistics](#statistics)
        - [Bayesian Statistics](#bayesian-statistics)
        - [Exponential family](#exponential-family)
        - [Historical aspects](#historical-aspects)
        - [Inference and mathematical aspects](#inference-and-mathematical-aspects)
        - [Missing data](#missing-data)
        - [Regression modeling](#regression-modeling)
        - [Statistical software](#statistical-software)
      - [Time Series](#time-series)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts-5)
      - [Causal Inference](#causal-inference)
      - [Econometrics](#econometrics-1)
      - [Statistics \& Probability](#statistics--probability)
      - [Forecasting](#forecasting)
    - [Datasets](#datasets-4)
      - [Forecasting](#forecasting-1)
      - [Marketing applications](#marketing-applications)
    - [Packages](#packages-5)
      - [Python](#python-3)
        - [Time Series](#time-series-1)
      - [R](#r)
    - [Papers](#papers-5)
      - [Clustering](#clustering-1)
      - [Probabilistic Graphical Models and associated optimization techniques](#probabilistic-graphical-models-and-associated-optimization-techniques)
      - [Statistics](#statistics-1)
        - [Bayesian Statistics](#bayesian-statistics-1)
        - [Causality](#causality)
        - [Distributions](#distributions)
        - [Statistical hypothesis testing (NHST)](#statistical-hypothesis-testing-nhst)
    - [Posts and threads](#posts-and-threads-5)
      - [Bayesian Statistics](#bayesian-statistics-2)
      - [General topics](#general-topics)
      - [Variable selection / Feature selection](#variable-selection--feature-selection)
    - [Talks, conferences, and videos](#talks-conferences-and-videos-5)
      - [Bayesian Statistics](#bayesian-statistics-3)
      - [Stochastic Processes](#stochastic-processes)
  - [📄 Text Mining and Natural Language Processing](#-text-mining-and-natural-language-processing)
    - [Books](#books-6)
    - [Courses and lecture notes, posts](#courses-and-lecture-notes-posts-6)
    - [Datasets](#datasets-5)
    - [Packages](#packages-6)
    - [Papers](#papers-6)
    - [Posts and threads](#posts-and-threads-6)
    - [Talks, conferences, and videos](#talks-conferences-and-videos-6)

## 🤖 Artificial Intelligence, Computational Intelligence, and Machine Learning
### Books
#### Computational Intelligence
- Engelbrecht, Andries P. Computational intelligence: an introduction. John Wiley & Sons, 2007. [[Link]](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470512517)
#### Deep Learning
- Bishop, Christopher M., and Hugh Bishop. "Deep learning: foundations and concepts." Springer, 2024. [[Link]](https://www.bishopbook.com/)
- Deisenroth, Marc Peter, A. Aldo Faisal, and Cheng Soon Ong. Mathematics for machine learning. Cambridge University Press, 2020. [[Link]](https://mml-book.github.io/)
- Goodfellow, Ian, Yoshua Bengio, and Aaron Courville. Deep learning. MIT Press, 2016. [[Link]](https://www.deeplearningbook.org/)
- Grohs, Philipp, and Gitta Kutyniok, eds. Mathematical aspects of deep learning. Cambridge University Press, 2022. [[Link]](https://www.cambridge.org/core/books/mathematical-aspects-of-deep-learning/8D9B41D1E9BB8CA515E93412EECC2A7E)
- Prince, Simon JD. Understanding Deep Learning. MIT press, 2023. [[Link]](https://udlbook.github.io/udlbook/)
- Zhang, Aston, et al. Dive into deep learning. Cambridge University Press, 2023. [[Link]](https://d2l.ai/)
#### Explainable AI
- Biecek, Przemyslaw, and Tomasz Burzykowski. Explanatory model analysis: explore, explain, and examine predictive models. CRC Press, 2021. [[Link]](https://ema.drwhy.ai/)
- Hall, Curtis and Pandey. Machine Learning for High-Risk Applications. O'Reilly, 2023. [[Link]](https://www.oreilly.com/library/view/machine-learning-for/9781098102425/)
- Molnar, Christoph. Interpretable machine learning. Lulu. com, 2020. [[Link]](https://christophm.github.io/interpretable-ml-book/)
#### Machine Learning
- Bishop, Christopher M., and Nasser M. Nasrabadi. Pattern recognition and machine learning. Vol. 4. No. 4. New York: Springer, 2006. [[Link]](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/)
- Deisenroth, Marc Peter, A. Aldo Faisal, and Cheng Soon Ong. Mathematics for machine learning. Cambridge University Press, 2020. [[Link]](https://mml-book.github.io/)
- Efron, Bradley, and Trevor Hastie. Computer age statistical inference, student edition: algorithms, evidence, and data science. Vol. 6. Cambridge University Press, 2021. [[Link]](https://hastie.su.domains/CASI/)
- Hastie, Trevor, Robert Tibshirani, and Martin Wainwright. Statistical learning with sparsity: the lasso and generalizations. CRC press, 2015. [[Link]](https://hastie.su.domains/StatLearnSparsity/)
- Huber, Martin. Causal analysis: Impact evaluation and Causal Machine Learning with applications in R. MIT Press, 2023. [[Link]](https://mitpress.ublish.com/ebook/causal-analysis-impact-evaluation-and-causal-machine-learning-with-applications-in-r-preview/12759/Cover)
- James, G., Witten, D., Hastie, T., Tibshirani, R., Taylor, J. An Introduction to Statistical Learning: With Applications in Python; Springer: Berlin/Heidelberg, Germany, 2023. [[Link]](https://www.statlearning.com/)
- Katsov, Ilya. Introduction to algorithmic marketing: Artificial intelligence for marketing operations. Grid Dynamics, 2017. [[Link]](https://www.algorithmicmarketingbook.com/)
- MacKay, David JC. Information theory, inference and learning algorithms. Cambridge university press, 2003. [[Link]](https://inference.org.uk/itila/book.html)
- Murphy, Kevin P. Probabilistic machine learning: Advanced topics. MIT Press, 2023. [[Link]](https://probml.github.io/pml-book/book2.html)
- Murphy, Kevin P. Probabilistic machine learning: an introduction. MIT Press, 2022. [[Link]](https://probml.github.io/pml-book/book1.html)
- Siddiqi, Naeem. Intelligent credit scoring: Building and implementing better credit risk scorecards. John Wiley & Sons, 2017. [[Link]](https://www.wiley.com/en-fr/Intelligent+Credit+Scoring%3A+Building+and+Implementing+Better+Credit+Risk+Scorecards%2C+2nd+Edition-p-9781119279150)
### Courses and lecture notes, posts
#### Deep Learning
- Lippe, Phillip. UvA Deep Learning Tutorials. 2022. [[Link]](https://uvadlc-notebooks.readthedocs.io/en/latest/)
- Ollion, Charles, and Olivier Grisel. Deep Learning course: lecture slides and lab notebooks. Institut Polytechnique de Paris, 2017. [[Link]](https://m2dsupsdlclass.github.io/lectures-labs/)
#### Explainable AI
- Galli, Soledad. Interpreting Machine Learning Models [[Link]](https://www.trainindata.com/p/machine-learning-interpretability)
- Lakkaraju, Hima, et al. Explainable Artificial Intelligence: From Simple Predictors to Complex Generative Models. Harvard University, 2023. [[Link]](https://interpretable-ml-class.github.io/)
#### Machine Learning
- Christensen, Henrik I. Support Vector Machines - SVM & RVM. Georgia Insitute of Technology. [[Link]](https://faculty.cc.gatech.edu/~hic/CS7616/pdf/lecture9.pdf)
- Inria. Machine learning in Python with scikit-learn. FUN, 2023. [[Link]](https://www.fun-mooc.fr/en/courses/machine-learning-python-scikit-learn/)
- MLU-Explain Team. MLU-Explain. Amazon (2021). [[Link]](https://mlu-explain.github.io/)
#### Reinforcement Learning and Control Theory 
- Dimitry Bertsekas. Reinforcement Learning and Optimal Control. [[Link]](http://www.mit.edu/~dimitrib/RLbook.html)
- Elad Hazan, Karan Singh. Introduction to Online Nonstochastic Control. [[Link]](https://arxiv.org/abs/2211.09619)
### Datasets
- Andreas Luttens, et al. Large-scale Docking Datasets for Machine Learning. 2, Zenodo, 8 May 2023. [[Link]](https://zenodo.org/records/7953917)
- Randal S. Olson, William La Cava, Patryk Orzechowski, Ryan J. Urbanowicz, and Jason H. Moore (2017). PMLB: a large benchmark suite for machine learning evaluation and comparison. BioData Mining 10, page 36. [[Paper]](https://biodatamining.biomedcentral.com/articles/10.1186/s13040-017-0154-4) [[Code]](https://github.com/EpistasisLab/pmlb)
### Packages
#### Data loading
- mlx-data. Efficient framework-agnostic data loading. Apple, 2023. [[Link]](https://github.com/ml-explore/mlx-data)
#### Explainable AI
- Alibi explain. Open-source interpretability library supporting black box, white box, global and local interpratability methods. [[Link]](https://docs.seldon.io/projects/alibi)
- Dalex. Responsible Machine Learning in Python. [[Link]](https://dalex.drwhy.ai/python/)
- Scikit-explain. User-friendly Python module for machine learning explainability with a comprehensive toolset of interpretability methods. [[Link]](https://scikit-explain.readthedocs.io/)
- Shapash. Shapash: User-friendly Explainability and Interpretability to Develop Reliable and Transparent Machine Learning Models. MAIF, 2021.[[Link]](https://maif.github.io/shapash/)
- Sudjianto, Agus, et al. "PiML Toolbox for Interpretable Machine Learning Model Development and Validation." arXiv preprint arXiv:2305.04214 
#### Feature Engineering
- Feature_engine. Feature engineering package with sklearn like functionality. [[Link]](https://feature-engine.trainindata.com/en/latest/)
#### Hyperparameter optimization
- Optuna. A hyperparameter optimization framework. [[Link]](https://optuna.org/)
#### Machine Learning techniques
- Catboost. A fast, scalable, high-performance Gradient Boosting on Decision Trees library used for ranking, classification, regression, and other machine learning tasks for Python, R, Java, and C++. Supports computation on CPU and GPU. [[Link]](https://catboost.ai/)
- Khuat, Thanh Tung, and Bogdan Gabrys. "hyperbox-brain: A Toolbox for Hyperbox-based Machine Learning Algorithms." arXiv preprint arXiv:2210.02704 (2022). [[Link]](https://arxiv.org/abs/2210.02704)
- quantile-forest. Quantile Regression Forests compatible with scikit-learn. [[Link]](https://zillow.github.io/quantile-forest/)
### Papers
#### Deep Learning
##### Bayesian approaches
- Arbel, Julyan, et al. A Primer on Bayesian Neural Networks: Review and Debates. arXiv preprint arXiv:2309.16314 (2023). [[Link]](https://arxiv.org/abs/2309.16314)
- Hellström, Fredrik, et al. Generalization bounds: perspectives from information theory and PAC-Bayes. arXiv preprint arXiv:2309.04381 (2023). [[Link]](https://arxiv.org/abs/2309.04381)
- Kingma, Diederik P., and Max Welling. "Auto-encoding variational bayes." arXiv preprint arXiv:1312.6114 (2013). [[Link]](https://arxiv.org/abs/1312.6114)
- Nalisnick, Eric, and Padhraic Smyth. "Stick-breaking variational autoencoders." arXiv preprint arXiv:1605.06197 (2016). [[Link]](https://arxiv.org/abs/1605.06197)
##### Generative aspects
- Coste, Simon. Diffusion. University of Paris, 2023. [[Link]](https://scoste.fr/posts/diffusion/)
- Galerne, Bruno, and Valentin De Bortoli. Generative Modelling. ENS Paris-Saclay, 2023. [[Link]](https://vdeborto.github.io/project/generative_modeling/)
##### Mathematical aspects: approximation and generalization
- Bartlett, Peter L., Andrea Montanari, and Alexander Rakhlin. Deep learning: a statistical viewpoint. Acta numerica 30 (2021): 87-201. [[Link]](https://arxiv.org/abs/2103.09177)
- Berner, Julius, et al. The modern mathematics of deep learning. arXiv preprint arXiv:2105.04026 (2021): 86-114. [[Link]](https://arxiv.org/abs/2105.04026)
- DeVore, Ronald, Boris Hanin, and Guergana Petrova. Neural network approximation. Acta Numerica 30 (2021): 327-444. [[Link]](https://arxiv.org/abs/2012.14501)
- Jacot, Arthur, Franck Gabriel, and Clément Hongler. "Neural tangent kernel: Convergence and generalization in neural networks." Advances in neural information processing systems 31 (2018). [[Link]](https://arxiv.org/abs/1806.07572)
- Hornik, Kurt. "Approximation capabilities of multilayer feedforward networks." Neural networks 4.2 (1991): 251-257. [[Link]](https://web.njit.edu/~usman/courses/cs677_spring21/hornik-nn-1991.pdf)
- Hornik, Kurt, Maxwell Stinchcombe, and Halbert White. "Multilayer feedforward networks are universal approximators." Neural networks 2.5 (1989): 359-366. [[Link]](https://cognitivemedium.com/magic_paper/assets/Hornik.pdf)
- Petersen, Philipp Christian. Neural network theory. University of Vienna 535 (2020). [[Link]](http://pc-petersen.eu/Neural_Network_Theory.pdf)
##### Mathematical aspects: optimization
- Khaled, Ahmed, and Peter Richtárik. "Better theory for SGD in the nonconvex world." arXiv preprint arXiv:2002.03329 (2020). [[Link]](https://arxiv.org/abs/2002.03329)
- Sun, Ruoyu. Optimization for deep learning: theory and algorithms. arXiv preprint arXiv:1912.08957 (2019). [[Link]](https://arxiv.org/abs/1912.08957)
#### Machine Learning
##### Conformal Prediction
- Angelopoulos, Anastasios N., and Stephen Bates. "A gentle introduction to conformal prediction and distribution-free uncertainty quantification." arXiv preprint arXiv:2107.07511 (2021). [[Link]](https://arxiv.org/abs/2107.07511)
- Fontana, Matteo, Gianluca Zeni, and Simone Vantini. "Conformal prediction: a unified review of theory and new challenges." arXiv preprint arXiv:2005.07972 (2020). [[Link]](https://arxiv.org/abs/2005.07972)
##### Explainable AI
- Bilodeau, Blair, et al. "Impossibility theorems for feature attribution." Proceedings of the National Academy of Sciences 121.2 (2024): e2304406120. [[Link]](https://arxiv.org/abs/2212.11870)
- Ibrahim Amoukou, Salim. Trustworthy machine learning: explainability and distribution-free uncertainty quantification. Diss. université Paris-Saclay, 2023. [[Link]](https://www.biblio.univ-evry.fr/theses/2023/2023UPASM034.pdf)
- Huang, Xuanxiang, and Joao Marques-Silva. "The inadequacy of Shapley values for explainability." arXiv preprint arXiv:2302.08160 (2023).
(2023). [[Link]](https://arxiv.org/abs/2302.08160)
##### Fuzzy sets
- Khuat, Thanh Tung, Dymitr Ruta, and Bogdan Gabrys. "Hyperbox-based machine learning algorithms: a comprehensive survey." Soft Computing 25.2 (2021): 1325-1363. [[Link]](https://arxiv.org/abs/1901.11303)
##### Imbalanced data problems
- Elor, Yotam, and Hadar Averbuch-Elor. "To SMOTE, or not to SMOTE?." arXiv preprint arXiv:2201.08528 (2022). [[Link]](https://arxiv.org/abs/2201.08528)
- van den Goorbergh, Ruben, et al. "The harm of class imbalance corrections for risk prediction models: illustration and simulation using logistic regression." Journal of the American Medical Informatics Association 29.9 (2022): 1525-1534. [[Link]](https://academic.oup.com/jamia/article/29/9/1525/6605096)
##### Training ML models
- Mirzasoleiman, Baharan, Jeff Bilmes, and Jure Leskovec. "Coresets for data-efficient training of machine learning models." International Conference on Machine Learning. PMLR, 2020. [[Link]](https://proceedings.mlr.press/v119/mirzasoleiman20a.html)
### Posts and threads
#### Explainable AI (XAI)
- Of Models and Meanings. SHAP is the Blockchain of xAI. Of Models and Meanings, 2022. [[Link]](https://modelmeanings.wordpress.com/2022/05/12/shap-is-the-blockchain-of-xai/)
- Of Models and Meanings. What You Could Do with the Shapley Computation. Of Models and Meanings, 2022. [[Link]](https://modelmeanings.wordpress.com/2022/09/04/what-you-could-do-with-the-shapley-computation/)
#### Imbalanced data problems
- Mougan, Carl. Why SMOTE is not used in prize-winning Kaggle solutions?. Data Science, 2021. [[Link]](https://datascience.stackexchange.com/questions/106461/why-smote-is-not-used-in-prize-winning-kaggle-solutions)
### Talks, conferences, and videos
- Dieng, Adji B. Learning From Data: The Two Cultures. Association for Computing Machinery, 2021. [[Link]](https://youtu.be/JJnTLNoNTME?si=uiuHKCcPFhF7sz6h)
- Rich, DJ. Mutual Information. True Theta LLC, 2020. [[Link]](https://www.youtube.com/@Mutual_Information)

## 📊 Business Intelligence, Data Visualization, Communicating and Reporting
### Books
- Duarte, Nancy. Resonate: Present visual stories that transform audiences. John Wiley & Sons, 2013. [[Link]](https://www.duarte.com/resources/books/resonate/)
- Duarte, Nancy. Slide: ology: The art and science of creating great presentations. Vol. 1. Sebastapol: O'Reilly Media, 2008. [[Link]](https://www.duarte.com/resources/books/slideology/)
- Knaflic, Cole Nussbaumer. Storytelling with data: A data visualization guide for business professionals. John Wiley & Sons, 2015. [[Link]](https://www.storytellingwithdata.com/books)
- Knaflic, Cole Nussbaumer. Storytelling with data: let's practice!. John Wiley & Sons, 2019. [[Link]](https://www.storytellingwithdata.com/books)
- Wexler, Steve, Jeffrey Shaffer, and Andy Cotgreave. The big book of dashboards: visualizing your data using real-world business scenarios. John Wiley & Sons, 2017. [[Link]](https://www.bigbookofdashboards.com/)
- Wilke, Claus O. Fundamentals of data visualization: a primer on making informative and compelling figures. O'Reilly Media, 2019. [[Link]](https://clauswilke.com/dataviz/)
### Courses and lecture notes, posts
### Datasets
### Packages
#### Data structures
##### Python
- Polars. Dataframes powered by a multithreaded, vectorized query engine, written in Rust. [[Link]](https://www.pola.rs/)
#### Data Visualization and Reporting
##### Julia
- Genie. 🧞The highly productive Julia web framework. [[Link]](https://genieframework.com/)
###### Python
- Marimo. marimo is an open-source reactive notebook for Python — reproducible, git-friendly, executable as a script, and shareable as an app. [[Link]](https://marimo.io/)
- PyGWalker. Turn your pandas dataframe into an interactive UI for visual analysis. [[Link]](https://docs.kanaries.net/pygwalker)
- Streamlit. A faster way to build and share data apps. [[Link]](https://streamlit.io/)
- Vizro. Vizro is a toolkit for creating modular data visualization applications. [[Link]](https://github.com/mckinsey/vizro)
## Papers
### Posts and threads
### Talks, conferences, and videos

## 💻 Computer Science and Software Engineering
### Books
#### Algorithmics, data structures, and programming languages
- Downey, Allen. Think complexity: complexity science and computational modeling. " O'Reilly Media, Inc.", 2018. [[Link]](https://www.greenteapress.com/complexity/)
- Downey, Allen. Think data structures: algorithms and information retrieval in Java. " O'Reilly Media, Inc.", 2017. [[Link]](https://greenteapress.com/wp/think-data-structures/)
- Downey, Allen. Think Python. " O'Reilly Media, Inc.", 2012. [[Link]](https://greenteapress.com/wp/think-python-2e/)
- Johnston, Nathaniel, and Dave Greene. Conway's Game of Life: Mathematics and Construction. Self-published, 2022. [[Link]](https://conwaylife.com/book/)
- Miller, Brad, and David Ranum. Problem-solving with algorithms and data structures. University of Auckland, 2013. [[Link]](https://dlib.hust.edu.vn/bitstream/HUST/17856/1/OER000000244.pdf) [[Website]](https://www.openbookproject.net/books/pythonds/index.html)
- Nipkow, Tobias. "Functional Data Structures and Algorithms A Proof Assistant Approach." (2023). [[Link]](https://functional-algorithms-verified.org/)
#### Scientific programming
- Blondel, Mathieu, and Vincent Roulet. "The Elements of Differentiable Programming." arXiv preprint arXiv:2403.14606 (2024). [[Link]](https://arxiv.org/abs/2403.14606)
#### Software development
- Chacon, Scott, and Ben Straub. Pro git. Springer Nature, 2014. [[Link]](https://git-scm.com/book/en/v2)
#### Databases
- Petrov, Alex. Database Internals: A deep dive into how distributed data systems work. O'Reilly Media, 2019. [[Link]](https://www.databass.dev/)
### Courses and lecture notes, posts
#### Algorithms
- Roughgarden, Tim. Lecture Notes. Columbia University. [[Link]](https://timroughgarden.org/notes.html)
#### Scientific programming
- Raschka, Sebastian. Scientific Computing in Python: Introduction to NumPy and Matplotlib. sebastianraschka.com, 2020. [[Link]](https://sebastianraschka.com/blog/2020/numpy-intro.html)
#### Software engineering
- Atlassian. Gitflow workflow. [[Link]](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- Atlassian. Trunk-based development. [[Link]](Trunk-based development)
- Shvets, Alexander. Refactoring Guru. 2014. [[Link]](https://refactoring.guru/)
### Packages
#### Python
##### Data processing
- Bytewax. Python Stream Processing. [[Link]](https://bytewax.io/)
##### GUI
- Textual. The lean application framework for Python. Build sophisticated user interfaces with a simple Python API. Run your apps in the terminal and a web browser. [[Link]](https://github.com/Textualize/textual)
### Papers
### Posts and threads
### Talks, conferences, and videos

## 🗺️ Geospatial Analysis
### Books
- Lovelace, Robin, Jakub Nowosad, and Jannes Muenchow. Geocomputation with R. CRC Press, 2019. [[Link]](https://r.geocompx.org/)
- Moraga, Paula. Geospatial health data: Modeling and visualization with R-INLA and shiny. CRC Press, 2019. [[Link]](https://www.paulamoraga.com/book-geospatial/)
- Moraga, Paula. Spatial Statistics for Data Science: Theory and Practice with R. CRC Press, 2023. [[Link]](https://www.paulamoraga.com/book-spatial/)
### Courses and lecture notes, posts
### Datasets
### Packages
### Papers
### Posts and threads
### Talks, conferences, and videos

## 👩‍🔬 Mathematics, Operations Research, Game Theory, and Simulations
### Books
#### Algebra
- Axler, Sheldon. Linear algebra done right. Springer Nature, 2023. [[Link]](https://linear.axler.net/)
#### Applied Mathematics
- Isoz, Vincent. Opera Magistris (Elements of Applied Mathematics). Sciences.ch, 2016. [[Link]](https://archive.org/details/OperaMagistris)
#### Game Theory and Simulations
- Downey, Allen B. Modeling and Simulation in Python: An Introduction for Scientists and Engineers. No Starch Press, 2023. [[Link]](https://greenteapress.com/wp/modsimpy/)
#### Graph Theory
- McNulty, Keith. Handbook of graphs and networks in people analytics: with examples in R and Python. CRC Press, 2022. [[Link]](https://ona-book.org/index.html)
- Sargent, Thomas J., and John Stachurski. Economic Networks: Theory and Computation. QuantEcon, 2022. [[Link]](https://networks.quantecon.org/)
#### Optimization
- Boumal, Nicolas. An Introduction to Optimization on Smooth Manifolds. Cambridge University Press, 2023. [[Link]](https://www.nicolasboumal.net/book/)
- Boyd, Stephen P., and Lieven Vandenberghe. Convex optimization. Cambridge University Press, 2004. [[Link]](https://web.stanford.edu/~boyd/cvxbook/)
- Kwon, Changhyun. Julia Programming for Operations Research. Changhyun Kwon, 2019. [[Link]](https://juliabook.chkwon.net/book/frontmatter)
- Martins, J. R. R. A. and Ning, A., Engineering Design Optimization, Cambridge University Press, 2022. [[Link]](https://mdobook.github.io/)
- Nesterov, Yurii. Lectures on convex optimization. Vol. 137. Berlin: Springer, 2018. [[Link]](https://link.springer.com/book/10.1007/978-3-319-91578-4)
- Sargent, Thomas J., and John Stachurski. Dynamic Programming Volume 1. QuantEcon, 2023. [[Link]](https://dp.quantecon.org/)
#### Sequential Problems
- Powell, Warren B. Sequential decision analytics and modeling: modeling with Python. Now, 2022. [[Link]](https://castle.princeton.edu/sdamodeling/)
### Courses and lecture notes, posts
#### Mathematical Finance
- Kempthorne, Peter, et al. "Topics in mathematics with applications in finance." Massachusetts Institute of Technology: MIT OpenCouseWare, 2013. [[Link]](https://ocw.mit.edu/courses/18-s096-topics-in-mathematics-with-applications-in-finance-fall-2013/)
- Roncalli, Thierry, Course 2023-2024 in Portfolio Allocation and Asset Management. SSRN, 2024. [[Link]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4698165&s=09)
#### Probability
- Arya, Nisha. Learn Probability in Computer Science with Stanford University for FREE. KDNuggets, 2023. [[Link]](https://www.kdnuggets.com/learn-probability-in-computer-science-with-stanford-university-for-free)
### Datasets
### Packages
#### Optimization
- Diamond, Steven, and Stephen Boyd. "CVXPY: A Python-embedded modeling language for convex optimization." Journal of Machine Learning Research 17.83 (2016): 1-5. [[Link to the paper]](https://www.jmlr.org/papers/v17/15-408.html) [[Link to the package]](https://www.cvxpy.org/)
- PyPortfolioOpt. Financial portfolio optimisation in python, including classical efficient frontier, Black-Litterman, Hierarchical Risk Parity. [[Link]](https://github.com/robertmartin8/PyPortfolioOpt)
- scikit-portfolio. A portfolio optimization tool with scikit-learn interface. Hyperparameters selection and easy plotting of efficient frontiers. [[Link]](https://scikit-portfolio.github.io/scikit-portfolio/)
#### Sensitivity analysis
- SALib. Sensitivity Analysis Library in Python. Contains Sobol, Morris, FAST, and other methods. [[Link]](https://github.com/SALib/SALib)
### Papers
### Posts and threads
#### Optimization
- Jones, Andy. Natural gradients. Andy Jones. [[Link]](https://andrewcharlesjones.github.io/journal/natural-gradients.html)
### Talks, conferences, and videos
- MATLAB. Why Padé Approximations Are Great! | Control Systems in Practice. YouTube, 2022. [[Link]](https://www.youtube.com/watch?v=3TK8Fi_I0h0)

## 🤯 Methodology, interactions, and philosophical aspects of Science
### Building theories
- Jaccard, James, and Jacob Jacoby. Theory construction and model-building skills: A practical guide for social scientists. Guilford publications, 2019. [[Link]](https://www.guilford.com/books/Theory-Construction-and-Model-Building-Skills/Jaccard-Jacoby/9781462542437) [[Website]](https://www.theory-construction.com/Main.html)
### Computational Science
- Judd, Kenneth. The Potential Partnership Between Economics and Computational Science. PyData Chicago, 2021. [[Link]](https://youtu.be/wcEktEN52tY?si=jr83xLEFTY7-5fRp)
### Machine Learning and Statistics
- Breiman, Leo. "Statistical modeling: The two cultures (with comments and a rejoinder by the author)." Statistical science 16.3 (2001): 199-231. [[Link]](https://projecteuclid.org/journals/statistical-science/volume-16/issue-3/Statistical-Modeling--The-Two-Cultures-with-comments-and-a/10.1214/ss/1009213726.pdf)
- Harrell, Frank. "Classification vs. Prediction". Statistical Thinking, 2017. [[Link]](https://www.fharrell.com/post/classification/)
### Mathematics
- Polya, George. How to solve it: A new aspect of mathematical method. Vol. 85. Princeton university press, 2004. [[Link]](https://press.princeton.edu/books/paperback/9780691164076/how-to-solve-it)
### Scientific approaches
- Wolfram, Stephen. A new kind of science. Vol. 5. Champaign, IL: Wolfram media, 2002. [[Link]](https://www.wolframscience.com/nks/)

## 📈 Statistics, Econometrics, and Data Mining
### Books
#### Clustering
- Govaert, Gérard, and Mohamed Nadif. Co-clustering: models, algorithms and applications. John Wiley & Sons, 2013. [[Link]](https://www.amazon.fr/Co-Clustering-G%C3%A9rard-Govaert/dp/1848214731/ref=tmm_hrd_swatch_0?_encoding=UTF8&qid=1697294646&sr=8-1)
- Scrucca, Luca, et al. Model-Based Clustering, Classification, and Density Estimation Using mclust in R. Chapman and Hall/CRC, 2023. [[Link]](https://www.taylorfrancis.com/books/mono/10.1201/9781003277965/model-based-clustering-classification-density-estimation-using-mclust-luca-scrucca-chris-fraley-brendan-murphy-adrian-raftery)
#### Econometrics
- Ding, Peng. "Linear Model and Extensions." arXiv preprint arXiv:2401.00649 (2024). [[Link]](https://arxiv.org/abs/2401.00649)
- Evans, Richard W., Computational Methods for Economists using Python, Open access Jupyter Book, v#.#.#, 2023. [[Link]](https://opensourceecon.github.io/CompMethods)
- Wooldridge, Jeffrey M.. Introductory Econometrics: A Modern Approach. Brésil, Cengage Learning, 2020. [[Link]](https://www.amazon.fr/Introductory-Econometrics-Approach-Jeffrey-Wooldridge/dp/1337558869/ref=sr_1_1?crid=1B5NKJCMW9EM0&keywords=econometrics+a+modern+approach&psr=PDAY&qid=1696924730&s=pbdd&sprefix=econmetrics+a+modern+approach%2Cpbdd%2C94&sr=1-1)
#### Statistics
##### Bayesian Statistics
- Martin, Osvaldo A., Ravin Kumar, and Junpeng Lao. Bayesian modeling and computation in Python. CRC Press, 2021. [[Link]](https://bayesiancomputationbook.com/welcome.html)
- McElreath, Richard. Statistical rethinking: A Bayesian course with examples in R and Stan. Chapman and Hall/CRC, 2020. [[Link]](https://xcelab.net/rm/statistical-rethinking/)
##### Exponential family
- Agresti, Alan. Categorical data analysis. Vol. 792. John Wiley & Sons, 2012. [[Link]](https://www.wiley.com/en-us/Categorical+Data+Analysis%2C+3rd+Edition-p-9781118710944)
- Efron, Bradley. Exponential families in theory and practice. Cambridge University Press, 2022. [[Link]](https://www.cs.columbia.edu/~blei/fogm/2018F/materials/Efron2018.pdf)
##### Historical aspects
- Fischer, Hans. A history of the central limit theorem: from classical to modern probability theory. Vol. 4. New York: Springer, 2011. [[Link]](https://www.medicine.mcgill.ca/epidemiology/hanley/bios601/GaussianModel/HistoryCentralLimitTheorem.pdf)
##### Inference and mathematical aspects
- Soch, Joram, et al. StatProofBook/StatProofBook.Github.Io: StatProofBook 2021. 2021, Zenodo, 2022. [[Link]](https://statproofbook.github.io/)
- Wasserman, Larry. All of nonparametric statistics. Springer Science & Business Media, 2006. [[Link]](https://link.springer.com/book/10.1007/0-387-30623-4)
- Wasserman, Larry. All of statistics: a concise course in statistical inference. Vol. 26. New York: Springer, 2004. [[Link]](https://www.stat.cmu.edu/~larry/all-of-statistics/)
##### Missing data
- Van Buuren, Stef. Flexible imputation of missing data. CRC Press, 2018. [[Link]](https://stefvanbuuren.name/fimd/)
##### Regression modeling
- McNulty, Keith. Handbook of regression modeling in people analytics: with examples in R and Python. CRC Press, 2021. [[Link]](https://peopleanalytics-regression-book.org/index.html)
##### Statistical software
- Kuhn, Max, and Julia Silge. Tidy modeling with R. " O'Reilly Media, Inc.", 2022. [[Link]](https://www.tmwr.org/index.html)
- Wickham, H., Çetinkaya-Rundel, M., & Grolemund, G. (2023). R for data science. " O'Reilly Media, Inc.". [[Link]](https://r4ds.hadley.nz/)
#### Time Series
- Cochrane, John H. "Time series for macroeconomics and finance." (1997). [[Link]](https://static1.squarespace.com/static/5e6033a4ea02d801f37e15bb/t/5eea91f725f16202da96235d/1592431098027/time_series_book.pdf)
- Hyndman, R.J., & Athanasopoulos, G. (2021) Forecasting: principles and practice, 3rd edition, OTexts: Melbourne, Australia. [[Link]](https://otexts.com/fpp3/)
- Neusser, Klaus. Time series econometrics. Springer publication, 2016. [[Link]](https://www.amazon.fr/Time-Econometrics-Klaus-Neusser-ebook/dp/B01H30JHNA/ref=sr_1_1?crid=1QZFENEHXT9DG&keywords=Neusser%2C+Klaus.+Time+series+econometrics&qid=1696924805&sprefix=neusser%2C+klaus.+time+series+econometrics%2Caps%2C92&sr=8-1)
### Courses and lecture notes, posts
#### Causal Inference
- Cunningham, Scott et al. Mixtape Sessions: Causal Inference. 2022. [[Link]](https://github.com/Mixtape-Sessions/)
- Ding, Peng. "A First Course in Causal Inference." arXiv preprint arXiv:2305.18793 (2023). [[Link]](https://arxiv.org/abs/2305.18793)
#### Econometrics
- Canay, Ivan. Econ 480-3 - Introduction to Econometrics. Northwestern University, 2021. [[Link]](https://sites.northwestern.edu/iac879/teaching/e-lectures-econ480/)
- De Haan, Monique. ECON4150 - Introductory Econometrics. University of Oslo, 2018. [[Link]](https://www.uio.no/studier/emner/sv/oekonomi/ECON4150/v18/)
#### Statistics & Probability
- Dunn, Peter  K. The Theory of Distributions, 2023. [[Link]](https://bookdown.org/pkaldunn/DistTheory/)
- Kozyrkov, Cassie. Statistical Thinking. YouTube, 2019. [[Link]](https://www.youtube.com/playlist?list=PLRKtJ4IpxJpBxX2S9wXJUhB1_ha3ADFpF)
- Kunin, Daniel, et al. Seeing Theory. Brown University, 2016. [[Link]](https://seeing-theory.brown.edu/)
#### Forecasting
- Manani, Galli. Feature Engineering for Time Series Forecasting, 2022. [[Link]](https://www.trainindata.com/p/feature-engineering-for-forecasting)
### Datasets
#### Forecasting
- Godahewa, Rakshitha, et al. "Monash time series forecasting archive." arXiv preprint arXiv:2105.06643 (2021). [[Link]](https://arxiv.org/abs/2105.06643)
- Lotsa Data. Salesforce, Hugging Face (2024). [[Link]](https://huggingface.co/datasets/Salesforce/lotsa_data)
#### Marketing applications
- "6 Free, High-Quality, Marketing Mix Modeling Datasets | Forecastegy." Web. 10/14/2023 [[Link]](https://forecastegy.com/posts/free-high-quality-marketing-mix-modeling-datasets)
- Gaël Bernard and Periklis Andritsos. Datasets Simulating Customer Journeys. [[Link]](https://customer-journey.me/datasets/)
### Packages
#### Python
##### Time Series
- Alexandrov, Alexander, et al. "Gluonts: Probabilistic and neural time series modeling in python." The Journal of Machine Learning Research 21.1 (2020): 4629-4634. [[Link]](https://ts.gluon.ai/stable/)
- Salvador, Stan, and Philip Chan. "Toward accurate dynamic time warping in linear time and space." Intelligent Data Analysis 11.5 (2007): 561-580. [[Link]](https://github.com/slaypni/fastdtw)
- Fold. Fast Adaptive Time Series ML Engine. [[Link]](https://dream-faster.github.io/fold/)
- Functime. Time-series machine learning at scale. Built on Polars for embarrassingly parallel feature engineering and forecasts. [[Link]](https://github.com/neocortexdb/functime)
- HierarchicalForecast. Probabilistic Hierarchical forecasting 👑 with statistical and econometric methods. [[Link]](https://nixtla.github.io/hierarchicalforecast/)
- MFLES. A Specific implementation from ThymeBoost written with the help of Numba. [[Link]](https://github.com/tblume1992/MFLES)
- mlforecast. Scalable machine 🤖 learning for time series forecasting. [[Link]](https://nixtla.github.io/mlforecast/)
- NeuralForecast. Scalable and user-friendly neural 🧠 forecasting algorithms. [[Link]](https://nixtla.github.io/neuralforecast/)
- SKForecast. Simplifies using sklearn models to do single and multistep forecasting and backtesting. [[Link]](https://skforecast.org)
- StatsForecast. Lightning ⚡️ fast forecasting with statistical and econometric models. [[Link]](https://nixtla.github.io/statsforecast/)
- ThymeBoost. Forecasting with Gradient Boosted Time Series Decomposition. [[Link]](https://github.com/tblume1992/ThymeBoost)
- vectorbt. Find your trading edge, using the fastest engine for backtesting, algorithmic trading, and research. [[Link]](https://github.com/polakowo/vectorbt)
#### R
- Ross, Gordon J., and Dean Markwick. "dirichletprocess: An R package for fitting complex Bayesian nonparametric models." (2018). [[Link]](https://cloud.r-project.org/web/packages/dirichletprocess/vignettes/dirichletprocess.pdf)
- van Buuren, S., and K. Groothuis-Oudshoorn. “Mice: Multivariate Imputation by Chained Equations in R”. Journal of Statistical Software, vol. 45, no. 3, Dec. 2011, pp. 1-67, doi:10.18637/jss.v045.i03. [[Paper]](https://www.jstatsoft.org/article/view/v045i03)  [[Package]](https://cran.r-project.org/web/packages/mice/index.html)
### Papers
#### Clustering
- Keribin, Christine, Gilles Celeux, and Valérie Robert. "The latent block model: a useful model for high dimensional data." ISI 2017-61st world statistics congress. 2017. [[Link]](https://inria.hal.science/hal-01658589/)
- Pham, Tung, et al. "Fast support vector clustering." Vietnam Journal of Computer Science 4 (2017): 13-21. [[Link]](https://link.springer.com/article/10.1007/s40595-016-0068-y)
- Pham, Tung, Trung Le, and Hang Dang. "Scalable support vector clustering using budget." arXiv preprint arXiv:1709.06444 (2017).

#### Probabilistic Graphical Models and associated optimization techniques
- Blei, David M. Build, compute, critique, repeat: Data analysis with latent variable models. Annual Review of Statistics and Its Application 1 (2014): 203-232. [[Link]](https://www.annualreviews.org/doi/abs/10.1146/annurev-statistics-022513-115657)
- Blei, David M., Alp Kucukelbir, and Jon D. McAuliffe. "Variational inference: A review for statisticians." Journal of the American Statistical Association 112.518 (2017): 859-877. [[Link]](https://arxiv.org/pdf/1601.00670)
- Dieng, Adji Bousso. Deep Probabilistic Graphical Modeling. Columbia University, 2020. [[Link]](https://arxiv.org/abs/2104.12053)
- Figurnov, Mikhail, Shakir Mohamed, and Andriy Mnih. "Implicit reparameterization gradients." Advances in neural information processing systems 31 (2018). [[Link]](https://proceedings.neurips.cc/paper_files/paper/2018/file/92c8c96e4c37100777c7190b76d28233-Paper.pdf)
- Gelman, Andrew, Xiao-Li Meng, and Hal Stern. "Posterior predictive assessment of model fitness via realized discrepancies." Statistica sinica (1996): 733-760. [[Link]](https://www.jstor.org/stable/24306036)
- Kim, Kyurae, et al. "Black-Box Variational Inference Converges." arXiv preprint arXiv:2305.15349 (2023). [[Link]](https://arxiv.org/abs/2305.15349)
#### Statistics
##### Bayesian Statistics
- Clarke, Bertrand, and Yuling Yao. "A Cheat Sheet for Bayesian Prediction." arXiv preprint arXiv:2304.12218 (2023). [[Link]](https://arxiv.org/abs/2304.12218)
##### Causality
- Assaad, Charles K., Emilie Devijver, and Eric Gaussier. "Survey and evaluation of causal discovery methods for time series." Journal of Artificial Intelligence Research 73 (2022): 767-819. [[Link]](https://www.jair.org/index.php/jair/article/view/13428)
##### Distributions
- Leemis, Lawrence M., and Jacquelyn T. McQueston. "Univariate distribution relationships." The American Statistician 62.1 (2008): 45-53. [[Paper]](https://www.math.wm.edu/~leemis/2008amstat.pdf) [[Website]](https://www.math.wm.edu/~leemis/chart/UDR/UDR.html).
- Olszewski, Adrian. Challenging the cult of the prevalent normal distribution in nature. 2KMM, 2023. [[Link]](https://www.2kmm.pl/blog/On-the-ubiquity-of-skewness-in-nature/)
##### Statistical hypothesis testing (NHST)
- Gelman, Andrew. “Commentary: P Values and Statistical Practice.” Epidemiology, vol. 24, no. 1, 2013, pp. 69–72. JSTOR. Accessed 10 Dec. 2023. [[Link]](https://stat.columbia.edu/~gelman/research/published/asa_pvalues.pdf)
- Greenland, Sander et al. “Statistical tests, P values, confidence intervals, and power: a guide to misinterpretations.” European journal of epidemiology vol. 31,4 (2016): 337-50. doi:10.1007/s10654-016-0149-3 [[Link]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4877414/)
- Lakens, Daniël. “Equivalence Tests: A Practical Primer for t Tests, Correlations, and Meta-Analyses.” Social psychological and personality science vol. 8,4 (2017): 355-362. doi:10.1177/1948550617697177 [[Link]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5502906/)
- Lin, Mingfeng, et al. “Research Commentary: Too Big to Fail: Large Samples and the p-Value Problem.” Information Systems Research, vol. 24, no. 4, 2013, pp. 906–17. JSTOR. Accessed 10 Dec. 2023. [[Link]](http://www.stat.ntu.edu.tw/download/%E6%95%99%E5%AD%B8%E6%96%87%E4%BB%B6/bigdata/Research%20Commentary%20-%20Too%20Big%20to%20Fail%20Large%20Samples%20and%20the%20p-Value%20Problem.pdf)
- Lumley, Thomas et al. “The importance of the normality assumption in large public health data sets.” Annual review of public health vol. 23 (2002): 151-69. doi:10.1146/annurev.publhealth.23.100901.140546 [[Link]](https://pubmed.ncbi.nlm.nih.gov/11910059/)
- Mohd Razali, Nornadiah, and Bee Yap. ‘Power Comparisons of Shapiro-Wilk, Kolmogorov-Smirnov, Lilliefors and Anderson-Darling Tests’. J. Stat. Model. Analytics, vol. 2, 01 2011. [[Link]](https://www.researchgate.net/publication/267205556_Power_Comparisons_of_Shapiro-Wilk_Kolmogorov-Smirnov_Lilliefors_and_Anderson-Darling_Tests)
- Morey, Richard D et al. “The fallacy of placing confidence in confidence intervals.” Psychonomic bulletin & review vol. 23,1 (2016): 103-23. doi:10.3758/s13423-015-0947-8 [[Link]](https://pubmed.ncbi.nlm.nih.gov/26450628/)
- Olzsewski, Adrian. Mann-Whitney (Wilcoxon) and Kruskal-Wallis FAIL to compare medians in general. Quantile regression should be used to compare medians instead. [[Link]](https://gist.github.com/adrianolszewski/2cec75678e1183e4703589bfd22fa8b2)
- Olszewski, Adrian. On the p-values - links library significance ditching. Adrian Olszewski, 2022. [[Link]](https://docs.google.com/document/d/16KXpFW_nvF9l0eNlc56c-yY-B9VziPGWEkyDjibvwp8/edit)
- Olzsewski, Adrian. Testing hypotheses through statistical models opens a universe of new possibilities. Learn how to improve your daily work with this approach. [[Link]](https://github.com/adrianolszewski/model-based-testing-hypotheses)Pernet, Cyril. “Null hypothesis significance testing: a short tutorial.” F1000Research vol. 4 621. 25 Aug. 2015, doi:10.12688/f1000research.6963.3 [[Link]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5635437/)
- Serdar, Ceyhan Ceran et al. “Sample size, power and effect size revisited: simplified and practical approaches in pre-clinical, clinical and laboratory studies.” Biochemia medica vol. 31,1 (2021): 010502. doi:10.11613/BM.2021.010502 [[Link]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7745163/)
- The American Statistician, Volume 73, Issue sup1 (2019) [[Link]](https://www.tandfonline.com/toc/utas20/73/sup1)
- Verhagen, Arianne P., et al. ‘Is the p Value Really so Significant?*’. Australian Journal of Physiotherapy, vol. 50, no. 4, 2004, pp. 261–262. [[Link]](https://www.sciencedirect.com/science/article/pii/S0004951414601227)
### Posts and threads
#### Bayesian Statistics
- Camara-Escudero, Mauro. Variational Auto-Encoders and the Expectation-Maximization Algorithm. Mauro Camara-Escudero, 2020. [[Link]](https://maurocamaraescudero.netlify.app/post/variational-auto-encoders-and-the-expectation-maximization-algorithm/)
- Patacchiola, Massimiliano. Evidence, KL-divergence, and ELBO. Massimiliano Patacchiola, 2021. [[Link]](https://mpatacchiola.github.io/blog/2021/01/25/intro-variational-inference.html)
- Yao, Yuling. Bayes is guaranteed to overfit, for any model, any prior, and every data point. Yuling Yao, 2023. [[Link]](https://www.yulingyao.com/blog/2023/overfit/)
#### General topics
- Harrell, Frank. Classification vs. Prediction. Statistical Thinking, 2017. [[Link]](https://www.fharrell.com/post/classification/)
#### Variable selection / Feature selection
- gung Reinstate Monica (https://stats.stackexchange.com/users/7290/gung-reinstate monica). Algorithms for Automatic Model Selection. Cross Validated, https://stats.stackexchange.com/q/20856. [[Link]](https://stats.stackexchange.com/a/20856)
- Shtoff, Alex. “Are polynomial features the root of all evil?". Alex Shtoff, 2024. [[Link]](https://alexshtf.github.io/2024/01/21/Bernstein.html)
- Sribney, Bill. What are some of the problems with stepwise regression? StataCorp, 1996. [[Link]](https://www.stata.com/support/faqs/statistics/stepwise-regression-problems/)
### Talks, conferences, and videos
#### Bayesian Statistics
- Chopin, Nicolas, et al. "Bayesian Causal Inference for Real World Interactive Systems." Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining. 2021. [[Link]](https://bcirwis2021.github.io/schedule.html)
- Jordan, Michael. Nonparametric Bayesian Methods: Models, Algorithms, and Applications II. UC Berkeley, 2017 [[Link]](https://youtu.be/yfLoxwjCGNY?si=wdmK-yGImMiPihDk)
- Maxim Kochurov. State of Bayes Lecture Series. PyMC Labs, 2023. [[Link]](https://www.youtube.com/watch?v=X4y2UfU-2cs&list=PL1iMFW7frOOsh5KOcfvKWM12bjh8zs9BQ)
- Pragmatic Data Scientists. Making Informed Decisions with Bayesianism: A Conversation with Kenneth, Statistician at Meta. Pragmatic Data Scientist, 2023. [[Link]](https://www.youtube.com/watch?v=6269mm4XQOI)
#### Stochastic Processes
- Hakenes, Hendrik. Ito's Lemma -- Some intuitive explanations on the solution of stochastic differential equations. University of Bonn, 2021. [[Link]](https://youtu.be/_4zyAFpJ_Z4?si=hd4aVpI3ClKavcyu)

## 📄 Text Mining and Natural Language Processing
### Books
- Silge, Julia, and David Robinson. Text mining with R: A tidy approach. " O'Reilly Media, Inc.", 2017. [[Link]](https://www.tidytextmining.com/)
### Courses and lecture notes, posts
### Datasets
- Horwood, Ghraham V. Humanitarian Assistance and Disaster Relief (HA/DR) Articles and Lexicon. V1, Harvard Dataverse, 2017, doi:10.7910/DVN/TGOPRU. [[Link]](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/TGOPRU)
### Packages
### Papers
- Goldberg, Yoav. "A primer on neural network models for natural language processing." Journal of Artificial Intelligence Research 57 (2016): 345-420. [[Link]](https://arxiv.org/abs/1510.00726)
- Minaee, Shervin, et al. "Large Language Models: A Survey." arXiv preprint arXiv:2402.06196 (2024). [[Link]](https://arxiv.org/abs/2402.06196)
### Posts and threads
### Talks, conferences, and videos
