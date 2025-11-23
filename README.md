## CMSE202-f25-Honors-Project
This project models triathlon performance using object-oriented Python classes for swimming, biking, and running. It incorporates physiological metrics such as VO₂ max, resting heart rate, fatigue, and training hours to predict race outcomes.

## Requirements
- Python
- Libraries: 'matplotlib,' 'numpy,' 'seaborn,' 'random'
  
## Features
- Predicts triathlon finishing times based on athlete background (swimmer, biker, runner).
- Compares outcomes across Olympic and Sprint triathlon distances.
- Visualizes relationships between VO₂ max, resting heart rate, training hours, and finishing time.
- Includes z-score normalization for sex-specific comparisons.
  
## Limitations
- Current model does not account for age or gender differences.
- Training quality is not distinguished from training volume.
- Data used for sprint triathlon comparisons is limited to females ages 18–24.

## How to Use
1. Clone the repository and install requirements:
   - git clone https://github.com/yourusername/triathlon-outcomes.git
2. Run the simulation
3. Adjust metrics:
   - Change swim, bike, and run paces by editing the Triathlete class inputs.
   - Modify VO₂ max, resting heart rate, fatigue, and training hours to see how they affect predicted finishing times.
