## 💡Inspiration 
Life can get hard sometimes. Whether in school, work, relationships, or physical health, we all face challenges that make us angry and disappointed. People often remove this frustration by cursing out loud and in the process hurt somebody else or by punching a wall, hurting themselves. Studies show that such actions, known as venting out, positively impact your mental health but negatively impact those around you. Venting out is good for you but venting out in the correct manner is even more important.

We are inspired by President Abraham Lincoln’s “hot letters” written during the civil war, ones that he wrote to vent out his frustration with his colleagues and enemies but never posted. Today we have many more sophisticated tools to vent out all our anger and we made a platform to do so in an effective manner. We call this platform VentOut

![3](https://user-images.githubusercontent.com/85804252/158043719-2a287e41-7f87-4110-8868-cfd9866d9f91.png)

---

## 🤔What it does 
When an individual is stressed, they often look for an outlet to release their tension, whether it be through friends, family or even just yelling out into the street. **VentOUT** takes this simple idea and creates a space where anyone can anonymously vocalize their feelings and see that they are not alone in their struggles.

**VentOUT** is a chat application created to make it easier for individuals to vent and vocalize their inner thoughts. We take in a user's audio message, transcribe it to text and post it in an anonymous space.  At the same time, we provide these individuals with positive resources to understand what is making them upset and encourage them to take appropriate action. We have identified 4 main categories where people face challenges with mental health: work, school, relationship, and health. For each of these categories, we provide users with a chat room to anonymously express their frustrations and curse out loud. In order to ensure there is no toxic profanity on our application, we filter out curse words said by the user in their frustration.

![4](https://user-images.githubusercontent.com/85804252/158043718-bd8f02c3-7b80-4cd5-936b-a8b57ed07f66.png)

---

## 🦾 How to built it
* __Frontend:__ React.js, Tailwind
* __Backend:__ Node, Express, Circle CI, AssemblyAI, Firebase
* __Deployment:__ Github Pages
* __Tools:__ Git


![How we built (1)](https://user-images.githubusercontent.com/85804252/158071482-ffe89529-bae8-4bdc-9d95-dbee0d218b54.png)

---


## 👨🏻‍🤝‍👨🏽 Mental Health Track

We began this hackathon with a singular aim: make an interface that allows users to vocalize their inner struggles in order to improve their mental health.  We are a team of 4 driven to build technology to tackle mental health issues.

[![About.png](https://i.postimg.cc/G26Q43qr/About.png)](https://postimg.cc/njY75Jyw)

---


## 🎨Best UI/UX

heavily inspired by the revised version of **Iterative** design process, which not only includes visual design, but a full-fledged research cycle in which you must discover and define your problem before tackling your solution & then finally deploy it.

![Double-Diamond](https://i.postimg.cc/bvQV3jHt/doublediamonddesignprocess.png)

> 1. **Discover**: a deep dive into the problem we are trying to solve.
> 2. **Define**: synthesizing the information from the discovery phase into a problem definition.
> 3. **Develop**: think up solutions to the problem.
> 4. **Deliver**: pick the best solution and build that.

This time went for the minimalist **Tailwind UII** design. We utilized design tools like Figma,  Photoshop & Illustrator to prototype our designs before doing any coding. Through this, we are able to get iterative feedback so that we spend less time re-writing code.

![2](https://user-images.githubusercontent.com/85804252/158043682-f2b270de-4f97-414c-aeed-f75e99820bef.png)

---

## 📚Research 

Research is the key to empathizing with users: we found our specific user group early and that paves the way for our whole project. Here are a few of the resources that were helpful to us —

- https://www.mskcc.org/news/coping-grief-7-things-remember-when-dealing-loss
- https://www.suu.edu/blog/2018/08/ten-tips-for-healthy-relationships.html
- https://opportunity.org/learn/lists/10-habits-of-successful-students
- https://www.theatlantic.com/family/archive/2020/05/how-choose-fulfilling-career/611920/


## 🤖 Best Use of AssemblyAI

We are using AssemblyAI's APIs to convert the speech to text. The user can convert his speech to text in the chatroom. We use the /transcript endpoint to make a call to the API using the audio user generates and send the transcript back to the frontend of the application. We also use the profanity check API to remove curse words from being displayed on our application. Although we implemented the functionality to use AssemblyAI in the backend, we didn't use it in the frontend because we needed an immediate response which was not possible through the API.

---

## 🛠 Best Usage of CI/CD sponsored by CircleCI

We are using CircleCI for continuous integration and deployment. CircleCI is a free service that provides continuous integration and deployment for your applications. It’s a great way to test our code, run our tests, and deploy our code.

## 🚀 What's next for VentOUT

- Building a mobile app to let users vent out on the go!



