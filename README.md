## Finding API eBay with python
#### References:
- https://github.com/DrPi101/webscrape-rm/blob/master/README.md
- https://github.com/DrPi101/webscrape-rm/blob/master/ebayapitest.py

#### Steps:
- Install ebasysdk: **pip install ebaysdk**
- Install BeautifulSoup: **pip install beautifulsoup4**
- Save your eBay AppID in a file called **ebayapi.py**: ebayapi='YOUR APP-ID'
- Create a main file called **ebayapitest.py** and paste code from https://github.com/Migueldrums/eBay-Finding-API/blob/main/ebayapitest.py
- Change **siteid** (line 7) to **EBAY-US**. This depends on the eBay site where you want to search.  [(Reference)](https://developer.ebay.com/devzone/merchandising/docs/concepts/siteidtoglobalid.html) 
- Run the code with **python ebayapitest.py** and type what you want to search for. **Example: Thinkpad t470** (Many results will appear, so it is advisable to use Ctrl+C after 2 seconds)