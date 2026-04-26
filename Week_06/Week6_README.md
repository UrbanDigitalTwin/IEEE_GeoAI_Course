# Week 6: Urban Flood Depth Estimation Pipeline

This folder contains the notebook and supporting material for this week of the course.

## 📘 Weekly Overview
This week presents the end-to-end urban flood depth estimation pipeline by combining vehicle-centered crops, enhancement logic, per-crop prediction, and weighted aggregation.

## 📓 Main Notebook
`week06_urban_flood_depth_estimation_pipeline.ipynb`

> Add a Google Colab badge here if you want students to open the notebook directly from GitHub.

```markdown
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](ADD-YOUR-COLAB-LINK-HERE)
```

## 🎯 Learning Goals
- understand the stages of a multi-step flood pipeline
- understand why enhancement may help small crops
- interpret crop-level flood predictions
- combine crop predictions into a stable scene-level output

## 🧩 Main Topics
- crop expansion
- small-crop enhancement logic
- per-crop severity prediction
- confidence × area weighting
- scene-level flood estimate
- annotated outputs

## 🛠 Recommended Tools
- Google Colab
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Optional: `ultralytics`
- Optional: `opencv-python`

## 📂 Suggested Folder Contents

```text
Week6/
│
├── README.md
├── week06_urban_flood_depth_estimation_pipeline.ipynb
├── data/              # optional week-specific data
├── outputs/           # generated results, plots, logs
└── images/            # optional figures or visuals
```

## ✅ Expected Outputs
- per-crop flood-level predictions
- aggregation tables
- final scene-level flood estimate
- annotated output visualization

## 🧠 Weekly Workflow
1. Read the notebook overview and learning objectives
2. Run the notebook from top to bottom
3. Review the figures, tables, and outputs carefully
4. Complete the mini exercise
5. Complete the weekly assignment or modification task
6. Save outputs or notes for later weeks

## 📝 Assignment Guidance
Students should submit or document:
- the completed notebook
- written responses to the mini exercise
- weekly assignment output or modifications
- short interpretation of what they learned

## 🔍 Practical Relevance
This week shows how multiple visual processing steps combine into a full urban flood estimation workflow.

## 🔗 Connection to the Course
Week 6 is the core pipeline week where earlier concepts are combined into one operational workflow.

## 🚀 Suggestions for Extension
Possible extensions for this week:
- add more data examples
- improve visualizations
- compare alternative methods
- connect outputs to a later week
- document assumptions clearly

## 🤝 Contribution Ideas
You can improve this week by contributing:
- clearer instructions
- cleaner plots
- better comments in code
- more realistic datasets
- alternative student exercises
