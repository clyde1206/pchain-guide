.. _Token Swap:

==========
Token Swap
==========

The ERC-20 PI to native PI swap service has been shutdown at 23:59 on March 31st 2020 (UTC+8) as voted by the Community.

There are two methods to complete the token swap: Exchange Swap and PIwallet Swap

Currently, 4 exchanges (Bibox, Gate.io, Bithumb, Upbit) support native PI. Please note that Bittrex exchange is currently swapping and migrating to our Mainnet.

If your ERC 20 PI tokens are in the ERC 20 wallet, e.g. MEW, Imtoken or cold wallet, please make sure that you keep its private key and/or keystore file well before token swap via PIwallet. If not, then you have to transfer the ERC 20 PI tokens to new ERC 20 address which can be created on PIwallet. (:ref:`Create account on PIwallet<Create or import account>`)

- Exchange Swap (Closed at 23:59 on April 22nd 2020 UTC+8)
Bithumb supports the PCHAIN swap. You can deposit ERC 20 PI to Bithumb account and they will be swapped automatically.
Details: https://support.bithumb.pro/hc/en-us/articles/360033820673-Bithumb-Global-PI-Listing-Jul-31-2019

- PIwallet Swap (Closed at 23:59 on March 31st 2020 UTC+8)
PIwallet only support native PI, and the address created on PIwallet is compatible with ERC-20 address. 

Please read the following reminders before you start PIwallet swap.

1. Update PCHAIN Wallet to the latest version. Click `here <https://github.com/pchain-org/wallet/releases>`_ to download PIwallet.
2. Ensure that you keep the private key and/or keystore file of the ERC-20 PI address well. 
3. Ensure there is a minimum amount of ETH (recommend 0.00036 ether which is 6 gwei*60,000) in your ERC-20 PI address to cover the gas fee.
4. After you send the swap transaction, you will receive your native PI within 2 business days at most.
5. The swap need to get 12 blocks confirmation in Ethereum so the swap may take dozens of minutes.

Step 1: Open the PIwallet and click ‘Token Swap’ tab.

.. image:: ../_static/tokenswap/tokenswap0.png

Step 2: Import your ERC-20 PI address to PCHAIN wallet.

	**Notice:** If you don't wanna import your current ERC-20 address's private key or keystore to PIWallet, you can create an ethereum address by MEW or imToken and tranfer all ERC-20 PI to this new address and then do the token swap.

	Option1: Click ‘Import Private Key ’, fill out its private key. Set password and repeat it. Then click ‘Import’ to confirm. 
	Noticed: Please keep the password well by yourself.   

	.. image:: ../_static/tokenswap/tokenswap1.png

	It will show your ERC-20 PI address and your ERC-20 PI balance there. 

	.. image:: ../_static/tokenswap/tokenswap2.png

	Option 2: Click ‘Import Keystore’, ‘select keystore file’ from your computer.

	.. image:: ../_static/tokenswap/tokenswap3.png

	.. image:: ../_static/tokenswap/tokenswap4.png

	Enter its password and click ‘Import’.

	.. image:: ../_static/tokenswap/tokenswap5.png

	And you will see the ERC-20 PI address and ERC-20 PI balance there.

	.. image:: ../_static/tokenswap/tokenswap6.png

Step 3: Confirm your native PI address.
The default native PI address below is your ERC-20 PI address after importing. 

.. image:: ../_static/tokenswap/tokenswap7.png

If you want to use new address to receive native PI, then click ‘Create Wallet’. Set the password and repeat it. Click ‘Create’ to confirm.

.. image:: ../_static/tokenswap/tokenswap8.png

Step 4: Fill out the amount that you want to swap. Then Click ‘Token Swap’ .
Enter the password and click ‘Confirm’ to continue. Please ensure there is enough ETH in your ERC-20 PI address to cover gas fee. 

.. image:: ../_static/tokenswap/tokenswap9.png

Confirm the swap info. Then click ‘Send Transaction’. It will go to Etherscan automatically, and please be patient to wait for the transaction to succeed.

.. image:: ../_static/tokenswap/tokenswap10.png

.. image:: ../_static/tokenswap/tokenswap11.png

Noticed: If the Etherscan page shows ‘pending’ status or ‘unable to locate this transaction Hash’  status for a long time (e.g. more than 1 hour ), **you can resend with the same amount and greater gas fee. If nonce is same with the former transaction’s, then your former swap transaction will be dropped and replaced by this new one.**

.. image:: ../_static/tokenswap/tokenswap12.png

Step 5: Click ‘Wallet’ tab to check your balance.

.. image:: ../_static/tokenswap/tokenswap13.png

Welcome to :ref:`stake on PCHAIN as Validator<Staking>`! 
