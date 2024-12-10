
<br />
<p align="center">
  <a href="https://github.com/Levis-KG-Kim/stock-price-movement-Classification-Project">
    <img src="images/line.png" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">Stock Market Prediction using Classification Models</h3>

</p>


<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installations">Installations</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>


## About The Project

A hedge fund that trades on markets all over the world seeks a model they can add to their trading arsenal. Specifically, they want a model that will help them decide when to open and close their long term swing trades i.e trades that span between a few days to years. By taking in information as it comes in daily, the model should be able to analyse market sentiment and predict market movement the following day - Bullish or Bearish.
It can be used for any asset traded in a stock exchange given there is data of at least 5 days prior.
If the prediction is bullish for the following day output is 1 if bearish output is 0.
The dataset used is sp500 and is sourced from yfinance(yahoo finance).

[Stock Price movement classification using Logistic regression and decision trees](https://github.com/Levis-KG-Kim/stock-price-movement-Classification-Project)

You can include tables or images to summarize your results when and if appropriate.



### Dependencies

Here are packages and other dependencies that need to be installed to run this project: 
* yfinance
* Python
* Sci-kit learn
* Pandas
* Matplotlib
* Seaborn

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Levis-KG-Kim/stock-price-movement-Classification-Project
   ```
2. Setup (and activate) your environment
  ```sh
  conda env create -f requirements.yml
  ```

## Usage

This project can be used for any stock market assets all over the world as long as the required features i.e daily close price and daily volume which can be used to engineer other features.
Examples of users are retail traders, trading firms, investment institutions, hedge funds etc.
From the information predicted, it's possible to time opening and closing of trades.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## License

Distributed under the MIT License.


## Authors

Name- Gichuhi Levis Kimani - [@your_twitter](https://twitter.com/your_username) 
Email- gichuhilevis0@gmail.com
linkedIn- 

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)


## Acknowledgements

You can acknowledge any individual, group, institution or service.
* [Moringa School](https://moringaschool.com/)
* [Yahoo Finance](https://finance.yahoo.com/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAGc1pxKo3NqRvx4x83PEljG3LG-097MMsoJe4zngxK1UPYZfQ1VKGG5L7Oo01prT_oot-K8F4rdmAedbPpMPRRyi_bZ3CbPDUBbEZChQJmmGEZk1J_FQcN41qiHU3FsDyhfKby335UfwaLwZr83Z2vpN1D0VAsMuyB4JLXTB6xt_)


## Thank you