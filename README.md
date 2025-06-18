# ![1CFFD0F2](https://github.com/user-attachments/assets/db17f6b5-fe11-4aa7-84b1-803fce53cf7d)Accepted by JSTARS 2025
 SHSRD: Efficient Conditional Diffusion Model for Single Hyperspectral Image Super-Resolution 

 <https://ieeexplore.ieee.org/document/11036681>
 
Code is coming soon.
## Abstract

The emergence of deep neural networks has spurred progress in single hyperspectral image (HSI) super-resolution. However, mainstream models prioritize network architecture and optimization, **overlooking the limitations of hyperspectral image datasets' small scale and potential data imbalance**. Direct training models with such datasets can lead to issues like **overfitting**.

To address these dataset-centric challenges, we propose **SHSRD** (Hyperspectral Image Super-Resolution Diffusion framework), an advanced super-resolution framework specifically designed for HSIs based on the **diffusion model**. It incorporates a **spectral information injection module**, which selectively introduces diverse spectral information into the model in a conditional manner, enabling **efficient spectral information perception**.

Furthermore, a **two-stage training strategy** is meticulously devised:
1.  **Large-Scale Pre-training:** The model is initially pre-trained on a large-scale natural image dataset.
2.  **Transfer Learning:** Leveraging transfer learning, the knowledge acquired from the natural image dataset is seamlessly transferred to the single hyperspectral image super-resolution task.

This strategic approach **culminates in the realization of high-quality super-resolution for single hyperspectral images**, effectively addressing the challenges associated with **limited training data** in hyperspectral imaging. SHSRD also demonstrates **significant generalization**: requiring only **one pre-training session** on a natural image dataset for scale-specific tasks, it allows for **rapid transfer** to any small HSI dataset.

**Extensive experiments** on four public datasets demonstrate that **SHSRD outperforms state-of-the-art methods**.
