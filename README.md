Project description will go here

The following artefacts define this project:
- Open-ended data wrangling and exploration notebooks in `/research_notebooks`
- Finalised notebooks for sharing and presentation in `/final_notebooks`
- PowerPoint slides for stakeholder presentation in `/final_reports`
- Saved high DPI figures in `/figs`
- Raw data in `/data`
- Single python scripts in `/scripts`, which can be run to perform the data wrangling, analysis and visualisation in a single step. Assumes source data exists in `/data`. Run `step1_wrangle.py` first to wrangle the data, then `step2_eda.py` within the same directory. Step 1 outputs a cleaned CSV which will be input to step 2.