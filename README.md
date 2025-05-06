# 🚀 Rock-Art-Segmentation

> Deep Learning Project (Group 33) - Rock art segmentation is a contemporary challenge in the field of computer vision. This project aims to simplify the segmentation process by leveraging pretrained models. 
>
> Rock art carvings, or petroglyphs, offer insights into the social structures and beliefs of past societies. Traditional documentation methods are time-consuming, and often get corrupted. With the advancement of computer vision, there is growing interest in applying artificial intelligence to archaeological research. This paper explores the use of transfer learning and data augmentation for the detection and segmentation of rock art motifs. By doing so, we aim to enhance the accuracy and efficiency of archaeological analysis and later develop an online heritage website to preserve cultural heritage using modern digital tools. 

---

## 📝Dataset
- LUMS Repository - 234 images
- [🌌 View Rock Art Identification Project on Roboflow](https://universe.roboflow.com/race-jvd8v/rock-art-identification/browse)


## 📚 Improvements

### 💡 First Improvement

- YOLOV7_Cropping - implementation of Roboflow's pretrained YOLOV7 model to crop images from a new dataset.
- SAM - implementation of SAM VIT for image segmentation on LUMS dataset.
- MaskRCNN - implementation of MaskRCNN for image segmentation on LUMS & Roboflow dataset.
- DeeplabV3 - implementation of DeeplabV3 for image segmentation on LUMS & Roboflow dataset.
- Segformer - implementation of Segformer for image segmentation on LUMS & Roboflow dataset.
##
### 💡 Final Improvement

- Upernet-Swin - implementation of UperNet with Swin Backbone and diffusion model for data augmentation.
- Unet_Segformer - implementation of UNet with Swin Backbone.
##
### 🦗 Extra Files

- output.md - contains outputs for SAM
  
---

## 🤓 Conclusion
This study demonstrates the potential of leveraging deep learning techniques, particularly transfer learning and data augmentation, to improve the detection and segmentation of rock art carvings. By automating and enhancing the documentation process, we reduce the limitations of manual methods and open new pathways for large-scale archaeological analysis. The integration of AI not only boosts efficiency and accuracy but also paves the way for long-term preservation through digital platforms. Ultimately, this work contributes to safeguarding cultural heritage and making it more accessible for future research and public engagement.
