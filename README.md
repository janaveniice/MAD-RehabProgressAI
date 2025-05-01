# MAD Rehab Progress Speed AI
This **logistic regression model** predicts the user's rehab progress speed based on the following details
1. Age
2. Number of exercises
3. Total exercise duration (in days)
4. Exercise adherence (in %)

After training, the model was converted to an ONNX and optimized for mobile application deployment. <br>
This model was built as a part of RehabMate, a mobile application for personalized and accessible rehabilitation.

## Set Up
### **1. Create virtual environment**
```bash
python -m venv myenv
```

### **2. Acitvate virual environment**
```bash
myenv\Scripts\activate
```

### **3. Install required packages**
```bash
pip install -r requirements.txt
```

### **4. Select virtual environment as interpreter**
1. Ctrl+Shift+P
2. Search for `Python: Select Interpreter`
3. Select `Python 3.12.x ('myenv')`