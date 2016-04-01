# flashtpx

Repository for fitting Grade of Membership (GoM) model using Factor Loading ash (FLash) due to Wei [ check [site](http://kkdey.github.io/flashtpx)]

Grade of Membership (GoM) models are a popular tool for clustering counts data. They have widespreas applications in population genetics and text modeling and recently, we have applied this model to cluster the samples (tissue or single cell samples) in RNA-seq reads data. There are already available software for clustering and visualizing RNA-seq expression data using GoM models - check [maptpx](https://cran.r-project.org/web/packages/maptpx/index.html) due to Matt Taddy and [CountClust](https://www.bioconductor.org/packages/3.3/bioc/html/CountClust.html) .

There are three issues we want to address in standard GoM models considered in the above packages.

- Incorporate sparsity in membership probability matrix and/or cluster membership matrices.

- Speed up the GoM model for big data

- To make the GoM model more flexible to overdispersion effects which are difficult to account for in standard GoM models.

Please check the homepage for FLASH [here](https://github.com/stephens999/ashr) and for any queries, contact [Wei Wang](https://github.com/NKweiwang).

