# Image-visual-question-and-answer

This is a Streamlit app for Visual Question Answering (VQA) using the ViLT (Vision-and-Language Transformer) model. Given an image and a question, the app uses a pre-trained ViLT model to predict the answer to the question based on the contents of the image

# How to Run the App

Install the required dependencies. You can do this by creating a virtual environment and installing the dependencies from the requirements.txt file:

      pip install -r requirements.txt
      
Run the Streamlit app:

      !streamlit run app.py & npx localtunnel --port 8501
      
Once the app is running, you can access it in your web browser at **http://localhost:8501/**.

# How to Use the App

1. When you open the app, you'll see a title "Visual Question Answering with ViLT".

2. Upload an image: Click on the "Choose an image file" button and select an image from your local machine. Supported formats are JPEG and PNG.

3. Ask a question: In the text input below the image, enter a question related to the contents of the image. For example, "What animal is in the picture?".

4. Click "Enter" to submit the question.

5. The app will process the image and question using the pre-trained ViLT model.

6. The predicted answer to your question will be displayed below the image.

7. If you want to ask a new question or upload a different image, simply repeat steps 2 to 4.

# Default Image

If you do not upload an image, the app will use a default image from the COCO dataset. This default image is used to demonstrate the functionality of the app even if you don't have an image to upload.

# Model Information

The app uses a pre-trained ViLT model for Visual Question Answering. The model and processor are loaded from the "dandelin/vilt-b32-finetuned-vqa" checkpoint.

# Contact

If you have any questions, suggestions, or feedback, feel free to reach out to us:

**Email**: ceo@adople.com
