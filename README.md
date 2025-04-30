# ✈️ NYC Flights 2013 Analysis

An in-depth data analysis project using the `nycflights13` dataset in R. This project investigates flight delays, seasonal trends, weather effects, and airline performance for all flights departing from New York City airports in 2013.

---

## 📁 Project Structure

nycflights13-project/

├── Group7_FinalProject_RedSquadron_v002.Rmd   # Main R Markdown analysis file

├── README.md                                  # Project description and usage instructions

├── LICENSE                                    # MIT License for reuse

├── data/                                      # (Optional) Raw or processed datasets used in analysis

│   └── sample_data.csv                        # Example: any custom data used

├── images/                                    # Visualizations and plots (e.g., .png, .jpg)

│   └── delay_distribution_plot.png

├── output/                                    # Rendered reports (HTML, PDF, etc.)

│   └── Group7_FinalProject_Report.html

└── .gitignore                                 # Files and folders ignored by Git

---

## 📦 Requirements

This project was built using R and the following packages:

- `nycflights13`
- `tidyverse`
- `lubridate`
- `dplyr`
- `ggplot2`
- `knitr`
- `rmarkdown`

To install them, run:

```r
install.packages(c("nycflights13", "tidyverse", "lubridate", "dplyr", "ggplot2", "knitr", "rmarkdown"))
```

## 🚀 How to Run

Follow these steps to reproduce the analysis in RStudio:

1. Clone or Download the Repository
   
    Click the green "Code" button at the top of the repository.

    Choose Download ZIP and extract it, or run:

    git clone https://github.com/ashwinsatra/nycflights13-project.git

2. Open the Project in RStudio
   
    Launch RStudio.

    Open the file:

   Group7_FinalProject_RedSquadron_v002.Rmd

3. Install Required R Packages
   
    Run the following command in the RStudio Console:

   ```{r}
   install.packages(c("nycflights13", "tidyverse", "lubridate", "dplyr", "ggplot2", "knitr", "rmarkdown"))
   ```
4. Run the Code or Knit the Report
   
    Option 1: Click "Knit" to render the .Rmd file to HTML or PDF.

    Option 2: Use "Run" to execute each code chunk interactively.

5. View the Output
   
    The rendered report (HTML or PDF) will be saved in the output/ folder if specified.

    Visualizations will appear in the Plots pane and can be saved manually or via code into the images/ folder.

## 📊 Key Insights

Peak Delays: Summer months (especially July) had the highest average delays.

Airline Comparison: Some airlines consistently performed better than others in terms of punctuality.

Weather Correlation: Adverse weather conditions like wind and precipitation significantly contributed to flight delays.

Time-of-Day Effect: Flights later in the day were more prone to delays due to cascading effects.


## 📌 Dataset Summary
The nycflights13 R package includes the following datasets:

flights: Over 336,000 flight records departing NYC in 2013

weather: Hourly weather data from each airport

airlines: Airline names and codes

airports: Metadata for origin and destination airports

planes: Aircraft information

https://cran.r-project.org/web/packages/nycflights13/nycflights13.pdf

## 👥 Authors

Group 7 – Red Squadron

Ashwin Satra

Dushyant Vaishnaw

Sunny Khade

Houze Zhao

UCR MSBA – Winter 2025

## 📄 License

This project is licensed under the MIT License.

## 💡 Acknowledgements
Hadley Wickham – nycflights13 package creator

UC Riverside Business Analytics Program
