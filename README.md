# Smartphone Use During Lectures Among Undergraduate Information Systems Students at Addis Ababa University

A small-scale research project for the Research Methods group assignment (Section 02).
Instructor: **Dr. Ermiyas A.**

## About the project

Students bring their smartphones to every lecture. A phone can help with learning, for example by looking up a term or opening the slides. It can also pull attention away through chatting, social media or games. Earlier studies link phone use in class with lower note-taking and lower grades (Kuznekoff & Titsworth, 2013; Kates et al., 2018). However, there is no recorded data on how Information Systems (IS) students at AAU use their phones during lectures.

This study is a **quantitative descriptive survey** that answers two questions:

- **RQ1:** How often do undergraduate IS students at AAU use their smartphones during lectures?
- **RQ2:** For what purposes do these students use their smartphones during lectures?

**General objective:** To investigate how undergraduate IS students at AAU use their smartphones during lectures.

**Specific objectives:**
1. To determine how often students use their smartphones during lectures.
2. To identify the purposes for which students use their smartphones during lectures.

## Repository structure

```
/
├── proposal/        Approved research proposal (PDF + Markdown version)
├── instruments/     Questionnaire (draft → final) and its sources
├── pilot-study/     Pilot plan, pilot results, and changes made to the instrument
├── data/
│   ├── raw/         Raw survey export (NOT committed – contains timestamps/personal data)
│   └── cleaned/     Cleaned, anonymized dataset used for analysis
├── analysis/        Excel workbook(s), frequency tables, charts
├── report/          Final research report, contribution statement, AI usage declaration
├── presentation/    Final presentation slides
├── meeting-notes/   Dated notes from group meetings
├── references/      Reference list (APA 7th) and notes on sources
└── README.md        This file
```

## Methodology summary

| Item | Plan |
|---|---|
| Approach | Quantitative, descriptive survey |
| Population | Undergraduate IS students, AAU |
| Sample | About 100 students from different year levels |
| Instrument | Closed-ended questionnaire: 5-point frequency scale (Never → Always) and a tick-list of purposes |
| Collection | Online, via Google Forms |
| Analysis | Descriptive statistics (frequencies, percentages), tables and charts in Microsoft Excel |

## Software and datasets

- **Google Forms**: questionnaire delivery
- **Microsoft Excel**: data cleaning, descriptive statistics, charts
- **Microsoft Word**: report writing (exported to PDF)
- **Git / GitHub**: version control and collaboration
- **Dataset:** primary survey data collected by the group (`data/cleaned/`). No external datasets are used.

## Group members and roles

| # | Name | ID | Role |
|---|---|---|---|
| 1 | Gebrie Gashaw | UGR/3021/17 | _TDB_ |
| 2 | Hayder Yishak | UGR/8455/17 | _TBD_ |
| 3 | Yishak Tamirat | UGR/8090/17 | _TBD_ |
| 4 | Michael Yerom | UGR/8127/17 | _TBD_ |
| 5 | Yitbarek Tesfaye | UGR/4389/17 | _TBD_ |

> Roles to be agreed at the first group meeting (see `meeting-notes/`). Suggested roles: project coordinator, instrument and pilot lead, data collection lead, data analysis lead, report editor and references.

## Reproducing the analysis

1. Export the Google Forms responses as CSV and save them to `data/raw/` (git-ignored).
2. Clean the data following the steps in `data/README.md`, then save the result as `data/cleaned/responses_clean.csv`.
3. Open the workbook in `analysis/` and paste the cleaned data into the `data` sheet. The frequency tables and charts update from that sheet.
4. The tables and figures in `report/` are taken from the workbook outputs.

## Timeline

| Date | Milestone |
|---|---|
| Nov 25, 2026 | Repository created, link shared on Google Classroom |
| _TBD_ | Instrument finalized, pilot study done |
| _TBD_ | Data collection completed |
| _TBD_ | Analysis completed |
| Dec 13, 2026 | Final report, slides and repository due |

## Key references

- Kates, A. W., Wu, H., & Coryn, C. L. S. (2018). The effects of mobile phone use on academic performance: A meta-analysis. *Computers & Education, 127*, 107–112.
- Kuznekoff, J. H., & Titsworth, S. (2013). The impact of mobile phone usage on student learning. *Communication Education, 62*(3), 233–252.

The full list is in [`references/references.md`](references/references.md).
