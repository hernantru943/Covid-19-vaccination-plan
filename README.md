# Covid-19 vaccination plan - Project

# Analysis purpose:

How to increase the Covid-19 vaccinated population in low income neighborhoods in NY with a vaccination plan throughout the MTA system.

# Who benefits from exploring this question or building this model/system?

Client: we have been asked to deliver a preliminary analysis for a non profit organization called Foundation for Morristown Medical Center, who will improve tremendously its resources effectiveness on organizing the logistic of their "Vaccination points" in NY by identifying the bussiest stations by day an hour to get as many vaccinated population as possible in low income communities. 

The Foundation for Morristown Medical Center (FFMMC) is a standalone foundation, which is a not-for-profit fundraising organization that solicits funds in its general appeal for the benefit and support of Atlantic Health System, Inc. and AHS Hospital Corporation (the Corporation), and all subsidiaries thereof. Morristown Medical Center is the principal recipient of the fundraising carried out by FFMMC.

Low income population: we will decrease the mortality rate on low income communities due to Covid-19 pandemic.

# What dataset(s) do you plan to use, and how will you obtain the data?

To do this, you will take advantage of free, accessible data about the patterns of transit traffic in New York City: MTA turnstile data.
http://web.mta.info/developers/turnstile.html

# What characteristics/features do you expect to work with?

We are planning to use features such as # entries and # exits by zip code, day and hour in order to identify de bussiest stations to set the Vaccination Points.

# If modeling, what will you predict as your target?

We will be using a linear model to predict the volume of MTA users in low income communities by station, days and hours vs other stations in NY that are not low income.

# MVP Goal:

Highly-trafficked stations in low income communities.
