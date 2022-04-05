# blockchain_POC
Simple blockchain POC using python flask, anaconda spyder

1) download and install anaconda
2) pip install flask
3) pip install requests

step 1 : launch spyder from anaconda navigator
![image](https://user-images.githubusercontent.com/43343732/161747209-97f4dd38-1140-4831-b8c0-f11da1da3d6a.png)


step 2 : select **currency_note_node_5001** and press ctrl + enter key and do the same for **currency_note_node_5002** and **currency_note_node_5003** with new console tabs each.

step 3 : connect all the nodes with each other. request required from each port. http://127.0.0.1:5001/connect_node, http://127.0.0.1:5002/connect_node and http://127.0.0.1:5003/connect_node
![image](https://user-images.githubusercontent.com/43343732/161745848-9314c2db-c63a-4dab-ab9f-edba66294ae9.png)

step 4 : add transactions
![image](https://user-images.githubusercontent.com/43343732/161746622-b596cb86-9e03-4a0c-8b88-2e13f5694571.png)


step 5 : before mining block replace your chain
![image](https://user-images.githubusercontent.com/43343732/161746854-faeac713-d9ba-48ea-aeef-b0ee160d9847.png)


step 6 : mine block
![image](https://user-images.githubusercontent.com/43343732/161746678-d36c4124-98ea-48de-9e13-aac4fad57a41.png)


step 7 : to see the same block in any node just follow the step 5 with port where chain is not updated.
