<h1>🏠 House Price Prediction System</h1>

<p align="center">
  <b>Machine Learning Project | Flask Web App | Pickle Model Deployment</b><br>
  Developed by <b>Kaamari Ramya</b>
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
This project is a <b>House Price Prediction System</b> built using Machine Learning.
It predicts the price of a house based on multiple features such as bedrooms, bathrooms,
square footage, location, and more.
</p>

<p>
The trained model is saved using a <b>pickle file (.pkl)</b> and integrated into a 
Flask-based web application for real-time predictions.
</p>

<hr>

<h2>⚙️ Tech Stack</h2>
<ul>
  <li>🐍 Python</li>
  <li>📊 Scikit-learn (ML Model)</li>
  <li>🌐 Flask (Backend)</li>
  <li>🎨 HTML & CSS (Frontend)</li>
  <li>💾 Pickle (Model Serialization)</li>
</ul>

<hr>

<h2>🧠 Machine Learning Workflow</h2>

<h3>1️⃣ Data Preprocessing</h3>
<ul>
  <li>Handled missing values</li>
  <li>Selected relevant features</li>
  <li>Converted categorical data into numerical form</li>
</ul>

<h3>2️⃣ Model Training</h3>
<ul>
  <li>Used regression algorithm (Linear Regression / MLR)</li>
  <li>Trained on housing dataset</li>
  <li>Evaluated model accuracy</li>
</ul>

<h3>3️⃣ Model Saving</h3>
<p>
After training, the model was saved using pickle:
</p>

<pre>
import pickle
pickle.dump(model, open("house_price_project1.pkl", "wb"))
</pre>

<h3>4️⃣ Model Loading in Flask</h3>
<p>
The saved model is loaded inside the Flask app to make predictions:
</p>

<pre>
model = pickle.load(open("house_price_project1.pkl", "rb"))
</pre>

<hr>

<h2>🚀 How the System Works</h2>

<ol>
  <li>User enters house details in the web interface</li>
  <li>Data is sent to Flask backend</li>
  <li>Backend processes input and feeds it to the model</li>
  <li>Pickle model predicts the house price</li>
  <li>Prediction is displayed on the UI</li>
</ol>

<hr>

<h2>📥 Input Features</h2>

<ul>
  <li>Bedrooms</li>
  <li>Bathrooms</li>
  <li>Sqft Living</li>
  <li>Sqft Lot</li>
  <li>Floors</li>
  <li>Waterfront</li>
  <li>View</li>
  <li>Condition</li>
  <li>Sqft Above</li>
  <li>Sqft Base</li>
  <li>Year Built</li>
  <li>Year Renovated</li>
  <li>City</li>
  <li>Country</li>
</ul>

<hr>

<h2>📸 Project Interface</h2>
<img width="1899" height="994" alt="image" src="https://github.com/user-attachments/assets/30b86ef6-e6e7-4016-bfe5-800d141cb837" /><h1 align="center">
</p>



<p align="center">
  Clean UI with left profile panel and right prediction form.
</p>

<hr>

<h2>📁 Project Structure</h2>

<pre>
project/
│── app.py
│── house_price_project1.pkl
│
├── templates/
│     └── index.html
│
├── static/
│     ├── css/
│     │     └── style.css
│     └── Ramya.jpg
</pre>

<hr>

<h2>▶️ How to Run the Project</h2>

<pre>
# Install dependencies
pip install flask numpy pandas scikit-learn

# Run the app
python app.py
</pre>

<p>
Open browser and go to:
<b>http://127.0.0.1:5000/</b>
</p>

<hr>

<h2>✨ Key Highlights</h2>
<ul>
  <li>✔ Real-time prediction using ML model</li>
  <li>✔ Clean and responsive UI</li>
  <li>✔ End-to-end ML deployment</li>
  <li>✔ Pickle-based model integration</li>
</ul>

<hr>

<h2>👩‍💻 About Me</h2>
<p>
<b>Kaamari Ramya</b><br>
Aspiring Data Scientist passionate about Machine Learning and building intelligent systems.
🌐Live Application : https://regression-project1.onrender.com
for support: ✉️kammariramyachary@gmail.com
  
</p>

<hr>

<p align="center">
  ⭐ If you like this project, consider giving it a star!
</p>
