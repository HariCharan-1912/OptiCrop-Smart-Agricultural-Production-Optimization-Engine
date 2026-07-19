# OptiCrop-Smart-Agricultural-Production-Optimization-Engine
##Live Link: https://opticrop-smart-agricultural-product.vercel.app/

---

```markdown
# OptiCrop: Smart Agricultural Production Optimization Engine

OptiCrop is an intelligent, self-contained agricultural optimization engine designed to bridge the gap between environmental telemetry data and precise data-driven farming decisions. By training a high-accuracy machine learning classifier core over multi-variable parameter vectors, the platform provides real-time crop recommendations, target suitability audits, and strategic resource management roadmaps for farmers, research teams, and policymakers alike.

## 🚀 System Architecture & Key Features

OptiCrop runs a clean, multi-tier execution lifecycle that decouples client-side presentation layers from core backend predictive services:

*   **Scenario 1: Predictive Crop Recommendation Engine:** Automatically evaluates local topsoil chemical balances along with micro-climate variables to output the highest-yielding crop classification match.
*   **Scenario 2: Target Suitability & Variance Auditor:** Cross-references a user-specified crop choice against real-time parameters to flag environmental compatibility mismatches and resource efficiency profiles.
*   **Scenario 3: Macro Policy & Strategy Planner:** Renders structural agro-ecological zoning limits and strategic resource management guidelines tailored for regional stakeholders.
*   **Built-in Boundary Sanitizer:** Integrates strict server-side numeric checks validating float values to safely protect the machine learning backend from out-of-range exceptions.

## 📁 Directory Structure

```text
OptiCrop/
│
├── static/
│   └── style.css            # Custom layout themes and UI tab styling definitions
│
├── templates/
│   ├── index.html           # Multi-Scenario tabbed form controls web dashboard
│   └── result.html          # Dynamic crop diagnostics and result summary panel
│
├── app.py                   # Core Flask web server, boundary validation & context router
├── train_model.py           # Multi-model evaluation script (fully optimized for Windows consoles)
├── model.pkl                # Serialized high-accuracy Random Forest classifier binary
└── requirements.txt         # Verified Python environment package dependencies mapping

```

## 🛠️ Tech Stack & Dependencies

* **Frontend Design Core:** HTML5, CSS3, JavaScript, Bootstrap v5 (CDN Layout)
* **Application Gateway Routing Engine:** Python 3.10+ / Flask Micro-framework
* **Data Science & Inference Tools:** Scikit-Learn, Pandas, NumPy
* **Model Storage Persistence Layer:** Serialized Python Pickle Stream (`model.pkl`)

## 💻 Local Workspace Run Instructions

### 1. Pre-requisites

Ensure you have an environment configuration containing Python 3.10 or higher. An **Anaconda distribution installation** is strongly recommended for clean dependency wheel sandboxing.

### 2. Isolate & Setup the Virtual Workspace

Open your preferred terminal console workspace within your IDE (e.g., VS Code) and run the following commands to activate your environment and install package wheels:

```bash
# Activate your base Anaconda command prompt mapping layer
C:\Users\haric\anaconda3\Scripts\activate

# Install required analytics and server dependencies cleanly
python -m pip install --no-cache-dir -r requirements.txt

```

### 3. Compile the Machine Learning Core Pipeline

Execute the evaluation matrix model engine script. This trains and compares four distinct algorithmic layers (Logistic Regression, KNN, Decision Tree, and Random Forest), selected by accuracy score boundaries, and compiles the persistent weights store:

```bash
python train_model.py

```

*Note: The script prints out the respective algorithmic leaderboard metrics and outputs a clean text confirmation upon generating `model.pkl` to safeguard local deployment workflows against encoding exceptions.*

### 4. Boot up the Live Web Service Engine

Start the local WSGI server daemon loop:

```bash
python app.py

```

### 5. Access the Web Application

Open any modern web browser interface window and navigate to the loopback local server gateway address:

```text
[http://127.0.0.1:5000/](http://127.0.0.1:5000/)

```

## 📊 Evaluation & Verification Results

During training evaluation sweeps, the comparative pipeline scores historical target patterns cleanly, yielding competitive accuracies across configurations:

* **Logistic Regression Pipeline:** 65.33%
* **K-Nearest Neighbors Core:** 51.67%
* **Decision Tree Architecture:** 94.00%
* **Random Forest Ensemble:** **96.00%** *(Selected & Serialized)*

By processing data vectors locally via native NumPy structures rather than setting up heavy external cloud network lookups, the execution engine delivers rapid response turnarounds with an average system inference speed under **400 milliseconds**.

## 🔮 Scalability Future Roadmap

* **IoT Field Device Integrations:** Construct direct REST API hooks to receive live, automated macro telemetry feeds from physical NPK field hardware sensors.
* **Automated Climate Broadcast Sync:** Connect input variables directly to live environmental forecasts via automated OpenWeatherMap engine API pipelines.
* **GIS Layout Visualizer:** Implement interactive satellite geospatial maps directly into the Scenario 3 system analytics console layer.

---

*Developed by Haricharan as part of the SmartBridge Skill Wallet Milestone Projects Evaluation Program (2026).*

```

```
