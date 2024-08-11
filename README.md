# Sales Forecasting System

## Developed by Wajson Geoffrey Musa

### Project Overview

This Sales Forecasting System is a web-based application that uses machine learning techniques to predict sales based on historical data. The system combines unsupervised learning (K-means clustering) with supervised learning (Random Forest Regression) to provide accurate sales predictions.

### Features

- Data preprocessing and cleaning
- Feature engineering from order dates
- K-means clustering for pattern recognition
- Random Forest Regression for sales prediction
- Web-based user interface for easy interaction
- Real-time sales forecasting based on user input

### Technologies Used

- Python 3.x
- Flask (Web Framework)
- Pandas (Data Manipulation)
- Scikit-learn (Machine Learning)
- HTML/CSS (Frontend)

### Installation

1. Clone the repository:


### Usage

1. Ensure your sales data is in a CSV file named `sales_data.csv` in the project root directory.

2. Run the Flask application:


3. Open a web browser and go to `http://localhost:5000`

4. Input the required information and click "Forecast Sales" to get a prediction.

### Project Structure

- `app.py`: Main Flask application
- `templates/`: HTML templates for the web interface
- `sales_data.csv`: Historical sales data (not included in repository)

### Data Requirements

The `sales_data.csv` file should include the following columns:
- Order Date
- Order Quantity
- Discount %
- Shipping Cost
- Total (target variable)

### Future Improvements

- Implement more advanced time series analysis
- Add data visualization features
- Integrate with real-time data sources
- Implement user authentication for secure access

### Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Contact

For any queries or suggestions, please contact:
Wajson Geoffrey Musa
Email: geoffreymusa08@gmail.com
LinkedIn: https://www.linkedin.com/in/geoffrey-wajson-8b1411189/

