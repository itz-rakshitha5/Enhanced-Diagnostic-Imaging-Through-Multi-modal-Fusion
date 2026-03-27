## Proposed Model Results (Hybrid CNN–Transformer)

This folder contains graphical, qualitative, and quantitative results of the proposed model.

---

### 📈 Graph Analysis (Graphs Folder)

The graphs compare CT, MRI, and fused images based on different metrics:

- **Entropy Graph:** The fused image shows higher entropy, indicating richer information content.  
- **PSNR Graph:** Higher PSNR values indicate better image quality and reduced noise.  
- **SSIM Graph:** Higher SSIM shows improved structural similarity in the fused image.  

---

### 📷 Qualitative Results (Qualitative Folder)

The fused images demonstrate effective combination of CT and MRI modalities.  
The model preserves important edges, textures, and structural details while enhancing overall clarity.

---

### 📊 Quantitative Results (Quantitative Folder)

The model is evaluated using **PSNR, SSIM, Mutual Information (MI), RMSE, and Entropy**:

- Higher **SSIM** → better structural similarity  
- Higher **PSNR** → improved image quality  
- Lower **RMSE** → more accurate reconstruction  
- Higher **MI** → better fusion of information  
- Higher **Entropy** → richer content in fused image  

---

### ✅ Conclusion

The proposed Hybrid CNN–Transformer model effectively combines local and global features, outperforming CNN and GAN models in both visual quality and quantitative metrics.
