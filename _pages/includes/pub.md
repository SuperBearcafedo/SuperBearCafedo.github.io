
# 📝 Publications 
## 🩸 Diabetes Glucose Monitoring


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAI 2025</div><img src='images/GluTANN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GluTANN: Transformer-Based Continuous Glucose Monitoring Model with ANN Attention](https://ieeexplore.ieee.org/abstract/document/11050478) \\
**Sijie Xiong**, Youhao Xu, Cheng Tang, Jianing Wang, Shuqing Liu, Atsushi Shimada

[**Project**](https://ieeexplore.ieee.org/abstract/document/11050478) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**: In this work, we propose an innovative model based on Transformer architecture, GluTANN, with specially designed ANNs acting as self-attentions and paired correlations preserved by the encoder-decoder structure. Extensive experiments across five recognized datasets demonstrate that GluTANN has great competitiveness in reducing uncertainty while preserving satisfying accuracy, providing a feasible approach to effective glucose management and diabetes medical decisions.
- **Core Idea**: Reduce redundant tokens of Transformer-based models as much as we can.
- **Domain**: Time Series Forecasting, Diabetes, Glucose Monitoring
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE CYBCONF 2026 (Session Chair)</div><img src='images/GluPIDHW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GluPIDHW: A PID-Holt-Winters Model for Personalized Glucose Monitoring](https://www.ieeecyb2026.net/col.jsp?id=115) \\
Youhao Xu+, **Sijie Xiong+**, Tao Sun, Jianing Wang, Cheng Tang, Atsushi Shimada

[**Project**](https://www.ieeecyb2026.net/col.jsp?id=115) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**: The increasing worldwide incidence of diabetes has created a pressing demand for accurate and reliable glucose monitoring. Nevertheless, conventional machine learning methods exhibit limitations in trustworthiness and personalization, while deep learning methods with excellent trustworthiness underperform in accuracy and responsiveness. To realize an equilibrium, we propose an efficient model named GluPIDHW. Built upon an optimized Holt–Winters architecture augmented by a PID controller, GluPIDHW achieves improved accuracy and enhanced responsiveness. Extensive experiments conducted on five recognized datasets and out-of-distribution tasks demonstrate the superiority performance of GluPIDHW over excellent counterparts. This leadership is further validated by a Friedman testing and collectively, GluPIDHW offers a promising paradigm for continuous glucose monitoring and data-driven medical diagnose.
- **Core Idea**: Analogy from PID controller to Holt-Winters model.
- **Domain**: Time Series Forecasting, Diabetes, Glucose Monitoring
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE PRMVAI 2026 (Chair)</div><img src='images/GluConv.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">


[GluConv: Toward Trustworthy Convolutional Modeling for Sequential Signal Forecasting](https://github.com/SuperBearcafedo/GluConv) \\
**Sijie Xiong**, Haiqiao Liu, Yinlong Hu, Atsushi Shimada


[**Project**](https://github.com/SuperBearcafedo/GluConv) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>


- **Abstract**: Sequential signal forecasting is a fundamental challenge in machine learning, requiring models that simultaneously achieve high accuracy, responsiveness, trustworthiness. Existing shallow machine learning approaches provide fast inference but frequently lack trustworthiness in long-term supervision, while deep learning methods with improved reliability typically suffer from reduced responsiveness and degraded accuracy performance. To address these limitations, GluConv, an efficient convolution-based forecasting framework, is proposed. Accuracy, trustworthiness, and responsiveness are well balanced and preserved. GluConv nearly builds upon multi-scale convolutional units to capture both variate correlation and temporal dependency in sequential signals. Extensive experiments on continuous glucose monitoring benchmarks demonstrate that GluConv consistently outperforms excellent machine/deep learning baselines on reliability and responsiveness, while maintaining competitive accuracy. These properties make GluConv a **Conv**incing, **Conv**olutional, and **Conv**enient scheme for trustworthy forecasting.

- **Core Idea**: Combine U-Net and Convolutions.

- **Domain**: Time Series Forecasting, Diabetes, Glucose Monitoring

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICASSP 2026 (Poster)</div><img src='images/GlucoMixer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GlucoMixer: An Efficient Glucose Monitoring Model with Mixers](https://ieeexplore.ieee.org/document/11464084) \\
**Sijie Xiong**, Jianing Wang, Tao Sun, Cheng Tang, Fumiya Okubo, Atsushi Shimada

[**Project**](https://ieeexplore.ieee.org/document/11464084) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**: With the global prevalence in diabetes and scarcity of definitive clinic schemes, the need for effective and reliable glucose monitoring has become imperative. Due to excellent responsiveness and precision, machine learning (ML) models have been widely employed by continuous glucose monitors (CGMs). However, recent studies have raised concerns that ML-based models often exhibit limited trustworthiness, injecting uncertainty into medical practices. In contrast, deep learning (DL) models are recognized as more trustworthy, but they are struggling with accuracy. To strike a balance between accuracy and trustworthiness, we propose GlucoMixer, an Encoder-only architecture built predominantly with Mixer modules. To prevent future information leakage, we design a Mask Block that employs a lightweight triangular masking scheme. Given the presence of two diabetes types, we employ a convolutional layer to distinguish relevant information and take two Time Mixer Blocks to handle distinct patterns accordingly. Comprehensive In-Distribution (ID) and Out-of-Distribution (OD) evaluations across five benchmark datasets highlight GlucoMixer's superior performance in high predictive accuracy alongside excellent trustworthiness. According to the test ranking, GlucoMixer is more balanced across multiple evaluation metrics, demonstrating its potential as a practical spur for reliable glucose management and medical decisions.
- **Core Idea**: Combine linear projections and mask techniques to achieve a lightweight model.
- **Domain**: Time Series Forecasting, Diabetes, Glucose Monitoring
</div>
</div>

## 🚥🚦 Control & Time Series Forecasting
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI</div><img src='images/UMA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Unified Framework with Differential State Space Representations under Parallel Encoder and Decoder Scheme for Time Series Forecasting](https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence) \\
**Sijie Xiong**, Yuanyuan Zhang, Cheng Tang, Haoling Xiong, Yiding Li, Atsushi Shimada

[**Project**](https://github.com/Kyushu-U-AI/U-MA-EAAI-Official) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**:  Accurate time series forecasting plays a pivotal role across numerous real-world domains, underpinning applications ranging from finance to traffic management. Selective state space models that draw inspiration from control theory, displaying superior performance in multivariate time series forecasting. However, few variants offer a unified approach capable of achieving leading performance across simple and complex scenarios. An encoder and decoder convolutional network with skip connections can alleviate this issue. Thus, this paper proposes an innovative artificial intelligence framework for time series forecasting across diverse domains, borrowing the concept of encoder and decoder schemes and introducing a parallel encoder and decoder structure based on selective state space representations.  The proposed model enhances the vanilla selective state space models by integrating a forget gate mechanism, and a differential operation is incorporated to filter out random noise from transient signals, effectively refining and enhancing distinct features. Moreover, this framework incorporates long short term memory function along with an embedding channel attention mechanism to alleviate the potential disruption of long-term dependencies caused by down-sampling. This combination ensures the preservation of long-range embeddings and attentions, enhancing overall forecasting performance. Extensive experiments on benchmarking models and principal components across a wide range of prominent datasets highlight the unified effectiveness of the proposed framework in various scenarios, solidifying the superior position among leading models.
- **Core Idea**: Leverage Mamba and parallel U-Net structure with differential operations to cater for general time series forecasting.
- **Domain**: Time Series Forecasting, Control, Noise Reduction
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML</div><img src='images/KUMA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KUMA: A Novel Framework with Koopman Separation and Efficient Multilevel Extraction in Time Series Forecasting](https://icml.cc/virtual/2026/poster/64743) \\
**Sijie Xiong**, Cheng Tang, Atsushi Shimada

[**Project**](https://github.com/SuperBearcafedo/Review/tree/KUMA-Official) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**:  Time series forecasting plays a crucial role in a wide range of real-world applications and has become increasingly complex with the growth of multivariate dimensions and extended historical observations, leading to the prosperity of deep forecasting models. Previous models are hindered by three major challenges: high computational complexity, inefficient token utilization caused by redundancy and scarcity, and temporal distribution shifts resulting from non-stationary dynamics. Inspired by Koopman theory and the success of multilevel encoder–decoder architectures with skip connections, we design an input-dependent **K**oopman module to decompose time series into Koopman dynamics and residual dynamics. Building upon this formulation, we propose a **U**-shaped **M**ultilevel **A**ttention module (UMA) that integrates element-wise attention filtering and linear attention, giving rise to KUMA. The input-dependent Koopman operator mitigates the issue of operator mixture and alleviates temporal distribution shifts, while UMA achieves a favorable balance between token redundancy and token scarcity with acceptable computational efficiency. Comprehensive evaluations across 12 benchmark datasets demonstrate that KUMA achieves superior performance compared to existing excellent approaches.
- **Core Idea**: Design an adaptive Koopman module; Design the multilevel structure with Mamba-inspired linear attention.
- **Domain**: Time Series Forecasting, Separation Scheme
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASOC</div><img src='images/CMEMamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Nonlinear Dependencies of Mamba via Negative Feedback for Time Series Forecasting](https://doi.org/10.1016/j.asoc.2025.113758) \\
**Sijie Xiong**, Cheng Tang, Yuanyuan Zhang, Haoling Xiong, Youhao Xu, Atsushi Shimada

[**Project**](https://github.com/SuperBearcafedo/CME-Mamba) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**:  In this work, we are inspired by the curvature from financial domains and control systems, proposing CME-Mamba. The effectiveness, stability, robustness, etc., are discussed. Extensive experiments demonstrate that CME-Mamba grows excellent to uncover complex paradigms and predict future states in various domains, especially improving the performance for periodic and high-variate situations.
- **Core Idea**: Leverage negative feedback loop to enhance non-linearity for TSF models.
- **Domain**: Time Series Forecasting, Control
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICASSP 2026 (Oral)</div><img src='images/KPMG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KPMG: A Graphical Koopman-Mamba Approach for Financial Markets](https://ieeexplore.ieee.org/document/11461257) \\
**Sijie Xiong**, Cheng Tang, Fumiya Okubo, Tsubasa Minematsu, Yinlong Hu, Atsushi Shimada

[**Project**](https://ieeexplore.ieee.org/document/11461257) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**: Financial markets reflected by indices are substantial components of global economy. While existing models have achieved significant forecasting performance, they struggle to balance temporal and variate dependencies, which results in a trade-off between predictive accuracy and trustworthiness. Moreover, current models suffer from disturbances and impurities embedded in the financial data. To address these challenges, we propose KPMG, an efficient architecture that integrates the strengths of Mamba and Graph Neural Networks. With crucial features emphasized by Koopman operator and both temporal and variate dependencies mixed up in KPMG, accuracy and trustworthiness are significantly advanced. Extensive experiments on nine leading benchmarks across three index datasets demonstrate that KPMG has superiority over counterparts in prediction performance, while remaining acceptable computational complexity. Ablation studies further confirm the effectiveness of each designed module. The Friedman test consolidates the superiority of KPMG over counterparts.
- **Core Idea**: Leverage Mamba, graphical neural network (GNN) to predict financial markets.
- **Domain**: Time Series Forecasting, Finance, Index Forecasting
</div>
</div>

## 🏫 Education
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLEA 2025 (The Best Poster)</div><img src='images/FairytaleQA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-tuned T5 Models on FairytaleQA Chinese Dataset](https://library.apsce.net/index.php/ICLEA/article/view/5529) \\
**Sijie Xiong**, Haoling Xiong, Tao Sun, Haiqiao Liu, Fumiya Okubo, Cheng Tang, Atsushi Shimada

[**Project**](https://library.apsce.net/index.php/ICLEA/article/view/5529) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- **Abstract**: Question Answering (QA) is very important for comprehension learning and FairytaleQA is widely employed in this domain. However, rare versions in a limited number of alphabet languages restricts its application and current translators have five fatal errors. In our study, we manually translate FairytaleQA into Chinese and test its effectiveness via five fine-tuned T5 models.
- **Core Idea**: Extend current QA datasets on education for pre-trained models.
- **Domain**: Question-Answering, Education, Pre-trained Models
</div>
</div>

## Others
- Jianing Wang, Wei Dai, Tianyun Li, Xiang Zhu, Weiye Xu, **Sijie Xiong**, "[Optimization of Nonlinear Energy Sinks for Broadband Vibration Suppression in Marine Propulsion Systems](https://journals.sagepub.com/doi/abs/10.1177/10775463251410791)", *Journal of Vibration and Control (**JVC**)*. Jan. 2026.
- Yuanyuan Zhang, Haocheng Zhao, **Sijie Xiong**, Rui Yang, Eng Gee Lim, Yutao Yue, "[From High-SNR Radar Signal to ECG: A Transfer Learning Model with Cardio-Focusing Algorithm for Scenarios with Limited Data](https://ieeexplore.ieee.org/document/11216086)", *IEEE Transactions on Mobile Computing (**TMC**).* Oct. 2025.
- Tao Sun, **Sijie Xiong**, Cheng Tang, Haichuan Yang, Fumiya Okubo, Atsushi Shimada, "[Decomposed Seasonal-Trend Network with Rotary Attention for Time Series Forecasting](https://cmsworkshops.com/ICASSP2026/papers/accepted_papers.php)", *in 2026 IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP**).* May 2026.
- Yuanyuan Zhang, **Sijie Xiong**, Rui Yang, Eng Gee Lim, Yutao Yue, "[Recover from Horcrux: A Spectrogram Augmentation Method for Cardiac Feature Monitoring from Radar Signal Components](https://arxiv.org/abs/2503.19649)", *in 2025 47th Annual International Conference of the IEEE Engineering in Medicine & Biology Society (**EMBC**), IEEE*. Nov. 2025.
- Haiqiao Liu, Tsubasa Minematsu, Chengjiu Yin, **Sijie Xiong**, Atsushi Shimada, "[Exploring the Relationship Between System Operation Behaviors and Learning Achievement in Agricultural Education](https://library.apsce.net/index.php/ICCE/article/view/5974)", *in 2025 33rd International Conference on Computers in Education (**ICCE**), IEEE*. Oct. 2025.
- Tao Sun, Li Chen, **Sijie Xiong**, Cheng Tang, Gen Li, Atsushi Shimada, "[FERL-YOLO: Facial Expression Recognition Model of Learners](https://library.apsce.net/index.php/ICLEA/article/view/5498)", *in 2025 International Conference on Learning Evidence and Analytics (**ICLEA**), APSCE*. Sep. 2025.
- Shuqing Liu, Li Chen, **Sijie Xiong**, Haiqiao Liu, Cheng Tang, Atsushi Shimada, "[DiaRoBERTa: A Multi-Party Dialogue Model for Multi-Skill Recognition in Classroom Collaborative Problem Solving Discussions](https://library.apsce.net/index.php/ICLEA/article/view/5475)", *in 2025 International Conference on Learning Evidence and Analytics (**ICLEA**), APSCE*. Sep. 2025.
- Haiqiao Liu, Tsubasa Minematsu, Chengjiu Yin, Shuqing Liu, **Sijie Xiong**, Atsushi Shimada, "[Integrating Scaffolding Strategies with Environmental Monitoring Systems to Enhance Learning and Practical Skills in Agricultural Education](https://library.apsce.net/index.php/ICLEA/article/view/5497)", *in 2025 International Conference on Learning Evidence and Analytics (**ICLEA**), APSCE*. Sep. 2025.

