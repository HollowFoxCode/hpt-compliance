# hpt-compliance
hpt-compliance.com - 2026 HPT Compliance

# The Simple Guide: CMS HPT v3.0 Percentile Calculation

Under the April 1, 2026 enforcement rules, hospitals are no longer allowed to just list a "standard rate." You must now provide **Historical Percentiles** based on the last 12 months of actual payments.

### Step 1: The Raw Data Ingestion
Collect all of your **EDI 835 (Electronic Remittance Advice)** files from the last 12 months. This is where the real "Allowed Amounts" live. 

### Step 2: The Grouping
Sort every transaction by:
* **Payer** (e.g., Blue Cross)
* **Plan** (e.g., PPO Gold)
* **Code** (CPT, HCPCS, or DRG)

### Step 3: The Math (The "10/50/90" Rule)
For every specific service, you need three numbers:
1.  **10th Percentile:** The rate where only 10% of payments were lower. This shows the "low end" of what you get paid.
2.  **50th Percentile (Median):** The exact middle. This is the most important number in the v3.0 schema.
3.  **90th Percentile:** The rate where 90% of payments were lower. This shows your "top tier" pricing.

### Step 4: The Encode
These numbers must be placed into the "Plain CSV" or "Tall" format required by CMS. If you don't use the exact headers defined in the v3.0 Data Dictionary, the **CMS CLI Validator** will reject your file instantly.

---
**Need help with the transformation?**
Visit [HPT-Compliance.com](https://hpt-compliance.com) for automated EDI-to-MRF processing.
