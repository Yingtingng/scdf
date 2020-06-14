# Submission name



## Auto AI 
(Prediction of fires)



### Subsection 1.1

Mauris odio ante, rhoncus et varius vel, vulputate et enim. Aliquam erat volutpat. Proin lacinia libero velit, a dictum sapien ultricies quis. Vivamus dolor nibh, efficitur in ipsum vitae, faucibus eleifend felis.

### Subsection 1.2

Nullam nec lectus massa. Proin feugiat placerat nisi lacinia lobortis. Duis efficitur ac orci ac lobortis.

## Machine Learning 

### Early detection

From research, we found out a few signs of a fire - smoke, sparks, fire hazards such as cigarette buds. Hence we took the following steps to create our model:
1. Upload sample photos of early stages of a fire onto Cloud Annotations. 
2. Created a Watson Machine Learning (WML) instance
3. Trained out model using TensorFlow and Keras to identify fires
4. Imported the training model onto WML

Further steps to deploy such a project:
5. Sync the drones used for patrol to Cloud Annotations, which will take pictures periodically and upload them on cloud
6. If images have been detected to fall under the "fire" category, it will send warning messages to SCDF
7. SCDF will immediately deploy its members to fight the fire

## Conclusion


### Results

