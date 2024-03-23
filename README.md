# DYSCRIBB
**DYSCRIBB** is a software to detect **Dyslexia** in primary school children of india.
Dyslexia is a learning disability which affects reading and writing of individual.
In India, 15% of school children are affected by this, which accounts for about 35 million children.
We aim to build an application which helps in the early detection of dyslexia in these children. 
# Features
1. User has to input the handwritten text by scaning it and software determines if the word is correct or not.
2. A confidence score is given, that analyses the accuracy of detection.
3. **Audio-check**:
This code announces the stated word and the student has to write it. The handwritten spelling is then scanned and input.
If the written text doesn't match the announced word, the code displays the detected as well as the referenced words.
4. This code processes the image entered and tells the user if it exists or not in the dictionary.
5. If the image exists it specifies the existence of the word but if the word doesn't exist then the suggests the correct word.
6.  Through these techniques, the writing disability among the students can be combatted and the children can be provided with the right resources at the right time.
# Python Libraries used:
1. easyocr
2. pyttsx3
3. OpenCV
4. Matplotlib
5. numpy
6. nltk
7. Spellchecker
