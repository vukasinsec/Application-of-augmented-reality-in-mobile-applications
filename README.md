# *Application of augmented reality in mobile applications*

## **Overview**

This repository contains the source code for two Augmented Reality (AR) applications: Pokemon3D and MagicPaper. These applications demonstrate the implementation of AR technology using iOS devices, specifically iPhone, with the macOS operating system, Xcode IDE, and Swift programming language.

## **Pokemon3D**

Pokemon3D is an AR application that allows users to interact with 3D models of Pokemon characters overlaid on real-world surfaces using AR technology. The development of the application is divided into three phases:

1. **Image Recognition**: Users capture high-resolution images of Pokemon cards, which are then imported into the application. The ARImageTrackingConfiguration is utilized to recognize these images in real-time.
2. **3D Model Conversion**: 3D models of Pokemon characters are converted into the USDZ file format, which is compatible with ARKit. The Reality Converter tool or online converters can be used for this purpose.
3. **Integration**: The 3D models are linked to the corresponding images using scene nodes. Once integrated, the application is ready for use.

![GitHub Logo](gifs/pokemon.gif)

## **MagicPaper**

MagicPaper is a simpler AR application that replaces a static image with a dynamic video overlay using AR technology. The process involves:

1. **Video Integration**: Users select a video in .mp4 format and prepare an image to replace with the video. The SKVideoNode declaration is used to connect the video with AR technology.
2. **Scene Adjustment**: It's crucial to adjust the scene resolution and size to ensure proper display of the video overlay using the SKScene declaration.

![GitHub Logo](gifs/novine.jpg)

## **Purpose**

These applications aim to introduce users to modern technologies, particularly AR. With over 13 million downloads of AR-enabled applications, the future of this technology appears promising.

## **Installation**

To run these applications, ensure you have the latest version of Xcode installed on macOS. Clone this repository and open the project files in Xcode. Follow the instructions provided in the respective application folders for further setup and deployment instructions.

For more information on AR technology, refer to the provided literature and resources.
