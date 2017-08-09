StrathApps
=========

> WARNING: StrathApps are intended for experimenting and learning, NOT for a production environment.

StrathApps are a suite of apps built in php that can be readily deployed on [Multichain](https://github.com/MultiChain).

System Requirements
-------------------

An instance of [Strathchain](https://github.com/strathchain/strathchain)

Installation
------------

StrathApps are automatically installed during the [Strathchain](https://github.com/strathchain/strathchain) setup.

Creating an account
---------------------
* Visit `http://<IP Address>/strathapps/register.php` and enter your name, username and password.
* Your account will be created.
* You will automatially be taken to the signin page at `http://<IP Address>/strathapps/login.php`
* Enter your username and password to login.

StrathWallet
------------

1. StrathWallet is a simple blockchain powered wallet for Strathcoins, a smart asset.

2. To send Strathcoins, visit `http://<IP Address>/strathapps/ic_send_money.php`

3. To view your transactions, visit `http://<IP Address>/strathapps/ic_view_history.php`

StrathVault (experimental pre alpha, may not work)
------------

1. StrathVault is a simple blockchain powered document storage and retrieval system.

2. To access StrathVault visit `http://<IP Address>/strathapps/vault_upload.php`

3. Select a file to upload, add a description and click upload.

4. If all goes well, you should see a success mesage and the transaction id.

5. Clicking on the transaction id will take you to the Transaction Details page which shows:

  + the Transaction Id - can be clicked to view details
  + Uploader  - can be clicked to view details
  + Block Hash - can be clicked to view details
  + Confirmations
  + Date of Upload
  + Description
  + Download Link

6. To view / search uploads, visit `http://<IP Address>/strathapps/vault_download.php`

StrathContract (experimental pre alpha, may not work)
------------

1. StrathContract is a simple blockchain powered system for digitally signing contracts.

2. To upload a contract, visit `http://<IP Address>/strathapps/contract_upload.php`

3. To invite signees, visit `http://<IP Address>/strathapps/contract_invite.php`

4. To view contracts, visit `http://<IP Address>/strathapps/contracts_history.php`

5. To sign a contract for which you hve been invited, visit `http://<IP Address>/strathapps/contract_sign.php`

6. To view details of a particular contract, visit `http://<IP Address>/strathapps/contract_view_details.php`
