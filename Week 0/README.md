# Week 0 — Tooling Warm-Up

Week 0 is all about laying the groundwork so you can focus on reinforcement learning experiments later. By the end of this week you should be confident with the tooling, comfortable iterating on notebooks, and ready to sprint into algorithms.

## Objectives

- Set up a reproducible Python environment for the cohort.
- Refresh core Python concepts that will appear in later weeks.
- Get hands-on with NumPy, Pandas, and Matplotlib.
- Decide how you will package and upload your weekly progress (zip + shared drive/GitHub web upload).

## Before you start

- ✅ Python 3.10+ installed (`python --version`)
- ✅ Access to the shared project folder provided by your mentors

If you are coordinating with teammates, agree on where weekly uploads will live (shared drive folder, GitHub Classroom web uploader, etc.).

## Environment setup

```bash
cd WiDS-2024-Can-Computers-Think-main
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install notebook numpy pandas matplotlib tqdm
```

Create a `notes/` folder (or use your journal) to log what you try, bugs you hit, and ideas for later weeks. This habit makes reflections and demos much easier.

## Learning path

1. **Python refresher** → Work through `python-tutorial.ipynb`. Skim sections you already know, but run the code to ensure your setup works.
2. **NumPy essentials** → Complete `numpy-tutorial.ipynb`. Focus on array operations, broadcasting, random sampling, and vectorised maths.
3. **Pandas practice** → Explore `pandas-tutorial.ipynb`. Pay special attention to indexing, joins, and groupby operations.
4. **Matplotlib mini-project** → Use `matplotlib-tutorial.ipynb` to reproduce a plot from one of your past courses or the RL textbook.
5. **Stretch (optional)** → Recreate an analysis from a dataset you like. Summarise what you learned in two short bullet points.

## Deliverables

- A short update in your cohort channel or doc:
  - What tooling you set up.
  - Which notebooks/tutorials you completed.
  - One screenshot or snippet that made you curious.
- A zipped copy of your updated notebooks uploaded to the agreed weekly drop location.

## Looking ahead

Once you can comfortably read and modify the Week 0 notebooks, jump to `Week 1/README.md`, where you will start implementing the first reinforcement learning algorithms. Keep your Week 0 environment handy—you will reuse it throughout the track.