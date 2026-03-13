
# The Broken Set | Inventory Integrity System
**CodeRift Hackathon 2025 - PS-05 (Supply Chain/Logistics)**

[Live Demo Link](https://broken-set.vercel.app/dashboard)

## 01. The Problem
[cite_start]Wholesale garment businesses lose significant revenue (approx. ₹1.2 lakh/month for medium wholesalers) because existing tools track sets as "atomic units"[cite: 26, 27, 29]. [cite_start]This allows individual pieces to be stolen from within a set during storage or packing without detection[cite: 19, 20].

## 02. Our Solution
[cite_start]We built an inventory integrity system that enforces **piece-level accountability** across the entire stock lifecycle[cite: 50, 51]. [cite_start]Our app ensures that "Stock arrives complete and leaves complete" by creating a digital paper trail for every human touchpoint[cite: 4, 41].

## 03. Core Features (Control Points)
[cite_start]Our system implements the four mandatory control points[cite: 51]:
* **Inward Verification:** Reads supplier bills and logs actual pieces counted per set. [cite_start]Shortfalls are flagged as supplier discrepancies immediately[cite: 53, 54].
* **Storage Integrity:** Every set is tagged (QR/Barcode). [cite_start]Any access or "unbreaking" of a set is logged to a specific staff member[cite: 65, 66, 69].
* **Outward Verification:** A **hard rule** checkpoint. No set can be dispatched without a piece-count scan. [cite_start]Discrepancies block the dispatch and alert the supervisor[cite: 72, 74, 77].
* [cite_start]**Owner’s Reconciliation Dashboard:** A cross-location view of shrinkage trends, variance alerts, and accountability pinned to specific shifts and names[cite: 80].

## 04. Tech Stack
* **Frontend:** [e.g., Next.js / React]
* **Backend:** [e.g., Node.js / Firebase]
* **Database:** [e.g., MongoDB / PostgreSQL]
* [cite_start]**AI Integration:** [e.g., Tesseract OCR for Bill Extraction / Python for Pattern Detection] (Include only if used)[cite: 85, 89].

## 05. How to Run Locally
1. Clone the repo...
2. Install dependencies: `npm install`
3. Set up .env variables...
4. Run: `npm run dev`