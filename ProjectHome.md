For an effective disaster management system the faster and the accurate  data collection is essential. The data capered in forms have to reentered manually adding an additional step and potential bottleneck for the processing of information. Handwritten Character Recognition(HCR) technology can be used to automate this process to a great extend.
Two algorithms for Optical Character Recognition are, feature extraction method using traditional artificial intelligence techniques for classification, and neural network approach with virtually no pre-processing.
Goal of my project is developing a more accurate and robust system for character recognition, integration with Sahana database and capture the data entered on a XHTML form. The documents should be structured in accordance with well defined layouts for an error free data capturing using HCR based approach. The data then write to a XML file which can be easily feed into the respective Sahana Web Form.


Detailed Description

The feature point extraction algorithm is to identify characters based on features that are somewhat similar to the features humans use to identify characters. It follows image preprocessing, feature extraction (to create the vector of features) and then classify the obtained feature vectors to train the system.
The Artificial neural net (ANN) approach, translated the binary character data into a friendlier form, take the output  and trained a backpropagation network on it, outputting all the resulting weights and general network information. It then ran a full character set through the network and output identification information for all the characters the set contained.
Both methods cannot be optimised separately. The best method would be something that combined both approaches. Although the current network was trained on the full character data, it would be relatively easy to train a set on just the extracted feature data. The combined approach would maintain the desirable feature of the feature extraction method of generally making human-like mistakes while keeping the neural net method's identification speed. Careful adjustments to both the network's topography and the feature extraction process could radically improve the accuracy.
Using client side technologies, XHTML, JavaScript and CSS use to read the required XHTML DOM elements on the Web form. Identify the outer marks of the page and Extraction of the required components (XHTML elements) from the active Web form and  the recognition of handwritten characters in forms are the is a key challenges in this project. XML is a one extension of PHP which makes it simple to work with XML, whether it be reading from or writing to an XML document. After identifying the characters the results can be write to an XML file an then data  feed into the respective Sahana Web Form.


Project Plan

1.	Getting familiar with Artificial Neural Networks (FANN library),XML,  PHP. Then get familiar with the existing OCR code and research for how to improve the accuracy, robustness, integration with Sahana database and make user friendliness.
Estimated Completion: 30 May 2008
2.	Dvelop accurate method for accurate character recognition and Extraction of the required components (XHTML elements) from the active Web form l
Estimated Completion: 28 June 2008
3.	recognition of handwritten characters and the results are written to an XML file and feed data to a sahana web form.
Estimated Completion: 01 August 2008
4.	Testing, refactoring code and documentation
> Testing code.
> Fix bugs and refractor code solve other issues
> Documentation.
Estimated Completion: 12 August 2008

5.	Finalizing product
> Estimated Completion: 20 August 2008


Biography

> I'm a Level 4 student in Department of Electronic and Telecommunication Engineering of University of Moratuwa, Sri Lanka. I just finished my final year exam and now completing the final year project. My final year project is, Implementing Real time Red light violation system at an intersection using Image Processing and Computer Vision techniques. C++ and OpenCV libries are used for that. I implement a multiple object tracking algorithm, which is based on feature tracking, for the project. So I have lot more experience in working with C++ and openCV. Also I have worked and got lot of experience in doing C++ threading, database handling, various segmentation methods, motion segmentation, template matching, tracking algorithms and some more features.
> > In addition to C++ and OpenCV, I have used and familiar with many other technologies such as JAVA, PHP, JavaScript, C#.Net and database technologies such as MySQl and Microsoft SQl server.
I'm very interesting in Image Processing and Computer Vision. I have developed Optical Character Recognition code in Matlab. Currently i’m doing a research on multiple object tracking.
> > So I think I have gained sufficient knowledge for doing this project task. I'm really interested in developing open source applications and localization of open source products. I hope this year Google Summer of code will give me a better opportunity to involve with open source community and I will give my best commitment to the development of open source community.
Important Links
1. University of Moratuwa : http://www.mrt.ac.lk
2. Department of Eelectronic & Telecommunication Engineering : http://www.ent.mrt.ac.lk