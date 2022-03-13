# Project Title

FloodBot:Vision and AI Enabled Flood Detection Systems in Urban Environment

## FloodBot Data Samples
![](https://github.com/umbcfloodbot/FloodBot/blob/main/misc/sampleCapture.PNG| width=100)


## Abstract
Flash flood is one of the most commonly occurring natural disasters. However, communities are often ill-prepared for its pre-disaster precautions and post-disaster aftermath. We argue thatthe technical and economic resources are significant constraints in identifying, assessing, and reducing disaster risks. While other mature flood protection mechanisms exist, they are often expensive and site-specific. Expensive flood detection and control mechanisms are often limited to affluent communities, increasing the risk of flood damage to less affluent areas. Our research develops economically viable, scalable, and mobile Flashflood detection systems that are crucial in reducing disaster risks. We explore various state-of-the-art machine learning models, Internet of things (IoTs), crowd-sourcing, participatory sensing, and cloud infrastructure to deliver social media-based flash flood detection systems called FloodBot. The FloodBot is a scalable, mobile, and end-to-end mass-deployable alternative flashflood detection system based on vision, sound, and hearing. The Floodbot's vision is enabled by computer vision (CV) techniques, its auditory capabilities are enabled by acoustic scene classification (ASC) techniques, and conversational AI enables its speech. We train FloodBot to perform image recognition, detection, and segmentation using various convolutional neural networks (CNN) and then deploy transfer learning techniques to improve accuracy. Specifically, our thesis and FloodBot design exploit the power of deep learning models such as a convolutional neural network (CNN), single-shot multi-box object detection (SSD), segmentation model for vision-based tasks. 

We use Mel-Spectrogram-based auditory signal analysis and deep learning models to classify environmental sounds pertinent to flood events. We deploy memory-based end-to-end pre-trained language models such as Bidirectional Encoder Representations from Transformers (BERT)  to enable conversational power and seamless integration of FloodBot into social media. We then assesses the relevancy of the multimodal information (image + sound + social media) and pieces them together to deliver artificial intelligence (AI) needed to reduce damages and prepare the community during natural disasters. All in all, FloodBot integrates multimodal raw data and extracts valuable information required to detect floods.

### Prerequisites

What things you need to install the software and how to install them

```
cv2
numpy
pandas
platform
requests
json
time
librosa
```

### Installing

Import all the Packages (Sugessted in GoogleColab)

```
import librosa
import matplotlib.pyplot as plt
import IPython.display as ipd
import librosa
from pydub import AudioSegment
```


End with an example of getting some data out of the system or using it for a little demo

## General Approach
![alt text](https://github.com/umbcfloodbot/FloodBot/blob/main/misc/summary_fig.PNG =250x250)

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## FloodBot
![alt text](https://github.com/umbcfloodbot/FloodBot/blob/main1/misc/fog_1029.png)

## Authors

* **Bipendra Basnyat** - *More Collaberator & Information at* - https://mpsc.umbc.edu/projects/flash-flood-monitoring

See also the list of [contributors]****

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Paragraph

Bipendra Basnyat, Nirmalya Roy, Aryya Gangopadhyay.Environmental Sound Classification for Flood Event Detection, on The 18th International Conference on Intelligent Environments (IE2022), Kassel, June 2022 (\textit{Accepted Papers}).

Bipendra Basnyat, Nirmalya Roy, Aryya Gangopadhyay. Towards AI Conversing: FloodBot using Deep Learning Model Stacks, Pervasive and Mobile Computing, (\textit{Submitted Journal Paper under review}).

Neha Singh, Bipendra Basnyat, Nirmalya Roy, Aryya Gangopadhyay.Evaluation of Various Text Classification Models for Identifying Relevant
Flood Tweet, Pervasive and Mobile Computing, (\textit{Submitted Journal Paper under review}).

Bipendra Basnyat, Nirmalya Roy, Aryya Gangopadhyay. Flood detection using semantic segmentation and multimodal data fusion, on PerAwareCity, Kassel, Germany, March 2021.

Bipendra Basnyat, Neha Singh, Nirmalya Roy, Aryya Gangopadhyay, Vision Powered Conversational AI for Easy Human Dialogue Systems, IEEE 17th International Conference on Mobile Ad Hoc and Sensor Systems (MASS), IITR, NCR, India 2020.

Bipendra Basnyat, Nirmalya Roy, Aryya Gangopadhyay. Towards AI Conversing: FloodBot using Deep Learning Model Stacks, in Proceedings of the 6th IEEE International Conference on Smart Computing (SmartComp), Bologna, Italy, September 2020.

Neha Singh, Nirmalya Roy, and Aryya Gangopadhyay, Localized Flood Detection With Minimal Labeled Social Media Data Using Transfer Learning, AI for Social Good - AAAI Fall Symposium 2019, Association for the Advancement of Artificial Intelligence, Arlington, Virginia, USA, November 7 – 9, 2019.

Neha Singh, Nirmalya Roy and Aryya Gangopadhyay. Analyzing the Emotions of Crowd for Improving the Emergency Response Services, Pervasive and Mobile Computing (PMC) Journal, Volume 58, August 2019, Elsevier 2019

Amrita Anam, Aryya Gangopadhyay and Nirmalya Roy. Event Characterization and Separation using Wavelet Signatures, in proceedings of the 5th workshop on Mining and Learning from Time Series (MiLeTS) in conjunction with 25th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), Anchorage, Alaska, August 2019

Amrita Anam, Aryya Gangopadhyay, Nirmalya Roy. Identifying the Context of Hurricane Posts on Twitter using Wavelet Features, in Proceedings of the 5th IEEE International Conference on Smart Computing (SmartComp), Washington D.C., June 2019

Bipendra Basnyat, Nirmalya Roy and Aryya Gangopadhyay. A Flash Flood Categorization System using Scene-Text Recognition, in Proceedings of the 4th IEEE International Conference on Smart Computing (SmartComp), Sicily, Italy, June 2018

Amrita Anam, Aryya Gangopadhyay and Nirmalya Roy. Evaluating Disaster Time-line from Social Media using Wavelet Analysis, in Proceedings of the 4th IEEE International Conference on Smart Computing (SmartComp), Sicily, Italy, June 2018

Neha Singh, Nirmalya Roy and Aryya Gangopadhyay. Analyzing the Sentiment of Crowd for Improving the Emergency Response Services, in Proceedings of the 4th IEEE International Conference on Smart Computing (SmartComp), Sicily, Italy, June 2018

Bipendra Basnyat, Amrita Anam, Neha Singh, Aryya Gangopadhyay, and Nirmalya Roy. Analyzing Social Media Texts and Images to Assess the Impact of Flash Floods in Cities, in Proceedings of the 2nd IEEE International Workshop on Smart Service Systems (SmartSys), co-located with SmartComp, pp. 1-6, May 2017



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* This research is partially supported by the National Science Foundation under Award Numbers: 1640625 &  by U.S. Army Grant No. W911NF2120076
* Howard County Public Works  
* Evigia Systems LLC
* Progeny Systems Corporation
* MachineSense, LLC

