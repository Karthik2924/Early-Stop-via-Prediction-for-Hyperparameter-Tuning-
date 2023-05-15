# Early-Stop-via-Prediction-for-Hyperparameter-Tuning-
Predicts the accuracy of the model at a particular epoch given hyper parameters of the model and accuracy values for at least first 5 epochs.
### Files
* 'training_evaluation.ipynb' contains the code necessary for training the model.
* 'Inference.ipynb' contains the code to use the model predict the validation accuracy at particular epoch. Set the values of **E** and **M** in the notebook.
* 'new_best_model_rmse.pth' is the pretrained model used in inference.
### Running Instructions
* Google colab can be used to run the code. Open the notebook in colab and upload the dataset as well as pretrained model to the environment.
* The code can be run locally if all the libraries mentioned below are installed. Set the path to the pretrained model correctly if running locally.

### Libraries Required 
 * PyTorch
 * Sklearn
 * NumPy
 * Matplotlib
 * Pandas
