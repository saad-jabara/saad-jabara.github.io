# Portfolio Images Guide

This folder contains images for your portfolio projects. Below are instructions for creating/adding each image.

## Required Images

### 1. rag-project.jpg
**Project**: RAG From Scratch (Core Project)
**Suggested Content**:
- Screenshot of your RAG system code
- Diagram showing the RAG pipeline (document ingestion → embedding → retrieval → generation)
- ChromaDB vector database visualization
- Example query and response output
- LangChain workflow diagram

**Tools to Create**:
- Take a screenshot of your code in VS Code
- Use Excalidraw/Figma to create a pipeline diagram
- Screenshot the terminal output showing the RAG system working

---

### 2. movie-correlation.jpg
**Project**: Movie Correlation Analysis
**Suggested Content**:
- Correlation heatmap showing variables vs. gross revenue
- Scatter plots with regression lines
- Bar charts comparing different movie variables
- Pandas DataFrame output
- Matplotlib/Seaborn visualizations

**Tools to Create**:
- Run your Jupyter notebook and screenshot the visualizations
- Export plots directly from matplotlib
- Combine multiple charts using Figma or Canva

---

### 3. web-scraper.jpg
**Project**: Amazon Price Web Scraper
**Suggested Content**:
- Code snippet showing BeautifulSoup in action
- Amazon product page with highlighted elements being scraped
- CSV output showing scraped data
- Terminal output with scraping logs
- Before/After comparison of data

**Tools to Create**:
- Screenshot your Python code
- Show the scraping process in terminal
- Export the CSV data as a table screenshot

---

### 4. sql-cleaning.jpg
**Project**: Data Cleaning in SQL
**Suggested Content**:
- SQL query screenshots showing BEFORE and AFTER data
- Table showing messy data → clean data transformation
- Key SQL commands (UPDATE, DELETE, CASE WHEN, etc.)
- Data quality metrics improvement
- SQL Server Management Studio screenshot

**Tools to Create**:
- Screenshot your SQL queries in SSMS or Azure Data Studio
- Use Excel to show before/after data comparison
- Create a side-by-side comparison graphic

---

### 5. sql-exploration.jpg
**Project**: Data Exploration in SQL
**Suggested Content**:
- COVID-19 data tables and queries
- Aggregate statistics (SUM, AVG, COUNT)
- JOIN operations across multiple tables
- Geographic data analysis results
- Time series trend queries

**Tools to Create**:
- Screenshot SQL queries with result sets
- Export query results to Excel and visualize
- Show multiple queries and their outputs

---

### 6. tableau-dashboards.jpg
**Project**: Tableau Dashboards
**Suggested Content**:
- Dashboard showing KPIs and metrics
- Multiple visualizations (maps, charts, graphs)
- COVID-19 global trends map
- Airbnb pricing analysis by location
- Chocolate sales performance charts

**Tools to Create**:
- Take a full screenshot of your Tableau dashboard
- Export the dashboard as an image from Tableau
- Combine multiple dashboard views in one image

---

## Image Specifications

- **Format**: JPG or PNG
- **Dimensions**: 1200px × 675px (16:9 ratio) recommended
- **File Size**: Under 500KB for faster loading
- **Quality**: High resolution, clear text
- **Background**: Light or white background works best for screenshots

## Quick Screenshot Tips

### For Code Screenshots:
1. Use VS Code with a nice theme (Dark+ or Monokai)
2. Zoom in slightly for readability
3. Use Carbon.now.sh to create beautiful code screenshots

### For Visualizations:
1. Use high DPI/resolution exports
2. Ensure labels are readable
3. Use consistent color schemes

### For Diagrams:
1. Tools: Excalidraw, Figma, Draw.io, Lucidchart
2. Keep it simple and clear
3. Use arrows and labels

## Placeholder Alternative

If you don't have images ready yet, you can:
1. Create simple text-based placeholders using Canva
2. Use gradient backgrounds with project titles
3. Create diagram mockups using Figma

## Adding Images to Site

Once you have your images:

```bash
# Navigate to portfolio directory
cd /Users/alaadrobe/saad-jabara.github.io

# Copy images to portfolio-images folder
cp ~/Desktop/your-image.jpg portfolio-images/rag-project.jpg

# Commit and push
git add portfolio-images/
git commit -m "Add project screenshots"
git push
```

Your website will automatically update within 1-2 minutes!

## Need Help?

- **Canva** (Free): Create graphics and mockups - https://canva.com
- **Carbon** (Free): Create beautiful code screenshots - https://carbon.now.sh
- **Excalidraw** (Free): Create diagrams - https://excalidraw.com
- **Figma** (Free): Professional design tool - https://figma.com
