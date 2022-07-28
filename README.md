# Open+


<img src="./resource/opentofuture.png" alt="open+ log Image."/>

**A Breakthrough in Banking Services for Individuals with Disabilities.**

In a post-pandemic world, accessibility has emerged as a critical factor for all customers. 

According to the World Health Organization article published in 2021, over **1 billion** people live with some form of disability. For these people, carrying out various banking tasks becomes challenging.

**We, at Finastra, always strive to make world of finance OPEN.**

As a next step for fulfilling  this vision, we would like to take an opportunity to announce our new application with ready-to-integrate devkit, **OPEN+**, 

It is aimed to remove barriers and increase accessibilities of open banking for people with Visual & Hearing Impairment, Speech difficulties, physical impairment, and so on. 

**Thanks to this application, Financial institutions can now offer services to a new group of people who have any kind of impairments.**  

Open+ works on top of APIs on Finastra’s **FusionFabric.cloud platform** which can be easily integrated into the most common banking applications, the setup is fast and intuitive for any user.

## Key Features

<ul>
  <li><span style="font-weight:bold">Authentication:</span> Voice and Retina recognition </li>
  <li><span style="font-weight:bold">For users with arms disability:</span> Retina scan and movement tracking, voice inputs </li>
  <li><span style="font-weight:bold">For users with speech disability:</span> 3rd party AI sign language support </li>
  <li><span style="font-weight:bold">For users with visual impairment:</span> Voice inputs and audio output </li>
  <li><span style="font-weight:bold">Shortcuts for frequent tasks:</span>  Helps to eliminate repetitive actions for recurrent operations  </li>
    <li><span style="font-weight:bold">Request a near-by visit:</span> Enables customers to have assistance from bank staff in-person 
 </li>
</ul>



[Figma Design file](https://www.figma.com/file/CzHrvNVGyDUd7YdFxD5IwY/OPEN%2B?node-id=0%3A1 
)

[Demo Video]()

## High Level Architecture

### Architecture
<img src="./resource/architecture.png" alt="Architecture Image."/>

<ul>
    <li>The architecture leverages Finastra's Open Innovation platform FusionFabric.cloud.  
    </li>
    <li>The building blocks for Open+ will be deployed on FusionFabric.cloud Developer Portal and the application will be published on FusionStore so that it would be available for any financial institution to integrate. </li>
    <li>The Admin Portal provided by FusionFabric.cloud platform helps financial institutions to easily manage configurations, consents, users and also deploy new tenants and backend instances. </li>
    <li>Financial institution will subscribe to Open+ and proceed to make required configurations using admin portal. </li>
    <li>Post testing the application with test/UAT environment, financial institution can configure PROD tenant/backend instance and deploy the application live. 
    </li>
    <li>With successful configuration, a synchronous request-response architecture will be initiated and requests from customers will be routed through the secure architecture of the FusionFabric.cloud platform to the bank. </li>
    <li>Open+ also offers URLs to implement SSO provision through which financial institution will be able to integrate the Open+ toolkit into their existing application, which enables them to provide a wide range of services to their customers having any sort of disabilities. </li>
</ul>

 <img src="./resource/bank-service-portal.png">


 <em>**"Open+", enabling world of finance for specially abled users having accessibility challenges of any kind.**</em>