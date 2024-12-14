# Face Swap App 🤳✨

Welcome to the Face Swap App! This project demonstrates the power of computer vision by swapping faces between two images using OpenCV and dlib. 
It's a fun way to explore image processing techniques and can serve as a foundation for augmented reality applications.

## Features 🚀

Face Detection: Identify human faces in images using dlib's pre-trained models.
Landmark Extraction: Extract facial landmarks to understand facial structures.
Triangulation: Divide faces into triangles for precise mapping.
Affine Transformation: Warp triangles from the source face to match the destination face.
Seamless Cloning: Blend the swapped face seamlessly into the destination image using OpenCV's seamlessClone function.

## Usage 📸

* Prepare your images: Place your source and destination images in the images directory.
* Run the face swap script:
python face_swap.py --source images/source.jpg --destination images/destination.jpg
* View the result: The output image will be saved in the output directory.
