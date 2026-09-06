# Accelerator and Market Access Mock JSON Datasets

This directory contains high-fidelity mock JSON payloads for the **National Enterprise Development and Market Access Operating System**. These datasets represent realistic business development profiles, operational outcomes, and supply chain mappings within the Zambian trade ecosystem.

## 📂 Dataset Catalog

### 1. `applications.json`
* **Entity Mapping:** `StartupApplication`
* **Purpose:** Outlines incoming startup profiles, including founder credentials, SDG alignments, pitch decks, and AI scoring recommendations.
* **Key Context:** Mwamba Poultry Solutions (Agribusiness) and Kasama Garment Cooperatives (Manufacturing).

### 2. `assessments.json`
* **Entity Mapping:** `StartupAssessment`
* **Purpose:** Evaluates incoming startups across the 9 required categories (Innovation, Market, Team, Finance, Impact, Export, Jobs, Sustainability, and Technology).

### 3. `opportunities.json`
* **Entity Mapping:** `ContractOpportunity`
* **Purpose:** Lists recurring contract announcements from large corporations, mining companies, and retail off-takers (e.g., Shoprite, Konkola Copper Mines, and Lusaka Grand Hotel).

### 4. `contracts.json`
* **Entity Mapping:** `ActiveBusinessContract`
* **Purpose:** Tracks contract execution milestones, values, delivery confirmations, and milestone payments.

### 5. `performance.json`
* **Entity Mapping:** `StartupPerformanceRecord`
* **Purpose:** Collects monthly performance metrics (Revenue, Profit margin, and employment indicators for women, youth, and rural populations).

### 6. `risk-alerts.json`
* **Entity Mapping:** `OperationalRiskAlert`
* **Purpose:** Monitors operational health parameters and triggers alerts (e.g., working capital cash shortages) to initiate early mentorship interventions.

### 7. `starter-packs.json`
* **Entity Mapping:** `BusinessStarterPack`
* **Purpose:** Standardizes standard enterprise setups (Poultry Layers, Industrial Stitching units) detailing equipment lists (BOMs) and required regulatory licenses.

### 8. `campaigns.json`
* **Entity Mapping:** `InvestmentCampaign`
* **Purpose:** Details SME bond listings, crowdfunding, and debt tickets on the Startup Exchange.

### 9. `anchors.json`
* **Entity Mapping:** `AnchorBuyerProfile`
* **Purpose:** Profiles anchor corporations, their recurring HS-Code needs, and SME procurement commitments.

### 10. `national-summary.json`
* **Entity Mapping:** `NationalDevelopmentSummary`
* **Purpose:** Houses aggregated national economic outcomes (aggregate SME revenue, jobs created, and import substitution value).
