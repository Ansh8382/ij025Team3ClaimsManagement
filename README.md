# Claims Management Application

This is a full-stack MFPE project built as part of Cognizant CDE internship.

Following services are part of the application:
## Frontend:
* Member Portal

## Backend:
* Authorization microservice
* Member microservice
* Claim microservice
* Policy microservice

## Requirements
* Java 8
* Angular 12

## Setup

Launch the above mentioned 4 microservices in your IDE. Import the project as `Maven Project` and wait for the dependencies to install. If any port is unavailable in your machine you can change the port for the respective microservice in the `application.properties` file under `Backend/microservice/src/main/resources/application.properties`

After the 4 microservices are up and running launch the ClaimApp angular application using `ng serve`

## Usage

### Initial Launch

On initial launch of application the user is prompted with a home page of the application. In the navigation bar user can click the `Login` button for authentication.

![alt text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/Home.png)




### Login Portal

User has to enter his username and password to login. Following credentials can be used to login:

| Username   | Password| 
| -----------|:--------|
| aayush     | aayush01|
| ansh       | ansh01  |

![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/LoginInput.png)




## Logged In

Authenticated users can now access the features of the application from the navigation bar under their username.

![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/Features.png)




## Bills Portal

Registered users can enter their Member ID to view their bills which include Due Amount, Last paid date and Premium Amount. 
Use Member ID `M101` to view this user's bills.

![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/BillsPortal.png)


## Submitting a Claim

If a user wishes to submit a claim, the submit claim form can be used where the user can enter details regarding Member ID,hospital,policies, etc. Based on the details provided the status of the claim is decided to be either `pending` or `rejected`. User will also be alloted a `Claim ID` for future reference.

![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/SubmitClaim.png)


## Viewing Claim Status


The user can view the claim status at any time using the `Claim ID` generated in the previous step using the Claim status portal.


![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/ClaimStatus.png)


## Session Expiration


The users's session will be valid for `30 minutes` after which the user will be prompted to login again.

![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/SessionExpired.png)



## Developers

* [Aayush Bangroo](https://github.com/AayushBangroo)
* [Ankit Kharb](https://github.com/Ankit-Kharb)
* [Ansh Gupta](https://github.com/Ansh8382)
* [Apoorva S Menon](https://github.com/Apoorva-Menon)
