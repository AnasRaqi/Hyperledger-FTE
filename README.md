# Hyperledger-FTE
FTE will enable end-to-end tracking of medicinal products throughout the pharmaceutical supply chain



<img width="825" alt="Screen Shot 2022-02-08 at 8 40 14 AM" src="https://user-images.githubusercontent.com/47697877/152919386-b49b3395-6949-49ab-8a4f-ba1bfe0721ad.png">



#Process Flow 
1. The manufacturer produces drugs, then packages and labels them
2. The distribution company gathers packaged products and begins delivery
3. The distribution company send drugs to pharmacies
4. The distribution company send drugs to hospitals
5. The distribution company send drugs to physicians
6. Customers buy drugs from a pharmacy, hospital, or physician
#Flow Diagram 
<img width="759" alt="Screen Shot 2022-02-08 at 8 43 04 AM" src="https://user-images.githubusercontent.com/47697877/152919643-c4119cc1-7404-44a2-9a4c-5e9cd7b40c29.png">
#Entities
Manufacturer, Distribution, Pharmacy, Hospital, Physician, Customer. 
#Assets
We will record every transaction in the blockchain. 
#Query 
Drug ID
Drug name
FDA action date
Marketing status (prescription, over-the-counter, or discontinued)
Approval type (type of supplement or other regulatory action)
Search participants by ID
#Critial Files 
1. Model File: org.packt.farmatrace.cto
2. Script File: logic.js
3. ACL File: permissions.acl
4. Query File: queries.qry 
Note: We will setup a development environment and then create those critical file in the process. 
