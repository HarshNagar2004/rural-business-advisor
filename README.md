# Rural Business Advisor

A data-driven rural business decision-support platform for Maharashtra
(initial districts: Nagpur, Pune, Latur).

## 1\) Place datasets

Copy the 8 CSV files into `backend/data/datasets/`:

* pca\_villages.csv
* village\_clustering\_dataset (1).csv
* b04\_processed.csv
* b24\_processed.csv
* crop\_area\_processed.csv
* crop\_production\_processed.csv
* dairy\_development\_2010\_11 (1).csv
* village\_amenities\_processed (1).csv

## 2\) Backend

cd backend
python -m venv venv
venv\\Scripts\\activate           # Windows
pip install -r requirements.txt
python train.py
uvicorn main:app --reload

## 3\) Frontend

cd frontend
npm install
npm run dev

Open http://localhost:5173

\---

## License \& Copyright

© 2026 **Code Ninjas** (Team ID 056)
SIH 2026 · Problem Statement ID 26091

All Rights Reserved.

This project is submitted to Smart India Hackathon 2026.
Unauthorized copying, distribution, or commercial use of this
project without written permission from the team is prohibited.

**Contact:** \[nagarh285@gmail.com]

