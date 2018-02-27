![CardGate](https://cdn.curopayments.net/thumb/200/logos/cardgate.png)

# CardGate module for Drupal Commerce

[![Total Downloads](https://img.shields.io/packagist/dt/cardgate/drupal_commerce.svg)](https://packagist.org/packages/cardgate/drupal_commerce)
[![Latest Version](https://img.shields.io/packagist/v/cardgate/drupal_commerce.svg)](https://github.com/cardgate/drupal_commerce/releases)
[![Build Status](https://travis-ci.org/cardgate/drupal_commerce.svg?branch=master)](https://travis-ci.org/cardgate/drupal_commerce)

## Support

This payment module works with Drupal version **7.x** and makes use of Commerce version **1.x**

## Preparation

The usage of this module requires that you have obtained CardGate RESTful API credentials.
Please visit [My Cardgate](https://my.cardgate.com/) and retrieve your RESTful API username and password, or contact your accountmanager.

## Installation

1. Download and unzip the commerce_cardgate.zip file to your desktop.

2. Upload the **contents** of the zip file to your **Drupal modules** folder, which you can find here: **http://mywebshop.com/htdocs/sites/all/modules/**
   (Replace **http://mywebshop.com** with the URL of your webshop, so the files will end up in the **modules folder**)


## Configuration

1. Go to the **admin** section of your webshop and select **Modules**
   Scroll to the **Commerce (CardGate)** section.

2. Checkmark all the **payment methods** that you wish to activate.
   Scroll down and click **Save configuration**.

3. Go to the **admin** section of your webshop and select **Store, Configuration, Payment methods**.

4. Click at **CardGate Generic** on the **Edit** link.
   Click at **Actions** on the **Edit** link.
   
5. Enter the **Merchant ID** and the **Merchant API key** which you have received from CardGate.

6. Enter the **Site ID**, which you can find at **Sites** on <a href="https://my.cardgate.com" target='new'>My CardGate</a>.

7. Enter the **Gateway URL**, the default value is **secure.curopayments.net**

8. Enter the **Test Gateway URL**, the default value is **secure-staging.curopayments.net**

9. To test transactions, select **Test mode** and click **Save configuration**.

10. Go back to the **admin** section of your webshop and select **Store, Configuration, Payment methods**.

11. In the list **not enabled payment methods** select the payment method you wish to activate and click on the **Edit** link.
    At **Actions**, click on the **Edit** link.
    Select the appropriate **Currency** and **save it**.
    
12. At **Settings**, checkmark **Active** so the payment method will be visible in the checkout section of your webshop.

13. Repeat **steps 11 to 12** for each payment method you wish to activate.

14. When you are **finished testing** make sure that you switch the **CardGate Generic module** from **Test Mode** to **Live mode** and save it (**Save**).

## Requirements

No further requirements.
