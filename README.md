# 📥 Card-notifier

A simple script that gets executed once a transaction has completed that notifies an external service.

## ℹ️ Background

I wanted to create a service for my business that sends alerts to a dedicated Slack channel of card transactions over R1 000 for a member of the admin team to be able to monitor expenses.

![Example](/docs/example-card-notifier.png)

## ☑️ Requirements

- Access to the [Investec Programmable Banking API](https://developer.investec.com/za/api-products)
- Investec Programmable Cards [Quick Start Guide](https://offerzen.gitbook.io/programmable-banking-community-wiki/get-started/card-quick-start-guide)

## 🚀 Getting Started

- The function inside the `main.js` file is used to replace the `afterTransaction` function from within the Programmable Cards IDE on Investec Online
- You may setup any external service (I have used Slack in this case) and you can replace `webhook` details in the `env.json` file

## 📄 License

This project is MIT licensed.