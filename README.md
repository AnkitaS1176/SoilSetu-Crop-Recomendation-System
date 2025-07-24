# 1. Create workspace & go inside
mkdir SoilSetu; cd SoilSetu

# 2. Create venv
python -m venv .venv

# 3. Activate venv
.\.venv\Scripts\Activate

# 4. Unzip OR clone repo
# unzip project.zip 
# git clone <repo_url> .

# 5. Install deps
pip install --upgrade pip
pip install -r requirements.txt

# 6. Run the Flask app
python app.py
<img width="1024" height="1024" alt="Google_AI_Studio_2025-07-24T14_56_59 160Z" src="https://github.com/user-attachments/assets/08c2948e-0f39-458b-9ceb-4c3a7a31d887" />

🚀 How to Use
For Crop Recommendation:
Navigate to the "Crop Recommendation" section.
Enter the values for N, P, K, temperature, humidity, pH, and rainfall.
Click the "Recommend" button to see the suggested crop.
For Disease Prediction:
Go to the "Disease Prediction" section.
Upload an image of a plant leaf.
The model will analyze the image and display the predicted disease.[7]
For Soil Fertility Check:
Select the "Soil Fertility" tab.
Input the N, P, and K values of your soil.
The system will provide an analysis of your soil's fertility status.

📊 Datasets
Crop Recommendation: The model was trained on an augmented dataset combining rainfall, climate, and fertilizer data for various crops.[2] You can find a similar dataset on Kaggle.
Disease Prediction: The disease prediction model was trained on the PlantVillage Dataset, which contains thousands of images of healthy and diseased plant leaves across numerous species.[3]
📈 Future Scope
Incorporate a fertilizer recommendation system based on soil nutrient deficiencies.
Integrate real-time weather data using APIs.
Expand the disease prediction model to cover a wider variety of plants and diseases.
Provide detailed information and potential remedies for detected diseases.
🤝 Contributing
Contributions are welcome! If you have ideas for improvements or want to fix a bug, please feel free to open an issue or submit a pull request.
