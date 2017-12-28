OTC
=========

> WARNING: OTC are intended for experimenting and learning, NOT for a production environment.


System Requirements
-------------------

An instance of [OTC](https://github.com/ychaim/otc_chaim)

Installation
------------

OTC are automatically installed during the setup.

Creating an account
---------------------
* Visit `http://<IP Address>/otc/register.php` and enter your name, username and password.
* Your account will be created.
* You will automatially be taken to the sigin page at `http://<IP Address>/otc/login.php`
* Enter your username and password to login.


Vault
------------

1. Vault is a simple blockchain powered document storage and retrieval system.

2. To access Vault visit `http://<IP Address>/otc/vault_upload.php`

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

6. To view / search uploads, visit `http://<IP Address>/otc/vault_download.php`

Contract
------------

1. Contract is a simple blockchain powered system for digitally signng contracts.

2. To upload a contract, visit `http://<IP Address>/otc/contract_upload.php`

3. To invite signees, visit `http://<IP Address>/otc/contract_invite.php`

4. To view contracts, visit `http://<IP Address>/otc/contracts_history.php`

5. To sign a contract for which you hve been invited, visit `http://<IP Address>/otc/contract_sign.php`

6. To view details of a particular contract, visit `http://<IP Address>/otc/contract_view_details.php`


Wallet
------------

1. Wallet is a simple blockchain powered wallet for otcs, a smart asset.

2. To send otcs, visit `http://<IP Address>/otc/ic_send_money.php`

3. To view your transactions, visit `http://<IP Address>/otc/ic_view_history.php`
