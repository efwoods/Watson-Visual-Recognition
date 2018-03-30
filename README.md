# Watson-Visual-Recognition
This Repository Contains:
- Shell scripts which use curl commands to control the creation and deletion of classifiers
- A python script which sends a classify request to the Watson Visual Recognition Service
- A sample image




# For First Time Setup:

pip install --upgrade "watson-developer-cloud>=1.1.1" ( may need sudo at front)
python watson.py

# To Run Shell Scripts:

classifier_script.sh
./classifier_script.sh A.zip B.zip

get_classifier.sh : returns 
./get_classifier.sh

delete_classifier.sh
./delete_classifier.sh
