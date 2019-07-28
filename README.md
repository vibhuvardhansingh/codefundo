# Online Voting 
<img src="https://user-images.githubusercontent.com/48177487/61993848-9b127200-b08f-11e9-9b65-13af48d5a536.jpg" align="right"
     title="Right to Vote" width="200" height="178">
## Present voting system
The right to vote is an inalienable part of a citizen’s right in a democracy, subject to certain conditions laid down by the state. As per the Election commission of India, citizens are eligible to become voters only if he/she is enrolled at place of residence. At present voting is done in EVMs.

## Current issues
1. Different political parties have questioned about the hacking done in EVMs. This can be great threat to democracy.
2. A person may be living in a location other than the constituency where she/he is registered as a voter.So the person cannot  vote for his constituency which lead to partial voting win, in which everyone is not involved. 
3. Many voters randomly give their votes. There is no information given about the candidates past history or his present agenda.
## Our solution to Current issues

![blockchain-voting-system](https://user-images.githubusercontent.com/48177487/62005761-a29c4e80-b155-11e9-8742-5a1afe213b16.png)


1. Blockchain technology has the ability to introduce a system that is seemingly impossible to hack .Once a voter is eligible to vote, they would receive a key that would allow them to vote exactly once. We will also use elliptical curve cryptography. Plus, the whole voting process would be decentralized, which means that there is no central agency which must be trusted to conduct the elections fairly and securely. Anybody can participate and become a node in the system as long as they meet requirements which are confirmed during registration  which will collectively ensure that the system is available throughout the duration of the election, and that the votes are counted correctly. In this way every vote will be safe.


2. We will build a application ussing flutter framework and will be using technologies of machine learning.A voter will open the app in his home and using his/her smartphone , face and finger prints  will identified and it will be cross checked with his adhaar card. After succesful verification, the voter can give his vote and the vote will be verified using blockchain. This will help a person from a different place to vote for his constituency.

3. In our app ,all the information related to candidate will be present such as his past records,current agenda and also if there is any criminal case against him . This will give a clear idea to a voter to whom to vote.

<img src="https://firebasestorage.googleapis.com/v0/b/code-fun-do-26d59.appspot.com/o/cfd_screenshot.jpg?alt=media&token=d1ba6ebb-c795-4988-a93d-eed6057e7e8a" align="center"
     title="Right to Vote" width="400" height="200">

## Technology Used  
- Azure Blockchain Service on Remix.

Smart Contracts will verify transaction and will keep the voter anonomous.

- Flutter Framework for Cross Platform App.

App will consist of a Ballot Paper List and Contestants Profile

- Firebase Database, Storage and ML Kit

Firebase will store the information of contestants in Database and Storage.
- Cloud Functions on Node.JS

Cloud Functions will Integrate Firebase Database and Microsoft Azure Blocking.

- Machine Learning and Face Detection Modals

Scanning of Voter ID and Face Detection will reduces chances of fraud.



