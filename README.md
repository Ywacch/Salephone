# Salephone

Salephone is an e-commerce app that automates the listing of smartphones on various platforms by predicting future prices based on historical data. It helps users choose phones from a catalogue, where each phone has detailed price history data. This enables the automation of listings with competitive pricing.

![Salephone Overview]((https://github.com/Ywacch/smartphone_datagrabber/blob/main/Salephone%20architecture.jpg)) 

## Features

- **Automated E-commerce Listings**: Automatically generates and manages listings for smartphones on e-commerce platforms.
- **Historical Price Data**: A comprehensive dataset of smartphone prices, spanning over 4 years and containing 5 million+ records.
- **Price Predictions**: Utilizes machine learning models to forecast future smartphone prices, enabling users to set competitive pricing for their listings.
- **Efficient Data Processing**: Asynchronous data fetching and caching for faster API responses and improved system performance.
- **High Availability**: Built with replication and caching to ensure reliability and fast access to data.

## Architecture

Salephone is divided into several services, each designed to handle a specific part of the process, including data collection, machine learning-based price prediction, API access, and e-commerce integration. 

## Related Repositories

The Salephone system is composed of several microservices, each hosted in its own repository:

- [Data Collection Service](https://github.com/Ywacch/smartphone_datagrabber)
- [Price Prediction Service](https://github.com/Ywacch/SalephoneTrader)
- [API Service](https://github.com/Ywacch/SalephoneAPI)
- [E-commerce Integration Service](https://github.com/Ywacch/SalephoneLister)
- [End user Web Application](https://github.com/Ywacch/SalephoneApp)
