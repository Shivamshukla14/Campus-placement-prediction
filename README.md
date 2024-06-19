# Campus-placement-prediction

**Predict your campus placement chances!**

This Flask app leverages a trained Random Forest machine learning model (**accuracy: 93%**), enabling you to estimate your likelihood of securing a campus placement.

**Features:**

- User-friendly web interface for seamless interaction.
- Robust Random Forest model trained on relevant data.
- Clear prediction display with both placement outcome and probability.

**Installation:**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Shivamshukla14/Campus-placement-prediction.git
   ```
2. **Create a Virtual Environment (Recommended):**
   This isolates project dependencies and avoids conflicts. Instructions vary depending on your environment:
    - Python `venv`: `python -m venv <venv_name>`
    - Virtualenv: `virtualenv <venv_name>`
3. **Activate the Virtual Environment:**
   ```bash
   source <venv_name>/bin/activate  # Linux/macOS
   <venv_name>\Scripts\activate.bat  # Windows
   ```
4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

**Usage:**

1. **Run the Application:**
   ```bash
   python app.py
   ```
2. **Access:**
   Open http://127.0.0.1:5000/ in your web browser.

**Input:**

Enter the requested information on the web page, including:

- Gender
- Specialization
- Technical Skills
- Work Experience
- Marks (SSC, HSC, MBA - if applicable)

**Output:**

The app will display the predicted placement outcome (placed or not placed) along with the corresponding probability (rounded to two decimal places) based on the model's prediction.

**Model:**

- This app utilizes a trained Random Forest model stored as `campusplacementpredictor.pkl` .
- The model achieves an accuracy of **93%**, indicating its effectiveness in placement prediction based on the training data.

**Considerations:**

- For enhanced robustness, consider incorporating error handling and more informative user feedback.
- Security measures are crucial for public deployment.
- The model's accuracy reflects the quality of the training data. It's a valuable tool for estimation, but real-world placements may involve additional factors.

**Disclaimer:**

This application serves as a demonstration tool. The actual placement decision-making process might involve additional criteria beyond the scope of this model.
