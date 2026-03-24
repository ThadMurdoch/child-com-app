Summary
Single Sentence: This code creates a high-contrast web interface that uses the MediaPipe Face Landmarker to interpret mouth opening as a "scroll" command and eye closing as a "speak" command.

Paragraph: The application loads the MediaPipe machine learning models directly into the browser to track 478 3D facial landmarks in real-time. It calculates the distance between the inner lips and the aperture of the eyelids. When these values cross a calibrated threshold, the app triggers a visual highlight change or utilizes the Web Speech API to announce the selected phrase through the device's speakers.

Scientific Abstract
The implementation of touchless human-computer interfaces (HCI) for individuals with severe motor impairments can be achieved through computer vision-based gesture recognition. This implementation utilizes the MediaPipe Face Landmarker via a CDN-delivered JavaScript framework. The algorithm employs a normalized Euclidean distance between specific landmark indices (13, 14 for mouth; 159, 145 for eyes) to determine intent. By utilizing client-side processing, the system minimizes latency and ensures data privacy, which is critical for assistive technology in home-care environments.

Executive Summary: "Cyrus" Assistive Communicator
Functionality:

Mouth Open: Moves the yellow selection box to the next phrase.

Both Eyes Closed (0.5s): Selects the phrase and speaks it.

Interface: High-contrast (Yellow on Black) for CVI (Cortical Visual Impairment) support.

Instructions for Use:

Placement: Mount the phone/tablet securely in front of the child's face.

Lighting: Ensure the face is well-lit from the front, not the back.

Calibration: Use the "Sensitivity" sliders if the app is too twitchy or not responsive enough.
