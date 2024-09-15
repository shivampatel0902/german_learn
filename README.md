📘 Assignment Project: DLMDSPWP01 – Programming with Python

📑 Table of Contents
•	📄 Introduction
•	✨ Features
•	🛠 Technologies Used
•	⚙️ Installation and Setup
•	🚀 Usage
•	🗂 Project Structure
•	🌱 Git Instructions
•	👤 Contributors
•	📜 License

📄 Introduction
This project is a solution to the task for course DLMDSPWP01 – Programming with Python. The objective is to process four training datasets and one test dataset, each containing x-y pairs of values, and map them to 50 ideal functions. The program selects four ideal functions that best fit the training data using the least-square criterion. The test data is then mapped to these chosen functions based on a specific deviation threshold.

✨ Features
•	🎯 Selects four ideal functions that best fit the training data.
•	🔗 Maps test data to the chosen ideal functions based on deviation criteria.
•	📊 Visualizes the training data, test data, ideal functions, and deviations.
•	✅ Incorporates unit tests to verify program functionality.
•	🏗 Utilizes object-oriented design with inheritance and exception handling.

🛠 Technologies Used
•	Programming Language: Python 🐍
•	Libraries/Tools:
o	Pandas 📊
o	NumPy 🔢
o	SQLAlchemy 🗃
o	Bokeh 📈
o	SQLite 🗄

⚙️ Installation and Setup
1.	Clone the repository:
git clone https://github.com/yourusername/assignment-project.git

2.	Navigate to the project directory:
cd assignment-project

3.	Install the required Python libraries:
pip install -r requirements.txt


🚀 Usage
1.	Ensure the required datasets (training data, test data, and ideal functions) are available.

2.	Run the main program:
python main.py

3.	The program will load the datasets into an SQLite database, select the best fit ideal functions, map the test data, and visualize the results.

🗂 Project Structure
•	src/: Contains the source code 📂
•	data/: Contains datasets (training, test, and ideal functions) 📁
•	visualization/: Contains the visualization outputs (graphs) 📉
•	tests/: Contains unit tests for the program 🧪
•	database/: Contains the SQLite database 🗄
🌱 Git Instructions
•	To clone the develop branch:
git clone -b develop https://github.com/yourusername/assignment-project.git

•	To add and commit changes:
git add . 
git commit -m "Added new feature" 
git push origin develop

•	To create a pull request, navigate to the repository on GitHub and initiate a pull request from your branch to the develop branch.

👤 Contributors
•	Shivam Padmani - GitHub Profile
📜 License
•	This project is licensed under the MIT License - see the (LICENSE) file for details.




