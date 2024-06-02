# HigMISnet
## Generalized medical image segmentation using DWT based multilayer fusion and dual mode attention into high resolution pGAN

Objective: Automatic medical image segmentation is crucial for accurately isolating target tissue areas in the image from background tissues, facilitating precise diagnoses and procedures. While the proliferation of publicly available clinical datasets led to the development of deep learning-based medical image segmentation methods, a generalized, accurate, robust, and reliable approach across diverse imaging modalities remains elusive.

Approach: This paper proposes a novel high-resolution parallel generative adversarial network (pGAN)-based generalized deep learning method for automatic segmentation of medical images from diverse imaging modalities. The proposed method showcases better performance and generalizability by incorporating novel components such as partial hybrid transfer learning, discrete wavelet transform (DWT)-based multilayer and multiresolution feature fusion in the encoder, and a dual mode attention gate in the decoder of the multi-resolution U-Net-based GAN. With multi-objective adversarial training loss functions including a unique reciprocal loss for enforcing cooperative learning inpGANs, it further enhances the robustness and accuracy of the segmentation map.

Main results: Experimental evaluations conducted on nine diverse publicly available medical image segmentation datasets, including PhysioNet ICH, BUSI, CVC-ClinicDB, MoNuSeg, GLAS, ISIC-2018, DRIVE, Montgomery, and PROMISE12, demonstrate the proposed method's superior performance. The proposed method achieves mean F1 scores of 79.53%, 88.68%, 82.50%, 93.25%, 90.40%, 94.19%, 81.65%, 98.48%, and 90.79%, respectively, on the above datasets, surpass state-of-the-art segmentation methods. Furthermore, our proposed method demonstrates robust multi-domain segmentation capabilities, exhibiting consistent and reliable performance. The assessment of the model's proficiency in accurately identifying small details indicates that the high-resolution generalized medical image segmentation network (Hi-gMISnet) is more precise in segmenting even when the target area is very small.

Significance: The proposed method provides robust and reliable segmentation performance on medical images, and thus it has the potential to be used in a clinical setting for the diagnosis of patients.

Hi-gMISnet Framework:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/dbe8481a-e53a-403f-96da-92f7e3b81c41)

Architecture of the Hi-gMISnet's generator:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/16e794e4-34bf-4583-a448-58ae8bdd971e)

Published paper's link: https://iopscience.iop.org/article/10.1088/1361-6560/ad3cb3

** Codes will be uploaded soon in this repository
