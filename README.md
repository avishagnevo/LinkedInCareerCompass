# LinkedInCareerCompass
Data Collection Lab (094290) Final Project : Career Compass: Navigating Salary Insights with AI

### Overview
This project aim to create a feature specially for LinkedIn's end-users, our project enhances LinkedIn's Salary Insights tool with an AI-powered pipeline for personalized salary analysis. Drawing from a large dataset "/LinkedIn/profile" (collected by Bright Data), our project uses advanced statistical and machine learning techniques to offer a tailored view of the users' salary wellness.

### Repository Structure
- **data/**: Stores datasets for the analysis and modeling phases.
  - `min_max_salary.json`: Provides salary ranges for various of popular job positions.
  - `positions_above_300.csv`: Catalogs frequently listed job positions from "/LinkedIn/profile".
  - `predictions.csv`: Records the salary predictions generated by our models.
  - `salary_positions.csv`: Correlates specific job positions with salary data from "Indeed" website.
  - `user_params.csv`: Containes parameters for custom user salary inference.

- **src/**: Includes all Jupyter Notebooks forming our workflow.
  - `preprocessing_analysis_synthesize_train_inference.ipynb`: Covers the entire process from data cleaning to model training and inference.
  - `prompt_inference.ipynb`: Used for running the model inference to generate user-specific salary insights.
  - `parse_min_max_salary.ipynb`: Transforms scraped raw data into a structured CSV format for the data sythesizing.

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/LinkedInCareerCompass.git
cd LinkedInCareerCompass
pip install -r requirements.txt
```

### Usage
Within the `src/` directory, the Jupyter Notebooks can be run in sequence to replicate our data processing and analysis pipeline and result datasets.
