With the recent developments in deep learning, automatic cell segmentation from images of microscopic examination slides seems to be a solved problem as recent methods have achieved comparable results on existing benchmark datasets. However, most of the existing cell segmentation benchmark datasets either contain a single cell type, few instances of the cells, not publicly available. Therefore, it is unclear whether the performance improvements can generalize on more diverse datasets. Authors present a large and diverse cell segmentation dataset **BBBC041Seg**, which consists both of uninfected cells (i.e., red blood cells/RBCs, leukocytes) and infected cells (i.e., gametocytes, rings, trophozoites, and schizonts).

Additionally, all cell types do not have equal instances, which encourages researchers to develop algorithms for learning from imbalanced classes in a few shot learning paradigm. Furthermore, authors conduct a comparative study using both classical rule-based and recent deep learning state-of-the-art (SOTA) methods for automatic cell segmentation and provide them as strong baselines. Authors believe the introduction of BBBC041Seg will promote future research towards clinically applicable cell segmentation methods from microscopic examinations, which can be later used for downstream tasks such as detecting hematological diseases (i.e., malaria).

BBC041Seg consists of ground truth masks of different cell types from more than 1300 microscopic exam slides. Authors provide annotated masks as ground truths for images taken from BBBC041v1 dataset (Ljosa et al., 2012), which is a publicly available object detection dataset. Furthermore, authors also conduct a benchmark study using the BBC041Seg dataset leveraging both non-learning rules-based methods and recent deep learning-based state-of-the-art (SOTA) methods for automatic cell segmentation. The contribution of this paper can be summarized as follows.

1. Authors prepare and introduce BBBC041Seg, a cell segmentation dataset consisting of 1300+ images from BBBC041-v1 (Ljosa et al., 2012), and their cell segmentation masks as ground truth labels, which is significantly larger and more diverse than existing benchmark datasets.

2. Authors perform a series of controlled experiments by implementing both classical rule-based and deep learning state-of-the-art approaches and provide a comparative analysis using the proposed dataset.

3. Authors make the dataset publicly available to provide a platform for researchers to focus more on generalized cell segmentation methods that are more clinically acceptable. Dataset is available at [GitHub](https://github.com/Deponker/Blood-cell-segmentation-dataset).
