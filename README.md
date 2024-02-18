**Enhancing Indoor Thermal Comfort with Passive Cooling Methods**

**Overview:**
This project focuses on identifying and evaluating passive cooling methods for existing residential buildings in Sri Lanka, aiming to address the challenges of maintaining indoor thermal comfort in the region's hot and humid climate. The research emphasizes sustainable, cost-effective alternatives to traditional active cooling methods. This repo mainly include the data analysis and visualization scripts used to generate graphs and plots.

**Key Features:**
- **Literature Review:** The project starts with an in-depth literature review, cataloging various passive cooling techniques.
  
- **Categorization and Ranking:** Passive cooling methods are categorized based on applicability to existing residential buildings and ranked by their relative cost-effectiveness.

- **Simulation Analysis:** The chosen method, high-reflective roof painting, undergoes detailed analysis using simulation output results.

- **Python Data Analysis:** Python programming is integral to the project, utilized for data analysis and visualization tasks. The script parses and analyzes simulation-generated data, employing algorithms from ASHRAE 55: 2020 to calculate Predicted Mean Vote (PMV) values. These values are then used to assess the thermal comfort of occupants.

- **GitHub Repository Structure:**
  - `/src/input/baseline`: Contains raw data generated for baseline building that does not have high reflective roof painting.
  - `/src/input/improved`: Contains raw data generated for improved building that have high reflective roof painting.
  - `/src`: Python scripts used for data analysis and visualization.
  - `/src/output`: Output data, graphs and plots generated from data analysis.
  - `README.md`: Comprehensive project overview, setup instructions, and guidelines.

**How to Use:**
1. **Clone the Repository:** `git clone https://github.com/yourusername/project-repo.git`
2. **Navigate to the Project Directory:** `cd src`
3. **Run the Python Script:** `data_analysis.ipynb`

**Contributing:**
Contributions are welcome! Whether you're interested in adding more passive cooling techniques, improving data analysis scripts, or enhancing documentation, feel free to submit a pull request.

**License:**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.