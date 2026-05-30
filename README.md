# FIT2179 Assignment 2 – Interactive Data Visualisation

## Dashboard Title

**When the Rain Won't Stop: Understanding Flood Risk and Vulnerability in Malaysia**

---

## Dashboard Story Structure

### Section 1 – Where Do Floods Strike Most Often?

This section introduces the spatial and temporal distribution of flood impacts across Malaysia.

| Visualisation                                      | Idiom           | Dataset |
| -------------------------------------------------- | --------------- | ------- |
| Flood Losses by State                              | Choropleth Map  | DOSM    |
| Flood Events and Affected Population by State-Year | Bubble Timeline | EM-DAT  |

**Key Question:** Where and when do flood impacts occur?

---

### Section 2 – What Drives Flooding in Malaysia?

This section explores climate conditions associated with flood events.

| Visualisation                    | Idiom               | Dataset          |
| -------------------------------- | ------------------- | ---------------- |
| Rainfall and Temperature Trends  | Dual Line Chart     | Rainfall Dataset |
| Rainfall Anomalies by Year       | Diverging Bar Chart | Rainfall Dataset |
| Monthly Flood Frequency by State | Heatmap             | EM-DAT           |

**Key Question:** What climatic patterns contribute to flooding?

---

### Section 3 – How Do Different Floods Behave?

This section compares flood duration across different flood types.

| Visualisation          | Idiom   | Dataset |
| ---------------------- | ------- | ------- |
| Flood Duration by Type | Boxplot | EM-DAT  |

**Key Question:** Are all floods alike?

---

### Section 4 – What Are the Human and Economic Consequences?

This section investigates economic losses and their relationship with rainfall.

| Visualisation              | Idiom                      | Dataset         |
| -------------------------- | -------------------------- | --------------- |
| Flood Losses by State      | Interactive Lollipop Chart | DOSM            |
| Loss Composition by Sector | Interactive Donut Chart    | DOSM            |
| Rainfall vs Flood Losses   | Scatterplot                | DOSM + Rainfall |

**Key Question:** What damage do floods cause?

---

### Section 5 – Which States Face the Greatest Risk?

This section combines multiple indicators into a composite vulnerability assessment.

| Visualisation                       | Idiom            | Dataset                  |
| ----------------------------------- | ---------------- | ------------------------ |
| Composite Flood Vulnerability Score | Radial Bar Chart | DOSM + EM-DAT + Rainfall |

**Key Question:** Which states are most vulnerable overall?

---

## Datasets

### Department of Statistics Malaysia (DOSM)

Used for:

* Flood losses by state
* Sector-level loss breakdown
* Vulnerability calculations

### EM-DAT International Disaster Database

Used for:

* Flood event records
* Flood duration
* Flood frequency
* Affected population

### Malaysian Rainfall Dataset

Used for:

* Annual rainfall trends
* Maximum temperature trends
* Rainfall anomalies
* Vulnerability calculations

---

## Interactivity

### Bubble Timeline

* Click a state to highlight its flood history.

### Dual Line Chart

* Brushing interaction allows users to focus on specific year ranges.

### Lollipop + Donut Chart

* Selecting a state updates the donut chart to reveal sector-level damage composition.

### Scatterplot

* Interactive filtering by region and rainfall threshold.

### Radial Bar Chart

* Hover interaction highlights individual state vulnerability profiles.

---

## Design Principles

* Story-driven narrative structure.
* Consistent colour encoding across all charts.
* Accessible typography and spacing.
* Linked interactions between views.
* Progressive storytelling from geography → climate → behaviour → impacts → vulnerability.

---

## Visualisation Sequence

1. Choropleth Map
2. Bubble Timeline
3. Dual Line Chart
4. Rainfall Anomaly Chart
5. Heatmap
6. Boxplot
7. Lollipop Chart
8. Donut Chart
9. Scatterplot
10. Radial Bar Chart

---

## Author

Emilly Lau Jie Yee

FIT2179 – Data Visualisation
Monash University
