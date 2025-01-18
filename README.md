#Alzheimers' AI Espy

##A web based application for alzheimers' disease detection

###Introduction

Alzheimer’s AI Espy is a user-friendly website designed to enhance the detection of Alzheimer’s disease while addressing delays in appointments and improving healthcare accessibility. The platform streamlines appointment booking with an intuitive interface, eliminating human coordination and reducing wait times. Clinicians can securely upload medical images for disease detection and prescriptions, enabling precise diagnoses and personalized care.

Alzheimer’s disease (AD), a progressive form of dementia, leads to cognitive and behavioral impairments that disrupt daily life. While current treatments cannot cure AD, early detection can mitigate its progression and enhance quality of life. With the number of Alzheimer’s cases expected to double by 2050, innovative solutions like Alzheimer’s AI Espy are crucial for improving patient outcomes.

###Objective 

* To provide a fast, accurate, and affordable way of diagnosing Alzheimer's disease using deep
learning models

* To increase the awareness and understanding of Alzheimer's disease among the general
public and the medical community

* To empower the patients and their caregivers to take charge of their health and well-being by
providing them with tailored advice and support.

####Project Architecture

![Screenshot 2025-01-18 181340](https://github.com/user-attachments/assets/c77c95d0-e471-4be9-a86f-6bf5b6c5433e)

####Tech Stack 

* Python (language)
* TensorFlow (Machine learning framework for building neural network)
* Keras (Deep learning framwork to import pretained models)
* NumPy (Numerical computing library to perform calculations)
* Matplotlib (Data visualization library to show accuray, loss curves)
* Flask (Python web framework for building web applications)
* HTML/CSS JavaScript (Web dev technologies used for the front-end of the application)
* MySQL (Relational DBMS used to store and manage data)
* XAMPP (Open-source server environment to locally host the website)


####Project Details

* Type of learning - Supervised learning
* Data type - MRI scans (taken from Kaggle)
* Target size - 128x128
* Classes - MildDemented, ModerateDemented, NonDemented, VeryMildDemented
* Model - CNN, MobileNet
* Optimizer - Adam optimizer
* Accuray - 55% (CNN), 98%(MobileNet)

#### How to Run?

######1. prerequisites:

* Python (version 3.7 or above)
* pip (Python package manager)
* XAMPP
* MySQL Workbench
* VS code
    * Python extensions
    * SQL extensions

######2. Downnload and Open the Project in VS code

* Download the project as a ZIP file and extract it.
* Open the VS Code and navigate to the **File** menu -> Select the folder containing your project.
* The folder structure will appear in the Explorer pane.

######3. Download the Dataset from Kaggle

* Go to Kaggle and download the dataset as a ZIP file.
* Extract the dataset and place it in the specified directory.

######4. Setup a Virtual Environment

* Open the terminal in VS Code (Ctrl+` or View → Terminal).
* Create a virtual environment

    `python -m venv venv`
* Activate the virtual environment
    * On Windows:
      
          `venv\Scripts\activate`
    * On macOS/Linux:
      
          `source venv/bin/activate`

######5. Install Dependencies

Use the <mark>requirements.txt</mark> file to install dependencies.

    `pip install -r requirements.txt`

######6. Run the Application

**Start MySQL Server**

* Open XAMPP and start only the MySQL service.

**Open the Terminal**
* First ensure that the virtual environment is active.
* Run the main script
  
   `python app.py`
* The application will start and display a local server URL
* Open the URL in your browser to access the application.

**Shutdown and Cleanup**

* Stop the local server (Ctrl + C)
* Deactivate the virtual environment.

    `deactivate`
*Stop the MySQL service in XAMPP.











