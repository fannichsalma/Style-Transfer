🖼️ PyTorch Neural Style Transfer
🎯 Overview
This project implements a neural style transfer technique using PyTorch. The goal is to transfer the artistic style of one image onto the content of another image, creating a visually appealing blend of both. Utilizing deep learning models, this approach leverages convolutional neural networks to achieve high-quality style transfer results.

🚀 Features
Artistic Style Transfer: Transfer the style from an artwork to your content image.
Customizable Parameters: Adjust parameters such as style weight, content weight, and more.
Pre-trained Models: Utilizes pre-trained neural networks for efficient and high-quality results.
Interactive Visualization: View real-time results of the style transfer process.
🛠️ Requirements
Python: 3.6 or higher
PyTorch: 1.0 or higher
NumPy
PIL (Pillow)
Matplotlib
📦 Installation
Clone the Repository:

git clone https://github.com/fannichsalma/Style-Transfer.git
Navigate to Project Directory:

cd Style-Transfer
Install Dependencies: Create a virtual environment and install the required packages.

pip install -r requirements.txt
🏗️ Usage
Prepare Images: Place your content and style images in the images/ directory.

Run Style Transfer: Execute the following command to start the style transfer process:


python style_transfer.py --content_image path/to/content.jpg --style_image path/to/style.jpg --output_image path/to/output.jpg
Adjust Parameters: Modify parameters in style_transfer.py for custom results, such as:

style_weight to control the influence of the style image.
content_weight to control the influence of the content image.
📈 Results
High-Quality Outputs: Generates visually stunning results by combining the content and style images.
Real-Time Preview: View intermediate results to adjust parameters for optimal style transfer.
🔧 Technology Stack
PyTorch: For implementing neural style transfer algorithms.
NumPy: For numerical operations.
PIL (Pillow): For image processing.
Matplotlib: For visualizing results.


📢 Acknowledgements
Inspired by Gordica Leksa's PyTorch Neural Style Transfer.
Special thanks to the open-source community for their contributions.
🛠️ Contributing
Feel free to fork the repository and submit pull requests with improvements or new features. For detailed contribution guidelines, please refer to the CONTRIBUTING.md file.
