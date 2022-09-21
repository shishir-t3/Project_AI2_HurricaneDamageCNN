# Project_AI2_HurricaneDamageCNN
Hurricane Iota was a devastating late-season Category 4 Atlantic hurricane which caused severe damage to areas of Central America already devastated by Hurricane Eta just less than two weeks prior. The 31st and final tropical cyclone, 30th named storm, 14th hurricane, and record-tying seventh major hurricane of the record-breaking 2020 Atlantic hurricane season, Iota originated as a tropical wave that moved into the Eastern Caribbean on November 10. Over the next few days, the wave began to become better organized and by November 13, it developed into a tropical depression north of Colombia. 


![image](https://user-images.githubusercontent.com/99063438/191453991-98f24ae8-3e3c-40e1-93a2-ab550ba68609.png)

Iota's precursor disturbance generated flash flooding on several Caribbean islands. Tropical cyclone watches and warnings were first issued on November 14 in parts of Colombia, Nicaragua, and Honduras, with the latter two countries still recovering from Eta. Heavy rains associated with a tropical wave and Iota brought heavy rainfall to parts of Colombia, leading to flash flooding and mudslides. Extremely heavy rain fell on much of Nicaragua, widening flash flooding caused by the hurricane's high storm surge. Mudslides caused extensive damage and multiple deaths. At least 67 people were killed due to Iota, including at least 28 in Nicaragua and 16 in Honduras, among other countries.


## Dataset
With the dataset collected from satelitte imaging, we are trying to identify whether a House has been damaged or not damaged by visualising the top of the houses from the satellite image. Since doing the damage survey manually by driving by each house is both time and cost expensive, we are trying to build a model which will be able to do so by just looking at the image data collected by the satelitte imagery.
The dataset is divided into 4 categories:

   1. train_another: the training data; 5000 images of each class(damage/no damage)
   2. validation_another: the validation data; 1000 images of each class(damage/no damage)
   3. test_another: the unbalanced test data; 8000/1000 images of damaged/undamaged classes
   4. test: the balanced test data; 1000 images of each class(damage/no damage)
 
The dataset provided below has been labelled into two categories:

  No damage:
  
  ![image](https://user-images.githubusercontent.com/99063438/191454527-caa4af07-37f2-4b52-ad31-29e02369a09c.png)
    
  Damage:
  
  ![image](https://user-images.githubusercontent.com/99063438/191454638-35ac990f-0133-48e5-b54b-f08f92d6752e.png)


## Visualisation For Models

### Saliency Maps

![image](https://user-images.githubusercontent.com/99063438/191455400-5e1db7db-4baa-4e40-adfe-a0b54819d7ba.png)

### Grad-CAM

![image](https://user-images.githubusercontent.com/99063438/191455477-ce7fb7f3-ae25-4d31-a088-ca3b15a25df0.png)
