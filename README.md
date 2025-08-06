# MP4VI
MP4VI is a Python Jupyter application that makes it easy to convert AVI video files to MP4. It also provides several configurable parameters to customize the conversion process.

## Usage

1. Upload your video file to the notebook environment.

2. Run the Lib command to load the necessary libraries.

3. In the App script, you can customize the conversion:

    * **Filename**: Match the file_name variable to your uploaded video's filename (e.g., `my_example_video.avi`). This will be the name of the final MP4 file (e.g., `my_example_video.mp4`).

    * **Quality**: Adjust key parameters to balance file size and quality.

      * `crf` (Constant Rate Factor): Controls video quality.

      * `preset`: Manages the encoding speed versus compression efficiency.

      * `b:a` (Audio Bitrate): Sets the audio quality.

4. Run the script to begin the conversion and generate your downloadable MP4 file.

## Open Source
MP4VI is an open-source project. Feel free to fork the repository, explore the code, and contribute to its development!

## License
This project is licensed under the [MIT License](LICENSE) – see the [LICENSE file](LICENSE) for details.
