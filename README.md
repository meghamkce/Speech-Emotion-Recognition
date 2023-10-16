# Speech-Emotion-Recognition
During recent years, speech recognition plays a crucial role in helping others for ease of use. Several popular 
technology companies such as Google, Samsung, and Apple have been applying speech recognition to translate 
human speech into sentences for their users to navigate through their products easily. By having speech recognition, 
it opens new branches to the research field which specifically speech emotion recognition (SER).Speech emotion recognition is a machine learning field that enables the model to classify human emotions based 
on speech itself. Emotions have several modalities that can be perceived by speech, psychological signals, facial 
expression, etc. Compared to other modalities, speech signals proves to be much more versatile and easy to acquire1
. 
In Indonesia, researches that are available about this topic is quite a few, and some of the available ones showing 
low accuracy compared to the research outside Indonesia. On the previous research that use Indonesian language, 
their data collection method relies on natural conversation in talk shows as their source of data2
. However, gathering 
data through talk shows may cost bias in terms of speaker’s lack of ability to show their fully extent emotion due to
public image and being watched by the crowds. Therefore, this paper is composed with different collection method 
which is adopted from RAVDESS rules. Data is gathered through volunteers that is being handed out with 
predetermined sentences and to be repeated per emotion. There are three classifying methods that are used in this 
research for analyzing two specified emotions (happy, sad) using SVM, Logistic Regression (LR), and Multi-Layer 
Perceptron (MLP). Predecessor research that was conducted using SVM gives an accuracy of 68.31%2
. By using 
three classification models, it will give the opportunity to compare which dataset performs better. The algorithm in 
SVM was used for classifying emotions with linear kernel. On the other hand, it could also be done in MLP which is 
one of the classes of neural networks. And lastly, LR puts into consideration as its simple capability and economic 
performance compared to the others
