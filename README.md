# Maji Ndogo Water Access Analysis | Power BI

## Project Overview

Maji Ndogo is a data analytics project focused on understanding water access, water-source distribution, and infrastructure challenges.

Using Power BI, I developed an interactive multi-page dashboard to explore water access across different locations, identify areas with limited access to safe water, and examine water-source infrastructure and improvement records.

The project demonstrates data modeling, data visualization, analytical thinking, and the use of Power BI to communicate insights from a real-world data problem.

## Business Problem

Access to safe and reliable water is an important development challenge. Understanding where people obtain water, how many people are affected by unsafe access, and where infrastructure improvements may be needed can help stakeholders make more informed decisions.

This project explores questions such as:

- How many water sources are represented in the dataset?
- How many people are served by the available water sources?
- Which water-source categories serve the largest populations?
- Which areas have the highest number of people without safe water access?
- What infrastructure improvement and water-quality records are available?

## Dashboard Pages

The Power BI report contains five pages:

### 1. Overview
Provides a high-level summary of water access, including:

- Total water sources
- Total population served
- People without safe water access
- Safe water access percentage
- People per water source
- Population by water-access category
- Top areas by people without safe water access

### 2. Sources
Explores the distribution of water sources by type and the population served by different source categories.

### 3. Towns
Examines water access and the population affected across towns and locations.

### 4. Infrastructure
Explores water-source infrastructure and available improvement records, including source status and improvement information.

### 5. Recommendations
Summarizes findings and provides recommendations based on the analysis.

## Key Metrics

The report includes measures such as:

- Total Population Served
- Total Water Sources
- Average People Served
- People Affected
- People Without Safe Access
- People With Safe Access
- Safe Access Percentage
- Problem Sources
- Problem Rate
- People per Source

Metric definitions depend on the underlying data and the assumptions used in the report.

## Tools and Technologies

- **Power BI Desktop** — dashboard development and visualization
- **Power Query** — data preparation and transformation
- **DAX** — calculated measures and analytical calculations
- **Data modeling** — relationships between water sources, visits, locations, pollution, and infrastructure project records

## Data Model

The project uses the following tables:

| Table | Description |
|---|---|
| `water_source` | Water-source identifiers, source types, and population served |
| `visits` | Visit records, source IDs, location IDs, queue times, and dates |
| `location` | Town, province, address, and location information |
| `well_pollution` | Pollution records and pollutant measurements |
| `queue_composition` | Queue demographics |
| `project_progress` | Infrastructure improvement and project status records |
| `infrastructure_cost` | Unit costs associated with infrastructure improvements |
| `water_source_related_crimes` | Crime records associated with water-source locations |

Additional calculated columns and measures were created in Power BI to support analysis.

## Key Findings

The dashboard highlights differences in water access across source types and locations.

The Overview page indicates that a substantial population is represented in the unsafe-water-access categories, including people using broken household taps, contaminated wells, and rivers.

The report also identifies locations with high numbers of people without safe water access, helping focus attention on areas that may require further investigation.

Detailed findings should be interpreted using the definitions and limitations of the underlying dataset.

## Recommendations

Based on the analysis, the report provides recommendations such as:

- Prioritize locations with high numbers of people without safe water access.
- Investigate water-source categories associated with unsafe access.
- Review infrastructure improvement records to understand the status of recorded projects.
- Use water-quality records to identify sources requiring further assessment.
- Monitor water access and infrastructure indicators over time where suitable historical data is available.

## Repository Contents

```text
Maji-Ndogo-Power-BI/
├── README.md
├── Maji_Ndogo_Project.pbix
├── screenshots/
├── data/
└── docs/
```

## How to Use the Project

1. Download the Power BI report file (`.pbix`) from this repository.
2. Open it using Power BI Desktop.
3. Explore the report pages using the page navigation buttons.
4. Interact with the available filters and visuals.

If the original data files are not included, users may need access to the source dataset to refresh the report.

## Limitations

- The analysis depends on the completeness and accuracy of the supplied dataset.
- Recorded pollution or project records may not represent every water source.
- A recorded improvement status should not automatically be interpreted as the current operational condition of a source.
- The dashboard provides analytical insights and does not replace field verification.

## Author

**Grace Muthui**

- GitHub: [gragra-kj](https://github.com/gragra-kj)
- Portfolio: [Portfolio Website](https://portfoliogracie.netlify.app)

