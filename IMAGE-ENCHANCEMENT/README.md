# Image Enhancement Web App

This is a web application built with Flask that allows users to upload images and enhance them using various image enhancement models including Real-ESRGAN and GFPGAN.

## Setup

1. Clone the repository:

git clone <https://github.com/BRUNDAVANAMSUREKHA/IMAGE-ENCHANCEMENT>


2. Navigate to the project directory

3. Install dependencies:

pip install -r requirements.txt

4. Also download the required predefined models given below

- GFPGAN v1.2
- GFPGAN v1.3
- GFPGAN v1.4
- RestoreFormer
                    
5. Download model weights:

Run the following command to download the required model weights:

python app.py

6. This will automatically download the necessary model weights to the project directory.

## Usage

1. Start the Flask server:

python app.py

2. Open your web browser and go to `http://localhost:5000`.

3. Upload an image and select the desired enhancement version and scale.

4. Click on the "Enhance" button to process the image.

5. After processing, the enhanced image will be displayed along with the original image.

## Sample images

Sample input and output images

![WhatsApp Image 2024-04-25 at 21 34 17_cd1a4043](https://github.com/BRUNDAVANAMSUREKHA/IMAGE-ENCHANCEMENT/assets/122956099/2255eb9e-029a-4d9c-920f-9e599194cbb8)

![WhatsApp Image 2024-04-25 at 21 34 37_8498d7aa](https://github.com/BRUNDAVANAMSUREKHA/IMAGE-ENCHANCEMENT/assets/122956099/53216de5-0ef3-47c0-841f-5d5a5ae408fe)

![WhatsApp Image 2024-04-25 at 21 34 53_67c8befa](https://github.com/BRUNDAVANAMSUREKHA/IMAGE-ENCHANCEMENT/assets/122956099/8f115bd0-7ae3-4bba-9080-465b051ed3a3)

![WhatsApp Image 2024-04-25 at 21 35 10_835495d3](https://github.com/BRUNDAVANAMSUREKHA/IMAGE-ENCHANCEMENT/assets/122956099/d66bc934-e2c7-4355-8588-2e19150427be)

![WhatsApp Image 2024-04-25 at 21 32 32_e1e18657](https://github.com/BRUNDAVANAMSUREKHA/IMAGE-ENCHANCEMENT/assets/122956099/2cee72fb-2bcb-41de-aacd-2edba869951f)

## Folder Structure

- `static`: Contains static files including CSS, JavaScript, and uploaded images.
  - `uploads`: Directory to store uploaded images.
  - `outputs`: Directory to store enhanced images.
- `templates`: Contains HTML templates for rendering web pages.

## Dependencies

- torch>=1.7
- basicsr>=1.4.2
- facexlib>=0.2.5
- gfpgan>=1.3.7
- realesrgan>=0.2.5
- numpy
- opencv-python
- torchvision
- scipy
- tqdm
- lmdb
- pyyaml
- yapf
- flask

