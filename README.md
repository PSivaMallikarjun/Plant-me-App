# Plant Me AI

## Overview
Plant Me AI is an AI-powered web application that analyzes deforestation-prone areas using satellite imagery and predicts optimal locations for drone-based seed and sapling dispersal. The app utilizes machine learning techniques, including KNN clustering, to improve prediction accuracy over time.

## Features
- **Satellite Image Analysis:** Detects deforestation-prone areas.
- **AI-Driven Predictions:** Suggests optimal locations for seed-dropping.
- **Drone Integration:** Enables automated seed dispersal.
- **Gradio UI:** Provides an interactive and user-friendly interface.
- **Self-Trained Model:** Improves with fine-tuning and clustering (KNN-based optimization in future versions).
- **Deployed on Hugging Face Spaces** for free hosting and GPU acceleration.

## Technologies Used
- **Python** (Google Colab for development)
- **OpenCV (cv2)** for image processing
- **NumPy & Matplotlib** for data analysis and visualization
- **TensorFlow & PyTorch** for model training and predictions
- **Gradio** for web interface
- **Hugging Face Spaces** for deployment

## Installation
To run the project locally:
```bash
pip install gradio opencv-python numpy tensorflow torch torchvision pillow matplotlib
```

## Running the App
Execute the following command in your terminal:
```bash
python app.py
```
Or deploy directly to Hugging Face Spaces using:
```bash
gradio deploy
```
https://huggingface.co/spaces/SivaMallikarjun/PlantMeAI
## Future Enhancements
- Implement **KNN clustering** for better predictions.
- Train the model on **larger datasets** for improved accuracy.
- Integrate **real-time satellite feeds** for dynamic analysis.
- Add **weather-based adaptive seeding algorithms**.

## Contributing
We welcome contributions! Feel free to fork the repo and submit pull requests.

## License
This project is licensed under the MIT License.

---
💡 *Let's combat deforestation with AI-driven solutions!* 🌱🚀

![Screenshot 2025-03-20 002654](https://github.com/user-attachments/assets/aa6bc8f4-5391-401b-9278-b773cbd4fc45)

![Screenshot 2025-03-20 002702](https://github.com/user-attachments/assets/2bee6246-c245-4453-abf8-79bf9b4b2c61)

![Screenshot 2025-03-20 001945](https://github.com/user-attachments/assets/e70c15e5-973f-4e44-b327-90e60a52dfef)


