# Multi_Organ_Segmentation_Transformer

Welcome to the Multi-Organ Segmentation Transformer repository! This project presents an innovative approach to multi-organ segmentation in medical imaging using transformer-based architectures. Leveraging the power of self-attention mechanisms, this model offers state-of-the-art performance in accurately delineating multiple organs from medical images.

UNETR model: UNEt TRansformers (UNETR) utilizes a transformer as the encoder to learn sequence representations of the input volume and effectively capture the global multi-scale information, while also following the successful “U-shaped” network design for the encoder and decoder. The transformer encoder is directly connected to a decoder via skip connections at different resolutions to compute the final semantic segmentation output.

The Model code is available in the model.py file

Test/Train: codes are available in Test.py nd Train.py. The batch size is typically set to 8 or 16 on low-configurative GPUs due to memory constraints and 32 or 64 for better accuracies.

Environmentdetails: Please prepare an environment with python=3.7, then use the command "pip install -r requirements.txt" for the dependencies.

Reference • Dataset : https://paperswithcode.com/dataset/miccai-2015-multi-atlas-abdomen-labeling
or use the [synapse preprocessed dataset](https://www.synapse.org/#!Synapse:syn3193805/wiki/)

![image](https://github.com/ShaisthaAara/Multi_Organ_Segmentation_Transformer/assets/123624263/05d9ee19-1276-4fa5-84c7-ade1d3df2311)
![image](https://github.com/ShaisthaAara/Multi_Organ_Segmentation_Transformer/assets/123624263/2f8d872b-6b5a-458c-812c-7994ed9cada1)
