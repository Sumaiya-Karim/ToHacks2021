# ToHacks2021 - Community Cookbook
An app to connect you to community farms 

# ToHacks2021 - Community Cookbook
## Inspiration
In the midst of Downtown Toronto, subway delays, assignments and projects deadlines, midterms and finals, we often find ourselves running behind schedules and away from our families, friends and our communities. As warmer weather comes, it reminds us of the local business and farmers with vendors setting up in  Gould Street offering a range of products from honey, coffee, breakfast, Salmon burgers, baked goods etc. As we walk through Gould Street in May, this brings local communities together, supporting each other and creating a positive environment as they spend their time in the Market. And Now, we believe it's our time to give back to our community, by supporting small businesses and Farmers’ Market in unprecedented times. 

Inspired by the Alberta Approved Farmer Market and existing recipes apps, we were motivated to design the **Community Cookbook** app that allows local business and farmers to notify their subscribers about their opening and closing times, location and updates of their market effectively. It also features exclusive sections for home cooks, food lovers and new bakers/cooks to share their favorite recipes/lockdown recipes much more with their family, friends and their local community. 

## What it does
The Community Cookbook, utilizes a phases development approach before launching to our users across Ontario. 

Our application, it's in the early stages of development, we are currently focusing on the Farmers’ Market as they are opening up soon. We used **Courier** to deliver our notifications to subscribers based on their preferences via email or SMS using two providers: **SendGrid** and **Twilio**. This notification feature allows the subscribers to remind the hours of openings for their local Farmers’ Market, Public Health and COVID-19 Updates and additional measures taken for precautions to maintain health and well-being. 
![CommunityCookbook_App_2](https://user-images.githubusercontent.com/64792891/118210163-10536080-b438-11eb-8ffb-b011f94be755.png)


## How we built it
As a first step, we designed our prototype of Community Cookbook using the existing templates in proto.io to add functionality that best fits our theme coherently. 

Next, we identified the best way to use  **Courier**, to build notifications to stay connected with our subscribers based on their preferences for their latest updates from their local farmers’ market. By following the setup guidelines provided by the mentors, we were able to create our account with  **SendGrid** and  **Twilio SMS** and integrate with Courier. 

> * Setup Guide:  SendGrid and Courier Integration - Email notifications
> * Setup Guide: Twilio SMS and Courier Integration - SMS notifications
>> By following these guidelines, we were able to take advantage of a "no-code visual editor" to orchestrate SMS messages/email notifications to send notifications using **Courier’s REST API**. Before setting up email or phone notifications for our multiple subscribers, we tested with the workshop materials, to send email notifications, SMS notifications and the best of email and phone notifications.

Once we were able to send notifications successfully in all three scenarios, we began to build our templates for Community Cookbook. We obtained the data such as the location, contact info and links to websites and social media from the officially recognized organization, **Farmers’ Markets Ontario® (FMO)** that was required to **create design notifications templates**. We were able to send notifications to subscribers one at a time for all the stated scenarios from workshop materials. To simplify this design process, we **created automation templates** for batch users, which allows us to send the same message with many subscribers in a short period of time. 
> * How to build and trigger multi-step notification automations to users
>> By following these guidelines, we were able to automate and send one-time notifications with our subscribers based on their best of email or SMS notifications preferences with Courier. For demo purposes, Send notification to the best of email. 

![2](https://user-images.githubusercontent.com/64792891/118210211-29f4a800-b438-11eb-94e1-4a5c82ddb519.png)
![3](https://user-images.githubusercontent.com/64792891/118210228-30831f80-b438-11eb-954e-3f1e95cd6624.png)
![4](https://user-images.githubusercontent.com/64792891/118210242-37aa2d80-b438-11eb-8b51-9c4ec82542d5.png)
![image](https://user-images.githubusercontent.com/73046315/117564097-454a6680-b078-11eb-882c-9e95518e185a.png)

## Challenges we ran into
* Setting up accounts for Sendgrid and Twilio and Integrating with Courier. Every time, when we ran a test by running the workshop materials, we had an error message that said email/SMS that was undeliverable status.
* Unsure of how to create multiple recipients to receive the same notification for the scheduled time.
* Only templates with no data were shared with multiple users for both email/SMS notifications.

## What we learned
To identify and solve our technical issues following the guidelines of mentors,
* We were able to overcome this issue, by **creating a new sender** and **verifying email/phone number** with respective providers Sendgrid and Twilio and integrating with Courier. 
* We could **create an automated template in the designer section** of  **Courier** for **batch users**, automate and send one time or schedule notifications to subscribers.
* We needed to add **data information** in template details, and this could be found from templates that were created earlier in the designer section to create notifications based on their first choice or best of both email/SMS notifications. 

## Accomplishments that we're proud of
* Prototype that we created, which allowed us to be creative and explore many functionalities available.
* Able to send notifications to subscribers list that we created based on their first choice or best of email and SMS notifications preferences.
* Able to send automated notifications for all our subscribers for the desired template based on their best of email or SMS notification preferences with Courier.

## What's next for Community Cookbook
The NEXT BIG STEP for Community Cooking is to create a platform for home cooks/food lovers/ bakers to share their recipe and support local business and farmers markets from your neighbourhood with your family, friends and their neighbourhood in one touch. Some of the features we planned to incorporate include Some of the features we planned to incorporate include
* creating a coherent template for recipe that's easy to follow and accessible,
* notifying the followers when a home cooks share recipes using COURIER, and
* suggesting to check out local business and Farmers’ Market for the ingredients based on the location from Geotab data.

## References
https://www.ryerson.ca/ryerson-works/articles/workplace-culture/2017/why-visit-the-ryerson-market/
https://www.farmersmarketsontario.com/covid-19-updates/
https://www.farmersmarketsontario.com/view-market/?market_id=aberfoyle_farmers_market
https://apps.apple.com/ca/app/alberta-approved-farmer-market/id1091837660

## Devpost
https://devpost.com/software/community-cookbook#updates
