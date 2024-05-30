# VIS-NIR registration dataset

### A brief introduction to the VIS-NIR registration dataset
 

### Document interpretation 
   There are nine folders under the main folder of this dataset. Among them, "country" is used as the training set, and the other eight are used as test sets. For the eight test subset folders, each pair of cross-spectral images to be registered contains five files: "xxxx_nir.jpg", "xxxx_nir.npy", "xxxx_nir.txt", "xxxx_nir_pa.txt", and "xxxx_rgb.jpg"：
1. "xxxx_nir.jpg": Reference NIR image;  
2. "xxxx_rgb.jpg": VIS image to be registered.  
3. "xxxx_nir.txt"：Specific transformation parameters of the original NIR image.  
4. "xxxx_nir_pa.txt"：specific affine transformation parameters corresponding to "xxxx_nir.txt". (That is, the affine transformation parameters that VIS images need to learn)   
5. "xxxx_nir.npy"：equivalent to the content in "xxxx_nir_pa.txt", but the npy format is easier for the program to read.  




