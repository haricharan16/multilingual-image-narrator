# Multilingual Image Narrator

An AI-based assistive system designed to help visually impaired people understand images through audio descriptions in Indian languages.

The project takes an image, generates a caption in English using **ViT-GPT2**, translates it into a selected Indian language using **IndicTrans2**, and converts the translated text into speech using **gTTS (Google Text-to-Speech)**.

## Workflow

1. **Image Captioning:** ViT-GPT2 generates an English description of the input image.
2. **Language Translation:** IndicTrans2 translates the generated caption into the selected Indian language.
3. **Text-to-Speech:** gTTS converts the translated caption into audio.

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- ViT-GPT2
- IndicTrans2
- gTTS
- Deep Lake
- Flickr30k Dataset

## Supported Languages

The project supports 10 Indian languages:

- Hindi
- Telugu
- Tamil
- Bengali
- Gujarati
- Kannada
- Malayalam
- Marathi
- Punjabi
- Urdu

## Dataset

The project uses the [Flickr30k dataset](https://datasets.activeloop.ai/docs/ml/datasets/flickr30k-dataset/) for image captioning.

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Run the notebook cells in sequence.
3. Install the required libraries and load the pretrained models.
4. Download or access the Flickr30k images using the dataset section.
5. Provide an image path and select your preferred language.
6. Run the processing function to generate the translated caption and audio narration.

## Project Objective

To make visual information more accessible by combining image captioning, multilingual translation, and speech generation into a single assistive pipeline.
