# PlantFlow

Lettuce Segmentation and Biomass Prediction through Deep Neural Networks and Machine Learning.

Built by Saahas Swaroop and Jonathan S. Cardenas at Ferrarezi Labs @ the University of Georgia. Paper publications pending.

To setup the environment run the following commands:

MacOS/Linux
```
python3 -m venv venv
source venv/bin/activate
cd setup
pip3 install -r requirements.txt
```

Windows
```
py -3 -m venv venv
venv\Scripts\activate
cd setup
pip3 install -r requirements.txt
```
To run TensorBoard run the following commands:

```
tensorboard --logdir logs/hyperparm_tuning/regression/{LFW/LDW/LA}
```