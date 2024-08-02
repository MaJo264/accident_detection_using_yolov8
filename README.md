# Accident Detection Using YOLOv8

This project showcases an advanced accident detection system developed using **YOLOv8** (You Only Look Once, version 8). As part of my Master's semester project, I undertook this initiative to harness the power of deep learning and computer vision for real-time accident detection. The objective was to create a robust model capable of accurately identifying accident scenes from a variety of sources.

## Dataset Collection

The custom dataset used for training and testing the model was meticulously gathered from diverse sources. These sources included traffic cameras, dashcam footage, and publicly available accident datasets. By compiling images and videos of both accidents and non-accidents, I ensured a comprehensive dataset that enhances the model's ability to distinguish between normal and emergency situations. The dataset was stored and managed using **Google Drive**, facilitating seamless integration with the training environment.

## Model Training and Testing

**Google Colab** served as the primary platform for training and testing the YOLOv8 model. Leveraging the computational power of Google Colab's GPUs allowed for efficient training of the deep learning model on the large dataset. The training process involved fine-tuning the YOLOv8 architecture to detect accidents with high precision and recall. Several hyperparameters were optimized during this phase to achieve the best possible performance.

The trained model was rigorously tested using a separate validation dataset to evaluate its accuracy and robustness. Performance metrics such as precision, recall, and mean average precision (mAP) were calculated to assess the model's effectiveness in real-world scenarios. The results demonstrated the model's capability to reliably detect accidents in various conditions and environments.

## Project Outcome

This project successfully delivered a state-of-the-art accident detection system using **YOLOv8**, capable of real-time performance. The trained model can be deployed in traffic monitoring systems to enhance road safety by providing timely alerts of accidents, potentially saving lives and reducing response times. The combination of a well-curated custom dataset, advanced deep learning techniques, and the power of cloud computing has resulted in a robust and reliable accident detection solution.
