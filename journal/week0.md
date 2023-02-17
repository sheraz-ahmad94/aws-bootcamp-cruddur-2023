# Week 0 — Billing and Architecture

## Challenges

Here is my journal for the week 0 challenges and what I did about them.

## Watched Week 0 - Live Streamed Video
Yes. I watched the live stream, twice. Once live, and the other time when I was doing the challenges.

## Watched Chirag's Week 0 - Spend Considerations
I did.

## Watched Ashish's Week 0 - Security Considerations
Done

## Recreate Conceptual Diagram in Lucid Charts or on a Napkin
Done. Following along the live stream I made **[THIS](https://lucid.app/lucidchart/604affa5-4b62-4366-b59a-70fb08449474/edit?viewport_loc=-59%2C-174%2C2389%2C1148%2C0_0&invitationId=inv_96baacf3-54d8-4d87-b679-a7d7d3925705)** in the Lucid Chart.

## Destroy your root account credentials, Set MFA, IAM role
> Setting Up MFA
- Logged in using the Amazon AWS login page and went to Security Credentials in the top right corner.
- Next, Clicked on Assign MFA Device and added MFA to my root account using the Google Authenticator App on my Phone
- Now, every time I try to login to my account, it asks for the code from my Auth App 

![1](https://user-images.githubusercontent.com/57315716/219812817-38640c36-51b5-4157-b8d5-932bbcf19121.png)

> Setting Up IAM User
- Clicked the Search Bar and entered IAM for Identity and Access Management and opened it.
- Clicked on Add Users and filled in the relevant user details to make add a new user with certain permissions.
- The IAM User account has almost the same permissions as the Root account except few.

![2](https://user-images.githubusercontent.com/57315716/219814371-8c2556bd-a02f-4860-8c12-6c101de03da5.png)

## Use EventBridge to hookup Health Dashboard to SNS and send notification
> Setting Up MFA
- Type EventBridge in Search Bar and Open it - Amazon EventBridge
- Next, Click on CreateRule. Fill in the basic information. And select Health Change as an Event Alert
- Add a new SNS Topic, health-change and subscribe it using your email.

![3](https://user-images.githubusercontent.com/57315716/219816116-04ee996f-d139-432d-a72b-c1971980e7ea.png)


- Add this SNS Topic as a target in your EventBridge Rule
 
![4](https://user-images.githubusercontent.com/57315716/219816142-37c47d94-116b-4b0b-896c-f58754f509bc.png)

## Review all the questions of each pillars in the Well Architected Tool
> DONE

## 
