# Playfair Recreation  

**Author:** Nadine Thomas  
**Format:** PDF (Quarto/R Markdown)  

## Overview  

This project is a recreation and critique of William Playfair’s historical chart that visualized the extent, population, and revenues of European nations after the Division of Poland and the Treaty of Luneville. The project consists of four main parts:  

1. **Critique of Playfair’s Original Visualization**
   
   <img width="566" height="313" alt="image" src="https://github.com/user-attachments/assets/55524d39-2d2d-4ba7-b293-ea22689b908f" />

   - An evaluation of Playfair’s use of line, color, shape, and size.  
   - Discussion of strengths (clear use of line and color for variables) and weaknesses (misleading scaling of circle areas, confusing use of color for both variables and categories).  

3. **Recreation of Playfair’s Chart in R**

   <img width="1152" height="576" alt="image" src="https://github.com/user-attachments/assets/c1fe5cfc-92ad-42ca-acea-c7dc17c46f22" />

   - Using `ggplot2` and `ggforce`, the original chart is reimplemented.  
   - The dataset (`playfair_european_nations.csv`) is reformatted, country names adjusted for readability, and radii calculated to approximate circle areas.  
   - Visual elements are styled to resemble Playfair’s chart, including population and taxation lines, dashed connectors, and categorical color distinctions.  

5. **Alternative Visualization: Clustered Bar Chart**  
   - To improve interpretability, the data is transformed and visualized as a grouped bar chart.  
   - Population, taxation, and area are compared side-by-side for each country.  
   - Faceting by "Power" (Maritime vs. Land) allows clearer comparisons.  
   - Countries are sorted by taxation to highlight disparities (e.g., Britain & Ireland’s high taxation relative to other nations).  

6. **Design Reflection**  
   - Discussion of why clustered bar charts were chosen over alternatives such as bubble plots or grouped box plots.  
   - Step-by-step notes on improving readability (adjusting axis breaks, reformatting labels, facet sizing, theme selection).  
