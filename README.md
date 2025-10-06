# Health-Data-Science-Seminar
I conducted a comparative analysis of two research papers on breast cancer detection using machine learning. The report examined the DE_RBF_KELM model and the optimized ensemble learning with XAI, comparing their methods, datasets, and performance. Both achieved high accuracy, enhancing early cancer diagnosis.


In this report, we will critically examine both studies, focusing on their methodologies, results, and their potential impact on breast cancer diagnostics. 
ELM & KELM
Extreme Learning Machine (ELM) is a single hidden layer feed-forward network (SLFN) focused on fast learning but can
suffer from "dead nodes" due to random input weights, impacting 4 accuracy. Kernel ELM (KELM) improves ELM by transforming nonlinearly separable
data into a linearly separable form using kernel functions, enhancing regression and classification accuracy. Unlike ELM, KELM's output function is independent of network architecture, utilizing various kernel functions such as radial basis (RBF-KELM), polynomial (Poly-KELM), and wavelet (Wav-KELM).
