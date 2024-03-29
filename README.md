
---

# MCQ Assistant Tool
![image](https://github.com/MY-EG/MCQ_Assistant_Tool/assets/158834031/d158b764-1de7-4cc2-bfe1-6b5170e7bbdf)




## Overview
The MCQ Assistant Tool is a Python script that assists in managing multiple-choice questions (MCQs) by generating scripts for setting answers and correcting them through a graphical user interface (GUI).

## Features
- **Set Answers Script**: Generates a script (`Set Answers (Number).py`) for setting correct answers to MCQs.
- **Correction GUI Script**: Generates a script (`Correction Machine (Number)GUI.py`) for correcting MCQ answers through a graphical interface.


## Requirements
- Python 3.x
```sh
pip install pyautogui
```

## Usage
1. **Setup**:
   - Ensure you have Python installed on your system.
   - Clone or download the repository to your local machine.


2. **Generate Scripts**:
   - Run the `MCQ_Assistant_Tool.py` script.
   - Enter the number of questions when prompted and click "Start" or press Enter.
   - You can enter at least 5.

![image](https://github.com/MY-EG/MCQ_Assistant_Tool/assets/158834031/95fa36bf-d4e1-4746-a28f-001274dcb399)

   - Two Python scripts will be generated:
     - `Set Answers (Number).py`: Use this script to input the correct answers.
     - `Correction Machine (Number)GUI.py`: Use this script to correct the answers through a graphical interface.

4. **Set Answers**:
   - Execute the `Set Answers (Number).py` script using Python.
   - Enter the correct answers for each question when prompted.
   - Once all answers are entered, the script will close automatically.
   - You can use uppercase letters, lowercase letters and numbers
   - A=a=1
   - B=b=2
   - C=c=3
   - D=d=4
   - E=e=5

![image](https://github.com/MY-EG/MCQ_Assistant_Tool/assets/158834031/04a4477b-744a-4e9b-947e-54992141dab4)

4. **Correct Answers**:
   - Run the `Correction Machine (Number)GUI.py` script using Python.
   - Use the graphical interface to input the answers.
   - The correctness of each answer will be displayed alongside the question.
   - You can also use here uppercase letters, lowercase letters and numbers
   - The correctness of each answer will be displayed (correct: ✔️, incorrect: ❌) alongside the question.
   - The overall score will be displayed at the top.
   - The score table background color changing with the score high.
   - 0-50 red
   - 50-75 orange
   - 75-100 green


![image](https://github.com/MY-EG/MCQ_Assistant_Tool/assets/158834031/ba261c65-ec60-4feb-ab83-6cfdfc8c10ea)



## Disclaimer
This script is provided as-is and may require adjustments to fit specific use cases. Please review and understand the code before executing it, especially if using it in a production environment.

## Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.


---
