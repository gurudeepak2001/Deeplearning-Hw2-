How to Run the Code
For running the code, I recommend using Palmetto as the environment. Follow the steps below:

1. Clone the Repository
Start by cloning the repository and transferring all the necessary files to your Palmetto home directory.
git clone <your-repo-url>

2. Transfer Files to Palmetto
After cloning the repository, ensure all the relevant files, such as scripts, models, and datasets, are transferred to your Palmetto home directory, maintaining the appropriate folder structure.

3. Ensure Dataset Availability
Make sure the MSVD dataset is present in your home directory on Palmetto, as you will need it for testing the videos during evaluation.
to unzip use code:
tar -xvzf MLDS_hw2_1_data.tar.gz

4. Pre-trained Model
Ensure the pre-trained model file (modelhw2.h) is placed in the appropriate folder for saved models, as training a new model from scratch can take lot of time.

5. Execute the Shell Script
To run the model and generate the output BLEU score along with a text file, use the following command:
./hw2_seq2seq.sh
First set the correct file permissions by running:
chmod +x hw2_seq2seq.sh
6. Modify Paths as Needed
Depending on your execution environment or setup, you might need to adjust argument 1 and argument 2 in the shell script (hw2_seq2seq.sh). Additionally, ensure the correct paths for the dataset and model are specified in the model_test and model_train Python files.
