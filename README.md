# AI-Case-Study

## Overview and Origin

* Affectiva is an artificial intelligence software development company that specializes in processing human emotions and cognitive states by analyzing facial and vocal expressions.
  
* Affectiva was incorporated in 2009 by founders Dr. Rana el Kaliouby and Dr. Rosalind Picard as a spin out of the MIT Media Lab. It was acquired by Smart Eye on May 25,<sup>th</sup> 2021 for $73.5 million [^1]

* The company was founded on the idea or principle of humanizing technology to improve the interaction or experience between humans and machines. 

* Affectiva was provided with $53 million in funding by the following venture capital investors: Kleiner Perkins Caufield Byers, Horizon Ventures, Fenox Venture Capital, and WPP [^2]

## Business Activities

* The world is now saturated with smart devices and advanced AI systems, which have afforded humanity amazing cognitive achievements. Unfortunately, most of these technologies don't always provide the same potential for advancement in emotional intelligence (EQ). Affectiva's goal is to solve this problem or gap between IQ and EQ by designing AI systems that can create empathetic interactions with humans.

* The benefits of imbuing AI with emotional intelligence are applicable in many different fields; however Affectiva's targeted base are consumers in automotive safety, advertising, entertainment, and participants in online or in-person quality research. Affectiva reports utilizing a global dataset of over 14 million videos collected from 90 countries. Their Media Analytics solutions are used by 90 percent of the world's largest advertisers, and 26 percent of Fortune Global 500 companies.

![Affectiva's dataset](images_folder/data-from-90-countries-min.png)

* A key component that makes Affectiva's approach to Emotion AI unique stems from the company pioneering the field of emotion analytics as a result of cofounder Rana el Kaliouby's desire to use "Affective Computing" to provide individuals with autism the tools to better comprehend our sensory world, while meeting the academic and financial demands of MIT's Media lab. Similarly, many other Emotion AI companies have implemented complex multi-modal deep learning and generative systems to capture emotion through a variety of methods including facial expressions, tone of voice, environmental factors, social setting, and cultural context. However, Affectiva differs by being one of the first companies to illustrate how the desire to improve communication and human understanding can be beneficial across multiple sectors.[^3][^4]

* Machine Learning Models based on Deep Learning are the primary technological approaches Affectiva uses to capture human emotion through artificial intelligence. Some primary ways human emotion and cognitive states are expressed are through facial expressions and vocal tonality. There is a large variety of human expression and vocal tonality. In addition, these expressions or tones are constantly changing or adapting to new stimuli. This creates a complex problem that requires an algorithm that uses deep neural networks to analyze, classify, segment, and model this evolving data by automatically extracting features of the data to guide the learning process. Affectiva uses the following two deep learning architectures to accomplish this task:
  
  1. Convolutional Neural Networks (CNN)
     - Multi-task (multi-attribute) networks for both regression and classification
     - Region proposal networks
  2. Recurrent Neural Networks (RNN)
     - Long Short-Term Memory (LSTM)
     - Deep Recurrent Non-Negative Matrix Refactorization (DR-NMF)
     - CNN + RNN nets [^5]

## Landscape

* Emotion AI is a subcategory with the field of the Facial and Speech Recognition Technology popular in culture first through science fiction but more notably through the advent of smart phones, smart homes, and voice assistants.

* Facial Recognition Systems are based on proprietary algorithms that perform three basic functions:
  1. Detection - process of finding a face, not necessarily an identity.
  2. Analysis - maps the face by measuring eyes, shape of chin, distance between nose and mouth, and then converts that into a string of numbers or points to create a "faceprint".
  3. Recognition - the attempt to verify a person's identity for security purposes.[^6]
 
* Speech Recognition Systems are also based on various algorithms and computation techniques to recognize speech and turn it into an accurate text transcript. Here are a list of the some of the methods used:
  1.  Natural Language Processing (NLP) - interaction between humans and machines through speech and text.
  2.  Hidden Markov Models - allows coders to incorporate part-of-speech tags into a probabilistic model. Each sequenced model within speech recognition is assigned a label for further mapping and the determination of the appropriate label sequence.
  3.  N-grams - assigns probability to sentences or phrases.
  4.  Neural Networks - mimics the interconnectivity of the human brain through layers of nodes. Each node is made up of inputs, weights, a bias (or threshold), and an output. If output exceeds a given threshold, it "fires" or activates the node, passing data to next layer in the network.
  5.  Speaker Diarization - an algorithm identifies and segments speech by speaker identity.[^7]

* Below is an example of OpenAI's Whisper, an open-source automatic speech recognition model that shows how large and diverse datasets containing multiple languages and tasks are transcribed into text by an end-to-end approach using an encoder-decoder transformer:
 
  ![OpenAI Speech Processing](images_folder/asr-summary-of-model-architecture-desktop.svg) [^8]

      
* A common trend in the field of Emotion AI havs been to utilize sensory data to better understand and predict human behaviors. This type of data analytics is in high demand for the advertising/retail, entertainment, automotive, and behavioral research sectors. Several other companies in this field include Realeyes, Noldus, and Cognovi Labs.[^9]

## Results

* Affectiva has had a major impact on automotive safety, advertising, and the entertainment business, where a large part of a company's success is based on the ability to tell a brand-related story that will resonate with consumers. Affectiva has been at the forefront of providing organizations with a way to measure and gauge large data sets comprised of how audiences and consumers' feel or react to specific content. This insight has been used to improve brand experiences and communication to better the connection with customers and positively impact profits and margins.

* Accuracy and real time estimates of emotions are some of the metrics at the core of Affectiva's deep learning models, in order to provide useful insight on consumer's emotional response to certain brands and content. Their approach to speed and accuracy involves the following:
  -  Joint-training with shared layers between models (multi-tasking learning)
  -  Iterative benchmarking/profiling of on-device performance
  -  Model compression: training compact models from larger models
 
  ![Affectiva's Metrics](images_folder/DeepLearningSpeedVsAccuracy.png)

* Affectiva's solutions and products are comparable to those provided by other Emotion AI companies, particulary in the categories of Visual and Conversation AI. Their software provides facial coding, eye tracking, emotion recognition, audio tonality, text sentiment, custom reporting, and a customer engagement score.[^10]

## Recommendations

* As a consultant or advisor it is always a challenge to determine how well a software integrates with another application, especially given the complexity of Affectiva's multi-modal emotion perception system. I would recommend the company provide more information on its API metrics. Affectiva has already rolled out a Software Development Kit (SDK) which provides the technology needed to assist developers with integrating technology onto apps and browsers; however, it would be beneficial to offer additional products or services to assist integration for smaller organizations with less technological capabilities. By allocating more resources to address social concerns and increasing accessibility and efficacy with their SDKs, Affectiva could extend their exploration of how emotion analytics can help facilitate humanity's desire understand one another and create meaningful connections in this new digital frontier.[^11]


[^1]: https://www.businesswire.com/news/home/20210525005790/en/Smart-Eye-Acquires-Affectiva-to-Solidify-Stronghold-on-Interior-Sensing-Market 
[^2]: https://www.affectiva.com/about-affectiva/
[^3]: https://koablog.wordpress.com/2015/10/20/an-origin-story-affectiva/
[^4]: https://pubmed.ncbi.nlm.nih.gov/17312261/
[^5]: https://www.affectiva.com/deep-learning/
[^6]: https://www.nytimes.com/wirecutter/blog/how-facial-recognition-works/
[^7]: https://www.ibm.com/topics/speech-recognition
[^8]: https://openai.com/research/whisper
[^9]: https://www.ventureradar.com/keyword/Emotion%20AI
[^10]: https://deepanshugahlaut.medium.com/top-emotion-ai-companies-to-watch-out-for-in-2023-db925868fd9f
[^11]: https://www.affectiva.com/news-item/affectiva-launches-an-sdk-to-bring-emotion-tracking-to-mobile-apps/


