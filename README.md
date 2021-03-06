# World Bank Survey Revamp



## ABSTRACT

The World Bank Global Program for Safer Schools is an initiative to improve school infrastructure safety at risk from natural hazards and disasters for children. Currently, 1.6 billion students attend schools across the world with about 6.6 million schools operating worldwide. However, due to earthquakes, an average of 2500 fatalities occur annually due to insufficient infrastructure quality. The World Bank’s Global Program for Safer Schools plans investments and interventions for schools most impacted by natural disasters to improve safety for children. To accomplish this, the World Bank created a database, the Global Library for School Infrastructure, and uses data collection tools to develop plans for their Roadmap for Safer and Resilient Schools. Data collection is done by non-technical members of the community. It includes submitting photos of schools and answering questions about power supply, water access, environmental safeguards, and the learning environment. The current tool used for data collection is ArcGIS Survey123, a form and data collection tool. The World Bank has tasked us with simplifying and improving the questionnaire and designing an intuitive interface to guide users to input the desired information.


<img src="img/img1.png" width="200">     <img src="img/img2.png" width="200">   
<img src="img/img3.png" width="200">     <img src="img/img4.png" width="200">



### Problem Statment

Non-technical users need an easy way to collect surveying data on school buildings and submit this data to the World Bank Global Program. We have observed that the ArcGIS Survey123 survey tool is challenging to use, hard to read and understand, and discouraging to use, which is causing inaccurate data to be submitted, and fewer forms to be received.

## USER RESEARCH
### User Research Questions
1. Name, age, occupation
2. Describe your experience filling out forms/questionnaires. Is there any time you had a frustrating or confusing time completing a form?
3. If you have ever given up on filling out a form, why did you stop?
4. How would you prefer to navigate lengthy forms on a mobile device? (i.e step through multiple pages, scroll through one long page, etc.)
5. What motivates you to complete filling out a form?
6. What is something useful or something you have liked while filling out a form?


### Current Survey Questions
1.  What is your first impression of this survey?
2. Did you have any trouble understanding any of the questions on the form
3. Is there anything we can add to the question to make it more clear?
4. Was the interface easy to understand?
5. How easy or difficult did you find filling out this form?

### User Interview Results

**Andrew Saxon**

Andrew Saxon is a 20-year-old busboy and Math major at Cal Poly, SLO. Andrew is not a huge fan of filling out surveys but will do them when they are required or if a friend asks him to complete one. His biggest qualm with surveys is when they are too long or have a ton of pages to click through. He likes when forms have multiple choice questions and are all on one page.
Upon looking at the survey on the mobile app, Andrew was initially confused why it was in Spanish and could not figure out how to change the language. While completing the survey, he wanted some example photos to help him get good angles. He did really like the error feature that allowed him to click through the errors one by one.

**Emma Clarke**

Emma Clarke is a 20-year-old RPTA major at Cal Poly, SLO. Emma likes taking surveys and finds them satisfying to complete. Her biggest issue when completing surveys in the past is when they are too long or the questions are worded poorly. She likes when forms have multiple choice questions or give time estimates as to how long they will take to complete.
Upon looking at the survey on the mobile app, Emma did not like the font of the questions and found it confusing when a whole new question would pop up asking for a minimum of 3 photos. She also did not understand what the questions meant by “tier.” She also wanted to be able to review all of her answers before submitting without having to click back through each page. Overall, Emma thought the form was pretty good but would have liked a time estimate at the beginning to know how long the form would take. 

**Charles Huynh**

Charles Huynh is a 50-year-old Software QA. He does not like filling out physical forms because they take too much time and effort. He prefers a step-by-step format when filling out forms since one long page is tiring and hard to go back to where he leaves off. He thinks that dropdown menus and progress bars (like Google Forms) are useful for selecting items and being aware of the status.
Upon looking at the survey on the mobile app, Charles did not like how small the text was on the screen. Throughout the survey, he was frustrated with some terms. He was not sure what “Tier” levels or “Shifts” meant. He felt it was too difficult and inconvenient to obtain information from the principal/staff. Overall, he said the interface was easy to understand but hard to read. He felt that the form was pretty difficult to fill out because it was tiring and hard to read.

**Isabelle Huynh**

Isabelle Huynh is a 23-year-old Bioengineer. She does not like forms that require personal information or that take way too much time to complete (>10min). She prefers a step-by-step format (like Google Forms) when filling out forms. While filling out a form, she thinks that autofill and radio buttons are useful because they cut down on time.
Upon looking at the survey on the mobile app, Isabelle thought that it looked old-school and ugly. She explained that it looked hard to fill out because there were too many fill-in answers. Throughout the survey, she was frustrated with some terms. She was not sure what “Tier” levels or “Shifts” meant. She felt it was too difficult and inconvenient to obtain information from the principal/staff. Overall, he said the interface was easy to understand but hard to read. Since she thought that the form was not aesthetic, it was demotivating to fill out. Also, the next button on the bottom right of the page did not work and confused her.

**Cimran Virdi**

Cimran Virdi is a 26-year-old Engineering Lead. To begin the interview, the user was asked general questions about their experience with forms and surveys. From these questions, we learned that the user had a lot of complaints regarding previous form experience and made it clear that ill-prepared forms cost her time and patience. From there, we moved into a walk-through of the current version of the World Bank form. Throughout this experience, the user had difficulties understanding the stylistic components of the form, the questions that were being asked, and the form's structure. In particular, the user became frustrated with the design of dropdown and multi-select menus, finding them faulty and hard to understand and use. By the end of the walk-through, the user was left dismayed by the time spent filling out the form and the overall unpleasant experience.

**Mariclare Newsom**

Mariclare Newsom is a 21-year-old nursing student. The experience of the second user was not unlike the first. This user also expressed disinterest in filling out ill-designed and long forms. When walking through the current WB form, the user experienced many of the same confusions as the first with regards to the design and functionality of components on the form. Particularly, this user felt that it was unnecessary and unintuitive for sections of the form to be open and closed to reveal the questions. Additionally, they felt that many of the questions on the form would be easier to understand if diagrams, definitions, and links to more information were included. Overall, this user had a similarly unpleasant experience and was left feeling somewhat defeated.

**Adrian Kim**

Adrian Kim is 21 years old and a college student. He does not like forms that are overwhelmingly heavy in text. When Adrian was asked about other times he had given up filling out forms and why he stopped, he stated it was usually when the survey had an error but would not point him to where the error was.

Adrian was given the current form in-use by the World Bank and attempted to complete it, and was then asked follow-up questions. He was unsuccessful in completing the form and gave up while filling it out. Adrian stated that they were initially unphased by the form since it looked short despite being visually unappealing. He stated the questions were not difficult to understand, but that the questions were formatted poorly and the method of supplying an answer to some questions felt inconvenient and repetitive. For example, instead of having to select “yes” or “no” multiple times, a check box with questions lined up in a table would be easier to use. Also, the candidate had difficulty using the survey because the arrows at the bottom seemed to indicate the current page the user was on but did not function in any way. 

**Krishna Nathani**

Krishna Nathani is 18 years old and a senior in high school. She does not like long forms that require a lot of text input and prefers having pre-selected options. When asked if she has ever given up on filling out a form and why she gave up, she says if a form feels too long but does not have a progress bar, she will stop. 

Krishna was able to complete the survey but described it as unpleasant and challenging to use. She also felt negative about the interface and aesthetics of the survey. She disliked that font sizes did not differentiate questions and question descriptions. Krishna also disliked the background image and called it “distracting.” She also stated it would be easier if the surveys collapse feature was instead a “jump-to section” feature allowing for easier navigation.

### Persona
<img src="img/Persona.jpeg">

## DESIGN REQUIREMENTS

* Mobile-compatible survey
* Simplify questions
* Improve existing answer formats
* Language toggle
* Design that falls within accessibility guidelines (W3C)


## IDEATION PROCESS

### How Might We Questions

- How might we ensure correct answers to the survey?
- How might we ensure the survey is understandable across countries?
- How might we get information about school structures?
- How might we facilitate the collection of information from another country?
- How might we facilitate the collection of information across different languages?
- How might we make the survey consistent across platforms?
- How might we communicate the level of detail needed in a response?
- How might we ensure photo responses are completed in the correct way/angle?
- How might we account for things interrupting a surveyor mid-completion of the survey?
- How might we group questions together to ensure a more cohesive flow throughout the survey?
- How might we make the survey easy to navigate?
- How might we ensure users understand what the questions are asking?
- How might we make the form design more intuitive?
- How might we make the questions less subjective?

### Contextual Scenarios

Sara is an elementary school teacher in rural Guatemala whose goals are to teach her students English and keep them safe while at school. 

While on her way to school, Sara commutes on a busy dirt road for 30 minutes. Once at school she begins organizing her desk and lesson plan for the day. An hour later her students begin to arrive and take their seats in an overcrowded room. 

Sara teaches for 2 hours and then the class takes a 30-minute break for lunch. During lunch, the students are allowed to run around outside. Sarah watches them and makes sure no dangerous activity occurs. One of her students, Alex, scrapes his knee. Sarah cleans his knee and bandages it before returning to class for afternoon classes.

After lunch, it begins raining and water soon begins dripping from the ceiling. Sara rushes to put a bucket to collect it but notices that the water damage is quite excessive throughout the ceiling. She realizes this may be a hazard for her students. The school is in a high rainfall area so the problem will continue to worsen if it is not fixed.
Our new survey-tool app is intended for use on both mobile devices and desktop computers. It is not reliant on any other products.
To successfully fill out any of the surveys, users must provide answers to fields marked as “required,” which may ask for information an outside source can provide. For example, Sara may need to ask a school administrator or principal for specific information when filling out the school safety survey with our tool. She will need to fill out various fields and supply answers to questions in order to submit the survey. 

In order to successfully use our survey tool, Sara should be comfortable using a mobile phone and using mobile phone applications. The anticipated complexity of using our survey tool is low since users will directly respond with their answers to questions they see on the screen. 

Imagine you are asked to show the structure of a room in your building. How would you capture the different aspects of a building through a few photos?

### Wireframes and Sketches

Low-fidelity wireframe sketches and a mood board consisting of competitive analysis, fonts, and color palettes.

<img src="img/moodBoard.png" width="600">
<img src="img/Untitled_Artwork 31.png" width="600">


### The Prototype

[Link to Figma Here](https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FkSPZa9jUhjYr0hKn6XqKT1%2FSurvey-Mobile-Prototype%3Fnode-id%3D11%253A519)

### Rationale for Prototype

We are looking to learn about the different pain points that our users are struggling with in order to iterate back on the prototype based on the feedback we receive during testing.

## TESTING

### Explanation of Testing Method

For our user testing, we will be doing moderated, remote usability tests with five candidates in total. We have selected moderated usability tests because we want to see if users can successfully complete key tasks and navigate the interface we designed for our survey tool. Our goals with these moderated usability tests are: 

- Learn if users can understand the questions
- Identify missing features that would be convenient for users
- Eliminate cognitive workload and complexity with the tool
- Compare it to the effectiveness of the original tool (ArcGIS123) 

Ultimately, we ask ourselves if users find it easy to navigate our tool and submit a survey. For our usability tests, we have decided to use two scenarios for our users to follow:

- Imagine you are reporting building safety information to the world bank. Show me how you would report that information.
- Imagine you are attempting to fill out the survey but are interrupted. Show me how you would complete it.

After our users complete the usability tests, we will follow-up with these questions regarding using the tool:
- Were the questions easy to understand?
- If you were not sure how to answer a question, how would you go about answering it?
- Is there anything you think is missing from this survey tool?
- Were there any challenges with navigating the interface?
- How does this survey tool compare with others you may have used? 

### Summary of Testing Results

Through our five user tests, we found that the overall design of our survey tool was helpful to the users. We found that the main pain point for our users came from the ambiguous section overview page. Multiple users were unclear whether or not they needed to complete all sections and if there was a certain order they needed to be completed. Users also noted that questions requiring a photo upload were somewhat vague and requested follow-up information about how the photos should be taken. Users did state other than the photo upload that the questions were relatively easier to understand. Overall our users reported that completing this form was a lot less painful than most surveys sent to them. They liked the natural flow of the survey and the ability to navigate around the survey. Our users stated they preferred how our survey had sections separated rather than how ArcGis has collapsable sections and generally felt our tool was more manageable. 

### Detailed Findings

Our user interviews showed us both specific vulnerabilities and strengths with our survey tool prototype. When we asked our users to think aloud during our tests, some of the more positive comments were “I like the simplicity and aesthetic of the interface,” and, “I like how it feels easier to navigate and see the different sections, and that it tells me my progress.” Comments like these affirmed that our interface itself was satisfactory to users. We also received comments like “I wonder how long this survey is going to take?”, “Do I have to complete this in a specific order?”, and “I’m not sure how to answer this,” and these comments helped us identify what we needed to do next. From these comments, we realized our users needed more clarity when it came to the survey itself and desired more information for survey context as well. While doing our user tests, users spent significantly less time navigating the interface and reaching the surveys than they did on understanding and commenting on the surveys themselves. In addition, we also found our survey-tool is not as mistake-preventative as it should be because, during our user-tests, users would accidentally click the home-button and lose their progress while in the middle of the survey. Our users described this as potentially frustrating since surveys had the potential to be lengthy and a slip of their hand could cause them to lose their progress. We used an affinity diagram to categorize information we received from our user tests.

### Recommendations

Based on our feedback from user tests and analyzing our detailed findings, we were able to make five recommendations to our prototype to solve the problems our users ran into. Our first recommendation is to add clarifying instructions to the sections page within the survey to ensure users are not confused about the order in which questions must be answered and if all sections are required. Our second recommendation is to add example photos for questions that require a photo upload because users explained they lacked clarity on what the photos should look like.  Our third recommendation is to offer options to either advance directly to the next section and return all sections because our survey tool takes users back to the sections page whenever they complete a section instead of advancing directly to the next one; this would make the survey-taking portion smoother. Our fourth recommendation is to add a pop-up notification if the user decides to quit in the middle of a survey, asking if they would like to save their progress to avoid accidentally losing progress. Our fifth and final recommendation is to add a time estimate or additional progress bar to display how far the user is in the survey since each section can vary in the number of questions and may not give a more accurate estimate on the user’s progress. 

### Affinity Diagram

<img src="img/Affinity Diagram.png" width="600">

## FINAL PROTOTYPE

### Final Prototype Iteration

During user testing, we uncovered a few challenges our users faced while using our prototype including error prevention, a shortage of a clear path of instructions, and examples for specific questions. During our latest iteration, we added a few new features to our prototype to help our users overcome some of these challenges. Previously, in the School Safety Survey, we asked users to upload a photo of the school, but our page lacked clarity since it did not provide an example or specific instructions on how to take the photo. In our next iteration, we added a sample photo to guide users. Our users also mentioned they were unsure if survey sections needed to be filled out in a specific order. As a result, another feature we added for clarity was fading a section’s title color to show that it is “locked” until the previous section was completed to help the user understand the survey section order better. Our users also wanted us to improve error prevention to incase they automatically clicked the home button or back button on our survey by mistake, so we added an autosave notification to let them know their work was saved as a draft. A final change we made was adding in an estimated time to complete the survey for additional convenience to our users. The addition of the estimated time gives our users a sense of motivation if they know the survey’s approximate completion time. As a result, they are more likely to fill out the survey if they know how long it takes to complete the survey.


<img src="img/finalprototype7.png" width="200"> 	
Survey Sections (before user testing)                    

***
<img src="img/finalprototype6.png" width="200"> 
Survey Sections (after user testing)

***

<img src="img/finalprototype5.png" width="200">
Image upload (before user testing)

***

<img src="img/finalprototype4.png" width="200">
Image upload with example (and after user testing)

***

<img src="img/finalprototype3.png" width="200">
Survey Info page (before user testing)

***

<img src="img/finalprototype2.png" width="200">
Survey Info page (after user testing)

***

<img src="img/finalPrototype1.png" width="200">
New “saved as draft” screen (after user testing)

***

