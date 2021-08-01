# Speech Emotion Analyzer

## Description
Created as an Applied Deep Learning Trainee as part of the MIT FutureMakers program, a collaboration between the MIT RAISE initiative and SureStart. More information on my work during the program can be found here: [https://github.com/mferuscomelo/mit-futuremakers](https://github.com/mferuscomelo/mit-futuremakers)

Model trained by [MITESHPUTHRANNEU](https://github.com/MITESHPUTHRANNEU/Speech-Emotion-Analyzer)

## Notes
### Install PyAudio on Windows
1. Navigate to [https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) and download the `.whl` that matches your python version. For example, if you are running python 3.9.5, you would download `PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl`.
2. Open your terminal and navigate to the folder where the PyAudio wheel is saved. For example, if the file is in the `Downloads` folder, type `cd Downloads` and press enter.
3. Execute `pip3 install NAME_OF_FILE`, making sure to replace `NAME_OF_FILE` with the name of the file you downloaded. For example, if your file name is `PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl`, execute `pip3 install PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl`.

### Decoding model output
| Number | Label          |
|--------|----------------|
| 0      | female_angry   |
| 1      | female_calm    |
| 2      | female_fearful |
| 3      | female_happy   |
| 4      | female_sad     |
| 5      | male_angry     |
| 6      | male_calm      |
| 7      | male_fearful   |
| 8      | male_happy     |
| 9      | male_sad       |