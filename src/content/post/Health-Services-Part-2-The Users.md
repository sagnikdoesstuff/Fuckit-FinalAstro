---
publishDate: 2023-01-09T00:00:00Z
title: Health Services - Part 2 - The Users
excerpt: Built a Health Services platform from a ground-up. The patients/users can choose between the different packages, set appointment time & go for checkups. 
image: https://images.unsplash.com/photo-1584515933487-779824d29309?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80
category: Market research - User Interviews - Wireframes
tags:
  - Market research
  - User Interviews
  - Wireframes
---

> Market research, User Interviews, User Personas, Wireframes & Hi-Fidelity mocks
> 

> **Team size :** 3 (1 Business, Junior Designer, Me)
> 

## The Scope

Built a Health Services platform from a ground-up. The patients/users can choose between the different packages, set appointment time & go for checkups. 

The aim is to create a seamless experience for the providers & patients equally. Essentially go through the existing legacy system & redesign the system to address user pain points.

## My role

As a sole designer responsible for this project, I spearheaded the Services users module. While my other teammates are simultaneously building the Products section of the e-commerce platform, I also have to keep equal attention to how that’ll impact the Services module. 

I conducted user research for providers & patients. I produced wireframes, user flows & mockups. I created a design system for the wireframes & hi-fidelity mockups, that’ll be instrumental in developing the final design. I supervised the development of both front & back end.

## Legacy system analysis

Since DOC already has a system, I collected data points from a quantitative analysis tool (Hotjar) of the user behavior, when interacting with this system. The pain points involve mostly on the limited range of services provided as well as user interface.

Methods uses were existing user surveys & post purchase feedbacks.

## Step 1 : Market Research

****1MG - One of the most comprehensive website in Healthcare/Lab tests**
![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F7d5b5229-2617-4179-9101-d6ebc42cfbac%2FScreenshot_2023-03-20_at_6.50.23_AM.png?table=block&id=ebd39ccb-6635-4f63-8b2b-00e618049580&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)

**Pros :** Comprehensive selection of packages based on organs/body parts/conditions, Flexibility to add tests, Free Doctor Consultation, Online reports, Compare packages, Book test from prescription…etc.

**Cons:** No questionnaire based on users symptoms, Recommended tests, Live chat

****Healtopedia** 
![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F6712fc83-bfad-4d03-b00b-5c3a7d4df447%2FScreenshot_2023-03-20_at_6.52.52_AM.png?table=block&id=f2c71ff4-540c-4d7f-9818-a72a23de7e70&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)

**Pros:** Good categorization of packages based on organs (but returns no results eg. Breast, lungs) and conditions/states (eg. mental health, physiotherapy) , Online Chat

****Other Providers :** BP Healthcare, Sehatq (Indonesia), Gleneagles Hospital Malaysia, Lifecare

## Step 2: User Research

I went through the current user data, heatmaps on the legacy website. The quantitative data was through Hotjar & Google Tag Manager. 

Based on quantitative data, our user base ranges from 30-50 year old. 60% of female & 40% male. 

I interviewed around 10 users around that age group, to study what they look for, when they think about their healthcare needs. I discarded the severely niche concerns. I created 3 different user personas, based on the research.

## Step 3 : User Personas

#### Persona 1: Joya Singh

- 52 years old, Arts teacher, married, 55 year old husband
- Art teacher

###### Goals:
Wants to keep herself and her husband healthy

###### Challenges
Little experience navigating the healthcare system, bad experience with doctors, easily overwhelmed by number of tests, on a tight budget

###### Technology habits
Spends lot of time on FB, looks for recommended doctors & clinics on FB, enjoys YouTube videos, prefers email and text messaging over phone calls

---

#### Persona 2: Walter

- 43 years old, married, 5 year old kid

- Self employed

###### Goals: 
Tries to be one step ahead especially in matters of health

###### Challenges:
Lot of online experience in symptoms/tests, consults his doctor friend, separate budget for healthcare needs, maintain a list of specialist close-by,  not much free time

###### Technology habits:
Uses Google a lot for research, reads a lot online (blogs), makes decisions based on online reviews & suggestions

---

#### Persona 3: Erica

- 30 years old, married, no kids

- Manager

###### Goals: 
Get professional medical help easily, get diagnosed early

###### Challenges:
Hypertension, can’t loose weight, getting pregnant, turned off by rude doctors, taking care of her old parents, mildly tight budget, very busy

###### Technology habits:
Shops online, avid webmd browser, reads health blogs

--- 

## Step 4 : Improvements to do based on personas

- Personalized content
- Reasoning of “Why user should choose DOC for their healthcare services”
- Flexibility to choose packages (adding/removing additional tests)
- Recommendations based on their current & past conditions/symptoms
- Better segregation/definition of categories
- Better chat options
- Reviews of various packages, providers & doctors
- Quality blog content
- Online reports

## Step 5 : Wireframes

#### Category Structure & Sort feature

###### Browse by category feature

This will be intrumental in users who has little knowledge in browsing through the  health-care galaxy. It narrows down the choices & focuses on the exact type of packages the users are looking for. 

The back-end is done by creating the category structure for health services. Every packages created by the seller should fall under one of the pre-defined categories. We went through a rigorous excercise, where we built an extensive selection of categories, that any package can fall under. For the packages that falls under two different categories, we built a **product tag** feature, where the provider can tag the package under two or more different categories.

![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F31bef6cb-228d-4d7d-bb93-cf2e6143e816%2FScreen_Shot_2022-09-25_at_10.28.23_AM.png?id=83ce2543-214e-4050-8513-470615cd1cd7&table=block&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)


### **Home / Search / List & Map view**

Map view is a unique feature we found out that the users wanted. Selecting the clinic close-by based on their location. So, we added Map view in conjunction with the List view.

![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F874bcf82-629d-4efe-8955-18a62acf728f%2FScreen_Shot_2022-09-25_at_10.31.01_AM.png?id=5a8c4529-9a05-4c83-99ae-775545195d26&table=block&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)


### **Product & Cart Page**

![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fce4f442d-205a-49a8-8221-189247f301a8%2FScreen_Shot_2022-09-25_at_11.38.25_AM.png?id=67b94c69-f8fb-4005-8048-9f6d5206a239&table=block&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)

## Step 6 : Getting user feedback

I showed the detailed wireframe back to the interviewees & asked them if the design & experience satisfies their goals. They suggested a couple of minor changes, some which were logical. I did those changes & went on to make the hi fidelity version of the wireframes.

## Step 7 : Hi-Fidelity prototypes

My wireframes resembles very close to the hi-fidelity version. In my design process, I put a deal of emphasis on building a good design system. The benefits of creating a robust design systems are multiple. That helps my junior designers as well as the developers.

These were created on Figma.

![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Ff6a50f20-ddb5-4486-8a41-4b9ccdb93176%2FScreen_Shot_2022-09-25_at_1.40.55_PM.png?id=9a48e41c-1883-4d86-958b-cfc9d4c920bb&table=block&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)

![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F08b7c9a7-c860-4f00-9c0f-83d198b258ab%2FScreen_Shot_2022-09-25_at_1.41.28_PM.png?id=28153cef-13ba-43c3-8d86-a87152ef012a&table=block&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)

![Super wide](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F15590ac1-b9cc-4083-8499-62a7c4a5ff14%2FScreen_Shot_2022-09-25_at_1.42.20_PM.png?id=50296ca4-dea2-40a7-9cd8-0e310565fffa&table=block&spaceId=68b90edf-4a11-4efa-b8c7-74466f3700b6&width=2000&userId=79fb7369-6524-4f63-a09f-770a1c45036e&cache=v2)


## Step 8 : The Wait?

While the developers are building the new app, I went ahead & suggested the stakeholders to implement the new experience on the legacy system. So that we can test out the changes & if users are liking the new environment.

The stakeholders obviously liked it, since the legacy system’s backend was severely constrained & implementing the new system will open the bottleneck.

Everybody agreed that it’ll be limited release & users will be access the links through various marketing campaigns. The design in itself wasn’t at par with what I envisioned, but it’ll be a guide to a completely new user experience.

So, after carefully evaluating all options, we launched the newish design.

[https://www.doctoroncall.com.my/marketplace/health-screening](https://www.doctoroncall.com.my/marketplace/health-screening)

## The Results

We implemented Hotjar analytics & started to collect the data. Based on the data, we observed that the bounce rate & drop-off rate went down significantly.