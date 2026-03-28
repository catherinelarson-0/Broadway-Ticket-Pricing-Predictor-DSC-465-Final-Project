# Broadway-Ticket-Pricing-Predictor-DSC-465-Final-Project
This project is a final project for DSC 465: Machine Learning, at Creighton University. The desired goal is to create an artificial neural network model utilizing open-source data that predicts future Broadway ticketing prices. In completing this project, we hope to increase transparency for audience members.

---
## 📊 Dataset

### Dataset Source: [Link to Dataset](https://www.kaggle.com/datasets/praveensh/broadway-shows-data)

The data was uploaded by Praveen Shahani. It was scraped from the [Playbill website](https://playbill.com/grosses).
The data contains entries from the years 1985-2022, omitting entries during the COVID-19 pandemic, as theatres closed during this time period.

### Variable Descriptions

| Variable Name | Description |
|------|--------|
| Year | The week of the production's entry. |
| Show_name | The name of the production. |
| Potential_Gross | No provided description. |
| Difference | The difference between the previous week's productional gross and the current week's productional gross. |
| Average_ticket | The average ticket price for the production in the current entry's week. |
| Seats_Sold | The number of seats sold to ticketholders in the current entry's week. |
| Seats_in_theater | The number of seats in the current entry's theatre (assists in determining capacity and percentage of capacity). |
| Previews | [Definition of a Preview](). The number of shows with this designation for a given production, per week. |
| %cap | Mathematical Calculation that corresponds to the percentage of sold seats in the theater: Seats_Sold / (Seats_in_theater) * 8|
| diff_cap | The difference between the previous week's percentage capacity met, and the current week's percentage capacity met. |

**Preview Definition:** A performance that is held for members of the public before the production's official opening night.

---

## 👩‍💻 Team Members

This project was developed as a part of the DSC 465 - Machine Learning course.

| Name | GitHub |
|------|--------|
| [Catherine Larson] | [@catherinelarson-0](https://github.com/catherinelarson-0) |
| [Caitlyn Hern] | [@cihern11](https://github.com/cihern11) |
| [Harrison Nordmeyer] | [@HarrisonNordmeyer](https://github.com/HarrisonNordmeyer) |

---
