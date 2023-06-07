# 525 Bird Classification using CNN


#### [525 Bird Classification - demo on Streamlit Cloud](https://surajspatil99-525-bird-classification-app-p285sg.streamlit.app/)
use the above to get a live demo

#### Dataset link
https://www.kaggle.com/datasets/gpiosenka/100-bird-species

## Built with
+ [Python 3](https://www.python.org/) - awesome language.
+ [Streamlit](https://streamlit.io/) - a high-level Python Web framework that encourages rapid development and clean, pragmatic design.
+ [TensorFlow](https://www.tensorflow.org/) - popular python framework for building, training and deploying deeplearning models

![bird_classification](https://github.com/SurajspatiL99/525-Bird-Classification/assets/101862962/9fdb54f5-4ad7-4ba8-b4f4-5124aa9ff62d)

## Overview
Wildlife conservation has been recently transformed by the application of artificial intelligence. AI helps researchers determine the location of animals, date of sighting, migration patterns, and even an animal social group. AI is used by conservationists to monitor and protect animals in their natural habitat. There are an estimated 30,000 threatened species across the globe. Scientists are utilizing AI to understand what put these species at risk by offering information about where they are born, how many survive, where they go, and how far they go. Following are some advantages of AI in the conservation of animal species:

- AI facilitates the collection of vast and fascinating datasets and their analysis in no time.
- AI is helping wildlife researchers in studying the wild animal species collectively and making strategies to protect them.
- Artificial intelligence tracks wildlife patterns and predicts the extinction of endangered animal species.
- It helps conservationists to detect and stop wildlife poaching.
- It can provide information about the effects of climate change on wildlife and reducing its impact by designing a proper plan.
- AI assists in assessing the species population and see changes.
- It helps to stop illegal animal trade on social media.
- Artificial intelligence identifies and classifies animal species into various classes and provides detailed information about them.
- AI algorithms can conserve animal habitats by predicting animal migratory patterns.

## Model Building and Deployment
- This is a trained EfficientNetB0 model. It was trained on images of shape 224 X 224 X3.
- This model achieved an F1 score of 98.97 on the test set. 
- The model was trained for 15 epochs.
- The was then quantized using Tensorflow, this model was further trained for 1 epoch and then converted to tflite model.
- A web app was developed using streamlit and was deployed on stremlit community cloud
![image](https://github.com/SurajspatiL99/525-Bird-Classification/assets/101862962/2db8c889-412e-4233-b369-6820d5ad6b20)





