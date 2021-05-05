# Fabric-Defect-Detection-
Context In the context of textile fabric, rare anomaly can occurs, hence compromising the quality of the tissues. In order to avoid that in some scenario, it is crucial to detect the defect. This dataset is for educational purposes  Content Image size: 32x32 or 64x64 classes: ['good', 'color', 'cut', 'hole', 'thread', 'metal contamination'] rotations: 8 different rotations in [0, 20, 40, 60, 80, 100, 120, 140] Given an image size, a train and test dataset are available with randomly generated patches. Source images from the train and test are non-overlapping  different tasks are possible:  classification of the classes type classification of angles using only "good" images and testing of other classes texture representation learning / self-supervised learning Acknowledgements Based on the public dataset by the MVTec company Paul Bergmann, Michael Fuser, David Sattlegger, Carsten Steger. MVTec AD - A Comprehensive Real-World Dataset for Unsupervised Anomaly Detection; in: IEEE Conference on Computer Vision and Pattern Recognition (CVPR), June 2019  Inspiration the main goal of this dataset is to explore self-supervised learning on texture images in order to solve anomaly detection problems and learn a robust representation of texture in lieu of traditional image processing features (e.g. glcm, gabor,….)
