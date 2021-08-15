# Pre-training-Neural-Networks-On-Xeno-Canto-and-Ebird-for-Bioacoustic-Classification-Models
This project will use Xeno-Canto and Ebird  datasets to train neural networks and transfer learning to other dataset
This project has three main steps;
1. Pre-training models from Xeno-canto and eBird,
2. Build baseline models using bird audio data collected from Intaka Insland, Cape Town,
3. Fine -tuning the pre-trianed model using our collected data.

I have included the code for the baseline model, one of the notebooks used for pre-training and the notebook that was used for fine-tuning. 
Before training the model, our bird vocalizations were annotated using Sonic Visualiser and  converted into spectrograms using the Librosa
python library. [This link](https://github.com/emmanueldufourq/GibbonClassifier) contains the code that was adopted for our audio preprocessing.
