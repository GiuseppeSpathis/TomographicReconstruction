# TomographicReconstruction

Our project focuses on the reconstruction of lung tomographies. We utilized the Mayo Dataset for this purpose. We quantitatively and qualitatively compared the performance of three distinct algorithms: two classical iterative methods, namely Filtered Back Projection (FBP) and Total Variation (TV) Regularization, and a hybrid method. The hybrid approach implemented was the unrolled method Learned Primal-Dual Net, as presented in Adler's paper. All computations and implementations were carried out using the computational power of Google Colab.

- weights unrolled method: https://drive.google.com/file/d/1UsKFE4m9bSlFJMaQNNGfEzU4YxcBISTr/view?usp=sharing
- paper link https://arxiv.org/pdf/1707.06474
- Mayo's Clinic Dataset (https://cdas.cancer.gov/datasets/mayo/) consists of 3305 grey-scale images of dimension 512×512, representing real anonymized CT reconstructions of human lungs from 10 patients, available at: https://drive.google.com/drive/folders/13BEiz6t57qSbwBpCtfqllmYTLmkhQeFE?usp=share_link.

# Quantitative results on a subset of the test set 
![plot_geom_0_180_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/screenshotExcel.PNG)

# Qualitative and quantitative results on a selected image 

![plot_geom_-15_15_no_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/plots/plot_geom_-15_15_no_noise.png)


![plot_geom_-15_15_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/plots/plot_geom_-15_15_noise.png)


![plot_geom_-30_30_no_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/plots/plot_geom_-30_30_no_noise.png)


![plot_geom_-30_30_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/plots/plot_geom_-30_30_noise.png)


![plot_geom_0_180_no_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/plots/plot_geom_0_180_no_noise.png)


![plot_geom_0_180_noise](https://raw.githubusercontent.com/GiuseppeSpathis/TomographicReconstruction/main/results/plots/plot_geom_0_180_noise.png)


