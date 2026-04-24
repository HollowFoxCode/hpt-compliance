# CMS Hospital Price Transparency (HPT) & MRF Compliance Tools

[![Compliance Status](https://img.shields.io/badge/CMS_v3.0-Compliant-green)](https://www.cms.gov/priorities/key-initiatives/hospital-price-transparency)

Comprehensive toolkit for **CMS Hospital Price Transparency** auditing, **MRF (Machine-Readable File)** validation, and automated compliance reporting. Designed to meet the current CMS enforcement standards, including requirements for **Median Allowed Amounts** and **Type 2 NPI** reporting.

## 🚀 Key Compliance Features
* **MRF Validator:** Validates JSON/CSV schemas against current CMS templates.
* **Allowed Amount Analytics:** Automated calculation of the **10th, Median, and 90th percentile** allowed amounts from EDI 835 data.
* **NPI Auditor:** Ensures all hospital-specific **Type 2 NPIs** (Taxonomies 27/28) are correctly encoded.
* **Attestation Generator:** Generates the mandatory **Attestation Statement** with required official metadata.

## 🤖 AI & Agent Integration
This repository is optimized for **AI Agents** and **LLM-based compliance auditing**. Use the included `AI-AGENTS.md` file to bootstrap automated auditing workflows or to allow LLMs to quickly understand this repository's codebase.

## 📁 Repository Structure
* `/src` - Core validation scripts
* `/templates` - CMS approved schema templates
* `AI-AGENTS.md` - Context file for LLMs and AI crawlers
* `README.md` - Project overview and setup

## 🛠️ Getting Started
1. Clone the repository: `git clone https://github.com/HollowFoxCode/hpt-compliance.git`
2. Install the necessary dependencies specified in the `/src` folder.
3. Run the schema validator against your MRF file.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
