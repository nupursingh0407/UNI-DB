# Uni---DB
Uni-DB is a government document retrieval and management system developed using Python, MySQL database, OpenCV2 library, and Tkinter. The project aims to provide a secure and efficient way for users to fetch and manage their government documents by utilizing their Aadhar card number and fingerprints.

**Technologies Used**
**Python**: The primary programming language for the project.
**MySQL Database**: Used to store and manage user data and documents.
**OpenCV2 Library**: Employed for fingerprint recognition and image processing.
**Tkinter**: Utilized for creating the user interface.

**Features**
**Document Retrieval**: Users can retrieve their government documents by entering their Aadhar card number and providing fingerprints using the RS-307-X sensor module.
**Document Manipulation**: Authorized administrators can manipulate and update user documents in the presence of the user. This ensures the security and integrity of the document management process.
**Access Control**: The system ensures that only the authorized administrator, in the presence of the user, can access and update the documents. This is done by requiring both the Aadhar card number and fingerprints for authentication.
**Fingerprint Sensor**: The RS-307-X sensor module is used to capture and verify user fingerprints, adding an extra layer of security to the authentication process.

**Prerequisites**
-Ensure you have Python installed. You can download it from python.org.
-Set up a MySQL database and update the database configuration in the project.
-Install required Python packages using the following command:
*pip install -r requirements.txt

**Installation**
Clone the repository:
git clone https://github.com/your-username/Uni-DB.git

**Navigate to the project directory:**
cd Uni-DB

**Installation**

**Clone the repository:**
git clone https://github.com/your-username/Uni-DB.git

**Navigate to the project directory:**
cd Uni-DB

**Run the application:**
python main.py

**Usage**
-Launch the application.
-Enter your Aadhar card number and provide fingerprints using the RS-307-X sensor module.
-If you are an administrator, log in to manipulate and update user documents.
