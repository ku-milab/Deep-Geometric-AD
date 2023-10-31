# Deep Geometrical Learning for Alzheimer's Disease Progression Modeling

This is an implementation of the paper Deep Geometrical Learning for Alzheimer's Disease Progression Modeling with Pytorch.

> Under review (Accepted to IEEE-ICDM 2022)
> 
> **Abstract:** *Deep learning models based on resting-state functional magnetic resonance imaging (rs-fMRI) have been widely used to diagnose brain disease, particularly autism spectrum disorder (ASD). Existing studies used the functional connectivity (FC) of rs-fMRI and demonstrated notable classification performance. However, they have major limitations that include the lack of information in linear low-order FC as inputs to the model, not considering individual characteristics (i.e., different symptoms or varying stages of severity) among patients with ASD, and the difficulty in explaining the decision process. To address these issues, we propose a novel explainability-guided region of interest (ROI) selection (EAG-RS) framework that identifies non-linear high-order functional associations among brain regions by leveraging an explainable artificial intelligence technique and selects class-discriminative regions for brain disease identification.
Our proposed framework includes three steps; (i) inter-regional relation learning to estimate non-linear relations through random seed-based network masking, (ii) explainable connection-wise relevance score estimation to explore high-order relations between functional connections, and (iii) non-linear high-order FC-based diagnosis-informative ROI selection and classifier learning for ASD identification. We validate the effectiveness of our proposed method, by conducting experiments using the Autism Brain Imaging Database Exchange (ABIDE) dataset. Our proposed method achieves superior performance than those of comparative methods in various evaluation metrics. 
Further, we qualitatively analyzed the selected ROIs and identified ASD subtypes linked to previous neuroscientific studies.*

## Acknowledgements
This work was supported by Institute of Information & communications Technology Planning & Evaluation (IITP) grant funded by the Korea government(MSIT) (No. 2019-0-00079 , Artificial Intelligence Graduate School Program(Korea University) and No. 2022-0-00959, (Part 2) Few-Shot Learning of Causal Inference in Vision and Language for Decision Making).
