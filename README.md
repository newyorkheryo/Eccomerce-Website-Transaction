## Project Description
This capstone project involves generating fake transaction data from ecommerce websites and sending it to the other team via kafka. They do the same and we analyze their data and try to understand the algorithms they used to generate it.

Click here to see the [demo](https://drive.google.com/file/d/13EnXR1t0JLOYI8LY9EOjFcxR0lCpiTWw/view?usp=drive_link)

## Features
- Generates transaction data for each company over the span of 10 years
- Uses base data on products, companies, and customers stored in files to generate the transactions
      - Very customizable
- Can generate its own customers from over 20 different countries with accurate names to the region
- The price used in the transaction is converted from USD into the customer's local currency
- Bad data can also be generated for any row and column at a rate of 3%
- Creates a logistic growth for each company at differing rates
- Is fairly efficient, generates 2 million rows of transactions in 30 seconds on average
- Kafka producer and consumer send and receive data in under a minute as well
## Technologies Used
- Apache Spark
- Spark SQL
- Kafka
- Scala 2.12.11
- Zeppelin
- SBT
## Future Development
- Optimize Kafka consumer
- Further optimize data generation
- Allow new companies to be added
## Getting Started
- Clone this repository
- Make sure all required technologies are updated to their correct versions
## Contributors
- [Caleb Reid](https://github.com/calebreid2829)
- [Jaceguai De Magalhaes](https://github.com/jaceguaidemagalhaes)
- [Dare Fatade](https://github.com/ofatade)
- [Theodore Karl](https://github.com/TK-Rev)
- [Youngjung Kim](https://github.com/YoungjungKim016)
- [Aaron Schomer](https://github.com/AarSchoSkIg)
- [Jack Nguyen](https://github.com/Jackeywawa)
- [Newyork Her](https://github.com/newyorkher)
