# Market-Basket-Insights---IKEA-India
Precision Retail Marketing Analytics for IKEA India. Addressing CAC inflation, small-basket delivery deficits, and flatpack assembly friction via Marketing Mix Modelling, Apriori Basket Mining, and Strategic Perceptual Repositioning.
1. Marketing Mix Modelling (MMM)
Challenge: IKEA India faced paid media saturation, with 66.7% of its ₹196.3 Cr budget (₹130.9 Cr) locked in over-invested Meta and Google Search channels, yielding diminishing returns (0.85x and 1.12x mROAS) and eroding margins.
Action Taken: We modeled 104 weekly observations across five media channels, applying Adstock memory decay and L2 Ridge Regression with 5-fold cross-validation to resolve festive multicollinearity.
Results Derived: Shifting ₹7.0 Cr away from Meta and Search into high-return WhatsApp CRM (4.15x mROAS), YouTube (2.35x), and Influencers (2.10x) unlocked +₹14.99 Cr in net revenue (+13.5% lift) at zero extra budget.
2. Market Basket Analysis (MBA)
Challenge: IKEA suffered negative last-mile delivery economics because 35.7% of online orders contained single low-ticket items at a ₹4,200 baseline AOV, while bulky parcel freight consumed 8%–15% of product value (-₹110 net margin).
Action Taken: We mined 2,489 transaction lines across 1,222 carts using a two-stage Apriori pipeline (Support>=10%, Confidence>=25%, Lift>1.20), isolating 22 high-lift rules (4.48x–8.15x lift) to trigger dynamic checkout add-ons and room suites.
Results Derived: Multi-item cart share rose from 35.7% to 55.0%, lifting online AOV +21.4% to ₹5,100+, reducing freight drag to 7.9%–12.3%, and generating positive delivery margins (+₹810 to +₹2,326).
3. Strategic Perceptual Mapping (PCA)
Challenge: Because 85%–90% of Indian furniture retail includes free carpenter installation, IKEA faced cultural resistance to DIY flatpacks. Shoppers viewed self-assembly as unpaid labor and abandoned carts over 5%–15% assembly fees, trapping IKEA in high service friction (X = -1.73).
Action Taken: Surveying 450 urban consumers across five metros, we applied Principal Component Analysis (explaining 54.3% service variance) to map IKEA against Pepperfry, Home Centre, and Urban Ladder across service, price, and design.
Results Derived: PCA isolated an underserved "Affordable Turnkey" whitespace (X = +0.85, Y = 3.10), enabling IKEA to bundle subsidized doorstep assembly—self-funded by multi-item basket margins—while preserving its 6.6/7 design lead.
