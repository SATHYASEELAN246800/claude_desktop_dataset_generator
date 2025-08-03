# claude_desktop_dataset_generator


# 🧠 Smart Dataset Generator & ML Classifier

This project leverages **Claude Desktop AI** to generate diverse Tamil Nadu–oriented datasets and perform machine learning classification. It supports various roles, media types, domains, and outcome predictions using a structured MCP (Machine Learning + Content Pipeline) flow.

---

## 🔗 Claude Output

📎 [View Claude Artifact](https://claude.ai/public/artifacts/0289f87f-d9f4-4f06-9d5a-8b704e9ba01c)

---

## 🚀 Features

- Tamil Nadu–based names and districts
- Roles: Student, Developer, Farmer, etc.
- Media types: Text, Image, Audio, Video
- Job domains: Tech, Education, Healthcare, etc.
- Excel file export
- ML-ready structured data
- Outcome classification: Success / Failure / Pending
- Claude-generated Python ML code

---

## 🧾 Claude Prompt

```txt
Generate a smart dataset of 100 rows with fields:
- Name, Role, MediaType, Job Domain, Gender, Age, Income, Region, Duration, Status, Date, Outcome

Then:
1. Analyze (counts, income avg, trends, missing values)
2. Train ML model to predict Outcome
3. Export as SmartDataset.xlsx
4. Save to D:\claude desktop or provide download instructions
