----Aim----
To build a machine learning and deep learning system to classify MRI brain scans into 3 types of
brain tumors and no tumor. This is a multi-class image classification problem.

----Data Collection----
Dataset Used: Brain Tumor MRI Classification (Link: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)
• Type: Medical Image Dataset
• Classes: 3 Tumor Types [glioma, meningioma, pituitary] and no tumor
• Format: Images (jpg files) organized into 4 folders, one for each tumor type
• Input Shape: All images are resized to 130x130 pixels, with 3 color channels (RGB)
• Total Samples: 7022 images

----Data preprocessing----
Steps Taken:
• Read images using cv2.imread.
• Resize all to 130x130 to standardize input dimensions.
• Labels taken from folder names.
• Normalized image pixel values (0–255 scaled to 0–1).
• Encoded all classes to numbers
• Splitted into test and train sets

----Model Building----


