# CSE499B-Thesis
Bangla Sign Language Recognition using Multimodal Late Fusion

This project focuses on developing a Bangla Sign Language recognition system using a video dataset. The dataset includes two modalities: video and audio. To achieve robust sign language recognition, we applied a multimodal approach.

Key Steps:

Frame Extraction: We extracted video frames at a rate of 30 frames per second (fps) from the video data, which captures the visual features required for sign language recognition.

Audio Extraction: The audio data from the videos was also extracted and utilized as an additional modality to enhance the recognition process.

Unimodal Models: Separate models were trained on each modality:

Video-based Model: Trained on the extracted video frames to recognize signs from the visual features.

Audio-based Model: Trained on the extracted audio data to capture any audio cues related to the signs.

Multimodal Late Fusion: After training the unimodal models, we applied a multimodal late fusion technique to combine both models' predictions. This fusion technique leverages the complementary strengths of both the video and audio models, improving the accuracy of sign prediction.

The resulting system demonstrates the effectiveness of multimodal learning for recognizing Bangla Sign Language, offering a promising solution for applications in real-time sign language translation and accessibility.
