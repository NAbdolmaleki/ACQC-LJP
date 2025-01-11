# ACQC-LJP: Apollonius Circle-based Quantum Clustering using Lennard-Jones Potential

Quantum Clustering (QC) is widely regarded as a powerful method in unsupervised learning problems. This
method forms a potential function using a wave function as a superposition of Gaussian probability functions
centered at data points. Clusters are then identified by locating the minima of the potential function. However,
QC is highly sensitive to the kernel bandwidth parameter in the Schr¨odinger equation, which controls the shape
of the Gaussian kernel, and affects the potential function’s minima. This paper proposes an Apollonius Circlebased
Quantum Clustering (ACQC) method using Lennard-Jones Potential (LJP), entitled ACQC-LJP, to
address this limitation. ACQC-LJP introduces a novel approach to clustering by leveraging LJP to screen dense
points and constructing Apollonius circle-based neighborhood groups, enabling the extraction of adaptive kernel
bandwidths to effectively resolve the kernel bandwidth issue. Experimental results on real-world and synthetic
datasets demonstrate that ACQC-LJP improves cluster detection accuracy by 50% compared to the original QC
and by 10% compared to the ACQC method. Furthermore, the computational cost is reduced by more than 90%
through localized calculations. ACQC-LJP outperforms state-of-the-art methods on diverse datasets, including
those with small sample sizes, high feature variability, and imbalanced class distributions. These findings
highlight the method’s robustness and effectiveness across various challenging scenarios, marking it as a significant
advancement in unsupervised learning.


The SourceCode.rar file includes the MATLAB implementation :

For running the code you must start with ACQCLJPscript.m as the main script of the ACQC-LJP method.
The folder of ACQC-LJP contains two folders: dataset0(include synthetic datasets) and dataset1(include 24 real-world datasets).



# Condition to use any sources of this project
1. Please cite the following paper: N.Abdolmaleki, L.Mohammad Khanli, M.Hashemzadeh, S.Pourbahrami, ACQC-LJP: Apollonius circle-based quantum clustering using
Lennard-Jones potential, Pattern Recognition,161 (2025) 111342.
2. Please cite the following paper: N.Abdolmaleki, L.Mohammad Khanli, M.Hashemzadeh, S.Pourbahrami, ACQC: Apollonius Circle-based Quantum Clustering, Journal of Computational Science,64 (2022)101877.
3. Please do not distribute the database or source codes to others without the authorization from Dr. Mahdi Hashemzadeh (Corresponding author). Authors’ Emails: N.abdolmaleki@tabrizu.ac.ir (N. Abdolmaleki), l-khanli@tabrizu.ac.ir (L. M. Khanli), hashemzadeh@azaruniv.ac.ir (M. Hashemzadeh), sh.pourbahrami@tabrizu.ac.ir (S. Pourbahrami).
   
