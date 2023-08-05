# Math Operations API

This is a simple Flask API that performs basic math operations such as addition, subtraction, multiplication, and division. The API can be called through a web interface or via Postman/SoapUI.

## Getting Started

To get started with this API, follow the instructions below:

### Prerequisites

- Python 3. x
- Flask

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/syedshahlal/flask_test.git
   cd flask_test.git

2. Install the required dependencies using pip:

   ```bash
   pip install -r requirements.txt

### Usage

1. Run the Flask application:

   ```bash
   python app.py

2. The application will start running on http://127.0.0.1:5000/.

3. Open your web browser and navigate to http://127.0.0.1:5000/ to access the web interface.

4. Enter the numbers and select the operation from the dropdown to perform the math operation.

5. To call the API programmatically using Postman or SoapUI, use the following endpoint:

   ```Arduino
   POST http://127.0.0.1:5000/via_postman

  Provide the input in JSON format with the following keys:

  * operation: The type of math operation (e.g., 'add', 'subtract', 'multiply', 'divide').
  * num1: The first number for the operation (integer).
  * num2: The second number for the operation (integer).
  
  Example JSON request:
    
    {
    "operation": "add",
    "num1": 10,
    "num2": 5
    }
  The API will respond with the result in JSON format.
  
### Endpoints
  *  GET/POST http://127.0.0.1:5000/: Homepage to render the math operations web interface.
  *  POST http://127.0.0.1:5000/math: Endpoint called from the web interface to perform math operations.
  *  POST http://127.0.0.1:5000/via_postman: Endpoint for calling the API programmatically using Postman/SoapUI.
### Contributing
  Contributions are welcome! If you find any issues or have improvements to suggest, feel free to open an issue or submit a pull request.
  
### License
  This project is licensed under the MIT License - see the LICENSE file for details.
  
### Acknowledgments
  * This project was inspired by the need for a simple math operations API for educational and practice purposes.
  * Thanks to Flask for providing a simple and lightweight framework for building web applications.  
    

   
   
