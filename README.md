# Commerce API Postman Collection
Welcome to the demo of the Commerce API! You can use this Postman collection to test our API offering, string together cart flows, and make calls to a test environment with a test API key provided to you by Digital River.
## Documentation
You can find documentation on the Digital River API on our Developer Portal here: https://docs.digitalriver.com/commerce-api
# Installation and Use
To install the API Demo, you can click the Run in Postman button below:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/c9d17e796855a15cac83)

Alternatively, you can install this collection from your Postman client by directly downloading the .zip file, selecting "Import," and dropping in the .json file. 

## Step 1: Create or use an existing Global Commerce Site
Before you can start making Commerce API requests, you'll need to contact Digital River to start the process of creating a Global Commerce (GC) Site. This will also include a product/pricing/promotions setup step.

If you have an existing GC Site please discuss a migration with your assigned account team. To start the Site creation process go to the [Request Demo page](https://www.digitalriver.com/request-demo/) and request a test API key in the "Tell Us More" section and mention "Commerce APIs". From there, Digital River will reach out to you with further information. 

## Step 2: Obtain API credentials
Before you can start making Commerce API requests, you'll need to obtain test keys. After getting your keys, you can begin to make test calls to the API.

## Step 3: Perform a test request
In Postman, you will need to have your public and confidential keys available. Modify these variables in the [Collection Variables](https://learning.postman.com/docs/sending-requests/variables/#defining-collection-variables) section:

- *apiDomain* - **Production:** api.digitalriver.com | **CTE:** api-cte-ext.digitalriver.com
- *publicApiKey* - Generated for you and provided by Digital River
- *drjsApiKey* - Generated for you and provided by Digital River
- *confidentialApiKey* - Generated for you and provided by Digital River
- *confidentialSecret* - Generated for you and provided by Digital River

Once you set up the variables, simply go through the calls in order.

# Contact Us
If you have questions/concerns or if you want to move forward with Digital River, please visit our website at https://www.digitalriver.com/ and select “Contact Us.”
