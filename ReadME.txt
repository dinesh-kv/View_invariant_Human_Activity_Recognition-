Chhavi Dhiman and Dinesh Kumar Vishwakarma, "View-Invariant Deep Architecture for Human Action Recognition Using 
Two-Stream Motion and Shape Temporal Dynamics" in Transaction in Image Processing, Vol. 29, pp. 3835-3844, 2020.

The code was only tested on 8GB NVIDIA GeForce GPU CARD, 64-bit ubuntu.

Feel free to contact me at chhavi1990delhi@gmail.com if you have questions.

Please cite the paper if you use the code. The code is only given for research purposes.
 Please contact me if you need to use it for other purposes.

****************************************************************************************
1-  Sample code of SSIM based key frame selection out of given number of frames : SSIM_key_frame_sample_code
2-  computation for selected 10 key frames: NUCLA_HPM_Keyframes_features
    They are also provided as 10_key_HPM_features.mat and 10_key_HPM_features_labels.mat
3-  HPM_features are split view wise in HPM_View_wise-split 
4-  HPM_LSTM stream is learnt view wise using HPM_LST_view_wise
5-  DI-InceptionV3 stream is trained using DI_view_wise_model_training
5-  View wise Fusion of DI_InceptionV3 stream with HPM_LSTM stream are perfromed in DI_HP_test_view1/2/3_fusion
****************************************************************************************