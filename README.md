# ISL-translator-using-Mediapipe-FFCResNet-BiLSTM-
                
                 Indian Sign Language (ISL) is the primary mode of communication for the Deaf community in India.Our proposed system converts Indian Sign Language to text/speech using Mediapipe Hands, FFCResNet, BiLSTM and TTS.The proposed system offers an affordable, scalable, and accessible solution to empower the Deaf community in the real time.
Our dataset consists of 76 gestures related to doctor patient interface, letters, numbers and greetings which are pre-processed using MediaPipe Hands, that detects 21 landmarks on each hand. FFCResNet  which combines the global features in the frequency domain with the multi-scale local features in the spatial domain and achieves results with high accuracy , is utilized for feature extraction from the hand landmarks. BiLSTM helps in capturing the temporal dependencies between different gestures over time. The recognized gesture text is converted to speech using text to speech engine. We develop a web application for user interface.            
               ![WhatsApp Image 2024-09-10 at 4 09 49 PM (1)](https://github.com/user-attachments/assets/9185a1a4-2e16-4be7-b56e-5ebc641a84a7)
                                                        This is the Mediapipe hands output.


        MediaPipe Hands is a high-fidelity hand and finger tracking solution. It employs machine learning (ML) to infer 21 3D landmarks of a hand from just a single frame. Whereas current state-of-the-art approaches rely primarily on powerful desktop environments for inference, our method achieves real-time performance on a mobile phone, and even scales to multiple hands.

