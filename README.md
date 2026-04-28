# AFA-DETR
Our Paper：AFA-DETR: Asymptotic Frequency-Attention DETR with Spectral-Spatial Hybrid Encoder for fabric Defect Detection 



ABSTRACT
ransformer-based detectors, notably the state-of-the-art DEIM framework, excel in general vision but encounter severe representation bottlenecks in fabric defect detection. DEIM’s spatial self-attention encoder struggles with periodic textures, causing intractable spectral overlap between subtle defects and background noise. Furthermore, semantic "erosion" during multi-scale fusion and "polarity neutralization" in conventional attention severely constrain low-contrast anomaly detection.We propose AFA-DETR, built upon DEIM, introducing a spatial-frequency collaborative perception paradigm to overcome these limitations. First, a Global Frequency Token Mixer (GFTM) replaces spatial attention with 2D-FFT-driven dynamic spectral cross-correlation, adaptively decoupling background noise with minimal overhead. Second, a Residual-enhanced Ghost Progressive Adjacent Feature Fusion (RG-PAFF) module mitigates semantic "erosion" through progressive multi-scale interaction. Finally, a parameter-free Linear Polarity-Preserving Attention (LPPA) discards squared activations to explicitly preserve linear residual polarities, restoring sensitivity to elusive defects.AFA-DETR achieves 96.8%  96.8% mAP50 and 64.5% mAP with only 8.7M parameters and 14.3GFLOPs (representing a 42.3% reduction in computational overhead). Cross-architecture generalization experiments validate the plug-and-play capability of the model, establishing a new paradigm for resource-constrained industrial quality inspection. The source code and dataset are publicly available at https://github.com/yinwuxu/AFA-DETR.


4/26 submit







Baseline：https://github.com/Intellindust-AI-Lab/DEIM.git,这边只把论文核心部分即插即用模块AFA-encoder这一部分上传

DATASET: 通过网盘分享的文件：data 链接: https://pan.baidu.com/s/1IpGRv_WazPbjmxhGtylsGQ 提取码: 6666
