# Intelligent-Garbage-Management-System
### An intelligent system which can help smart cities to tackle garbage disposal issue.

Work load on municipality can be reduced with the help of this CNN based project, user can directly lodge complaint hassle free with their android application.
1. Idea is to identify if the image taken by user contains garbage or not at their end only, authorities need not to take care whether garbage is actually there or not.
2. This will not only reduce workload of workers of municaplities but also reduce false complaints from the user end.
3. Dataset is created by fetching images from google, yahoo, duckduckgo (Contains 3090 images)

## The following are combined to make this project:
      a. CNN based model converted to tflite for android.
      b. Android App for user to lodge complaints.
      c. Website for authorites to view complaints 
      
4. Convolution Neural Network based approach, MobileNet and VGG16 as a pre-trained model are used for creation of model.

      
## Accuracies of Models:

| Model | Val Accuracy |
| ------ | ------ |
| CNN | 84.45% |
| VGG16 | 90.15% |
| MobileNet_v1 | 94.05% |

5. MobileNet is chosen becuse of it's accuracy and being 32 times lighter than VGG16.

## Implementation

### Android Application:

![Screen 1 Android](https://user-images.githubusercontent.com/64465828/119958695-e619ab00-bfc0-11eb-9d0e-c123b68a9197.png)
![Screen 2 Android](https://user-images.githubusercontent.com/64465828/119958811-047fa680-bfc1-11eb-945c-5a68da61b718.png)

### Authority Website:

![Sceen 1 Admin](https://user-images.githubusercontent.com/64465828/119960101-3cd3b480-bfc2-11eb-82a3-42970b08ea2d.png)
![Screen 2 Admin](https://user-images.githubusercontent.com/64465828/119960172-507f1b00-bfc2-11eb-835f-f30a1afbb5be.png)
![Screen 3 Admin](https://user-images.githubusercontent.com/64465828/119960235-6260be00-bfc2-11eb-9d45-c76549f0c0c1.png)
