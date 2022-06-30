# Android-App-for-Text-Recognition (Tfinder!!)
I have developed an android app that can recognize and detect text from images using Vision API.
There are two annotation features that support optical character recognition (OCR):
  1. TEXT_DETECTION detects and extracts text from any image. For example, a photograph might contain a street sign or traffic sign. The JSON includes the entire extracted string, as well as individual words, and their bounding boxes.
  2. DOCUMENT_TEXT_DETECTION also extracts text from an image, but the response is optimized for dense text and documents. The JSON includes page, block, paragraph, word, and break information.
The app also has the functionality to detect and display real-time data from sensors (i.e. listed below) embedded in the mobile device.

Sensors:
  Accelerometer,
  Gyroscope,
  Magnetometer,
  Light Sensor,
  Proximity Sensor
