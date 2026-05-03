# Broadway Ticket Pricing Predictor - DSC 465 Final Project
This project is a final project for DSC 465: Machine Learning, at Creighton University. The desired goal is to create an adaptable and dynamic CNN/LSTM model utilizing open-source data that predicts future Broadway ticketing prices. In completing this project, we hope to increase transparency for audience members.

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
| Previews | The number of shows with this designation for a given production, per week. |
| %cap | Mathematical Calculation that corresponds to the percentage of sold seats in the theater: Seats_Sold / (Seats_in_theater) * 8|
| diff_cap | The difference between the previous week's percentage capacity met, and the current week's percentage capacity met. |

**Preview Definition:** A performance that is held for members of the public before the production's official opening night.

---

## 📢 Deployment

This project was deployed utilizing [HuggingFace](https://huggingface.co/spaces/Harrisonnord/DSC-465_Final_project/commits/main). It is publicly-available for prediction usage at the link provided.

### Limitations
The publicly-available dataset only contained data until 2022. Therefore, the model does not predict data past 2023. However, this is the reason why one of our primary project goals was to create an adaptable model. In the case that the data is updated with more recent dates, then with its adaptive capabilities, the model should continue to run with a high accuracy.

---

## 👩‍💻 Team Members

This project was developed as a part of the DSC 465 - Machine Learning course.

| Name | GitHub |
|------|--------|
| [Catherine Larson] | [@catherinelarson-0](https://github.com/catherinelarson-0) |
| [Caitlyn Hern] | [@cihern11](https://github.com/cihern11) |
| [Harrison Nordmeyer] | [@HarrisonNordmeyer](https://github.com/HarrisonNordmeyer) |

---

## 🔍 References

1. Maxwell, D. (2024, March 22). <i>The Truth About Ticket Prices - Is Greed Killing the West End?</i> The Sunday Times. https://www.thetimes.com/culture/theatre-dance/article/the-truth-about-ticket-prices-is-greed-killing-the-west-end-zv7m6sr6v. 

2. Nace, A. K. (2021) Hamilton: Gross Box Office and Sentiment Analysis for Broadway Shows.

3. Shahani, Praheen. “Broadway Shows Data.” Kaggle, https://www.kaggle.com/datasets/praveensh/broadway-shows-data.

4. Simunovic, A. (2025). Machine Learning-Driven Ticket Sales Prediction and Strategic Applications. [Unpublished master’s thesis]. Paris Lodron University of Salzburg. https://eplus.uni-salzburg.at/Abschlussarbeiten/content/titleinfo/12485190
