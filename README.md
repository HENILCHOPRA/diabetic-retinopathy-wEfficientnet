# diabteic-retinopathy-wEfficientnet
<img src="Diabetic-Retinopathy_SS-Graphic-1080x500.jpg" alt="DR Graphics">

# Overview
<ul>
  <li>What is Diabetic Retinopathy?</li>
  A complication of diabetes that affects the eyes. Diabetic retinopathy is caused by damage to the blood vessels in the tissue at the back of the eye (retina). Poorly controlled blood sugar is a risk factor. Early symptoms include floaters, blurriness, dark areas of vision, and difficulty perceiving colors. Blindness can occur.

  <li>Goal of this Project?</li>
  <ul>
    <li>Here I have used kaggle dataset of high resoultion images of human eye retina with annotated severity level.</li>
    <li>I used a vanilla Efficient model (EfficientnetB3) model on resized 947 sample images of size (256,256,3).</li>
    <li>Post that I augmented the model with attention layer to focus on specific area on learning feature from that region.</li>
   </ul>
   <li>Credits</li>
   <ul>
      <li><a href = "https://www.kaggle.com/c/diabetic-retinopathy-detection/overview"> Dataset</a></li>
      <li><a href = "https://keras.io/examples/vision/image_classification_efficientnet_fine_tuning/"> Keras Efficientnet</a></li>
      <li><a href = "https://www.kaggle.com/kmader/inceptionv3-for-retinopathy-gpu-hr#Attention-Model"> Attention model</a></li>
   </ul>
</ul>

<>
# Samples
<img src="samples.png" alt="Samples">

# Model Summary
<br>
Vanilla Efficientnet Model
<br>
<img src="Vanilla_Efficientnet_summary.png" alt="Vanilla Efficientnet Model Summary">
<br>
Attention Model
<br>
<img src="Attention_model_summary.png" alt="Attention Model Summary">