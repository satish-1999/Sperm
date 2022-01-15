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
The dataset has been trained with transfer Learning technique. The details of the Source code has been given below.<br><br>
<table>
  <tr>
    <th>Sperm Part</th>
    <th>File Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td rowspan="11">Acrosome</td>
    <td>ACROSOME_DenseNet.ipynb</td>
    <td>DenseNet model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_InceptionV3.ipynb</td>
    <td>InceptionV3 model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_MobileNet.ipynb</td>
    <td>MobileNet model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_MobileNetV2.ipynb</td>
    <td>MobileNetV2 model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_NASNET_Large.ipynb</td>
    <td>NASNET_Large model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_NASNET_Mobile.ipynb</td>
    <td>NASNET_Mobile model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_Resnet50.ipynb</td>
    <td>Resnet50 model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_VGG16.ipynb</td>
    <td>VGG16 model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_VGG19.ipynb</td>
    <td>VGG19 model implementation</td>
  </tr>
  <tr>
    <td>ACROSOME_Xception.ipynb</td>
    <td>Xception model implementation</td>
  </tr>
  <tr>
    <td>InceptionResNetV2_ACROSOME.ipynb</td>
    <td>InceptionResNetV2 model implementation</td>
  </tr>
  <tr>
    <td rowspan="11">Head</td>
    <td>Head1_DenseNet.ipynb</td>
    <td>DenseNet model implementation</td>
  </tr>
  <tr>
    <td>Head1_InceptionV3.ipynb</td>
    <td>InceptionV3 model implementation</td>
  </tr>
  <tr>
    <td>Head1_MobileNet.ipynb</td>
    <td>MobileNet model implementation</td>
  </tr>
  <tr>
    <td>Head1_MobileNetV2.ipynb</td>
    <td>MobileNetV2 model implementation</td>
  </tr>
  <tr>
    <td>Head1_NASNET_Large.ipynb</td>
    <td>NASNET_Large model implementation</td>
  </tr>
  <tr>
    <td>Head1_NASNET_Mobile.ipynb</td>
    <td>NASNET_Mobile model implementation</td>
  </tr>
  <tr>
    <td>Head1_Resnet50.ipynb</td>
    <td>Resnet50 model implementation</td>
  </tr>
  <tr>
    <td>Head1_VGG16.ipynb</td>
    <td>VGG16 model implementation</td>
  </tr>
  <tr>
    <td>Head1_VGG19.ipynb</td>
    <td>VGG19 model implementation</td>
  </tr>
  <tr>
    <td>Head1_Xception.ipynb</td>
    <td>Xception model implementation</td>
  </tr>
  <tr>
    <td>Head1_InceptionResNetV2.ipynb</td>
    <td>InceptionResNetV2 model implementation</td>
  </tr>
  <tr>
    <td rowspan="11">Vacuole</td>
    <td>Vacuole1_DenseNet.ipynb</td>
    <td>DenseNet model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_InceptionV3.ipynb</td>
    <td>InceptionV3 model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_MobileNet.ipynb</td>
    <td>MobileNet model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_MobileNetV2.ipynb</td>
    <td>MobileNetV2 model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_NASNET_Large.ipynb</td>
    <td>NASNET_Large model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_NASNET_Mobile.ipynb</td>
    <td>NASNET_Mobile model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_Resnet50.ipynb</td>
    <td>Resnet50 model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_VGG16.ipynb</td>
    <td>VGG16 model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_VGG19.ipynb</td>
    <td>VGG19 model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_Xception.ipynb</td>
    <td>Xception model implementation</td>
  </tr>
  <tr>
    <td>Vacuole1_InceptionResNetV2.ipynb</td>
    <td>InceptionResNetV2 model implementation</td>
  </tr>
</table>
