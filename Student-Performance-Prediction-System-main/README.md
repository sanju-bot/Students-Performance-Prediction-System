# Student Performance Prediction System

A machine learning-based system that predicts student academic performance (Pass/Fail) using **Logistic Regression**. The model analyzes key academic indicators to forecast final exam outcomes with real-time prediction capabilities.

## 📋 Features

- **Machine Learning Model**: Logistic Regression classifier
- **Real-time Predictions**: Instant pass/fail predictions for new students
- **Performance Metrics**: Detailed accuracy scores and classification reports
- **Data Visualization**: Generates prediction plots for visual analysis
- **Interactive Interface**: User-friendly input system for student performance prediction
- **High Accuracy**: 100% accuracy on test dataset

## 🔧 Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib

## 📦 Installation

1. Clone this repository:
```bash
git clone https://github.com/sanju-bot/Students-Performance-Prediction-System.git
cd Students-Performance-Prediction-System
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install pandas scikit-learn matplotlib
```

## 🚀 Usage

Run the main script:
```bash
python main.py
```

The program will:
1. Load the student dataset
2. Train a Logistic Regression model
3. Display model accuracy and classification report
4. Prompt you to enter student performance data:
   - Study Hours
   - Attendance (%)
   - Previous Marks
   - Assignments Score
   - Internal Marks
5. Generate a prediction (Pass/Fail)
6. Save a visualization as `prediction_plot.png`

## 📊 Model Details

### Features Used:
- **Study Hours**: Number of hours spent studying
- **Attendance**: Class attendance percentage
- **Previous Marks**: Marks from previous exams
- **Assignments**: Assignment submission scores
- **Internal Marks**: Internal assessment marks

### Model Performance:
- **Accuracy**: 100%
- **Precision**: 1.00 (both classes)
- **Recall**: 1.00 (both classes)
- **F1-Score**: 1.00 (both classes)

## 📁 File Structure

```
Students-Performance-Prediction-System/
│
├── main.py                    # Main script with model training & prediction
├── Student_data.csv           # Dataset containing student information
├── prediction_plot.png        # Output visualization
└── README.md                  # This file
```

## 📈 Dataset Format

The `Student_data.csv` file should contain the following columns:
- `Study_Hours` (float): Hours spent studying
- `Attendance` (float): Attendance percentage (0-100)
- `Previous_Marks` (float): Marks from previous exams
- `Assignments` (float): Assignment scores
- `Internal_Marks` (float): Internal assessment marks
- `Final_Result` (string): "Pass" or "Fail"

## 💡 Example Prediction

**Input:**
- Study Hours: 5
- Attendance (%): 85
- Previous Marks: 75
- Assignments Score: 80
- Internal Marks: 78

**Output:**
- **Prediction Result**: Pass ✓
- **Visualization**: Saved as `prediction_plot.png`

## 🔍 How It Works

1. **Data Loading**: Loads student performance data from CSV
2. **Data Preprocessing**: Converts categorical target variable to numerical (Pass=1, Fail=0)
3. **Feature & Target Separation**: Splits data into features (X) and target (y)
4. **Train-Test Split**: Divides data into 80% training and 20% testing
5. **Model Training**: Trains Logistic Regression on training data
6. **Evaluation**: Tests model accuracy and generates classification report
7. **Prediction**: Takes user input and predicts student performance
8. **Visualization**: Generates and saves performance plot

## 🛠️ Technologies Used

- **Python**: Programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning library
- **Matplotlib**: Data visualization

## 📝 Future Enhancements

- Add more classification models (Random Forest, SVM, etc.)
- Model comparison and ensemble methods
- Web interface for easier access
- Database integration for student records
- Batch prediction from CSV files
- Performance trend analysis

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Sanjay** - [GitHub Profile](https://github.com/sanju-bot)

## 📧 Contact

For questions or suggestions, please contact via GitHub Issues.

## 🙏 Acknowledgments

- Built with scikit-learn for machine learning
- Dataset structure inspired by real educational systems
- Community support and contributions welcome

---

**Last Updated**: May 6, 2026
