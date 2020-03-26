# hackcovid-checklist
Repository for checklist project for HackCOVID2020
<h1>CHECKLIST</h1>

<h1> Check List for Monitoring patients</h1>
<p> Currently, COVID-19 is spreading as fast as it can in our Country. We need lot of care to treat the current patients as well. We need a fool proof system to maintain the records of people who are in hospitals as well as in Home Quarantine. 
  So to make this secure we need to record all the data of patient.
  
  <h3>Technologies Used</h3>
  - Ethereum
  - IPFS
  - Solidity
  - node.js
  - express.js
  - react.js
  - npm
  
  <p>
  So we have Dapp that records the events. You can create a event and strike it when it is completed. So for each of this process we have all the data being secured in blockchain. 
  
  Example-
  
  Consider a patient-A who just got admitted. Now as there are many patients there is chance of tampering/mix of health reocrds of patient-A with B or others. This will greatly affect us. So We take a photo/pdf of patient -A upload it to IPFS and we'll get a hash. Then we store this hash in our Dapp along with patients name and record a transaction. This helps a lot.
  </p>
  
  
  <h2> Tools and Technologies required</h2>
  <hr>
  1. Truffle and Ganache<br>
  2. Node and NPM<br>
  3. Metamask extension<br>
  4. VS Code(any editor)
  <br>
  
  <p>So please install all the required pre-requistes.</p>
  
  
  <hr>
  
  <h3> Steps to follow to run the Dapp</h3>
  
  1. Install Ganache and Truffle and download this repo.
  2. open cmd and type ``` npm ``` to check if there's node.js installed in your system.
  3. Then navigate to path of the downloaded repo folder by typing 'cd *pathoffile`
  4. Type `truffle migrate` in cmd
  5. Then type `cd src`
  6. Now makesure you have Metamask installed in your browser and Ganache opened.
  7. Type `nodemon app.js`
  8. That's it you'll be redirected to live server 3000. if it is not opening then go to your browser and paste this `http://localhost:3000`
  9. If it does not behave properly on opening,come back and type `truffle migrate --reset` and follow the above procedure.
  
  <hr>
  
:+1: This so looks great - it's ready to run! :shipit:

Some images:

![First Initial Appearance](https://drive.google.com/file/d/1PrQu7CsvCxlG8UZ9apUpocCqo6EycU9H/view?usp=sharing)
