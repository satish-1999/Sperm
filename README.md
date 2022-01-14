<h1><center>Sperm Fertilisation Detection</center></h1>
The dataset is a collection of human sperm images from 235 patients with male factor infertility. Each image has been labeled by experts for normal or abnormal sperm acrosome, head, vacuole, and tail.<br><br>
The training, validation, and test sets contain 1000, 240, and 300 images, respectively.<br><br>
In dataset, each instance is a grayscale image capturing a single sperm. The head of the sperm is roughly located at the center of the image. Also, the sperm tail is not entirely visible in the images.<br><br>
Labels can be either <b> 0 </b> (normal, positive) or <b> 1 </b> (abnormal, negative).<br><br>
The dataset is available in <b>.npy</b> format. The details of the dataset has been given below.<br><br>
<center>
<table border="2">
  <tr>
    <td>File Name</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>x_128_train.npy</td>
    <td>Training set of 128x128-pixel version</td>
  </tr>
  <tr>
    <td>x_128_valid.npy</td>
    <td>Validation set of 128x128-pixel version</td>
  </tr>
  <tr>
    <td>x_128_test.npy</td>
    <td>Test set of 128x128-pixel version</td>
  </tr>
  <tr>
    <td>x_64_train.npy</td>
    <td>Training set of 64x64-pixel version</td>
  </tr>
  <tr>
    <td>x_64_valid.npy</td>
    <td>Validation set of 64x64-pixel version</td>
  </tr>
  <tr>
    <td>x_64_test.npy</td>
    <td>Test set of 64x64-pixel version</td>
  </tr>
  <tr>
    <td>y_acrosome_train.npy</td>
    <td>Acrosome Training set labels</td>
  </tr>
  <tr>
    <td>y_acrosome_valid.npy</td>
    <td>Acrosome Validation set labels</td>
  </tr>
  <tr>
    <td>y_acrosome_test.npy</td>
    <td>Acrosome Test set labels</td>
  </tr>
  <tr>
    <td>y_head_train.npy</td>
    <td>Head Training set labels</td>
  </tr>
  <tr>
    <td>y_head_valid.npy</td>
    <td>Head Validation set labels</td>
  </tr>
  <tr>
    <td>y_head_test.npy</td>
    <td>Head Test set labels</td>
  </tr>
  <tr>
    <td>y_vacuole_train.npy</td>
    <td>Vacuole Training set labels</td>
  </tr>
  <tr>
    <td>y_vacuole_valid.npy</td>
    <td>Vacuole Validation set labels</td>
  </tr>
  <tr>
    <td>y_vacuole_test.npy</td>
    <td>Vacuole Test set labels</td>
  </tr>
  <tr>
    <td>y_tail_train.npy</td>
    <td>Tail Training set labels</td>
  </tr>
  <tr>
    <td>y_tail_valid.npy</td>
    <td>Tail Validation set labels</td>
  </tr>
  <tr>
    <td>y_tail_test.npy</td>
    <td>Tail Test set labels</td>
  </tr>
</table>
</center>
The datset has been trained with transfer Learning technique. A sample of the model training has been shown below.

Epoch 1/25
34/34 [==============================] - ETA: 0s - loss: 0.7869 - accuracy: 0.6180

Epoch 00001: val_accuracy improved from -inf to 0.66250, saving model to xvgg16_1.h5
34/34 [==============================] - 87s 3s/step - loss: 0.7869 - accuracy: 0.6180 - val_loss: 0.6482 - val_accuracy: 0.6625


Epoch 2/25
34/34 [==============================] - ETA: 0s - loss: 0.6741 - accuracy: 0.6640

Epoch 00002: val_accuracy did not improve from 0.66250
34/34 [==============================] - 86s 3s/step - loss: 0.6741 - accuracy: 0.6640 - val_loss: 0.6520 - val_accuracy: 0.6167

Epoch 3/25
34/34 [==============================] - ETA: 0s - loss: 0.6187 - accuracy: 0.6950

Epoch 00003: val_accuracy improved from 0.66250 to 0.68333, saving model to xvgg16_1.h5
34/34 [==============================] - 86s 3s/step - loss: 0.6187 - accuracy: 0.6950 - val_loss: 0.6396 - val_accuracy: 0.6833

Epoch 4/25
34/34 [==============================] - ETA: 0s - loss: 0.5945 - accuracy: 0.6930

Epoch 00004: val_accuracy improved from 0.68333 to 0.70833, saving model to xvgg16_1.h5
34/34 [==============================] - 86s 3s/step - loss: 0.5945 - accuracy: 0.6930 - val_loss: 0.6313 - val_accuracy: 0.7083

Epoch 5/25
34/34 [==============================] - ETA: 0s - loss: 0.6159 - accuracy: 0.6810

Epoch 00005: val_accuracy did not improve from 0.70833
34/34 [==============================] - 86s 3s/step - loss: 0.6159 - accuracy: 0.6810 - val_loss: 0.6251 - val_accuracy: 0.7042

Epoch 6/25
34/34 [==============================] - ETA: 0s - loss: 0.5888 - accuracy: 0.6990

Epoch 00006: val_accuracy improved from 0.70833 to 0.71667, saving model to xvgg16_1.h5
34/34 [==============================] - 87s 3s/step - loss: 0.5888 - accuracy: 0.6990 - val_loss: 0.6267 - val_accuracy: 0.7167

Epoch 7/25
34/34 [==============================] - ETA: 0s - loss: 0.5947 - accuracy: 0.7010

Epoch 00007: val_accuracy did not improve from 0.71667
34/34 [==============================] - 86s 3s/step - loss: 0.5947 - accuracy: 0.7010 - val_loss: 0.6513 - val_accuracy: 0.6750

Epoch 8/25
34/34 [==============================] - ETA: 0s - loss: 0.5782 - accuracy: 0.7000

Epoch 00008: val_accuracy did not improve from 0.71667
34/34 [==============================] - 87s 3s/step - loss: 0.5782 - accuracy: 0.7000 - val_loss: 0.6369 - val_accuracy: 0.7167

Epoch 9/25
34/34 [==============================] - ETA: 0s - loss: 0.5748 - accuracy: 0.7120

Epoch 00009: val_accuracy did not improve from 0.71667
34/34 [==============================] - 86s 3s/step - loss: 0.5748 - accuracy: 0.7120 - val_loss: 0.6466 - val_accuracy: 0.6708

Epoch 10/25
34/34 [==============================] - ETA: 0s - loss: 0.5862 - accuracy: 0.7120

Epoch 00010: val_accuracy did not improve from 0.71667
34/34 [==============================] - 85s 3s/step - loss: 0.5862 - accuracy: 0.7120 - val_loss: 0.6371 - val_accuracy: 0.6792

Epoch 11/25
34/34 [==============================] - ETA: 0s - loss: 0.5577 - accuracy: 0.7310

Epoch 00011: val_accuracy did not improve from 0.71667
34/34 [==============================] - 87s 3s/step - loss: 0.5577 - accuracy: 0.7310 - val_loss: 0.6373 - val_accuracy: 0.6833

Epoch 12/25
34/34 [==============================] - ETA: 0s - loss: 0.5768 - accuracy: 0.7220

Epoch 00012: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5768 - accuracy: 0.7220 - val_loss: 0.6357 - val_accuracy: 0.6875

Epoch 13/25
34/34 [==============================] - ETA: 0s - loss: 0.5699 - accuracy: 0.7300

Epoch 00013: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5699 - accuracy: 0.7300 - val_loss: 0.6433 - val_accuracy: 0.6792

Epoch 14/25
34/34 [==============================] - ETA: 0s - loss: 0.5634 - accuracy: 0.7160

Epoch 00014: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5634 - accuracy: 0.7160 - val_loss: 0.6422 - val_accuracy: 0.6708

Epoch 15/25
34/34 [==============================] - ETA: 0s - loss: 0.5591 - accuracy: 0.7180

Epoch 00015: val_accuracy did not improve from 0.71667
34/34 [==============================] - 85s 2s/step - loss: 0.5591 - accuracy: 0.7180 - val_loss: 0.6368 - val_accuracy: 0.6958

Epoch 16/25
34/34 [==============================] - ETA: 0s - loss: 0.5628 - accuracy: 0.7320

Epoch 00016: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5628 - accuracy: 0.7320 - val_loss: 0.6245 - val_accuracy: 0.7083

Epoch 17/25
34/34 [==============================] - ETA: 0s - loss: 0.5498 - accuracy: 0.7290

Epoch 00017: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5498 - accuracy: 0.7290 - val_loss: 0.6245 - val_accuracy: 0.6958

Epoch 18/25
34/34 [==============================] - ETA: 0s - loss: 0.5585 - accuracy: 0.7270

Epoch 00018: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5585 - accuracy: 0.7270 - val_loss: 0.6310 - val_accuracy: 0.7042

Epoch 19/25
34/34 [==============================] - ETA: 0s - loss: 0.5468 - accuracy: 0.7370

Epoch 00019: val_accuracy did not improve from 0.71667
34/34 [==============================] - 83s 2s/step - loss: 0.5468 - accuracy: 0.7370 - val_loss: 0.6311 - val_accuracy: 0.6875

Epoch 20/25
34/34 [==============================] - ETA: 0s - loss: 0.5519 - accuracy: 0.7270

Epoch 00020: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5519 - accuracy: 0.7270 - val_loss: 0.6269 - val_accuracy: 0.7083

Epoch 21/25
34/34 [==============================] - ETA: 0s - loss: 0.5553 - accuracy: 0.7170

Epoch 00021: val_accuracy did not improve from 0.71667
34/34 [==============================] - 83s 2s/step - loss: 0.5553 - accuracy: 0.7170 - val_loss: 0.6462 - val_accuracy: 0.6542

Epoch 22/25
34/34 [==============================] - ETA: 0s - loss: 0.5370 - accuracy: 0.7170

Epoch 00022: val_accuracy did not improve from 0.71667
34/34 [==============================] - 84s 2s/step - loss: 0.5370 - accuracy: 0.7170 - val_loss: 0.6363 - val_accuracy: 0.6833

Epoch 23/25
34/34 [==============================] - ETA: 0s - loss: 0.5439 - accuracy: 0.7360

Epoch 00023: val_accuracy did not improve from 0.71667
34/34 [==============================] - 83s 2s/step - loss: 0.5439 - accuracy: 0.7360 - val_loss: 0.6459 - val_accuracy: 0.6542

Epoch 24/25
34/34 [==============================] - ETA: 0s - loss: 0.5473 - accuracy: 0.7450

Epoch 00024: val_accuracy did not improve from 0.71667
34/34 [==============================] - 83s 2s/step - loss: 0.5473 - accuracy: 0.7450 - val_loss: 0.6575 - val_accuracy: 0.6375

Epoch 25/25
34/34 [==============================] - ETA: 0s - loss: 0.5308 - accuracy: 0.7410

Epoch 00025: val_accuracy did not improve from 0.71667
34/34 [==============================] - 83s 2s/step - loss: 0.5308 - accuracy: 0.7410 - val_loss: 0.6430 - val_accuracy: 0.6583

The codes of all the Models has been attached.
