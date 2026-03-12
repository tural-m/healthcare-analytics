🏥 Healthcare Analytics Dashboard

End-to-end healthcare data analysis project — from raw relational data in DBeaver to normalized models and executive dashboards in Power BI.


🎯 Business Problem
A healthcare organization managing nearly 49,000 patients and $97M in billed amounts needed clear visibility into:

Why only 23% of billed amounts were being collected
Which case types and insurance carriers were driving the largest outstanding balances
How attorney fees, doctor performance, and user activity correlated with financial outcomes
Where operational bottlenecks were creating resolution delays


🔍 Key Findings
💰 Finance

Organization billed $97.06M but collected only $22.70M — a collection rate of just 23%
Outstanding balance of $45.54M with 65% concentrated in Low Risk cases that still remain unresolved
Lien cases carry the highest balance at $21.4M despite relatively low paid amounts

📋 Cases

Portfolio is heavily concentrated in Active No Fault cases (44K out of 48.89K total)
Case volumes peaked in 2022 at 15.4K and have declined each year since
40–64 age group represents 48.33% of all cases

🏥 Patients

48.89K total patients — 55% male, 38% female
Patient volumes mirror case trends — peak in 2022, declining through 2025
Top patients by outstanding balance have $0 collected against six-figure billed amounts

🏢 Insurance

44.32K insurance records across 16.88K doctors
Large unidentified insurance segment ($21.2M balance with missing name/ID) represents major data quality risk
Insurance company partnerships peaked at 122 in 2022, declining to 22 by 2025

👨‍⚕️ Doctors

Top doctor (Mohammad Dorri) billed $17.5M but collected only $4M — a $6.1M outstanding balance
Significant collection inconsistency across top 8 doctors
A few high-volume doctors account for a disproportionate share of unpaid balances

⚖️ Attorneys & Users

Attorney fees peaked at $0.97M in 2022 and dropped sharply to $0.02M by 2025
Fees concentrated in top 3 firms — reliance risk
Only 8 out of 274 users are actively billing — extreme engagement concentration


🛠️ Tech Stack
LayerToolPurposeSource DataDBeaverRaw relational databaseData PreparationPower Query EditorNormalization, cleaning, transformationsVisualisationPower BI6-page executive dashboardData ModellingPower BI Data ModelStar schema relationships

