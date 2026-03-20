# Credits
- Some of the code for captioning was borrowed from this [YouTube tutorial](https://www.youtube.com/watch?v=LWrRJx2wdWc) which does a similar task.

# Setup
1) Clone the repository
```
git clone https://github.com/chengyili2005/GenSubtitles.git
```
2) Download this font
- Download [arial.ttf](https://github.com/kavin808/arial.ttf) and drag into `temp/`

3) Install dependencies (I recommend make a [conda environment](https://docs.conda.io/projects/conda/en/stable/index.html) for these requirements)
```
pip install -r requirements.txt
```

# Usage
- Best used through VSCode for easier text editting
- In a terminal:
  ```
  python3 main.py [input_video_path] [output_directory]
  ```
- Half-way through the script, it will prompt you to make some edits to the subtitles. Listen to the video and follow the transcript to fix any errors.
- Lines can be found in output/[input_file].txt (Make sure to save the file before continuing the script).

For learning and entertainment purposes only. 

