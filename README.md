# Analyzing Workout Patterns

Compare cardio vs. strength training using public datasets.  
Includes a Jupyter Notebook, CSV data (downloadable from Releases), and a short PDF write-up.

---

## 📦 What’s in this repo
- `notebooks/analysis.ipynb` — main notebook
- `reports/midterm.pdf` — write-up
- `requirements.txt` — Python dependencies
- Data (two CSVs) — **hosted in GitHub Releases** (see below)

---

## ⬇️ Get the data (easy)
Download both CSVs from the **Data files v1** release:

- Small CSV: **cardioActivities.csv**  
  <https://github.com/samiksha756/analyzing-workout-patterns/releases/tag/data-v1>  
  Direct link: `<PASTE_CARDIO_CSV_URL_HERE>`

- Large CSV: **openpowerlifting_090afd8.csv.gz** (or `.csv`)  
  <https://github.com/samiksha756/analyzing-workout-patterns/releases/tag/data-v1>  
  Direct link: `<PASTE_OPENPOWERLIFTING_CSV_URL_HERE>`

Place both files in a local folder named `data/` at the repo root:
```
analyzing-workout-patterns/
├─ data/
│ ├─ cardioActivities.csv
│ └─ openpowerlifting_090afd8.csv.gz
├─ notebooks/
│ └─ analysis.ipynb
├─ reports/
│ └─ midterm.pdf
├─ requirements.txt
└─ README.md
```

### One-liner downloads
```bash
# create data folder
mkdir -p data
# download both files (replace the URLs below with your direct asset links)
curl -L "<PASTE_CARDIO_CSV_URL_HERE>" -o data/cardioActivities.csv
curl -L "<PASTE_OPENPOWERLIFTING_CSV_URL_HERE>" -o data/openpowerlifting_090afd8.csv.gz
