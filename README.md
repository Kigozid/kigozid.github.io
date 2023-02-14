<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Forex Trading Signals & Account Management</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
    integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css">
  <link rel="stylesheet" href="style.css">
  <script src="https://code.jquery.com/jquery-3.5.1.min.js" integrity="sha384-ZvpUoO/+PpLXR1lu4jmpXWu80pZlYUAfxl5NsBMWOEPSjUn/6Z/hRTt8+pR6L4N2" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
</head>

<body>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Forex Trading Signals & Account Management</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-
<div class="container mt-5">
  <h2>Select a Market</h2>
  <div class="btn-group mt-3" role="group">
    <button type="button" class="btn btn-secondary" id="currency-pairs-btn">Currency Pairs</button>
    <button type="button" class="btn btn-secondary" id="indices-btn">Indices</button>
  </div>
  <div class="mt-5" id="market-container">
    <!-- This container will be populated with the selected market's data -->
  </div>
</div>

<script>
  // Function to display the currency pairs
  function displayCurrencyPairs() {
    const marketContainer = document.getElementById('market-container');
    marketContainer.innerHTML = `
      <table class="table">
        <thead>
          <tr>
            <th>Currency Pair</th>
            <th>Bid</th>
            <th>Ask</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>EUR/USD</td>
            <td>1.20</td>
            <td>1.21</td>
          </tr>
          <tr>
            <td>GBP/USD</td>
            <td>1.30</td>
            <td>1.31</td>
          </tr>
          <!-- Add more currency pairs as needed -->
        </tbody>
      </table>
    `;
  }

  // Function to display the indices
  function displayIndices() {
    const marketContainer = document.getElementById('market-container');
    marketContainer.innerHTML = `
      <table class="table">
        <thead>
          <tr>
            <th>Index</th>
            <th>Value</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Dow Jones</td>
            <td>30,000</td>
          </tr>
          <tr>
            <td>S&P 500</td>
            <td>3,500</td>
          </tr>
          <!-- Add more indices as needed -->
        </tbody>
      </table>
    `;
  }

  // Event listeners for the buttons
  const currencyPairsBtn = document.getElementById('currency-pairs-btn');
  currencyPairsBtn.addEventListener('click', displayCurrencyPairs);

  const indicesBtn = document.getElementById('indices-btn');
  indicesBtn.addEventListener('click', displayIndices);
</script>
<div class="container mt-5">
  <h2>Select a Market</h2>
  <div class="btn-group mt-3" role="group">
    <button type="button" class="btn btn-secondary" id="currency-pairs-btn">Currency Pairs</button>
    <button type="button" class="btn btn-secondary" id="indices-btn">Indices</button>
  </div>
  <div class="mt-5" id="market-container">
    <!-- This container will be populated with the selected market's data -->
  </div>
</div>

<script>
  // Function to display the currency pairs
  function displayCurrencyPairs() {
    const marketContainer = document.getElementById('market-container');
    marketContainer.innerHTML = `
      <table class="table">
        <thead>
          <tr>
            <th>Currency Pair</th>
            <th>Bid</th>
            <th>Ask</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>EUR/USD</td>
            <td>1.20</td>
            <td>1.21</td>
          </tr>
          <tr>
            <td>GBP/USD</td>
            <td>1.30</td>
            <td>1.31</td>
          </tr>
          <tr>
            <td>USD/JPY</td>
            <td>110.50</td>
            <td>110.55</td>
          </tr>
          <tr>
            <td>AUD/CAD</td>
            <td>1.05</td>
            <td>1.06</td>
          </tr>
        </tbody>
      </table>
    `;
  }

  // Function to display the indices
  function displayIndices() {
    const marketContainer = document.getElementById('market-container');
    marketContainer.innerHTML = `
      <table class="table">
        <thead>
          <tr>
            <th>Index</th>
            <th>Value</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Dow Jones</td>
            <td>30,000</td>
          </tr>
          <tr>
            <td>S&P 500</td>
            <td>3,500</td>
          </tr>
          <tr>
            <td>NASDAQ</td>
            <td>13,000</td>
          </tr>
          <tr>
            <td>S&P 100</td>
            <td>2,000</td>
          </tr>
        </tbody>
      </table>
    `;
  }

  // Event listeners for the buttons
  const currencyPairsBtn = document.getElementById('currency-pairs-btn');
  currencyPairsBtn.addEventListener('click', displayCurrencyPairs);
<div class="container mt-5">
  <h2>Select a Market</h2>
  <div class="btn-group mt-3" role="group">
    <button type="button" class="btn btn-secondary" id="currency-pairs-btn">Currency Pairs</button>
    <button type="button" class="btn btn-secondary" id="indices-btn">Indices</button>
  </div>
  <div class="mt-5" id="market-container">
    <!-- This container will be populated with the selected market's data -->
  </div>
  <div class="text-center mt-3">
    <a href="https://tradingster.com" class="btn btn-primary" target="_blank">Go to Tradingster</a>
  </div>
</div>

<script>
  // Function to display the currency pairs
  function displayCurrencyPairs() {
    const marketContainer = document.getElementById('market-container');
    marketContainer.innerHTML = `
      <table class="table">
        <thead>
          <tr>
            <th>Currency Pair</th>
            <th>Bid</th>
            <th>Ask</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>EUR/USD</td>
            <td>1.20</td>
            <td>1.21</td>
          </tr>
          <tr>
            <td>GBP/USD</td>
            <td>1.30</td>
            <td>1.31</td>
          </tr>
          <tr>
            <td>USD/JPY</td>
            <td>110.50</td>
            <td>110.55</td>
          </tr>
          <tr>
            <td>AUD/CAD</td>
            <td>1.05</td>
            <td>1.06</td>
          </tr>
        </tbody>
      </table>
    `;
  }

  // Function to display the indices
  function displayIndices() {
    const marketContainer = document.getElementById('market-container');
    marketContainer.innerHTML = `
      <table class="table">
        <thead>
          <tr>
            <th>Index</th>
            <th>Value</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Dow Jones</td>
            <td>30,000</td>
          </tr>
          <tr>
            <td>S&P 500</td>
            <td>3,500</td>
          </tr>
          <tr>
            <td>NASDAQ</td>
            <td>13,000</td>
          </tr>
          <tr>
            <td>S&P 100</td>
            <td>2,000</td>
          </tr>
        </tbody>
      </

 
