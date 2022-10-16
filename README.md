# Web Service for collecting an information about NFTs
#### NFTSearcher - user provides an NFT address and clicks a button, it should display information about that NFT and store all data in a Postgres database.

# Installation
### 1.1 Before you begin, you will need to have the installed on your computer:

+ [Git](https://git-scm.com/)
+ [Python](https://www.python.org/)
+ [Flask](https://palletsprojects.com/p/flask/)

To install README "NFT", follow these steps:
```
# Clone this repository
$ git clone https://github.com/coffeewithtears/NFTSearhcer.git

# Create a virtual environment (optional but recommended):
$ python -m venv venv

# Activating the virtual environment:
$ source venv/bin/activate

# Install requirements:
$ pip install -r requirements.txt 

# Go to src directory:
$ cd src

# Run it:
$ flask --app app.py run
```
# Usage
Go to http://127.0.0.1:5000/ to see the app running.

# Examples

1.1 First, copy the nft address on the website https://solanart.io/

![photo1665925266](https://user-images.githubusercontent.com/96559542/196038100-eedb67e8-5422-4a16-865e-40387f778bda.jpeg)

1.2 On the first page of our site, paste the copied address: first, it inserts information about nft into the database.

![photo1665925217](https://user-images.githubusercontent.com/96559542/196038101-374be81e-a1e1-41ce-9c89-fcc58df76e9e.jpeg)

![photo1665925351](https://user-images.githubusercontent.com/96559542/196038099-68580196-41b3-494b-850d-c4f6a908e126.jpeg)

1.3 Repeat the process



1.4 Now it gives information about NFT.

![photo1665925393](https://user-images.githubusercontent.com/96559542/196038096-9acddb62-b88a-489b-81c5-91340a0d1067.jpeg)

# LICENSE

https://choosealicense.com/licenses/mit/
