# AtliQ Hotels - Hospitality Data Analysis

## Description

This project involves a comprehensive data analysis of hotel booking and revenue data for **AtliQ Hotels**. The goal is to provide data-driven insights to the management team, covering aspects like **occupancy rates**, **revenue generation**, **booking platforms performance**, and overall **market trends** across various cities and hotel categories.

The analysis is performed using Python in a Jupyter Notebook, utilizing key data science libraries to clean, transform, and visualize the data.

## Key Performance Indicators (KPIs) Analyzed

* **Occupancy Rate** (OCC $\div$ Capacity)
* **Revenue Realized** (Total revenue after deductions)
* **Average Daily Rate (ADR)**
* **Cancellation Rate**
* **Successful Bookings**

## Data Overview

The project utilizes a relational dataset structured for an ETL (Extract, Transform, Load) process. The datasets include:

| File Name | Description |
| :--- | :--- |
| `dim_date.csv` | Dimension table for date details (e.g., month, week, day type). |
| `dim_hotels.csv` | Dimension table for hotel properties (e.g., property ID, name, city, category). |
| `dim_rooms.csv` | Dimension table for room categories (e.g., room ID, room class). |
| `fact_bookings.csv` | Fact table containing booking-level data (e.g., revenue, booking status, platform, guests). |
| `fact_aggregated_bookings.csv` | Fact table with daily aggregated bookings and capacity data. |
| `new_data_august.csv` | Additional aggregated data for the month of August for time-series analysis. |

## Analysis Highlight: Revenue Distribution

The following visualization, generated from the `hospitality_analysis.ipynb` notebook, shows the distribution of **Revenue Realized** across different booking platforms.

![Revenue Realized Distribution by Booking Platform](assets/image_abbbe5.png)

* **Observation:** *[Note: You may update this observation based on the chart, but typically in these datasets, 'others' or a specific popular platform like 'makeyourtrip' dominate.]* For example: The 'Others' category or 'MakeYourTrip' accounts for the largest share of the revenue, highlighting their importance in the booking ecosystem.

## Technologies and Libraries Used

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:**
    * `pandas` (for data manipulation and analysis)
    * `numpy` (for numerical operations)
    * `matplotlib` & `seaborn` (for data visualization)

## How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Your-Username/Your-Repo-Name.git](https://github.com/Your-Username/Your-Repo-Name.git)
    cd Your-Repo-Name
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Open the Notebook:**
    Launch Jupyter Notebook or JupyterLab and open `hospitality_analysis.ipynb`. Run all cells sequentially to reproduce the data analysis, transformations, and visualizations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details (if you choose to add one).

## Contact

[Your Name] - [Your LinkedIn/GitHub Profile Link]
