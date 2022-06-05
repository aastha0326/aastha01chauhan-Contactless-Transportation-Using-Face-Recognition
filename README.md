# aastha01chauhan-Contactless-Transportation-Using-Face-
Contactless Transit/Metro transportation system using Face Recoognition 💻
Link To Presentation(https://drive.google.com/file/d/10bVUS_bbJXPMD_zaAbkNxe-E-BnVtdFP/view?usp=sharing)

As we are moving towards cashless and contactless economy, this project is a small thought in this direction. This project involves building a contactless Transit/metro system which utilizes facial recognition to maintain boarding and deboarding records of passengers. It covers areas such as facial detection, alignment, and recognition, along with the development of a web application to cater to various use cases of the system such as registration of new passengers, addition of photos to the training dataset, ride reports, payment gateway and so on. This project intends to serve as an efficient substitute for traditional manual cashing transportation systems.

This project aims to automate the traditional cashing system where the fare is paid manually. It also enables a service provider to maintain its records. Digitalization of the system would also help in better visualization of the data using graphs to display the no. of rides taken today, total duration of rides and their break time. Its added features serve as an efficient upgrade and replacement over the traditional transportation cashing system.


The system mainly works around 2 types of modes
Admin and User Mode
Following functionalities can be performed by the admin:
• Login
• Register new passengers to the system
• Add passenger photos to the training data set
• Train the model
• View ride report of all passengers. Resports can be filtered by date or passengers.

Following functionalities can be performed by the users/passengers:
• Login
• Mark his/her boarding time-in and deboarding time-out by scanning their face
• View ride report of self
• Pay the fare via razorpay Gateway

Face Detection
Dlib's HOG facial detector.

Facial Landmark Detection
Dlib's 68 point shape predictor

Extraction of Facial Embeddings
face_recognition by Adam Geitgey

Classification of Unknown Embedding
using a Linear SVM (scikit-learn)

Documentation 📰
This folder contains all the related documents. (https://drive.google.com/file/d/1izbbkCw2hz7rXJ_hm-p5Ely0s1ov0f_9/view?usp=sharing)

How To Run ?
clone it on your computer
make a separate python virtual environment or use the default one already installed on your machine
run pip install -r requirements.txt inside the repo
Run python manage.py runserver inside the project
Enjoy !
             
username: admin
password: Aastha@12345

username: ahilya
password: Aastha@12345

Presentation 🎓
Link To Presentation
(https://drive.google.com/file/d/10bVUS_bbJXPMD_zaAbkNxe-E-BnVtdFP/view?usp=sharing)

if (youEnjoyed) {
    starThisRepository();
}
Thank You!
