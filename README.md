# DCiFR

![](https://github.com/peter1125/DCiFR/blob/main/logo.png)

DCiFR (Demographic Characteristics in Facial Recognition) is a wrapper software allows you to run deep learning models to parse demographic characteristics from an image. This open-source wrapper software written in Python has a GUI that will allow you to run complex models without any knowledge of coding. This includes functions from [deepface](https://github.com/serengil/deepface) and is built with [PyQT5](https://pypi.org/project/PyQt5/) to provide the GUI.

## Getting Started

Dependencies for running DCiFR include deepface, and PyQT5.

Run
```
pip install deepface
```
and 
```
pip install PyQt5
```
to get started. 

## Attributes

+ Age

+ Race

+ Gender

+ Emotion


## Mode

Two different modes are supported on DCiFR. 

+ Single Mode: Upload and get the results for a single image. 
+ Batch Mode: Analysis of a multiple images at once. Select a folder to analyze in batch mode.


## Output
The results will be saved in the working directory as *dcifr_results.csv*

## Reference

+ [deepface](https://github.com/serengil/deepface)
+ [PyQT%](https://pypi.org/project/PyQt5/)

## License

    DCiFR: Demographic Characteristics in Facial Recognition.
    Copyright (C) 2021  Melina Raglin, Eungang (Peter) Choi, Erick Axxe

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
