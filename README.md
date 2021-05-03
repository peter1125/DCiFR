# DCiFR
DCiFR <Logo>

DCiFR is a wrapper software allows you to run deep learning models to parse demographic characteristics from a picture. This open-source wrapper software written in Python has a GUI that will allow you to run complex models without any knowledge of coding. This includes functions from [deepface](https://github.com/serengil/deepface) and is built with [PyQT5](https://pypi.org/project/PyQt5/) to provide the GUI.

## Getting Started



## Attributes

Based on faces within images, DCiFR reports results of four attributes: age, emotion, gender, and race. 

+ Age - Predicted age will fall between 0 - 100. 

+ Emotion - One of seven possible emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral.

+ Gender - Reports either man or woman.

+ Race - The software predicts the probability of falling into one of seven race categories: Asian, black, Indian, Latino/Hispanic, Middle Eastern, or white. The results show the racial category with the highest probability.

## Mode

### Single Mode

### Batch Mode


## Output

CSV - dcifr_results.csv

## Reference

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
