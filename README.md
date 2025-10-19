# Synthetic Project Analytics

This repository contains a **ready-to-use** project designed to showcase your skills in business analytics, program management, and data analysis. The project uses a *synthetic dataset* that simulates real-world project management scenarios and walks you through exploratory data analysis and predictive modeling.

## Project Overview

The goal of this project is to analyze and predict key aspects of project performance using a generated dataset. You'll start with an overview of the data, explore it visually, and then build predictive models to answer questions such as:

- Which factors influence whether a project finishes on time?
- How can we predict customer satisfaction based on project characteristics?

The repository is structured to help you demonstrate your analytical workflow—from understanding the data to building and evaluating models.

## Repository Structure

```text
├── synthetic_project_data.csv    # Synthetic dataset used in the notebook
├── analysis.ipynb                # Jupyter notebook with EDA and models
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation and instructions
```

### Data (`synthetic_project_data.csv`)

The dataset contains 200 synthetic projects with the following columns:

| Column                 | Type      | Description                                                      |
|-----------------------|-----------|------------------------------------------------------------------|
| `project_id`           | integer   | Unique identifier for each project                              |
| `project_name`         | string    | Randomly generated project name                                 |
| `team_size`            | integer   | Size of the project team (3–15)                                 |
| `project_duration_days`| integer   | Duration of the project in days (30–365)                        |
| `budget_k`             | float     | Project budget in thousands (approx. 50–500)                    |
| `complexity`           | integer   | Complexity level (1–5)                                           |
| `risk_level`           | categorical | Risk category: **Low**, **Medium**, **High**                     |
| `customer_satisfaction`| float     | Customer satisfaction score (0–100)                             |
| `on_time`              | boolean   | Whether the project finished on time (True/False)               |

This synthetic data is generated programmatically and does **not** represent any real projects.

### Notebook (`analysis.ipynb`)

The notebook walks you through:

1. Loading and inspecting the dataset.
2. Calculating summary statistics.
3. Creating visualizations such as histograms, bar charts, scatter plots, and a correlation heatmap.
4. Building a logistic regression model to predict **on-time completion**.
5. Building a linear regression model to predict **customer satisfaction**.
6. Interpreting the results and summarizing key insights.

Each section is clearly commented to make it easy to follow. Feel free to extend the notebook with additional analyses or models.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the repository** (or download the ZIP from GitHub). In a terminal:
   ```bash
   git clone https://github.com/your-username/synthetic-project-analytics.git
   cd synthetic-project-analytics
   ```

2. **Create a virtual environment** (recommended) and activate it:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook**:
   ```bash
   jupyter notebook analysis.ipynb
   ```

   This will open the notebook in your browser. Run the cells sequentially to explore the data and build the models.

## How to Use This Project to Demonstrate Your Skills

- **Beginner level**: Run the notebook as-is, observe the charts and model outputs, and write a short report summarizing your findings.
- **Intermediate level**: Modify the synthetic data generation or add new visualizations, such as interactive plots or dashboard components.
- **Advanced level**: Experiment with additional machine learning algorithms (e.g., decision trees, random forests, gradient boosting) and compare their performance. You could also integrate the analysis into a data pipeline or build an interactive app using a framework like Streamlit or Dash.

## Contributing

Contributions are welcome! If you'd like to extend this project or fix any issues, feel free to open an issue or submit a pull request. Because this project uses a synthetic dataset, it's a great starting point for practicing data analysis and machine learning skills without worrying about sensitive data.

## License

This project is released under the [MIT License](LICENSE) (if you choose to add one). Feel free to use and adapt it for your personal and professional projects.

---

Feel free to reach out if you have any questions or suggestions on how to improve this project.
