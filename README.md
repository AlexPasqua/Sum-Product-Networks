# Sum Product Networks (SPNs)

Survey and presentation about Sum-Product Networks (SPNs), created for the course _Beyond Deep Learning: Selected Topics on Novel Challenges_ @ Technical University of Munich (TUM)

<img width=250px src="https://www.dwih-newdelhi.org/files/2019/04/TUM-logo-1-954x517.png" />

### Abstract
Sum-Product Networks (SPNs) are a probabilistic framework that allows building tractable models from data, making it possible to perform various inference tasks in polynomial time.
They are based on a rooted directed acyclic graph in which terminal nodes are the indicators of the input random variables (they can be seen as univariate probability distributions) and internal nodes divides themselves into sum nodes, which perform mixtures of sub-distributions, and product nodes, which perform factorizations.
SPNs are related to probabilistic graphical models, such as Bayesian Networks, but the latter often suffer from tractability issues, since exact inference often requires exponential time.
SPNs are also linked to Neural Networks (NNs), they share some similarities but there exist also many differences between these two classes of models.
In some cases they can be used as alternatives to each other, to tackle similar kinds of problems, but they can also be applied in a complementary way, to exploit the best characteristics of both.
<br>

**Note:**
the report follows the [style guidelines of NeurIPS 2021](https://nips.cc/Conferences/2021/PaperInformation/StyleFiles)