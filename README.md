# Open+

An innovation bank application especially for **disabled people**.

<img src="./resource/opentofuture.png" alt="open+ log Image."/>

In a post-pandemic world, accessibility has emerged as a critical factor for all customers.  

According to the World health organization article published in 2021, over **1 billion** people live with some form of disability. For these people, carrying out various banking tasks becomes challenging. 

**We, at Finastra, always strive to make world of finance OPEN, would like to help them with more smoothy bank experience.**

As a next step for fulfilling this vision, we would like to take an opportunity to announce our new application with ready-to-integrate toolkit, **OPEN+**, 

It is aimed to remove barriers and increase accessibilities of open banking for people with Visual & Hearing Impairment, Speech difficulties, physical impairment, and so on. Thanks to this application, Financial institutions can now offer services to a new group of people who have any kind of impairments.  

Open+ works on top of APIs on Finastra’s **FusionFabric.cloud platform** which can be easily integrated into the most common banking applications, the setup is fast and intuitive for any user.


## More info
[Design](https://www.figma.com/file/CzHrvNVGyDUd7YdFxD5IwY/OPEN%2B?node-id=0%3A1 
)

[Demo Video]()

## Tech architecture
[Application Architecture]()

We provide a [Bank Service portal]() for bank to onboard their applications. Bank admin can configration the client secret to secure their api call from fusionfabric.cloud. 
They can also map the user from bank to fusionfabric.cloud so that the clinet can login directly with face or voice without any account number to reduce the complexity for disabled people.  

All the request to bank should come from [fusionfabric Cloud Servcies](./ffdc-services/README.MD) where the bank can config and handle the client secret. It will be very safe for bank to allow this request. And fusionfabric.cloud will handle operations for banks, they don't need to work on the complex frontend if they don't want. And also if they want, they can integrate the api into their own apps to enhance their bank app's accessibilty. 

Fusionfabric.cloud will encapsuaute the sdk and api from [Eye tracking solution](https://eyeware.tech/), [Voice recognition solution](https://www.ispeech.org/), [SLAIT](https://slait.ai/) for operation recognization and possible communication.. Fusionfabric.cloud will provide the api for applications to use. 