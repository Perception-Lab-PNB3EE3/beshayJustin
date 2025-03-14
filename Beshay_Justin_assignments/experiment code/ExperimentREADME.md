
# Background Noise and Memory Experiment

## Overview

This experiment investigates how different background noises (music, white noise, or silence) affect word memory and recall. Participants are asked to memorize a list of words under one of these conditions, complete a distraction task, and then recall the words.

Note: This experiment is for educational purposes only as part of the PNB 3EE3 course and is not approved for formal research.

---

## Folder Structure and Required Files

To run this experiment properly, you must place all necessary files together inside a folder named `experiment code/`.

### Required Folder Setup

```
experiment code/
│
├── experiment code final.html      # Main experiment code file (HTML)
├── music.mp3                      # Audio file for music condition
└── white_noise.mp3                # Audio file for white noise condition
```

Important:
- All files must be kept together in the same folder to ensure the experiment runs smoothly.
- The audio files are automatically used based on the randomly assigned condition — they will not load if they are not in the same folder as the HTML file.

---

## How to Run and Use the Experiment

### To Run the Experiment:

1. Download all necessary files listed above.
2. Place them in a single folder named `experiment code/`.
3. Open the `experiment code` folder on your computer.
4. Double-click `experiment code final.html` to launch the experiment in a web browser.
5. It is recommended to use Google Chrome for best performance.

---

### How to Interact with the Experiment:

- Read all instructions carefully on each screen.
- Participants must meet the eligibility criteria by checking a confirmation box:
  - Age 18+
  - Fluent in English
  - Normal or corrected-to-normal hearing
  - Use of a computer (no mobile devices)
- Participants are recommended to be in a quiet environment with volume turned up.
- After consenting, participants will proceed through practice tasks, study phases, and recall phases.
- Responses (e.g., typed words, answers to demographic questions) will be collected as part of the experiment.

---

## What Happens After the Experiment?

- Once the experiment is completed, a summary of the participant's responses will be shown on a results screen.
- A CSV file (`PNB3EE3_filtered_data.csv`) will automatically download, containing:
  - Recalled words
  - Response time for recalling words
  - Age, gender, and study habits
  - Familiarity rating (if in the music condition)
  - Assigned condition (music, white noise, silence)

Important Note:
- If participants do not consent, the experiment will close automatically, and no data will be saved.

---

## How the Code Works (Brief Explanation for Developers)

- Condition Assignment: Participants are randomly assigned to one of three background noise conditions: music, white noise, or silence.
- Audio Handling: The appropriate audio file is played automatically based on the assigned condition.
- Study Phase: All words are shown on screen while the audio plays.
- Distractor Task: Math problems are included to prevent rehearsal.
- Recall Task: Participants type all words they remember.
- Data Saving: Relevant participant data is automatically downloaded as a CSV file for later analysis.

---

## Technical Notes and Recommendations

- The experiment is designed to run locally on a computer.
- Internet connection is not required after downloading the files.
- Use Google Chrome or another modern browser for best performance.
- Participants should ensure:
  - Volume is on and adjusted to a comfortable level.
  - Quiet environment without distractions.

---

## Contact for Questions

If you have questions about the experiment, setup, or code, please contact:

Email: beshayj@mcmaster.ca

---

## License & Permissions

This experiment is designed for course-based educational purposes only and should not be distributed for research or commercial use without permission.
