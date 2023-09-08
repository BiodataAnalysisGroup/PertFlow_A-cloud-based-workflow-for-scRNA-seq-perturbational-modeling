## PertFlow-A-cloud-based-workflow-for-scRNA-seq-perturbational-modeling

PertFlow is a Colab-based workflow geared towards fundamental scRNA-seq analysis, pathway and transcriptional factor bioinformatic analysis and mainly perturbational modeling.

The user is encouraged to prepare an integrated scRNA-seq object with e.g., Scanpy or Seurat pipelines containing several patients or timepoints (if studying a longitudinal experiment).

We encourage the user to work with Anndata format in Python for Scanpy. For conversions between Seurat and Python, we include respective code chunks to facilitate interoperability.

From the PertFlow prototype, the user is welcomed to adapt any parts that he deems necessary to primarily build some biological context through the decoupler platform and then move on to the perturbational tools.

The Chronic Lymphocytic Leukemia (CLL) pilot can be very informative for a real-dataset implementation of the whole workflow and they ways the user can (a) validate ground-truths and (b) infer new knowledge with biological plausibility.

If deploying scGEN, the user is advised to change runtime type to GPU for faster implementation of the package.
