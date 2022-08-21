# Multi-Modal-Sentiment-Analysis-using-Attention
Word Embedding used - GloVe (Global Vectors for Word Representation) on Dataset - Multi-Domain Sentiment Dataset (version 2.0)

We found that the GRU layer as the bidirectional RNN in the Multi Modal Analysis Model
gives efficient performance. It not only takes less training time than the state of the art, but gives
higher validation accuracy in most of the domains. On the other hand, if we consider the
validation accuracy in both the modules separately then state of art gives a higher accuracy in the
domain module whereas our model in experiment 5 gives a higher validation accuracy in the
sentiment module. Overall, we require our model to predict the sentiment accurately. Thus we
can, to some extent, use the Multi Modal Analysis Model with GRU instead of LSTM as a
bidirectional RNN layer gives a better performance. This can be attributed to the nature of GRU
being more efficient for small datasets.


Abbreviations: 

▪ d_pred_acc : The accuracy of the model to predict the domain. Accuracy is the fraction
of predictions our model got right.

▪ d_pred_loss: The loss in the model to predict the domain. Loss is a number indicating
how bad the model's prediction was on a single example.

▪ loss:The complete loss from both the domains. We use mean squared error for finding the
loss in our models.

▪ s_pred_acc : The accuracy of the model to predict the sentiment.

▪ s_pred_loss: The loss in the model to predict the sentiment.

▪ val_d_pred_acc : The accuracy of the model to predict the domain during validation.
Accuracy is the fraction of predictions our model got right.

▪ val_d_pred_loss: The loss in the model to predict the domain during validation. Loss is a
number indicating how bad the model's prediction was on a single example.

▪ val_loss:The complete loss from both the domains during validation. We use mean
squared error for finding the loss in our models.

▪ val_s_pred_acc : The accuracy of the model to predict the sentiment during validation.

▪ val_s_pred_loss: The loss in the model to predict the sentiment during validation.
