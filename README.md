# image-processing-ML
Ce notebook renferme les fonction de Feature extraction+Prétraitement+Modélisation+ Evaluation
*Les fonctions lbp_extractor, hog_extractor,hist_bgr, et hist_hsv retournent 4 scores de similarité avec nos classes de turbidite: very_low turbidity,low_turbidity,medium_turbidity,high_turbidity ceci etant en comparant l’histogramme de l’image passée en paramètre avec les 4 histogrammes des images de références de chaque clase (la 1ere image de chaque classe)
*On dispose aussi des fonctions suivantes: 
-haralick_extractor: retourne un vecteur de dimension 13*4 qui représente les 13 caractéristiques haralick de l’image selon les 4 directions (Up,Down,Right,Left).
-mean_std_bgr
-mean_std_hsv
-bgr_distribution
-image_colourfoulness
-contrast
-brightness
-sharpness
