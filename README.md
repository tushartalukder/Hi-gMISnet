# HigMISnet
## Generalized medical image segmentation using DWT based multilayer fusion and dual mode attention into high resolution pGAN

Objective: Automatic medical image segmentation is crucial for accurately isolating target tissue areas in the image from background tissues, facilitating precise diagnoses and procedures. While the proliferation of publicly available clinical datasets led to the development of deep learning-based medical image segmentation methods, a generalized, accurate, robust, and reliable approach across diverse imaging modalities remains elusive.

Approach: This paper proposes a novel high-resolution parallel generative adversarial network (pGAN)-based generalized deep learning method for automatic segmentation of medical images from diverse imaging modalities. The proposed method showcases better performance and generalizability by incorporating novel components such as partial hybrid transfer learning, discrete wavelet transform (DWT)-based multilayer and multiresolution feature fusion in the encoder, and a dual mode attention gate in the decoder of the multi-resolution U-Net-based GAN. With multi-objective adversarial training loss functions including a unique reciprocal loss for enforcing cooperative learning inpGANs, it further enhances the robustness and accuracy of the segmentation map.

Main results: Experimental evaluations conducted on nine diverse publicly available medical image segmentation datasets, including PhysioNet ICH, BUSI, CVC-ClinicDB, MoNuSeg, GLAS, ISIC-2018, DRIVE, Montgomery, and PROMISE12, demonstrate the proposed method's superior performance. The proposed method achieves mean F1 scores of 79.53%, 88.68%, 82.50%, 93.25%, 90.40%, 94.19%, 81.65%, 98.48%, and 90.79%, respectively, on the above datasets, surpass state-of-the-art segmentation methods. Furthermore, our proposed method demonstrates robust multi-domain segmentation capabilities, exhibiting consistent and reliable performance. The assessment of the model's proficiency in accurately identifying small details indicates that the high-resolution generalized medical image segmentation network (Hi-gMISnet) is more precise in segmenting even when the target area is very small.

Significance: The proposed method provides robust and reliable segmentation performance on medical images, and thus it has the potential to be used in a clinical setting for the diagnosis of patients.

### Building blocks

Hi-gMISnet Framework:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/08db1d5a-5874-4fd8-9181-525dddac7ee6)

Architecture of the Hi-gMISnet's generator:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/5e5dac24-39b8-4c5b-990c-eb93471ace90)

DWT based multilayer and multi-resolution feature fusion:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/330e36a0-39f2-49f0-b13e-26c116cf495b)

Dual mode Attention Gate (DAG):
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/3d761062-9f57-457c-9508-ab589658f778)

### Results

Comparative performance on PhysioNet ICH, BUSI, and CVC-ClinicDB datasets:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/5f7bbea4-4bb1-47a1-8f22-2e4afb348d4b)
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/aa406016-1d7a-48f3-ac97-0ba4f8a68e39)

Comparative performance on MoNuSeg, GLAS, and ISIC-2018 datasets:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/8ad67528-3a14-4652-8d79-febc9ed67c41)
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/85e7b2c9-1d2d-4ab1-87fb-ebdfc6f641da)

Comparative performance on DRIVE, Montgomery and PROMISE12 datasets:
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/d85ff5ed-4150-49a0-b500-4ea5e2eb0c5d)
![image](https://github.com/tushartalukder/HigMISnet/assets/65252460/e1335d9c-4591-4aab-bd55-884c728c2c5c)


Published paper's link: https://iopscience.iop.org/article/10.1088/1361-6560/ad3cb3

### Please cite as: 

@article{showrav2024hi,
  title={Hi-gMISnet: generalized medical image segmentation using DWT based multilayer fusion and dual mode attention into high resolution pGAN},
  author={Showrav, Tushar Talukder and Hasan, Md Kamrul},
  journal={Physics in Medicine and Biology}
} 

** Codes will be uploaded soon in this repository
