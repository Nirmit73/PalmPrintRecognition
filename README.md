# PalmPrintRecognition

### Intra and Inter-class variability in Palm Print Recognition

- Intra-class variability: refers to the variation or differences observed within the same class or group of data, particularly within the samples belonging to a single individual in the POLYU dataset. It quantifies the diversity or dissimilarity between multiple instances (left and right palm samples) of the same person.
- Inter-class variability: represents the degree of difference or dissimilarity between different classes or groups within the POLYU dataset. It measures the variation between left and right palm samples across individuals, providing insights into the distinctiveness or separability of different individuals based on their palm images.  

### Dataset Description
- The dataset used is The IIT Delhi palmprint image database consists of the hand images collected from the students and staff at IIT Delhi, New Delhi, India.
- The currently available database is from 230 users and all the subjects in the database are in the age group 12-57 years. Seven images from each subject, from each of the left and right hand, are acquired in varying hand pose variations. 

### Methodology  
- We conducted an analysis to assess inter and intra-class variability within the IITD dataset, comprising 6-7 left and right palm samples from 230 individuals
- Initially, we utilized the Local Binary Pattern (LBP), Gabor Filters, and Zernike Moments algorithm to extract features from the palm images. Subsequently, we employed distance metrics such as Euclidean distance to compute the intra-class variability for both left and right palms of each person.
- For inter-class variability, we computed the mean inter-class distance for both left and right palms, offering valuable insights into the dataset's variability and potential applications.
- The inter-class variability was calculated at different acceptable thresholds and the results is visualized by plotting a ROC curve of inter-class at different thresholds.

### Results
- Mean Inter and Intra-class Variability for the 3 algorithms
  
  ![image](https://github.com/Nirmit73/PalmPrintRecognition/assets/71959011/d92936b7-86ba-47a9-8624-25a5a7c6daca)   ![image](https://github.com/Nirmit73/PalmPrintRecognition/assets/71959011/25eb5f17-d52f-42a6-a380-4239cdb3ddd2)

- Time Complexity
  
  ![image](https://github.com/Nirmit73/PalmPrintRecognition/assets/71959011/6664c119-e366-42e8-bff9-62399d43580b)



