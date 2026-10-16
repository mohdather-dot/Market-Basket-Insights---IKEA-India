# Beyond the Allen Key: Restoring Omnichannel Profitability for IKEA India
**Precision Retail Marketing Analytics | Marketing Mix Modelling (MMM) • Market Basket Analysis (MBA) • Perceptual Mapping (PCA)**

📄 **[View Full Executive Presentation (PDF)](Presentation_Mohd_Ather_Rahim_25221125.pdf)** | 📊 **Tools:** Python (`Scikit-Learn`, `Pandas`), L2 Ridge Regression, Apriori Algorithm, PCA, Microsoft Power BI

---

## 📌 Executive Summary & Business Impact
IKEA India's omnichannel expansion faced a tri-fold profitability crisis: **paid media saturation** (66.7% of the ₹196.3 Cr budget locked in Meta & Search), **negative last-mile delivery economics** (35.7% single-item online carts at ₹4,200 AOV with 8%–15% freight drag), and **cultural resistance to DIY flatpack assembly**.

This project deploys a three-pillar analytical engine to restore unit economics:
* **Pillar 1 (MMM):** Reallocating **₹7.0 Cr** from saturated channels to high-mROAS drivers unlocks **+₹14.99 Cr in net incremental revenue (+13.5% lift)** at **₹0 extra budget**.
* **Pillar 2 (MBA):** Mining **1,222 carts** via 2-Stage Apriori uncovers **22 high-lift cross-sell bundles**, expanding online AOV by **+21.4% (₹4,200 → ₹5,100+)** and eliminating single-item delivery losses.
* **Pillar 3 (PCA):** Mapping **N = 450** metro survey responses isolates an underserved **"Affordable Turnkey" whitespace**, bridging DIY friction via subsidized doorstep installation.

---

## 📊 Executive Power BI Governance Dashboard
<!-- DRAG AND DROP YOUR SLIDE 8 POWER BI DASHBOARD SCREENSHOT BELOW THIS LINE -->
![IKEA India Power BI Dashboard](assets/powerbi_dashboard.png)

---

## 🔍 Analytical Pillars & Key Findings

### 1. Marketing Mix Modelling (L2 Ridge Regression & Adstock Decay)
* **Challenge:** Severe customer acquisition cost (CAC) inflation and diminishing returns in Meta (`0.85x mROAS`) and Google Paid Search (`1.12x mROAS`).
* **Methodology:** Modeled 104 weekly observations across 5 channels incorporating geometric Adstock memory carryover ($\lambda$) and L2 Ridge Regression with 5-fold cross-validation to resolve festive multicollinearity.
* **Model Diagnostics:** `R² = 0.9971` | `Adj R² = 0.9969` | `MAPE = 1.75%` | `Optimal α = 0.0518`
* **Actionable Shift:** Cut Meta (-₹5.0 Cr) and Search (-₹2.0 Cr); reinvest into WhatsApp CRM (+₹3.0 Cr at `4.15x mROAS`), YouTube/CTV (+₹2.5 Cr at `2.35x`), and Influencers (+₹1.5 Cr at `2.10x`).

<!-- DRAG AND DROP YOUR ADSTOCK & SATURATION CURVE IMAGE (image_3bd3e1.png) BELOW THIS LINE -->
![MMM Adstock and Saturation Curves](assets/mmm_curves.png)

---

### 2. Market Basket Analysis (Two-Stage Apriori Pattern Mining)
* **Challenge:** 35.7% of online orders contained single low-ticket items, resulting in a `-₹110` net delivery margin per order after last-mile freight costs.
* **Methodology:** Mined 2,489 transaction lines across 1,222 carts (`Support ≥ 10%`, `Confidence ≥ 25%`, `Lift > 1.20`), isolating 22 association rules across *Home Workspace*, *Modular Storage*, *Living Accent*, and *Tableware*.
* **Impact:** Pre-packaged room suites (e.g., *MICKE Desk + LOBERGET Chair + SIGNUM Cable Trunking*, `Lift = 4.48x–6.75x`) lift multi-item cart conversion to **55.0%** and compress freight cost to **7.9%–12.3%** of order value.

<!-- DRAG AND DROP YOUR SLIDE 5 OR SLIDE 6 MBA CHART BELOW THIS LINE -->
![MBA Apriori Rules and Unit Economics](assets/mba_economics.png)

---

### 3. Strategic Perceptual Mapping (Construct-Level PCA)
* **Challenge:** 85%–90% of Indian furniture retail offers free carpenter installation, trapping IKEA in high DIY assembly friction (`X = -1.73`) despite holding the highest design modernity score (`6.6 / 7.0`).
* **Methodology:** Applied Principal Component Analysis across 450 consumers in 5 metro cities (`54.3% variance explained` on Component 1: Fulfillment & Service Model).
* **Strategic Repositioning:** Bundling subsidized doorstep assembly (self-funded by multi-item room suite margins) shifts IKEA into the uncontested **"Affordable Turnkey" whitespace (`X = +0.85, Y = 3.10`)**.

<!-- DRAG AND DROP YOUR SLIDE 7 PERCEPTUAL MAP IMAGE BELOW THIS LINE -->
![PCA Strategic Perceptual Map](assets/pca_perceptual_map.png)