# MediXGen: AI-Powered Medical Report Generation from X-Rays

This project presents a prototype system for automated medical report generation from X-ray images, integrating advanced computer vision and natural language processing (NLP) techniques. Leveraging pre-trained CheXNet models for feature extraction and GloVe embeddings for text processing, the system identifies abnormalities in X-ray images and generates concise diagnostic reports. A sequence-to-sequence model with an attention mechanism ensures coherence and accuracy in report generation. The system was trained and evaluated on publicly available medical datasets, achieving a high accuracy of 96\%. To enhance interpretability, Grad-CAM was employed to produce visual explanations by highlighting regions of interest in the X-ray images, with bounding boxes delineating areas indicative of detected abnormalities. This approach not only enhances diagnostic efficiency and reduces radiologist workload but also provides visual insights into the model's decision-making process, thereby improving trust and transparency in AI-assisted diagnostic reporting. 

## Architecture
The proposed model integrates multi-modal input processing, encompassing both text and images, to generate diagnostic reports for X-ray images. It employs an encoder-decoder architecture with an attention mechanism, ensuring coherence and relevance in the generated reports. The model comprises three major components: the encoder, the attention mechanism, and the decoder. The architecture is depicted in the diagram.

### Architecture Diagram

Below is the architecture diagram of the proposed model:

![Architecture Diagram](https://github.com/Namrata-Patel/deeplearning_medical_report_generation/blob/main/figs/arch.png)


#### Best Weights for this model are available at:

https://drive.google.com/file/d/1ClDLBHVsh5Hd3czeo8ZIeneVYfk4M5gA/view?usp=drive_link

