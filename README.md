

# CPP-Driver Drowsiness Detection


# Driver Drowsiness Detection

This project aims to detect driver drowsiness using computer vision and deep learning techniques. It uses a webcam to capture the driver's face and eyes and checks whether the driver's eyes are closed for more than 10 seconds. If it detects that the driver's eyes have been closed for a prolonged period, it triggers an alarm to alert the driver to wake up.

The project is developed using the following technologies:

* OpenCV for computer vision tasks
* Keras for building and training the deep learning model
* Pygame for playing the alarm sound
* Haar Cascades for detecting the face, left eye, and right eye of the driver

## Getting Started

To get started with this project, you need to have Python 3 installed on your system. Then, you need to install the following packages:

* OpenCV
* Keras
* Pygame

You can install these packages using pip.

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs">pip install opencv-python keras pygame
</code></div></div></pre>

## Usage

To run this project, execute the following command:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs">python drowsiness_detection.py
</code></div></div></pre>

This will open the webcam, and the program will start detecting the driver's drowsiness.

## Acknowledgments

This project is inspired by [this tutorial](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/) by Adrian Rosebrock.
