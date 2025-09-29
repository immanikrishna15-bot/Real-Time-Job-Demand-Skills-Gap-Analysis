# Regional Job Market & Skills Gap Dashboard

Analyzes job demand and skill supply (Python, SQL, AI, etc.) across Tier-1 and Tier-2 Indian cities using data from LinkedIn, Naukri.com, and government sources. Interactive visualizations show real-time trends and skills gaps.

## Setup Instructions
1. Clone the repo:
   ```
   git clone https://github.com/immanikrishna15-bot/streamlit-data-dashboard.git
   ```
2. Navigate to the directory:
   ```
   cd streamlit-data-dashboard
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the dashboard:
   ```
   streamlit run dashboard.py
   ```

## Usage
- Visualize job demand and skills gap by region, city tier, and skill.
- Real-time dashboard with interactive maps and charts.

## Data Sources
- LinkedIn, Naukri.com job postings
- Census/education data
- Salary reports

## Files
- `data_pipeline.py`: Collect and process data
- `dashboard.py`: Streamlit app
- `requirements.txt`: Python dependencies
- `config.py`: Config variables (city tiers, APIs)
- Sample data files (`job_postings_sample.csv`, etc.)
