# SSCCP-Research:

#################################################################################################################
              Sleep Stage Classification for Child Patients Using DeConvolutional Neural Network
         
                      Xinyu Huang, Frédéric Li, Kimiaki Shirahama, and Marcin Grzegorzek

                       Institute of Medical Informatics      Department of Informatics
                       University of Lübeck, Germany         Kindai University, Japan
#################################################################################################################

** If you want use our codes, please reference the following publication[1]: 

[1] Xinyu Huang, Kimiaki Shirahama, Frédéric Li and Marcin Grzegorzek, Sleep stage classification for child patients using DeConvolutional Neural Network, Artificial Intelligence in Medicine, vol.110, pp.101981, 2020. DOI:10.1016/j.artmed.2020.101981.


###############
# Description #
###############

This README file describes the research materials of our study described in the article "Sleep Stage Classification for Child Patients Using Deconvolutional Neural Network".

This repository contain six main zip files containing:
  - the codes for deep learning models-SDCP(codes for DNN models.zip)
  - the codes for channel testing-SDCP(ChannelTesting.zip)
  - the codes for cross validation-SDCP(Cross-Validation.zip)
  - the codes for DNN models and k-fold cross-validation-Sleep-EDFX (codes for DCNN model and cross-validation (sleepedfx).zip)
  

A README file is provided in each zip file to describe its contents more in details and introduce how to execute the provided scripts.

The Python code provided requires the installation of the scikit-learn library [2], and the Keras library [3] with Tensorflow back-end [4] for deep-learning models. 

Sleep-EDFX dataset is avaiable in the PhysioNet [5,6].


########
# Size #
########


The total size of the codes is 94.2 kB


#######################
# Contact Information #
#######################

For any questions about the research materials of the repository or request the SDCP dataset that used in this paper, please contact us:

Xinyu Huang, Institute of Medical Informatics, University of Lübeck, Ratzeburger Allee 160, 23538 Lübeck, Germany (e-mail:
huang@imi.uni-luebeck.de)


########################
# References and links #
########################

[1] Xinyu Huang, Kimiaki Shirahama, Frédéric Li and Marcin Grzegorzek, Sleep stage classification for child patients using DeConvolutional Neural Network, Artificial Intelligence in Medicine, vol.110, pp.101981, 2020. DOI:10.1016/j.artmed.2020.101981.
    
[2] http://scikit-learn.org/stable/index.html
    
[3] F. Chollet et al., Keras, https://github.com/fchollet/keras

[4] I. Goodfellow et al. TensorFlow: Large-scale machine learning on heterogeneous systems. 
    http: //tensorflow.org/, 2015. Software available from tensorflow.org.

[5] B Kemp, AH Zwinderman, B Tuk, HAC Kamphuisen, JJL Oberyé. Analysis of a sleep-dependent neuronal feedback loop: the  
    slow-wave microcontinuity of the EEG. IEEE-BME 47(9):1185-1194 (2000).

[6] Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). 
    PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. 
    Circulation [Online]. 101 (23), pp. e215–e220.
