# MagicEden Minting Bot

# This bot will help you buy NFTs the fastest, but does not guarantee a 100% purchase.
This bot sends a request to the server magiceden.
Make sure the time on your computer is set correctly.

You can support me with some SOL : BmgFSsNKAKPgpo9U8mKZJ8kgCmHdnKX31UkpTMJaE8YB

### Support

-   [x] Window
-   [x] Mac (Intel + m1)
-   [x] Linux

---

-   Like I said this bot uses ChromeDriver so on mac there is a possiblity that you will have to allow the software to run in your privacy settings. Check mac folder for more info.

-   The chrome window will appear **WITHOUT** loading the images, this is to ensure the fastest loading.

---

## Tutorial

---

1. Clone the repository / Download zip file

    `git clone https://github.com/SolanaMike/Minting-bot-solana.git`

    OR

    [Download Zip File](https://github.com/SolanaMike/Minting-bot-solana/archive/refs/heads/main.zip)

---

1. Be sure you have installed Python correctly, [here is a link to download](https://www.python.org/downloads/)

---

2. Open command prompt

---

3. Install all python module

   `pip install selenium requests`
   
   and

   `python -m pip install git+https://github.com/np-8/webdriver_manager.git`

   (currently using this since the last webdriver manager main isn't working)
   
   or
   
   `pip install webdriver-manager`

---

4. Replace Phantom Passphrase and password in `config.json`

    `launchpadLink` --> Provide a link to the sale

    `seedPhrase` --> Specify the passphrase wallet (Careful do not share this key)

    `password` --> Enter your wallet password

---

5. Open CMD and go to directory

    `cd /path/to/directory/Minting-bot-solana`

---

6. Run the python file

    windows : `python main.py`

    mac : `python3 main.py`
