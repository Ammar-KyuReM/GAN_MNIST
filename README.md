# GAN_MNIST
Generating MNIST Images Using GAN

This project implements a Generative Adversarial Network (GAN) using **PyTorch**, written in a single Jupyter Notebook file: `GAN.ipynb`. The GAN is designed to generate realistic images from random noise.  
The project structure is kept simple and organized for easy understanding and replication.

The GAN consists of two main parts:
- A **Generator** network that creates fake images.
- A **Discriminator** network that distinguishes real images from fake ones.

The model is trained adversarially where both networks improve together over time.

---

## 📌 Important Information

- The project automatically saves:
  - Model checkpoints during training
  - Generated output images during and after training
- **All files are saved directly to your Google Drive.**  
  ➔ It is mandatory to mount your Google Drive before running the notebook.

---

## ⚙️ Requirements

Before running the notebook, ensure you have:
- Python 3.x environment
- PyTorch and torchvision installed
- Google Drive account linked and accessible
- Libraries installed: `numpy`, `scipy`, `Pillow`, `scikit-learn`

---

## 🚀 Setup Instructions

1. Upload or clone the repository to your environment:

    ```bash
    git clone https://github.com/your-username/gan-image-generation.git
    cd gan-image-generation
    ```

2. Open `GAN.ipynb` in Google Colab or Jupyter Notebook.

3. Mount your Google Drive at the start of the notebook:

    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

4. Run the notebook cells in order to:
    - Train the GAN model
    - Generate and save images automatically into your Google Drive

---

## 📂 Project Structure

gan-image-generation/
│
├── GAN.ipynb                 # Main Jupyter notebook file
├── output/                   # Folder to store generated images



---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repository, make enhancements, and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project.  
Please see the `LICENSE` file for more information.
