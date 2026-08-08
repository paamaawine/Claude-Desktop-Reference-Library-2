# Verified Data Visualization Libraries

---

## Repository 1

### Name
Matplotlib

### GitHub
https://github.com/matplotlib/matplotlib

### Status
Verified

### Rating
★★★★★

### Purpose
The standard plotting library for Python.

### Features
- Line charts
- Bar charts
- Pie charts
- Histograms
- Scatter plots
- Export to PNG, SVG and PDF

### Claude Should Study
- Statistical charts
- Scientific plotting
- Report graphics
- Publication-quality figures

### Why We Chose It
Matplotlib is the foundation of almost every scientific and statistical application written in Python.

---

## Repository 2

### Name
Plotly

### GitHub
https://github.com/plotly/plotly.py

### Status
Verified

### Rating
★★★★★

### Purpose
Interactive charting library.

### Features
- Interactive dashboards
- Zoom
- Hover information
- Export charts
- 3D charts
- Maps

### Claude Should Study
- Interactive charts
- Dashboard visualisation
- Statistical reporting

### Why We Chose It
Produces professional interactive charts suitable for management dashboards.

---

## Repository 3

### Name
Bokeh

### GitHub
https://github.com/bokeh/bokeh

### Status
Verified

### Rating
★★★★★

### Purpose
Interactive visualisation library.

### Features
- Interactive graphs
- Streaming data
- Dashboards
- Linked charts

### Claude Should Study
- Interactive analytics
- Business dashboards
- Data exploration

### Why We Chose It
Excellent for enterprise dashboards requiring live interaction.

---

## Repository 4

### Name
Altair

### GitHub
https://github.com/vega/altair

### Status
Verified

### Rating
★★★★★

### Purpose
Declarative statistical visualisation library.

### Features
- Statistical graphics
- Interactive filtering
- Layered charts
- Heatmaps

### Claude Should Study
- Statistical graphics
- Research visualisation
- Interactive reports

### Why We Chose It
Makes creating complex statistical graphics much simpler.

---

## Repository 5

### Name
PyQtGraph

### GitHub
https://github.com/pyqtgraph/pyqtgraph

### Status
Verified

### Rating
★★★★★

### Purpose
High-speed plotting library for Qt applications.

### Features
- Real-time plotting
- Live graphs
- Scientific plotting
- Image display
- ROI tools

### Claude Should Study
- Real-time graphs
- Scientific dashboards
- Signal visualisation

### Why We Chose It
Perfect for desktop applications requiring fast, real-time chart updates.

---

## Repository 6

### Name
HoloViews

### GitHub
https://github.com/holoviz/holoviews

### Status
Verified

### Rating
★★★★★

### Purpose
High-level visualisation framework.

### Features
- Interactive plotting
- Statistical graphics
- Large datasets
- Linked visualisations

### Claude Should Study
- Data exploration
- Interactive analysis
- Dashboard integration

### Why We Chose It
Simplifies complex visualisation workflows.

---

## Repository 7

### Name
Panel

### GitHub
https://github.com/holoviz/panel

### Status
Verified

### Rating
★★★★★

### Purpose
Build interactive dashboards.

### Features
- Interactive controls
- Widgets
- Dashboards
- Reports
- Live updates

### Claude Should Study
- Interactive reporting
- Dashboard development
- User controls

### Why We Chose It
Excellent for building analytical dashboards around Python applications.

---

## Repository 8

### Name
missingno

### GitHub
https://github.com/ResidentMario/missingno

### Status
Verified

### Rating
★★★★★

### Purpose
Visualise missing data.

### Features
- Missing value charts
- Heatmaps
- Matrix views
- Correlation plots

### Claude Should Study
- Data quality
- Missing data analysis

### Why We Chose It
Useful when preparing research datasets before statistical analysis.

---

## Repository 9

### Name
WordCloud

### GitHub
https://github.com/amueller/word_cloud

### Status
Verified

### Rating
★★★★★

### Purpose
Generate word clouds.

### Features
- Word frequency
- Custom colours
- Shape masking
- Export images

### Claude Should Study
- Text visualisation
- Keyword analysis
- NLP reporting

### Why We Chose It
Ideal for qualitative research and text analysis.

---

## Repository 10

### Name
Graphviz

### GitHub
https://github.com/xflr6/graphviz

### Status
Verified

### Rating
★★★★★

### Purpose
Create graphs and diagrams.

### Features
- Flowcharts
- Organisation charts
- Decision trees
- Network diagrams
- Process diagrams

### Claude Should Study
- Workflow diagrams
- Decision trees
- Database diagrams

### Why We Chose It
Useful for visualising workflows, organisational structures and AI decision models.

---

## Summary

### Primary Recommendation
- Matplotlib
- Plotly
- PyQtGraph
- Bokeh

### Secondary Recommendation
- Altair
- HoloViews
- Panel
- Graphviz
- WordCloud
- missingno

### Best Use Cases
- Statistical software
- Research reporting
- SPSS-style applications
- AI dashboards
- Financial analytics
- Business intelligence
- Live monitoring
- Scientific plotting
- Management reports
- Interactive desktop dashboards

# Verified Data Visualisation Standards

Data visualisation should help users understand patterns, comparisons, relationships and distributions.

## Matplotlib

Matplotlib is an approved library for creating static charts and figures.

GitHub Repository:

https://github.com/matplotlib/matplotlib

Status: APPROVED

Use Matplotlib when the application needs:

- Line charts
- Bar charts
- Histograms
- Scatter plots
- Box plots
- Area charts
- Custom figures

## Seaborn

Seaborn may be used when statistical visualisations are required.

GitHub Repository:

https://github.com/mwaskom/seaborn

Use it when its statistical chart features provide a clear benefit.

Do not add Seaborn when Matplotlib alone is sufficient.

## Chart Selection

Use:

- Line charts for trends over time
- Bar charts for comparisons
- Horizontal bar charts for ranked categories
- Pie or doughnut charts for simple proportions
- Scatter plots for relationships between variables
- Histograms for distributions
- Box plots for comparing distributions
- Heatmaps for matrix relationships

## Chart Accuracy

Charts must represent the underlying data accurately.

Avoid:

- Misleading scales
- Unlabelled axes
- Unclear units
- Excessive decoration
- Unnecessary three-dimensional effects

## Chart Titles

Use clear titles where they help explain the chart.

Titles should describe the information being shown.

## Axis Labels

Label axes when the meaning of the values is not obvious.

Include units where required.

## Legends

Use legends when multiple data series are displayed.

Do not include a legend when it adds no useful information.

## Missing Data

Clearly indicate when data are missing.

Do not represent missing values as zero unless zero is the correct meaning.

## Theme Consistency

Charts should follow the application's visual style where appropriate.

Fonts, spacing and layout should remain readable.

## Export

Where required, support export to suitable formats.

Examples include:

- PNG
- SVG
- PDF
- CSV
- XLSX

## Performance

Large datasets should be processed before visualisation where necessary.

Avoid rendering unnecessary points that do not improve understanding.

## Accessibility

Do not rely on colour alone.

Use:

- Labels
- Legends
- Patterns where useful
- Different line styles
- Clear annotations

## Visualisation Checklist

- [ ] Correct chart type selected
- [ ] Data represented accurately
- [ ] Title used where useful
- [ ] Axes labelled
- [ ] Units provided where required
- [ ] Legend used where necessary
- [ ] Missing data handled
- [ ] Charts remain readable
- [ ] Accessibility considered
- [ ] Export tested where required
- [ ] Large datasets handled efficiently
