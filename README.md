# Extract_text_NER
Automated Intelligent Web app to extract Entities from Document - Business Card
# Project Objectives

The main objectives of the project are as follows:

a) Develop a user-friendly web application that allows users to upload documents and extract text and data from them.
b) Implement advanced OCR algorithms to accurately recognize and extract text from documents of different formats, including PDF, images, and scanned documents.
c) Utilize NLP techniques to extract structured data, such as names, designations, phone numbers, and other relevant information, from the extracted text.
d) Provide a clean and intuitive user interface to visualize and review the extracted information, allowing users to make necessary edits and corrections.
e) Ensure scalability and performance of the web application to handle a large volume of document uploads and extractions concurrently.

## Key Features

The proposed web application will include the following key features:

a) **Document Upload:** Users will be able to upload documents in various formats, including PDF, images, and scanned documents.
b) **Text Extraction:** Advanced OCR algorithms will be employed to extract text from the uploaded documents accurately.
c) **Data Extraction:** NLP techniques will be utilized to identify and extract structured data such as names, addresses, dates, and other relevant information from the extracted text.
d) **Data Visualization:** The application will provide an intuitive user interface to visualize the extracted data, allowing users to review and make necessary edits or corrections.
e) **Security and Privacy:** Robust security measures will be implemented to protect user data and ensure compliance with privacy regulations.

## Deliverables

The following deliverables are expected upon the completion of the project:

- Fully functional web application for intelligently extracting text and data from business card images.
- Trained NER model capable of accurately recognizing entities on business cards.
- User-friendly interface for uploading business card images, reviewing and editing extracted information, and visualizing the recognized entities with bounding boxes.
- Detailed documentation providing guidelines for deploying, maintaining, and extending the web application.
- Training data, code repository, and project documentation for future reference.

## Existing Models and Limitations

There are different existing models to extract data from images. While existing models and techniques for business card entity recognition using computer vision can be effective, they also have some limitations and disadvantages. Here are a few:

- **Accuracy:** One of the main challenges with existing models is achieving high accuracy, especially when dealing with different types of business cards, variations in fonts, layouts, and image quality. Existing models may struggle with accurately extracting and recognizing all the entities on business cards, leading to errors and inaccuracies.
- **Limited Domain Knowledge:** Existing models are typically trained on generic datasets and may not have specific domain knowledge related to business cards. This can result in difficulties in accurately recognizing specialized information like job titles, company names, or industry-specific terms.
- **Sensitivity to Image Quality:** The performance of existing models heavily depends on the quality of the input images. Poor image quality, low resolution, blurry or distorted text, or unusual card designs can significantly impact the accuracy of the models, leading to incorrect entity recognition.
- **Lack of Generalization:** Existing models may struggle to generalize well to new or unseen business card layouts or languages that they were not specifically trained on. This limits their ability to handle diverse business card designs and multilingual text recognition.
- **Time and Resource Requirements:** Some existing models, particularly deep learning models, can be computationally expensive and require significant computational resources for training and inference. This can be a limitation in terms of deployment and scalability in a web app environment.
- **Need for Annotated Training Data:** Training accurate and robust business card entity recognition models often require large amounts of annotated training data. Collecting and labeling such data can be time-consuming and resource-intensive.
- **Customization and Fine-tuning:** Existing models may not be easily customizable or adaptable to specific business requirements or user preferences. Fine-tuning or retraining existing models to improve accuracy or handle specific use cases may require additional effort and expertise.

We assume we will be able to address these disadvantages and limitations in this project.

## Primary Focus

The primary focus is given to the following entities of a business card:

1. Person Name
2. Designation
3. Organization/University/College
4. Phone
5. Email
6. Website/URL

![image](https://github.com/athirakjayan/Extract_text_NER/assets/26280977/268abbd4-3c42-4a08-958b-71447b85f595)
