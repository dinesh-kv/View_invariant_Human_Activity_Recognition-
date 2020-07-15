#Introduction#
Human action Recognition for unknown views, is a challenging task. We propose a deep view-invariant human action recognition framework, which is a novel integration of two important action cues: motion and shape temporal dynamics (STD). The motion stream encapsulates the motion content of action as RGB Dynamic Images (RGB-DIs), which are generated by Approximate Rank Pooling (ARP) and processed by using fine-tuned InceptionV3 model. The STD stream learns long-term view-invariant shape dynamics of action using a sequence of LSTM and Bi-LSTM learning models. Human Pose Model (HPM) generates view-invariant features of structural similarity index matrix (SSIM) based key depth human pose frames. The final prediction of the action is made on the basis of three types of late fusion techniques i.e. maximum (max), average (avg) and multiply (mul), applied on individual stream scores. To validate the performance of the proposed novel framework, the experiments are performed using both cross-subject and cross-view validation schemes on three publically available benchmarks-NUCLA multi-view dataset, UWA3D-II Activity dataset and NTU RGB-D Activity dataset. Our algorithm outperforms existing state-of-the-arts significantly, which is measured in terms of recognition accuracy, receiver operating characteristic (ROC) curve and area under the curve (AUC).

#The details of work can be found on https://ieeexplore.ieee.org/document/8960517

# Cite above work as C. Dhiman and D. K. Vishwakarma, "View-Invariant Deep Architecture for Human Action Recognition Using Two-Stream Motion and Shape Temporal Dynamics," in IEEE Transactions on Image Processing, vol. 29, pp. 3835-3844, 2020, doi: 10.1109/TIP.2020.2965299.
