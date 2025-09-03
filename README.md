# Leveraging Implicit 3D Geometry for Biometric and Anthropometric Estimation from Gait

Source code for the conference paper presented in *IJCB 2025* (IEEE International Joint Conference on Biometrics)

## Abstract

Estimating biometric and anthropometric attributes from gait sequences presents a promising alternative to traditional body measurement techniques, particularly in unconstrained or low-resource environments. However, inferring metric attributes from 2D silhouette-based gait representations remains challenging due to the lack of volumetric cues. In this work, we propose a novel training strategy that leverages the geometric priors encoded by PIFuHD—a high-resolution implicit function-based model for 3D human reconstruction—to inject structural supervision into a gait encoder. Our method introduces a feature reconstruction branch that distills volumetric knowledge from precomputed PIFuHD embeddings during training, enabling accurate prediction of anthropometric attributes at inference time from 2D silhouette sequences alone. We evaluate our approach on the Health&Gait dataset, achieving substantial improvements over baselines in predicting multiple attributes, including height, weight, BMI, and body circumferences. These results demonstrate that shape-aligned supervision from implicit 3D models can effectively bridge the gap between geometric reasoning and efficient biometric estimation from visual gait data.

## Source code will be released soon !!

