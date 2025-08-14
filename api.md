# BankLab API Documentation

This document outlines the API structure of the BankLab project, organized by feature folders.

## 📂 `accounts`
- **account-link.json**: Link a new bank account.
- **account-list.json**: Retrieve a list of linked bank accounts.
- **account-refresh.json**: Refresh the data for a linked bank account.
- **account-transactions.json**: Get transactions for a specific account.
- **account-unlink.json**: Unlink a bank account.

## 📂 `analysis`
- **peer-comparison.json**: Compare financial data with peers.
- **transaction-summary.json**: Get a summary of transactions.
- **transactionBycategory.json**: Get transactions grouped by category.

## 📂 `calculator`
- **annuity-calculator.json**: Calculate annuity payments.
- **deposit-calculator.json**: Calculate deposit interest.
- **get-profile.json**: Get user profile for calculator defaults.
- **loan-calculator.json**: Calculate loan repayments.
- **savings-calculator.json**: Calculate savings growth.

## 📂 `cash`
- **cash-get.json**: Retrieve cash balance.
- **cash-set.json**: Set or update cash balance.

## 📂 `contents`
- **exchange-rate.json**: Get current currency exchange rates.
- **finance-quiz.json**: Get a finance-related quiz.
- **finance-terms-detail.json**: Get the definition of a specific finance term.
- **finance-terms-keyword.json**: Get finance terms by keyword.
- **finance-terms-list.json**: Get a list of all finance terms.
- **finance-terms-random.json**: Get a random finance term.
- **finance-terms-search**: Search for finance terms.
- **finance-terms.json**: General endpoint for finance terms.
- **gold-price.json**: Get the current price of gold.
- **news.json**: Get financial news.
- **quiz-all.json**: Get all quiz questions.
- **quiz-daily-result.json**: Get the results of the daily quiz.
- **quiz-statistics.json**: Get overall quiz statistics.
- **quiz-user-stats.json**: Get quiz statistics for a specific user.
- **stock-timeseries.json**: Get time-series data for a stock.
- **stocks-save-data.json**: Save stock data.
- **stocks.json**: Get general stock information.
- **upbit-crypto.json**: Get cryptocurrency data from Upbit.
- **upbit-search.json**: Search for cryptocurrencies on Upbit.
- **upbit-top-coins-by-type.json**: Get top cryptocurrencies by type from Upbit.

## 📂 `products`
- **annuity-detail.json**: Get details of an annuity product.
- **creditloan-detail.json**: Get details of a credit loan product.
- **deposit-detail.json**: Get details of a deposit product.
- **mortgage-loan-detail.json**: Get details of a mortgage loan product.
- **renthouse-loan-detail.json**: Get details of a rental house loan product.
- **savings-detail.json**: Get details of a savings product.

## 📂 `stocks`
- **stock-detail.json**: Get details for a specific stock.
- **stock-link.json**: Link a new stock account.
- **stock-list.json**: Get a list of linked stock accounts.
- **stock-refresh.json**: Refresh data for a linked stock account.
- **stock-unlink.json**: Unlink a stock account.

## 📂 `transaction`
- **get-transaction.json**: Retrieve a specific transaction.
- **status-transaction.json**: Check the status of a transaction.

## 📂 `typetest`
- **get-all-investment-products.json**: Get all investment products for the type test.
- **get-investment-type-result.json**: Get the result of an investment type test.
- **get-user-investment-type.json**: Get the user's saved investment type.
- **question-list.json**: Get the list of questions for the investment type test.
- **submit-answers.json**: Submit answers for the investment type test.
