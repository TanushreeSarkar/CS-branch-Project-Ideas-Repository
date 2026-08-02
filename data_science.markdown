# 📊 Data Science Project Ideas
Beyond the usual sales forecasting / customer segmentation / stock prediction set — these map to what data teams are actually hiring for: **causal inference, MLOps, feature stores, geospatial analytics, and LLM-assisted analysis**. 🚀

---

## 📋 Quick Reference Table

| # | Project | Tech Stack | Why It's Hireable |
|---|---------|-----------|-------------------|
| 1 | Marketing Mix Modeling Dashboard | Python, PyMC, Streamlit | MMM is a top-priority skill as third-party cookies disappear |
| 2 | Customer Churn Survival Analysis | Python, lifelines, scikit-learn | Survival analysis beats basic churn classifiers |
| 3 | Causal Inference for Pricing Experiments | Python, DoWhy, CausalML | Causal inference is the biggest 2025-26 DS skill gap |
| 4 | Real-Time Fraud Scoring Pipeline | Python, Kafka, XGBoost | Streaming ML is a strong differentiator over batch-only work |
| 5 | Geospatial Delivery Route Optimizer | Python, OR-Tools, GeoPandas | Combines optimization with geospatial analytics |
| 6 | Multi-SKU Demand Forecasting | Python, Prophet/N-BEATS | Forecasting is core to retail/supply-chain data science |
| 7 | Feature Store for ML Pipelines | Feast, PostgreSQL | MLOps infra skill, rare on junior resumes |
| 8 | A/B Test Sample Size & Power Calculator | Python, Streamlit | Statistical rigor is a top signal in DS interviews |
| 9 | Customer Lifetime Value Predictor | Python, BG/NBD model | Ties directly to a business's most important growth metric |
| 10 | Graph-Based Recommendation Engine | Python, Neo4j, GNN | Graph ML outperforms classic collaborative filtering |
| 11 | Data Quality Monitoring Framework | Great Expectations, Python | Data quality is the unsung foundation of every DS project |
| 12 | Synthetic Time-Series Data Generator | Python, TimeGAN | Solves data-scarcity problems in a novel way |
| 13 | Real Estate Price Prediction with SHAP | XGBoost, SHAP | Explainability is now expected alongside accuracy |
| 14 | Sports Win Probability Model | Python, logistic regression | Fun, demoable, and statistically rigorous |
| 15 | Supply Chain Anomaly Detection | Python, Isolation Forest | High-ROI use case with clear business stakeholders |
| 16 | NLP-Based Survey Response Analyzer | Python, transformers, topic modeling | Turns unstructured text into structured insight |
| 17 | Dynamic Pricing Engine (RL) | Python, reinforcement learning | Advanced technique with direct revenue impact |
| 18 | Employee Attrition Predictor with Fairness Audit | scikit-learn, Fairlearn | Shows awareness of algorithmic fairness, an HR-tech must |
| 19 | Weather-Impact Sales Correlation Dashboard | Python, Dash, weather API | Creative external-data feature engineering |
| 20 | Cohort Retention Analysis Tool | Python, pandas, Plotly | Core product-analytics skill for any subscription business |
| 21 | Multi-Touch Attribution Model | Python, Markov chains | Solves a genuinely hard marketing-analytics problem |
| 22 | Anomaly Detection in Financial Transactions | Python, Autoencoders | Deep learning applied to a classic fraud use case |
| 23 | LLM-Powered Data Storytelling Report Generator | Python, LLM, matplotlib | Combines classic DS with generative AI narration |
| 24 | Recommendation Cold-Start Solver | Python, hybrid content-based model | Solves a real production recsys pain point |
| 25 | Public Health Outbreak Trend Tracker | Python, pandas, time series | High social-impact, real-world data story |
| 26 | Automated Feature Engineering Pipeline | Featuretools, Python | Speeds up the most time-consuming part of modeling |
| 27 | Credit Risk Scorecard Builder | Python, WOE/IV, logistic regression | Classic, interview-tested fintech modeling technique |
| 28 | Real-Time Streaming Sensor Dashboard | Kafka, Streamlit | Shows real-time data engineering + viz skill |
| 29 | Support Ticket Auto-Routing (NLP) | Python, transformers | Practical customer-ops automation with clear ROI |
| 30 | Election/Poll Forecast Aggregator | Python, Bayesian modeling | Rigorous probabilistic modeling, great portfolio story |
| 31 | Customer Journey Funnel Analysis Tool | Python, SQL, Plotly | Core growth/product-analytics deliverable |
| 32 | Image-Based Quality Control Analytics | Python, OpenCV, statistics | Manufacturing analytics combining CV and stats |
| 33 | ML Model Data Drift Monitor | Evidently AI, Python | MLOps monitoring is essential once models hit production |
| 34 | Recommendation Explainability Tool | Python, SHAP for recsys | "Why was this recommended" is a real product feature |
| 35 | Energy Consumption Forecasting | Python, LSTM, XGBoost | Climate/energy-tech is a growing, funded DS sector |
| 36 | Sports Player Performance Clustering | Python, k-means, PCA | Fun unsupervised-learning application |
| 37 | Insurance Claims Anomaly Detector | Python, Isolation Forest | Direct fraud-prevention ROI in a regulated industry |
| 38 | Aspect-Based Restaurant Review Analyzer | Python, ABSA models | More sophisticated than generic sentiment analysis |
| 39 | Data Pipeline Orchestration with Airflow | Apache Airflow, Python | Data engineering fundamentals every DS role now expects |
| 40 | Marketing Campaign ROI Optimizer | Python, linear programming | Optimization skills applied to a real budgeting problem |
| 41 | Genomic Data Clustering Tool | Python, scikit-learn, bioinformatics | Bioinformatics is a specialized, well-paid DS niche |
| 42 | Traffic Congestion Prediction Model | Python, XGBoost, geospatial | Urban/smart-city analytics, socially relevant |
| 43 | Customer Complaint Root-Cause Analyzer | Python, LLM + clustering | Combines generative AI with classic clustering |
| 44 | Loan Default Early-Warning System | Python, gradient boosting | Direct fintech risk-modeling application |
| 45 | Market Basket Analysis | Python, Apriori/FP-Growth | Classic retail analytics, still widely used in practice |
| 46 | Survey Data Weighting & Bias Correction Tool | Python, statsmodels | Advanced statistical rigor most bootcamp grads skip |
| 47 | Video Game Player Churn Predictor | Python, XGBoost | Gaming analytics is a distinct, growing DS vertical |
| 48 | Auto-Generated Data Catalog with Metadata | Python, LLM, SQL introspection | Data discoverability tooling, a real platform need |
| 49 | Climate Data Trend Visualizer | Python, xarray, Plotly | Works with real scientific datasets, not toy CSVs |
| 50 | Subscription Cohort Revenue Model | Python, pandas, Dash | Core SaaS metrics work (MRR, cohort revenue) |

---

## 📖 Detailed Breakdown

### 1. Marketing Mix Modeling Dashboard 📢
- **Description**: Model how different marketing channels (TV, social, search) contribute to sales using Bayesian regression, then let users simulate budget shifts.
- **Tech Stack**: Python, PyMC, Streamlit
- **Why It's Cool**: Answers "which channel actually drives revenue" with real statistical rigor.
- **Hiring Appeal**: MMM has become a top-priority skill as third-party cookie tracking disappears.

### 2. Customer Churn Survival Analysis ⏳
- **Description**: Instead of predicting "will churn Y/N," model *when* a customer is likely to churn using survival analysis.
- **Tech Stack**: Python, lifelines, scikit-learn
- **Why It's Cool**: Gives a richer, time-aware answer than a binary classifier.
- **Hiring Appeal**: Survival analysis is a technique that immediately separates you from typical churn-classifier portfolios.

### 3. Causal Inference for Pricing Experiments 🎯
- **Description**: Estimate the true causal effect of a price change on demand, controlling for confounders, not just correlation.
- **Tech Stack**: Python, DoWhy, CausalML
- **Why It's Cool**: Answers "did the price change actually cause the sales lift" — a much harder question than correlation.
- **Hiring Appeal**: Causal inference is widely cited as the biggest skill gap in current data science hiring.

### 4. Real-Time Fraud Scoring Pipeline ⚡
- **Description**: Score transactions for fraud risk in real time as they stream through a Kafka pipeline, not in a nightly batch job.
- **Tech Stack**: Python, Kafka, XGBoost
- **Why It's Cool**: Real-time scoring has completely different engineering constraints than offline notebooks.
- **Hiring Appeal**: Streaming ML is a strong differentiator over the typical "trained a model in a notebook" portfolio piece.

### 5. Geospatial Delivery Route Optimizer 🗺️
- **Description**: Optimize multi-stop delivery routes using real road-network data and vehicle-routing algorithms.
- **Tech Stack**: Python, OR-Tools, GeoPandas
- **Why It's Cool**: Combines geospatial analytics with combinatorial optimization — genuinely hard math.
- **Hiring Appeal**: Logistics/delivery companies specifically hire for exactly this skill combination.

### 6. Multi-SKU Demand Forecasting 📦
- **Description**: Forecast demand across hundreds of products simultaneously, handling seasonality and intermittent demand.
- **Tech Stack**: Python, Prophet or N-BEATS, hierarchical forecasting
- **Why It's Cool**: Forces you to think about forecasting at scale, not just one clean time series.
- **Hiring Appeal**: Demand forecasting is core to retail, CPG, and supply-chain data science roles.

### 7. Feature Store for ML Pipelines 🗃️
- **Description**: Build a central repository where features are computed once and consistently served to both training and production inference.
- **Tech Stack**: Feast, PostgreSQL, Redis
- **Why It's Cool**: Solves the classic and painful training/serving skew problem.
- **Hiring Appeal**: Feature-store experience is genuinely rare on junior resumes and signals MLOps maturity.

### 8. A/B Test Sample Size & Power Calculator 📐
- **Description**: Build an interactive tool that computes required sample size, expected runtime, and statistical power for any A/B test design.
- **Tech Stack**: Python, Streamlit, statsmodels
- **Why It's Cool**: Prevents underpowered experiments before they even launch.
- **Hiring Appeal**: Statistical rigor around experimentation is a top signal in data science interviews.

### 9. Customer Lifetime Value Predictor 💰
- **Description**: Predict each customer's future value using probabilistic purchase models, not just a simple historical average.
- **Tech Stack**: Python, BG/NBD and Gamma-Gamma models (lifetimes library)
- **Why It's Cool**: Uses real customer-analytics theory rather than a naive heuristic.
- **Hiring Appeal**: CLV ties directly to a business's most important growth and retention metrics.

### 10. Graph-Based Recommendation Engine 🕸️
- **Description**: Model users and items as a graph and use graph neural networks to generate recommendations that capture indirect relationships.
- **Tech Stack**: Python, Neo4j, PyTorch Geometric
- **Why It's Cool**: Captures relationships classic collaborative filtering completely misses.
- **Hiring Appeal**: Graph ML is an advanced, differentiated skill few candidates can demonstrate hands-on.

### 11. Data Quality Monitoring Framework ✅
- **Description**: Automatically validate incoming data against defined expectations (nulls, ranges, schema) and alert when quality degrades.
- **Tech Stack**: Great Expectations, Python
- **Why It's Cool**: Prevents the classic "garbage in, garbage out" failure before it reaches a model.
- **Hiring Appeal**: Data quality is the unglamorous foundation every serious data team invests in.

### 12. Synthetic Time-Series Data Generator 🧬
- **Description**: Generate realistic synthetic time-series data that preserves temporal patterns for testing or augmentation.
- **Tech Stack**: Python, TimeGAN
- **Why It's Cool**: Solves real data-scarcity and privacy problems for time-series ML.
- **Hiring Appeal**: A novel technique that's rarely covered in standard DS bootcamp curricula.

### 13. Real Estate Price Prediction with SHAP 🏠
- **Description**: Predict housing prices and use SHAP values to explain exactly why the model priced each property the way it did.
- **Tech Stack**: XGBoost, SHAP, pandas
- **Why It's Cool**: Goes beyond "here's my R²" to actually explaining model behavior.
- **Hiring Appeal**: Explainability is now expected alongside accuracy in nearly every applied ML role.

### 14. Sports Win Probability Model 🏏
- **Description**: Build a live win-probability model that updates in real time as a match progresses (e.g., cricket, football).
- **Tech Stack**: Python, logistic regression, live data feeds
- **Why It's Cool**: Fun, demoable, and forces rigorous handling of live, evolving features.
- **Hiring Appeal**: Sports analytics is a growing, visible niche that makes for a memorable portfolio piece.

### 15. Supply Chain Anomaly Detection 🚚
- **Description**: Detect unusual patterns in shipment times, inventory levels, or supplier lead times before they become disruptions.
- **Tech Stack**: Python, Isolation Forest, pandas
- **Why It's Cool**: A high-ROI use case with clear, identifiable business stakeholders.
- **Hiring Appeal**: Supply-chain analytics roles are actively expanding post-pandemic disruption awareness.

### 16. NLP-Based Survey Response Analyzer 📝
- **Description**: Automatically theme and summarize thousands of open-text survey responses using topic modeling and transformers.
- **Tech Stack**: Python, transformers, BERTopic
- **Why It's Cool**: Turns a pile of unstructured text no one wants to read manually into structured insight.
- **Hiring Appeal**: A concrete NLP application every UX research and customer-insights team needs.

### 17. Dynamic Pricing Engine (Reinforcement Learning) 💵
- **Description**: Use reinforcement learning to adjust prices in real time based on demand, inventory, and competitor signals.
- **Tech Stack**: Python, RL (e.g., contextual bandits)
- **Why It's Cool**: An advanced technique with a direct, measurable revenue impact.
- **Hiring Appeal**: RL for pricing is a genuinely cutting-edge application most candidates haven't attempted.

### 18. Employee Attrition Predictor with Fairness Audit ⚖️
- **Description**: Predict employee attrition risk, then explicitly audit the model for bias across gender, age, or tenure groups.
- **Tech Stack**: scikit-learn, Fairlearn
- **Why It's Cool**: Doesn't stop at accuracy — actively checks whether the model is fair.
- **Hiring Appeal**: Algorithmic fairness awareness is now a genuine differentiator, especially in HR-tech.

### 19. Weather-Impact Sales Correlation Dashboard ☀️
- **Description**: Join sales data with historical weather data to quantify how conditions like rain or heat affect purchasing.
- **Tech Stack**: Python, Dash, weather API
- **Why It's Cool**: Creative external-data feature engineering most candidates never think to try.
- **Hiring Appeal**: Demonstrates the kind of lateral thinking that produces real business insight.

### 20. Cohort Retention Analysis Tool 📅
- **Description**: Build a tool that automatically generates cohort retention curves and heatmaps from raw event data.
- **Tech Stack**: Python, pandas, Plotly
- **Why It's Cool**: A visualization that instantly reveals product health trends.
- **Hiring Appeal**: Cohort analysis is a core deliverable for any subscription or app-based business's growth team.

### 21. Multi-Touch Attribution Model 🎯
- **Description**: Determine how credit for a conversion should be distributed across multiple marketing touchpoints using Markov chain modeling.
- **Tech Stack**: Python, Markov chains, pandas
- **Why It's Cool**: Solves a genuinely hard, contested problem in marketing analytics.
- **Hiring Appeal**: Attribution modeling is a top request from any marketing analytics or growth team.

### 22. Anomaly Detection in Financial Transactions 💳
- **Description**: Use an autoencoder to learn "normal" transaction patterns and flag reconstructions with high error as anomalies.
- **Tech Stack**: Python, Autoencoders (Keras/PyTorch)
- **Why It's Cool**: Deep learning applied to a classic tabular fraud-detection problem.
- **Hiring Appeal**: Fintech and payments companies constantly seek this exact anomaly-detection skill.

### 23. LLM-Powered Data Storytelling Report Generator 📖
- **Description**: Automatically generate a written narrative report (with charts) summarizing key trends in a dataset using an LLM.
- **Tech Stack**: Python, LLM API, matplotlib
- **Why It's Cool**: Combines classic exploratory data analysis with generative-AI narration.
- **Hiring Appeal**: A practical, novel application of LLMs to a real analyst-time-saving problem.

### 24. Recommendation Cold-Start Solver 🆕
- **Description**: Build a hybrid recommender that gives reasonable suggestions for brand-new users or items with zero interaction history.
- **Tech Stack**: Python, content-based + collaborative hybrid model
- **Why It's Cool**: Solves the specific failure mode that breaks most naive recommendation systems.
- **Hiring Appeal**: Cold-start is a genuine, recurring production pain point recsys teams deal with constantly.

### 25. Public Health Outbreak Trend Tracker 🏥
- **Description**: Analyze public health datasets to track and visualize disease outbreak trends across regions and time.
- **Tech Stack**: Python, pandas, time-series analysis
- **Why It's Cool**: High social-impact story built on genuinely messy, real-world public data.
- **Hiring Appeal**: A compelling narrative for public-health analytics or health-tech-adjacent roles.

### 26. Automated Feature Engineering Pipeline ⚙️
- **Description**: Automatically generate and rank candidate features from raw relational tables instead of hand-crafting each one.
- **Tech Stack**: Featuretools, Python
- **Why It's Cool**: Speeds up the single most time-consuming part of most modeling projects.
- **Hiring Appeal**: Shows you understand feature engineering deeply enough to automate it.

### 27. Credit Risk Scorecard Builder 💳
- **Description**: Build a traditional credit scorecard using Weight of Evidence and Information Value, the way banks actually do it.
- **Tech Stack**: Python, WOE/IV transformation, logistic regression
- **Why It's Cool**: Uses the actual industry-standard technique, not just a generic classifier.
- **Hiring Appeal**: This exact methodology is asked about directly in fintech/banking DS interviews.

### 28. Real-Time Streaming Sensor Dashboard 📡
- **Description**: Visualize live sensor data streaming through Kafka on an auto-updating dashboard.
- **Tech Stack**: Kafka, Streamlit, Python
- **Why It's Cool**: Shows you can handle both the data-engineering and visualization sides of streaming.
- **Hiring Appeal**: Real-time data skills increasingly separate senior candidates from batch-only juniors.

### 29. Support Ticket Auto-Routing (NLP) 🎫
- **Description**: Classify incoming support tickets by category and urgency, then auto-route them to the right team.
- **Tech Stack**: Python, transformers (fine-tuned classifier)
- **Why It's Cool**: A practical customer-ops automation with an immediately obvious time-savings story.
- **Hiring Appeal**: This exact use case shows up in nearly every CX/support-tooling company's roadmap.

### 30. Election/Poll Forecast Aggregator 🗳️
- **Description**: Aggregate multiple polls with proper weighting and uncertainty to produce a probabilistic election forecast.
- **Tech Stack**: Python, Bayesian modeling (PyMC)
- **Why It's Cool**: Rigorous probabilistic modeling applied to a domain everyone finds intuitively interesting.
- **Hiring Appeal**: A memorable, well-understood portfolio story that showcases genuine statistical depth.

### 31. Customer Journey Funnel Analysis Tool 🔻
- **Description**: Trace users through a multi-step funnel (visit → signup → purchase) and pinpoint exactly where drop-off happens.
- **Tech Stack**: Python, SQL, Plotly
- **Why It's Cool**: Immediately actionable — pinpoints the exact step a business should fix.
- **Hiring Appeal**: A core, constantly-requested deliverable for any growth or product analytics team.

### 32. Image-Based Quality Control Analytics 🏭
- **Description**: Analyze photos of manufactured parts to statistically track defect rates and flag quality drift over time.
- **Tech Stack**: Python, OpenCV, statistical process control
- **Why It's Cool**: Combines computer vision with classic statistical quality-control theory.
- **Hiring Appeal**: Manufacturing analytics is a concrete, high-ROI use case for industrial companies.

### 33. ML Model Data Drift Monitor 📉
- **Description**: Continuously compare live production data distributions against the training set and alert when drift crosses a threshold.
- **Tech Stack**: Evidently AI, Python
- **Why It's Cool**: Answers "is my model still trustworthy today" — the question that matters after deployment.
- **Hiring Appeal**: Drift monitoring is essential MLOps hygiene once any model reaches production.

### 34. Recommendation Explainability Tool 💡
- **Description**: For any recommendation a system produces, generate a human-readable "why you're seeing this" explanation.
- **Tech Stack**: Python, SHAP adapted for recommender systems
- **Why It's Cool**: Turns a black-box recommendation into something a user can actually trust.
- **Hiring Appeal**: Explainable recommendations are a real, requested product feature at consumer platforms.

### 35. Energy Consumption Forecasting ⚡
- **Description**: Forecast electricity demand at the grid or building level, accounting for weather and seasonality.
- **Tech Stack**: Python, LSTM, XGBoost
- **Why It's Cool**: Directly supports grid stability and renewable-energy planning.
- **Hiring Appeal**: Climate and energy-tech is a growing, well-funded data science sector.

### 36. Sports Player Performance Clustering ⚽
- **Description**: Cluster athletes into playing-style archetypes using performance statistics and dimensionality reduction.
- **Tech Stack**: Python, k-means, PCA
- **Why It's Cool**: A fun, visual application of unsupervised learning most people find intuitive.
- **Hiring Appeal**: Sports analytics is a distinct, growing niche with its own dedicated hiring pipeline.

### 37. Insurance Claims Anomaly Detector 🚨
- **Description**: Flag suspicious insurance claims that deviate statistically from expected patterns for similar claim types.
- **Tech Stack**: Python, Isolation Forest, pandas
- **Why It's Cool**: A concrete fraud-prevention use case in a heavily regulated, data-rich industry.
- **Hiring Appeal**: Insurance is one of the largest employers of applied data scientists globally.

### 38. Aspect-Based Restaurant Review Analyzer 🍽️
- **Description**: Go beyond overall sentiment to extract sentiment on specific aspects (food, service, price, ambiance) from reviews.
- **Tech Stack**: Python, Aspect-Based Sentiment Analysis (ABSA) models
- **Why It's Cool**: A meaningfully more sophisticated NLP task than generic positive/negative classification.
- **Hiring Appeal**: Aspect-level insight is what real product/marketing teams actually need from review data.

### 39. Data Pipeline Orchestration with Airflow 🌬️
- **Description**: Build a scheduled, dependency-aware pipeline that ingests, cleans, and loads data into a warehouse automatically.
- **Tech Stack**: Apache Airflow, Python, SQL
- **Why It's Cool**: Forces you to think about reliability and idempotency, not just one-off scripts.
- **Hiring Appeal**: Data engineering fundamentals are now expected of most data scientist roles, not optional.

### 40. Marketing Campaign ROI Optimizer 📈
- **Description**: Given a fixed marketing budget and channel performance data, use linear programming to find the allocation that maximizes ROI.
- **Tech Stack**: Python, linear programming (PuLP/SciPy)
- **Why It's Cool**: Applies real operations-research optimization to a budgeting decision, not just prediction.
- **Hiring Appeal**: Optimization skills paired with a business-facing story stand out from pure-prediction portfolios.

### 41. Genomic Data Clustering Tool 🧬
- **Description**: Cluster gene expression data to identify patient subgroups or biomarker patterns.
- **Tech Stack**: Python, scikit-learn, bioinformatics libraries (Biopython)
- **Why It's Cool**: Works with genuinely high-dimensional, domain-specific scientific data.
- **Hiring Appeal**: Bioinformatics is a specialized, well-paid data science niche with steady demand.

### 42. Traffic Congestion Prediction Model 🚦
- **Description**: Predict traffic congestion levels on specific road segments using historical and real-time geospatial data.
- **Tech Stack**: Python, XGBoost, geospatial features
- **Why It's Cool**: Combines time-series, geospatial, and tabular modeling in one project.
- **Hiring Appeal**: Urban/smart-city analytics is a socially relevant, growing DS application area.

### 43. Customer Complaint Root-Cause Analyzer 🔍
- **Description**: Cluster customer complaints by underlying root cause (not just topic), using an LLM to label clusters meaningfully.
- **Tech Stack**: Python, LLM API, clustering (HDBSCAN)
- **Why It's Cool**: Combines classic unsupervised learning with LLM-assisted interpretation.
- **Hiring Appeal**: Root-cause analysis is directly actionable for product and CX teams — not just a report.

### 44. Loan Default Early-Warning System ⚠️
- **Description**: Predict which active loans are trending toward default *before* they miss a payment, not after.
- **Tech Stack**: Python, gradient boosting (LightGBM/XGBoost)
- **Why It's Cool**: Early-warning framing is more actionable than a simple binary default classifier.
- **Hiring Appeal**: A direct, well-understood fintech risk-modeling application.

### 45. Market Basket Analysis 🛒
- **Description**: Discover which products are frequently purchased together and surface actionable cross-sell rules.
- **Tech Stack**: Python, Apriori or FP-Growth algorithms
- **Why It's Cool**: A classic technique that's still widely used in real retail merchandising decisions.
- **Hiring Appeal**: Retail analytics teams still rely on exactly this kind of association-rule mining.

### 46. Survey Data Weighting & Bias Correction Tool ⚖️
- **Description**: Reweight survey responses to correct for non-representative sampling using post-stratification techniques.
- **Tech Stack**: Python, statsmodels
- **Why It's Cool**: Advanced statistical rigor that most bootcamp-trained candidates never touch.
- **Hiring Appeal**: Signals genuine statistical depth beyond "I fit a model in scikit-learn."

### 47. Video Game Player Churn Predictor 🎮
- **Description**: Predict which players are likely to stop playing based on in-game behavior and engagement metrics.
- **Tech Stack**: Python, XGBoost, feature engineering on event logs
- **Why It's Cool**: Gaming data has unique behavioral patterns different from typical SaaS churn.
- **Hiring Appeal**: Gaming analytics is a distinct, fast-growing data science vertical.

### 48. Auto-Generated Data Catalog with Metadata 📚
- **Description**: Automatically scan database schemas and generate human-readable descriptions and lineage documentation using an LLM.
- **Tech Stack**: Python, LLM API, SQL schema introspection
- **Why It's Cool**: Solves the "nobody knows what this table means anymore" problem every data team has.
- **Hiring Appeal**: Data discoverability tooling is a genuine platform-team investment area right now.

### 49. Climate Data Trend Visualizer 🌡️
- **Description**: Analyze and visualize long-term climate datasets (temperature, precipitation) to surface regional trends.
- **Tech Stack**: Python, xarray, Plotly
- **Why It's Cool**: Works with real multidimensional scientific NetCDF data, not a toy CSV.
- **Hiring Appeal**: A compelling, socially relevant story for climate-tech or environmental data roles.

### 50. Subscription Cohort Revenue Model 💵
- **Description**: Model recurring revenue by cohort to project future MRR/ARR under different retention and growth assumptions.
- **Tech Stack**: Python, pandas, Dash
- **Why It's Cool**: Directly mirrors the exact metrics SaaS finance and growth teams live and die by.
- **Hiring Appeal**: Core SaaS metrics fluency (MRR, cohort revenue, net revenue retention) is a strong business-analytics signal.

---
