# County Rainfall and Planting Advisory

**Author:** Chepkirui Joyce Ngetich  
**Cohort:** PLP Data Analytics Cohort, 2026  

## Project Summary
This project cleans raw monthly rainfall records from a farmer-support NGO across five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, and Machakos), builds a 5 × 12 NumPy array, computes annual totals, monthly averages, wettest months, dry-month counts, and consecutive two-month planting windows, and exports `rainfall_summary.csv`.

## How to Run
Open `rainfall_analysis.ipynb` in Google Colab, install dependencies from `requirements.txt` (`pip install -r requirements.txt`), and click **Runtime → Restart and run all**.

## Planting Advisory
* Nairobi, Nakuru, Kisumu, and Mombasa share an April–May peak planting window, while Kisumu leads annual rainfall at 1,371 mm with 0 dry months.
* Machakos should target a November–December planting window (278 mm combined across the two months) and prepare for 6 dry months below 50 mm.
* Because Machakos had two missing/invalid entries (April `"N/A"` and September `""`) imputed at 68 mm, NGO field teams should verify station logs before finalizing seed dispatch.
