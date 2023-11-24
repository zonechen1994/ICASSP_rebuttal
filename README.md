**1.**   **Distinguishing PFR, self-channel and self-spatial attention modules.** 

This figure illustrates the distinctions between our Pixel Feature Refinement (PFR) module and the self-attention mechanisms based on spatial and channel attention modules. We represent features from the i-th and j-th channels as Fi and Fj, with Fi, x, y and Fj, m, n indicating specific coordinates within these channels. It's observed that the combination of Fi, x, y with Fj, m, n enhances the integrity of information. The self-channel attention module (a) calculates an attention metric between each channel, but fails to capture spatial correlation. In contrast, the self-spatial attention module (b) captures spatial correlation within individual channels but does not consider the entire channel set. Our PFR module (c) takes into account pixel-wise correlations across all channels, resulting in a more integrated and comprehensive structural information representation.

![image-20221023225816160](figs/fig1.png)



**2.**  **Visualization of heatmaps through PFR and CPFR modules.**

Visualization of heatmaps through PFR and CPFR modules**.** (a) Input image (top) and Ground Truth (bottom). Channel visualization (b) before and (c) after our PFR module. Our proposed CPFR module uses low-level features (d) and high-level features (e) to generate features (f). The features presented in (c) and (f) demonstrates the ability of PFR and CPFR modules to capture integrity features.

![image-20221023225816160](figs/fig2.png)

**3.**   **Experiments with Res2Net50 and PVT Backbones**

![image-20221023225816160](figs/fig3.png)





**4.**   **Integrity comparison between our method with other SOTAs.** 

Integrity comparisons among various methods at false negative ratios (FNR) are essential, as FNR is a direct indicator of integrity; lower values signify better performance.

![image-20221023225816160](figs/fig4.png)
