# Pneumonia-Detection

Throughout our pneumonia prediction project, we employed a diverse array of technologies and techniques to 
enhance the accuracy and efficacy of our diagnostic model. We commenced by constructing a simple Convolutional 
Neural Network (CNN) to analyze chest X-ray images, achieving an initial accuracy of 75.96%. Recognizing the 
potential for improvement, we explored data augmentation to diversify our training set and employed bagging to 
aggregate predictions from multiple CNN models, resulting in an ensemble accuracy of 87.0%. Subsequently, we 
harnessed the power of Adaptive Boosting (AdaBoost) to refine our model, yielding an accuracy of 75.48%. We then 
integrated gradient boosting with CNN outputs, achieving a model accuracy of 75.8%. Transitioning to transfer 
learning, we leveraged the pre-trained DenseNet121 architecture, obtaining a test accuracy of 79.49%. Our journey 
encompassed a blend of deep learning methodologies, ensemble techniques, and transfer learning, showcasing the 
iterative nature of model development and the iterative nature of model development and the multifaceted 
approaches required to address complex medical diagnostic challenges. Through these efforts, we've demonstrated 
the potential of advanced machine learning techniques in aiding medical professionals in pneumonia diagnosis, 
underscoring the importance of continual innovation and refinement in healthcare technology

### How to Build and Run

1. **Build the Docker image:**
   ```bash
   docker build -t streamlitPn .

2. **Run the container (choose a port):**
   ```bash
   docker run -p 8501:8501 streamlitPn


3. **Access the web application: Open your browser and visit:**
   ```bash
   http://localhost:8501
