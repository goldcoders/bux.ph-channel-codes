# Bux.ph Fetch Details Api

> Use With Thriftshop Site as a Serverless Function

## Requirements
- netlify-cli
- postman

## Development
- [ ] Clone this Repo

```sh
git clone https://github.com/goldcoders/bux.ph-channel-codes
cd  bux.ph-channel-codes
```

- [ ] Edit ENV: `cp .env.example .env anad edit .env`

- [ ] Install Any NPM Dependencies type: `yarn`

- [ ] Run Local Server: `netlify dev`

- [ ] open postman and set url to `http://localhost:8888/api` method: ***POST***

- [ ] Click Send, Receive the Response

<details>
  <summary>Response JSON</summary>

```json
{
    "Non Bank OTC": {
        "7-Eleven": {
            "code": "711_direct",
            "gateway": "Direct",
            "instructions": {
                "Payment": [
                    "Go to nearest branch",
                    "Present the barcode or reference number",
                    "Pay the specified amount",
                    "The Cashier will process your payment in real-time"
                ]
            },
            "terms": "https://www.cliqq.net/terms/"
        },
        "Bayad Center - Dragonpay": {
            "code": "BAYD",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "Cebuana - Dragonpay": {
            "code": "CEBL",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "LBC - Dragonpay": {
            "code": "LBC",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "Mlhuillier - Dragonpay": {
            "code": "MLH",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "SM/Supermarket/Savemore - Dragonpay": {
            "code": "SMR",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "Robinsons Dept Store - Dragonpay": {
            "code": "RDS",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "ECPay - Dragonpay": {
            "code": "ECPY",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "Palawan - Dragonpay": {
            "code": "PLWN",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "RD Pawnshop - Dragonpay": {
            "code": "RDP",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "RuralNet - Dragonpay": {
            "code": "RLNT",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "Posible": {
            "code": "posible",
            "gateway": "Direct",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.posible.net/privacy-policy"
        },
        "Partnerpay": {
            "code": "partnerpay",
            "gateway": "Direct",
            "instructions": {},
            "terms": ""
        },
        "Pay N Go": {
            "code": "payngo",
            "gateway": "Direct",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://bux.ph/bti_terms/"
        },
        "DA5": {
            "code": "da5",
            "gateway": "Direct",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://bux.ph/da5_terms/"
        },
        "ECPay": {
            "code": "ecpay",
            "gateway": "Direct",
            "instructions": {},
            "terms": ""
        },
        "USSC - ECPay": {
            "code": "ussc",
            "gateway": "ECPay",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://ussc.com.ph/privacy-policy/index.html"
        },
        "Rustans - ECPay": {
            "code": "rustan",
            "gateway": "ECPay",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://themarketplace.com.ph/privacy-policy"
        },
        "Shopwise - ECPay": {
            "code": "shopwise",
            "gateway": "ECPay",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.shopwise.com.ph/privacy_policy"
        },
        "Tambunting - ECPay": {
            "code": "tmbntng",
            "gateway": "ECPay",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://tambunting.ph/Main?privacy"
        },
        "CVM - ECPay": {
            "code": "cvm",
            "gateway": "ECPay",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "http://www.cvmpawnshops.com/privacy-policy/"
        },
        "Wellcome - ECPay": {
            "code": "wellcome",
            "gateway": "ECPay",
            "instructions": {
                "Payment": [
                    "Write Bux as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://wellcome.org/about-us/governance/privacy-and-terms"
        },
        "Expresspay - Dragonpay": {
            "code": "EXPY",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "Write Dragonpay as your Biller Name",
                    "Provide Reference number and make sure it is correctly entered in the Account Number field. A wrong account number can cause your transaction to remain unvalidated",
                    "Provide your Full name and make sure your Total amount is correct and the same on this receipt",
                    "Please provide a valid Contact number where we can reach you in case there are problems with the validation"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        }
    },
    "Banking": {
        "BPI - Dragonpay": {
            "code": "BPIA",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "You will be redirected to the chosen bank's webpage",
                    "Login to your Online Banking Account,You will receive a One-Time PIN (OTP) to your registered mobile number",
                    "Authorize the payment"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "UBP - Dragonpay": {
            "code": "UBPB",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "You will be redirected to the chosen bank's webpage",
                    "Login to your Online Banking Account,You will receive a One-Time PIN (OTP) to your registered mobile number",
                    "Authorize the payment"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        },
        "RCBC - Dragonpay": {
            "code": "RCBC",
            "gateway": "Dragonpay",
            "instructions": {
                "Payment": [
                    "You will be redirected to the chosen bank's webpage",
                    "Login to your Online Banking Account,You will receive a One-Time PIN (OTP) to your registered mobile number",
                    "Authorize the payment"
                ]
            },
            "terms": "https://www.dragonpay.ph/terms-and-conditions"
        }
    },
    "EWallet": {
        "GCash": {
            "code": "gcash",
            "gateway": "Direct",
            "instructions": {
                "Payment": [
                    "You will be redirected to the chosen bank's webpage",
                    "Login to your GCash Account,You will receive a One-Time PIN (OTP) to your registered mobile number",
                    "Authorize the payment"
                ]
            },
            "terms": "https://www.gcash.com/app/v1.0.0/terms-and-conditions"
        },
        "Grabpay": {
            "code": "grabpay",
            "gateway": "Direct",
            "instructions": {
                "Payment": [
                    "You will be redirected to the chosen bank's webpage",
                    "Login to your GrabPay Account,You will receive a One-Time PIN (OTP) to your registered mobile number",
                    "Authorize the payment"
                ]
            },
            "terms": "https://grab.com/ph/terms-policies/payment-rewards/"
        }
    },
    "Card Payments": {
        "Card Payments - Xendit": {
            "code": "visamc",
            "gateway": "Xendit",
            "instructions": {
                "Payment": [
                    "You will be redirected to the Xendit webpage",
                    "You will be prompted to enter your Card DetailsYou will receive a One-Time PIN (OTP) to your registered mobile number",
                    "Authorize the payment"
                ]
            },
            "terms": "https://www.xendit.co/en/terms-and-conditions/"
        }
    },
    "BNPL": {
        "Billease": {
            "code": "billease",
            "gateway": "Direct",
            "instructions": {},
            "terms": ""
        }
    }
}
```
</details>

## 1 Click Install For Production

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/goldcoders/bux.ph-channel-codes)

## Deploy on One Specific Site URL in Production

- Go to [Settings](https://app.netlify.com/sites/tss-test/settings/general)

- Click Change Site Name `bux.ph-channel-codes.${yourdomain}.com`

## Production

- make post request with Needed *payload* to `bux.ph-channel-codes.${domain}.com/api`

