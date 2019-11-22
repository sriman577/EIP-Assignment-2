# EIP-Assignment-2

Logs for 20 Epochs


Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 11s 178us/step - loss: 0.2305 - acc: 0.9270 - val_loss: 0.0893 - val_acc: 0.9707
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 5s 89us/step - loss: 0.0671 - acc: 0.9787 - val_loss: 0.0538 - val_acc: 0.9820
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 5s 87us/step - loss: 0.0512 - acc: 0.9838 - val_loss: 0.0479 - val_acc: 0.9850
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 5s 89us/step - loss: 0.0432 - acc: 0.9869 - val_loss: 0.0332 - val_acc: 0.9893
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0395 - acc: 0.9880 - val_loss: 0.0258 - val_acc: 0.9921
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0345 - acc: 0.9894 - val_loss: 0.0231 - val_acc: 0.9917
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 5s 89us/step - loss: 0.0324 - acc: 0.9901 - val_loss: 0.0272 - val_acc: 0.9910
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0291 - acc: 0.9905 - val_loss: 0.0252 - val_acc: 0.9927
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 5s 89us/step - loss: 0.0256 - acc: 0.9919 - val_loss: 0.0222 - val_acc: 0.9933
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 6s 92us/step - loss: 0.0254 - acc: 0.9914 - val_loss: 0.0214 - val_acc: 0.9936
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 5s 90us/step - loss: 0.0251 - acc: 0.9916 - val_loss: 0.0311 - val_acc: 0.9910
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0235 - acc: 0.9919 - val_loss: 0.0224 - val_acc: 0.9928
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0217 - acc: 0.9932 - val_loss: 0.0198 - val_acc: 0.9940
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0208 - acc: 0.9932 - val_loss: 0.0204 - val_acc: 0.9940
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0201 - acc: 0.9934 - val_loss: 0.0201 - val_acc: 0.9934
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 5s 87us/step - loss: 0.0189 - acc: 0.9938 - val_loss: 0.0219 - val_acc: 0.9935
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 5s 87us/step - loss: 0.0194 - acc: 0.9939 - val_loss: 0.0169 - val_acc: 0.9942
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0177 - acc: 0.9941 - val_loss: 0.0197 - val_acc: 0.9938
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0168 - acc: 0.9945 - val_loss: 0.0208 - val_acc: 0.9929
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 5s 90us/step - loss: 0.0167 - acc: 0.9945 - val_loss: 0.0191 - val_acc: 0.9945
<keras.callbacks.History at 0x7f532f7a9c18>



Model.evaluate

[0.01913787197246056, 0.9945]

Approach

Reduce the no of parameters and add either 1x1 layer or maxpooling layer. If both are added then no of parameters reduced and also accuracy decreases. So instead of adding both layers, add only one 1x1 layer. Then we got 99.4 accuracy and also no of parameters were decreased.
