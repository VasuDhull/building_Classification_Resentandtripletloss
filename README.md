Dataset - https://drive.google.com/file/d/1lE9fn6-BkymZsGaOx2GH96vdRyyVFqpb/view?usp=drive_link

Phase-1 : The Dataset is trained on the resent model and the confusion matrix is made for better infering the results

Phase-2 : The same resent model which is pretrained is used and the softmax layer is removed to add a mlp model in it's place, which is trained using the triplet loss.
Then the embedings which we get from the mlp model is converted to dimention of 2 using the t-SNE, to plot the output, then we can visualise the results.
