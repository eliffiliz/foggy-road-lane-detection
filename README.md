# Foggy Road Lane Detection

Lane detection on GAN-generated foggy road images using U-Net and classical image processing methods.

---

## Project Description
This project investigates lane detection performance under foggy weather conditions, which pose significant challenges for vision-based autonomous driving systems. 
Due to the limited availability of real foggy driving data, synthetic foggy road images are generated using Generative Adversarial Networks (GAN).

Lane detection is then performed using two different approaches:
1. Deep learning-based lane segmentation using the U-Net architecture
2. Classical image processing techniques for lane detection

The results obtained from both approaches are analyzed and compared to evaluate their effectiveness under adverse weather conditions.

---

## Methods

### Foggy Image Generation
- Synthetic foggy road images are generated using GAN.
- The generated images are used to simulate realistic foggy driving scenarios.

### Lane Detection with Deep Learning
- U-Net architecture is employed for pixel-wise lane segmentation.
- The model is trained on GAN-generated foggy images.
- Performance is evaluated using segmentation-based accuracy metrics.

### Lane Detection with Classical Image Processing
- Traditional image processing techniques such as edge detection, thresholding, and morphological operations are applied.
- These methods provide an interpretable baseline for comparison with deep learning results.

---

## Technologies
- Python  
- OpenCV  
- GAN  
- U-Net  
- CNN  
- Classical Image Processing Techniques  

---

## Performance Evaluation

Experimental results indicate a significant improvement in lane detection performance when deep learning-based methods are employed.  
While classical image processing approaches achieved an average performance of **89%**, the use of a U-Net-based deep learning model increased the performance to **96%** on GAN-generated foggy road images.

These findings demonstrate the robustness and effectiveness of deep learning methods compared to classical techniques under adverse weather conditions.  
Detailed experimental setup, evaluation metrics, and quantitative analyses are provided in the full paper.

---

## Visual Results

### GAN-Generated Foggy Image
<img src="https://github.com/user-attachments/assets/d256a518-9779-4197-aceb-bd32677cbe48" width="400"/>

*Figure 1. Example of a foggy road image generated using GAN.*

---

### Lane Detection Using Classical Image Processing
<img src="https://github.com/user-attachments/assets/577c0714-917e-4ef9-acab-8f65dcb7d577" width="400"/>

*Figure 2. Lane detection result obtained using classical image processing methods.*

---

### Lane Detection Using Deep Learning (U-Net)
<img src="https://github.com/user-attachments/assets/ba81bc27-e533-4f98-a171-e1b05ace608a" width="400"/>

*Figure 3. Lane segmentation result obtained using U-Net on a GAN-generated foggy image.*

---

## Academic Output

- **Conference Paper (Oral Presentation):**  
  *Lane Detection in Foggy Images using Generative Adversarial Networks*  
  1st International Conference on Pioneer and Academic Research (ICPAR 2025)

- **Journal Article:**  
  International Journal of Advanced Natural Sciences and Engineering Researches  
  Volume 9, Issue 7, 2025

---

## Full Paper Access

The full-text version of the article is openly available:

🔗 **Full Paper (PDF):**  
[Lane Detection in Foggy Images Using Generative Adversarial Networks](https://www.researchgate.net/profile/Serel-Oezmen-Akyol/publication/393361365_Lane_Detection_in_Foggy_Images_using_Generative_Adversarial_Networks/links/68667f5839c358351206a81e/Lane-Detection-in-Foggy-Images-using-Generative-Adversarial-Networks.pdf)

*(If the link does not open, try logging into ResearchGate or requesting a copy from the authors.)*


## Notes
Due to academic, ethical, and experimental considerations, the full source code is not publicly shared.

---

## Author
Elif Filiz  
Computer Engineering Graduate | MSc in AI (in progress)
