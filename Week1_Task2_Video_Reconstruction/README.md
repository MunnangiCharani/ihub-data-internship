Task 2: Video Reconstruction
In this task, I reconstructed a video using extracted frames.

Process
- Extracted frames at 30 fps (~1800 images)
- Reconstructed video using FFmpeg

Command Used
ffmpeg -framerate 30 -i frame_%04d.jpg output_video.mp4

Output
Video generated successfully from frames.

Learning Outcome
Learned how to reconstruct a video from image frames.

The video was reconstructed successfully from extracted frames.But,
Due to file size constraints, the video was compressed before uploading while maintaining acceptable quality.
