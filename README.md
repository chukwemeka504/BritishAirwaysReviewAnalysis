# BritishAirwaysReviewAnalysis
✈️ Project Summary
This project delves into passenger experiences with British Airways by leveraging web data extraction and advanced language processing. Through the application of machine learning and natural language techniques, it transforms raw user reviews into structured insights, revealing patterns in satisfaction, recurring issues, and customer priorities.
In parallel, a machine learning model was engineered to estimate the likelihood of users finalizing flight bookings, using behavioral and contextual data. This predictive component provides actionable intelligence for airlines to better understand customer intent and tailor engagement strategies.

🧭 Project Aims
Extract customer review data from the Skytrax website.
Process and sanitize textual feedback for analytical readiness.
Classify emotional tone of reviews as favorable, unfavorable, or neutral.
Detect underlying themes and frequent concerns through topic modeling.
Design a predictive model that forecasts whether a user will complete a booking.
Communicate key findings using visuals and presentations.

 Contents Overview
review_engine.ipynb – Primary notebook that handles the entire review workflow: scraping, cleaning, text analysis, sentiment scoring, and chart generation.
BA_review_data.csv – Processed dataset derived from the scraping phase (shared if distribution is allowed).
booking_intent_model.ipynb – Machine learning workflow for predicting booking decisions, including feature processing, model fitting, and evaluation.
model_brief.pptx – Condensed slides summarizing performance metrics and practical applications of the predictive model.
review_summary.pptx – Insightful breakdown of review sentiment, keyword patterns, and topic trends.
README.md – Full project documentation and usage guide.

 Tools & Technologies
Python – Main programming language for development.
BeautifulSoup – HTML parser used to extract structured data from Skytrax.
pandas – Data handling library for organizing and filtering large datasets.
TextBlob – Lightweight NLP library for sentiment classification.
scikit-learn – Toolkit for machine learning pipelines, including vectorization, classification, and topic modeling.
matplotlib / seaborn – Used to produce charts and graphs for insights.
wordcloud – Tool to visually highlight the most frequently mentioned terms.

Workflow Breakdown
Review Collection – Web-based data scraping from Skytrax to retrieve user-submitted reviews.
Text Cleaning & Structuring – Refining and formatting raw content for downstream tasks.
Sentiment Analysis – Determining the emotional tone of each review entry.
Theme Extraction – Identifying recurring feedback points using topic discovery methods.
Booking Propensity Modeling – Building a predictive model (Random Forest) to assess booking intent.
Visualization & Storytelling – Transforming data into understandable visuals and executive-ready presentations.

Key Findings
Sentiment Trends: A substantial portion of the reviews reflected negative sentiment, highlighting widespread customer dissatisfaction with various aspects of the airline experience.
Frequent Complaints: Recurring themes in critical reviews included poor food standards, inefficiencies in refund processing, and frequent delays in service.
Model Insights: Features such as how far in advance a booking is made, trip duration, and individual travel preferences were among the most influential predictors of booking completion.

 Strategic Recommendations
Customer Experience Improvements: Enhance meal quality, streamline refund handling, and proactively address service delays to boost satisfaction scores.
Targeted Marketing: Focus promotional efforts on customer segments and routes with higher booking success rates to improve conversion.
