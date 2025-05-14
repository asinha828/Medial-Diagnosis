 Medical Imaging Using Encrypted PNG and Homomorphic Inference
This project presents a secure and privacy-preserving framework for medical image classification using homomorphic encryption (HE). It converts DICOM images into PNG format, encrypts them using the CKKS scheme via TenSEAL, and performs inference directly on encrypted data, ensuring that sensitive medical information remains protected throughout the process.

🔍 Features
✅ Converts DICOM images to grayscale PNG

✅ Preprocesses and flattens image data for model input

✅ Applies homomorphic encryption using TenSEAL (CKKS)

✅ Simulates inference with a linear model on encrypted images

✅ Decrypts and returns predictions securely

✅ Inspired by the Diegif framework, with a focus on encrypted inference (not just training)

🧠 Technologies
Python, NumPy, PyTorch (for tensor ops)

TenSEAL (Homomorphic Encryption)

Pydicom, PIL, Torchvision

🏥 Use Cases
Secure AI inference for telemedicine

Privacy-preserving diagnostics in cloud environments

Research collaboration without sharing raw medical data
