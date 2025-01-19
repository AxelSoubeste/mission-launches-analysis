# Mission Launches Analysis

This project analyzes a dataset of global mission launches to uncover trends, patterns, and insights in the aerospace industry. The dataset includes information about mission dates, organizations, statuses, costs, and other relevant details.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Space exploration has been one of humanity's most ambitious endeavors. This project uses data analytics and visualization techniques to explore how mission launches have evolved over time, which organizations dominate the field, and how costs and safety have changed.

## Dataset Overview
The dataset used in this project is **Mission Launches**, sourced from Kaggle. It includes:
- Launch dates.
- Organizations responsible for the missions.
- Mission statuses (e.g., Success, Failure).
- Mission costs.

### Data Cleaning
- Removed rows with missing or incomplete data.
- Standardized date formats and extracted relevant temporal information (e.g., year, month).
- Simplified mission statuses into “Success” and “Failure” categories for analysis.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mission-launches-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mission-launches-analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the analysis script:
   ```bash
   python analysis.py
   ```
2. Follow the instructions in the script to interact with the data and generate visualizations.

## Key Findings
### 1. Most Active Organizations
- Identified the organizations with the highest number of mission launches in a given year.

### 2. Cost Analysis Over Time
- Visualized how the average cost of a mission has changed over the years, revealing trends in budget allocation.

### 3. Popular Launch Months
- Determined the months with the highest frequency of mission launches, showing seasonal preferences or patterns.

### 4. Safety Trends
- Analyzed the success and failure rates of missions over time, providing insights into advancements in technology and safety measures.

## Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data cleaning and transformation.
- **Matplotlib** and **Seaborn**: For creating insightful visualizations.
- **Jupyter Notebooks**: For interactive data analysis.

## Contributing
Contributions are welcome! If you'd like to:
1. Fork the repository.
2. Create a branch for your feature (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to explore the repository and let us know your thoughts. Happy analyzing!

