# Designing UX for AI Applications

[![Designing UX for AI Applications](./images/12-lesson-banner.png)](https://youtu.be/bO7h2_hOhR0) 


> *(Click the image above to view video of this lesson)*

User experience is a very important aspect of building apps. Users need to be able to use your app in an efficient way to perform tasks. Being efficient is one thing but you also need to design apps so that it an be used by everyone, to make it *accessible*. This chapter will focus on these area so you hopefully end up designing an app that people can and want to use.

## Introduction

User experience is how a user interacts with and uses a specific product or service be it a system, tool, or design. When developing AI applications, developers not only focus on ensuring the user experience is effective but also ethical. In this lesson, we cover how to build Artificial Intelligence (AI) applications that adresses user needs.

The lesson will cover the following areas:

* Introduction to User Experience and Undestanding User Needs
* Designing AI Applications for Trust and Transparency
* Designing AI Applications for Collaboration and Feedback

## Learning goals

After taking this lesson, you'll be able to:

* Understand how to build AI applications that meet the user needs.
* Design AI applications that promote trust and collaboration.

### Prerequisite

Take some time and read more about [user experience and design thinking.](https://learn.microsoft.com/en-us/training/modules/ux-design/)

## Introduction to User Experience and Understanding User Needs

In our fictitious education startup, we have two primary users, teachers and students. Each of the two users has unique needs. A user-centered design prioritizes the user ensuring the products are relevant and beneficial for those it is intended for.

The application should be **useful, reliable, accessible and pleasant** to provide a good user experience.

### Usability

Being useful means that the application has functionality that matches its intended purpose, such as automating the grading process or generating flash cards for revision. An application that automates the grading process should be able to accurately and efficiently assign scores to students' work based on a predefined criteria. Similarly, an application that generates revision flash cards should be able to create relevant and diverse questions based on its data.

### Reliability

Being reliable means that the application can perform its task consistently and without errors. However, AI just like humans is not perfect and may be prone to errors. The applications may encounter errors or unexpected situations that require human intervention or correction. How do you handle errors? In the last section of this lesson, we will cover how AI systems and applications are designed for collaboration and feedback.

### Accessibility

Being accessible means extending the user experience to users with various abilities, including those with disabilities, ensuring no one is left out. By following accessibility guidelines and principles, AI solutions become more inclusive, usable, and beneficial for all users.

### Pleasant

Being pleasant means that the application is enjoyable to use. An appealing user experience can have positive impact on the user encouraging them to return to the application and increasing business revenue.

![image illustrating UX considerations in AI](images/uxinai.png)

Not every challenge can be solved with AI. AI comes in to augment your user experience, be it automating manual tasks, or personalizing user experiences.

## Designing AI Applications for Trust and Transparency

Building trust is crtitical when designing AI applications. Trust ensures a user is confident that the application will get the work done, deliver results consistently and the results are what the user needs. A risk in this area is mistrust and overtrust. Mistrust occures when a user has little or no trust in an AI system, this leads to the user rejecting your application. Overtrust occurs when a user overestimates the capability of an AI system, leading to users trusting the AI system too much. For example, an automated grading system in the case of overtrust might lead the teacher not to proof through some of the papers to ensure the grading system works well. This could result in unfair or inaccurate grades for the students, or missed opportunities for feedback and improvement.

Two ways to ensure trust is put right at the centre of design is explainability and control.

### Explainability

When AI helps inform decisions such as imparting knowledge to the future generations, it is critical for teachers and parents to understand how AI decisions are made. This is explainability - understanding how AI applications make decisions. Designing for explainability includes adding details of examples of what an AI application can do. For example, instead of "Get started with AI teacher", the system can use: "Summarize your notes for easier revision using AI."

![an app landing page with clear illustration of explainability in AI applications](images/explanability-in-ai.png)

Another example is how AI uses user and personal data. For example, for a user with the persona student, they may have limitations based on their persona. The AI may not be able to reveal answers to questions but may help guide the user to think through how they can solve a problem.

![AI replying to questions based on persona](images/solving-questions.png)

One last key part in explainability is simplification of explanations. Students and teachers may not be AI experts, therefore explanations on what the application can or cannot do should be simplified and easy to understand.

![simplified explanations on AI capabilities](images/simplified-explanations.png)

### Control

Generative AI creates a collaboration between AI and the user, where for instance a user can modify prompts for different results. Additionally, once an output is generated, users should be able to modify the results making them have a sense of control. For example, when using Bing, you can tailor your prompt based on format, tone and length. Additionally, you can add changes to your output and modify the output as shown below:

![Bing search results with options to modify the prompt and output](images/bing1.png "Bing search results with options to modify the prompt and output")

Another feature in Bing that allows a user to have control over the application is the ability to opt in and opt out on the data AI uses. For a school application, a student might want to use their notes as well as the teachers' resources as revision material.

![Bing search results with options to modify the prompt and output](images/bing2.png "Bing search results with options to modify the prompt and output")

> When designing AI applications, intentionality is key in ensuring users do not overtrust setting unrealistic expectations of its capabilities. One way to do this is by creating friction between the prompts and the results. Reminding the user, that this is AI and not a fellow human being

## Designing AI Applications for Collaboration and Feedback

As earlier mentioned generative AI creates a collaboration between the user and AI. Most engagements are with a user inputing a prompt and the AI generating an output. What if the output is incorrect? How does the application handle errors if they occur? Does the AI blame the user or takes time to explain the error?

AI applications should be built in to receive and give feedback. This not only helps the AI system improve, but it also builds trust with the users. A feedback loop should be included in the design, an example can be a simple thumbs up or down on the output.

Another way to handle this is to clearly communicate the capabilities and limitations of the system. When a user makes an error requesting something beyond the AI capabilities, there should also be a way to handle this, as shown below.

![Giving feedback and handling errors](images/feedback-loops.png)

System errors are common with applications where the user might need assistance with information outside the scope of the AI or the application may have a limit of how many questions/subjects a user can generate summaries. For example a AI application trained with data on limited subjects for example, History and Math may not be able to handle questions around Geography. To mitigate this, the AI system can give a response like: "Sorry, our product has been trained with data in the following subjects....., I cannot be able to respond to the question you asked."

AI applications are not perfect, therefore, they are bound to make mistakes. When designing your applications, you should ensure you create room for feedback from users and error handling in a way that is simple and easily explainable.

## Assignment

Take any AI apps you've built so far, consider implementing the below steps in your app:

* **Pleasant:** Consider how you can make your app more pleasant. Are you adding explanations everywhere, are you encouraging the user to explore? How are you wording your error messages?

* **Usability:** Building a web app. Make sure your app is navigable by both mouse and keyboard.

* **Trust and transparency:** Don't trust the AI completely and it's output, consider how you would add a human to the process ot verify the output. Also consider and implement other ways to achieve trust and transparency.

* **Control:** Give the user control of the data they provide to the application. Implement a way a user can opt-in and opt-out data collection in the AI application.

<!-- ## [Post-lecture quiz](quiz-url) -->

## Congratulations, you have finished this course

Want to learn more about designing UX for AI Applications? Go to the [contiuned learning page](../13-continued-learning/README.md) to find other great resources on this topic.

Congratulations, you have completed this course! The building should not stop here. Hopefully you have been inspired to start building your own Generative AI startup. Head over to the [Microsoft Founders Hub](https://aka.ms/genai-foundershub) and apply for the program to recieve support on your journey. 
