# AWS Banker Bot

## Overview
This project demonstrates the use of **Amazon Lex** to build a conversational chatbot for banking operations. It integrates with **AWS Lambda** and uses **CloudFormation** for deployment.

## Features
- **Custom Intents**: Handle user-specific queries like checking balance or transferring funds.
- **Slots**: Capture user inputs like account types dynamically.
- **Context Tags**: Maintain conversation state for seamless follow-ups.
- **Lambda Integration**: Generate random bank balances and perform verification.
- **CloudFormation**: Automate the deployment of the entire chatbot stack.

## Key Intents
1. **WelcomeIntent**: Greets the user.
2. **CheckBalance**: Retrieves and verifies bank balance.
3. **TransferFunds**: Facilitates fund transfers between accounts.
4. **FallbackIntent**: Handles unrecognized inputs.
5. **FollowUpCheckBalance**: Maintains context for follow-up queries.
