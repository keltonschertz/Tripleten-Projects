
# 🛒 Superstore Returns Analysis Project

## 🎯 Objective
Help the CEO of the Superstore understand why customers are returning their orders and recommend actions to reduce return volume. Your analysis will include building visualizations, constructing a dashboard, and presenting findings in a compelling, data-driven story.

---

## 🔍 Part 1: What is Causing Returns?

### 🛠️ Data Preparation
- Join the `Returns` table to the `Orders` table using a **LEFT JOIN**
- Create a calculated field `Returned`:
  - `"Yes"` = 1
  - `null` = 0
- **Return Rate** = AVG(`Returned`)
- **Total Returns** = SUM(`Returned`)

### 📊 Required Worksheets
1. **Scatterplot**: Total Sales vs. Total Returns by Product Subcategory
2. **Bar Chart**: Return Rate by Product Category
3. **Customer Return Rate**: 
   - Filter out customers with only 1 order
4. **Geographic Map**: Return Rate by State/City
5. **Time Series**: Return Rate by Month/Week
6. **Composite Charts** (2):
   - Example: Date vs. Category with Return Rate
   - Example: Region vs. Subcategory with Return Rate

---

## 🧱 Part 2: Building a Dashboard for Monitoring Returns

### 📋 Dashboard Design Requirements
- **Mockups**:
  - Create 3 pen-and-paper dashboard sketches
  - Submit photos/scans
- **Choose One**:
  - Create your dashboard in Tableau based on your favorite sketch
- **Template Setup**:
  - Use empty containers to define layout
  - Submit a screenshot of your layout
- **Finalize Dashboard**:
  - Add worksheets to the layout
  - Add titles, images, markers
  - Ensure usability with filters and clean design

---

## 🎤 Part 3: Presenting Your Analysis and Dashboard

### 🧵 Story Arc
Create a story in Tableau using **captions** and **story points** to guide your presentation.


### 🖼️ Tableau Story
- Add all relevant worksheets and new charts as needed
- Build Story Points and dashboards to support each section
- Visulizations can be found here:<a href="https://public.tableau.com/views/feb22_17402655098970/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" Tableau Link </a>


