# Open+

An innovation bank application especially for **handicap people**.

<img src="./resource/opentofuture.png" alt="open+ log Image."/>

In a post-pandemic world, accessibility has emerged as a critical factor for all customers.  

According to the World health organization article published in 2021, over **1 billion** people live with some form of disability. For these people, carrying out various banking tasks becomes challenging. 

**We, at Finastra, always strive to make world of finance OPEN, would like to help them with more smoothy bank experience.**

As a next step for fulfilling this vision, we would like to take an opportunity to announce our new application with ready-to-integrate toolkit, **OPEN+**, 

It is aimed to remove barriers and increase accessibilities of open banking for people with Visual & Hearing Impairment, Speech difficulties, physical impairment, and so on. Thanks to this application, Financial institutions can now offer services to a new group of people who have any kind of impairments.  

Open+ works on top of APIs on Finastra’s **FusionFabric.cloud platform** which can be easily integrated into the most common banking applications, the setup is fast and intuitive for any user.


## More info
[Figma Design file](https://www.figma.com/file/CzHrvNVGyDUd7YdFxD5IwY/OPEN%2B?node-id=0%3A1 
)

[Demo Video]()

## Tech View

### Architecture
<img src="./resource/architecture.png" alt="Architecture Image."/>

The whole architecture is based on the fuionfabric.cloud. As our ambition of finance is to open. We will deploy all api services on fusionfabric.cloud so that every bank vendor can consume it. 

Apart from the api on fusionfabric.cloud, we have our **Open+ Mobile Devkit**, which enable the mobile app with more eye tracking/voice recgonization/sign language translate etc.

If bank vendor want to enhance their own app, they can integrate our devkit to enable huge of interactions in their bank app. 

If bank vendor don't want to spend much time on integrate devkit to their own app or they don't have enough time for it. We provide an app template just like what you can see from the design file. They can use our app template directly with some configurations.

What bank service vendor need to do is :
**Just subscribe open+ and make some configurations on our bank service portal then. You can extend their services to handicap users!**

### Bank Service Portal

<img src="./resource/bank-service-portal.png">

We provide a [Bank Service portal](https://org-admin.fusionfabric.cloud/) for bank to onboard their applications. Bank admin can manage the users, configration the client secret to secure their api call from fusionfabric.cloud etc. 

Fusionfabric.cloud already have a product called org admin portal, this can be reusable for open+ project. 

The bank can also map the user from bank to fusionfabric.cloud so that the clinet can login directly with face or voice without any account number to reduce the complexity for disabled people.  
### Fusionfabric.cloud API & open+ devkit
All the request to bank should come from [fusionfabric Cloud Servcies](./ffdc-services/README.MD) so the only things the bank need to do is to config and handle the requests properly. Everything behind the sceen for example the voice recognition and eye tracking etc, fusionfabric api and devkit will fully handle it. We also have a strict authentication check to secure all the operations. It will be very safe for bank to work with us. And fusionfabric.cloud will handle operations for banks, they don't need to work on the complex frontend if they don't want. And also if they want, they can integrate the api and devkit into their own apps to enhance their bank app's accessibilty. 

### Libaray 
<img src="https://static.tildacdn.com/tild3538-3236-4265-b137-373464343536/Logo_Full_Vice_Versa.svg" style="height: 40px;width: 100px; margin-right:10px" alt="slait">
<img src="https://eyeware.tech/wp-content/uploads/2017/04/eyeware-logo-white.svg" alt="eyeware" style="height: 40px; width: 100px; margin-right: 10px"> <img src="./resource/ispeech.png" alt="ispeech" style="height: 40px;  margin-right: 10px ">


Fusionfabric.cloud will encapsuaute the sdk and api from [Eye tracking solution](https://eyeware.tech/), [Voice recognition solution](https://www.ispeech.org/), [SLAIT](https://slait.ai/) for operation recognization and possible communication.. Fusionfabric.cloud will provide the api for applications to use. 