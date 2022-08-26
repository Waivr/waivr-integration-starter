# Waivr - JQuery Integration

This folder cover the following example:
- GIVEN that you have a checkout flow
- AND you want to integrate with Waivr
- THEN Create a Payment Instruction
- AND make the first payment

## Pre-Requirement
Your business needs to have been already onboarded with Waivr's and you have access to an API Access Token.

For more details about this process, please proceed with the following options:

## 1 - If you're a business partner or an independent merchant that directly integrates with Waivr

- API Documentation: https://docs.waivr.co/api/business_partner
- Check our postman example at this repository's `postman` folder located in the root node.
- Book a meeting with us to go over your needs.

## 2 - If you're a business partner and wants to transact on the behalf of a merchant

- API Documentation: https://docs.waivr.co/api/merchants
- Check our postman example at this repository's `postman` folder located in the root node.
- Book a meeting with us to go over your needs.

Note: For Step 2, it's mandatory that you as business partner has already configured Step 1.

## Integration Starter
- First, check `WaivrStore.html` which contains the onboarding and the payment instructions creation
- Second, check `WaivrStoreConfirmation.html` which displays the payment summary and make a payment
