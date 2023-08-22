# Speech_To_ASL

## **Description**
This project aims to bridge the gap and overcome limitations for individuals with speech or hearing impairments, enabling enhanced interaction and reducing communication barriers. By connecting people through sign language, the project strives to eliminate distances and ensure seamless communication within their environment. The project focuses on transforming human speech into text and subsequently generating American Sign Language (ASL) videos. The speech-to-text transformation employs a pretrained model, wav2vec. 

The dataset utilized in this project is sourced from https://www.kaggle.com/datasets/risangbaskoro/wlasl-processed. Through this initiative, the goal is to foster inclusivity and improved interaction for all individuals within society.

## **Project Code:**
Steps:
1. Define Problem
2. Installing needed Libraries
2. Data Collection
4. Data Pre-Processing
   - Normalization
   - Noise Cancelation
   - Speech to Text 
   - Text Processing
   - Labeling
5. Feature Extraction
6. English to WLASL
6. Display WLASL
7. Conclusion

## **Installation**
1. Clone the repository: `git clone https://github.com/Lexuz17/Speech_To_American_Sign_Language.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Obtain Kaggle API Key:
    - Create a Kaggle account and navigate to the 'Account' tab.
    - Scroll down to the 'API' section and click on 'Create New API Token'. This will download a JSON file containing your API key.
    - Place the downloaded JSON file in the project directory.

## **Results and Findings**
Here are the results and key findings from this project:
1. **ASL Sentence Generation and Grammar:** Transforming text to ASL involves considering ASL grammar for accurate translation, requiring attention to grammar rules to ensure meaningful content.
2. **Dataset Quality and Video Errors:** Dataset contained error-prone videos due to deletions. Rigorous data validation is crucial to prevent errors and ensure a complete dataset.
3. **Effective Speech-to-ASL Conversion:** Models showed promise in converting speech to text and generating fitting ASL videos. Accurate translation and video production were achieved.

In conclusion, this project presents promising results in bridging the communication gap through the transformation of human speech into American Sign Language. The findings indicate the potential for real-world applications to enhance inclusivity and interaction for individuals with hearing impairments.

## Contact
For any questions or inquiries, please contact jason.susanto1703@gmail.com
