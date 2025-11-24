# Hueristi.ca: Visual Learning and Research Using Concept Maps & Mind Maps
*Analysis by Emily Ashikari | Aspiring Semiconductor Engineering Manager | Fall 2025*
## Tool Overview
- **Provider**: Self-Owned by Engin Arslan
- **Pricing**: Basic: Free Professional: $7.99/month or $79.99/year
- **Core Functionality**: AI-powered concept maps for learning
- **Link**: https://www.heuristi.ca/features/ai-concept-map-maker
## My Testing Methodology
1. Start with Concept Maps using 2 areas where I can verify the answers: MEMS Manufacturing, Newton's Laws of Physics and one area where I want to learn more: Quantum Computing
2. Continue to expand the concept maps for 1 hour each
3. Create Quiz about the concepts (~30 mins each)
4. Create Lesson Plans about the concepts (~30 mins each)
5. Test all other features until I hit the limit for the free version(~20 mins each)
## Career-Relevant Use Cases
### Use Case 1: Training for MEMS Manufacturing Context
- **Context**: Teach a group of new engineers what the basic understanding of MEMS manufacturing is required
- **Process**: Created a concept map starting with MEMS manufacturing and expanded using the built-in buttons. I attempted to find the basic processes within manufacturing and build upon those. Then, I created a quiz about the concepts as well as a lesson plan from the map. When trying to find certain topics, I prompted the chat to encourage the specific answers I was aiming towards.
- **Output**: <img width="2124" height="1354" alt="image" src="https://github.com/user-attachments/assets/0ee565b7-315c-442e-a628-785ec368ea92" /> A concept map with different branches containing different information, <img width="2728" height="1272" alt="image" src="https://github.com/user-attachments/assets/b5b54df7-9624-4833-a162-5b6c1a1fbc57" /> A multiple choice quiz
- **Time Saved**: 1 hour
- **Quality Assessment**: The content was accurate but extremely repetitive. Different buttons created the same concepts and it was hard to get the AI to generate the core concepts that a new engineer would need to know. None of the button options were very clear either, I had difficulty understanding what was different between "HOW" and "CONCEPTS" they all seemed to produce similar things. The quiz was fully based off of the concept map so seemed very high level and didn't get to the core of each topic.
### Use Case 2: Create a lesson plan for high school students based on a concept map on Newtonian Physics
- **Context**: Create a lesson plan that a high school teacher could use about Newtonian Physics. Give the limitations of the classroom and any context needed.
- **Process**: Created a concept map of newton's three laws of physics and then created a lesson plan off of that. Included the below context. I played around with the "physics" buttons on the concept-map generation and it provided me with some experiments related to Newton's three laws.
- **Output**: <img width="1786" height="930" alt="Screenshot 2025-11-16 195117" src="https://github.com/user-attachments/assets/bb9d00a0-0357-4d04-a0e1-876961eb6c84" /> 
https://docs.google.com/document/d/1rPPa8tC-QdrsYjPnzPWAQRc-AMlaPlqNaJUFD9PL0OM/edit?usp=sharing
- **Time Saved**: 3 hours
- **Quality Assessment**: I think the lesson plan itself was pretty good. I think it should provide the content needed to teach however, rather than just providing the overview of what the teacher should prepare. It also created a large failure here that I will get to in the failure section. 
### Use Case 3: Learn about Quantum Computing
- **Context**: As someone with a background in Electrical Engineering, I want to learn more about quantum computing to understand it in case of an interview. I am also interested in working in quantum computing so I need to buff up my understanding of it.
- **Process**: Created a mind map from Quantum computing and continually clicked the provided buttons to understand the content better.
- **Output**: <img width="2198" height="1384" alt="image" src="https://github.com/user-attachments/assets/6700f606-0484-456a-ac86-cbfb72af928f" />
- **Time Saved**: 30 minutes
- **Quality Assessment**: This seemed very high level and did not expand my understanding by that much. As an engineer, I need proper equations and mathematical reasoning to understand these concepts. It is very hard for me to just read text and know what is going on. Visual diagrams would help too.
## Failures & Limitations
### Failure 1: When Making a Lesson Plan, rather than using content for High Schoolers, it switched to middle school
- **What I Tried**: Hit "Make a Lesson Plan" and create a Newtonian Physics lesson for high schoolers
- **Why It Failed**: Created a lesson plan for middle schoolers, not taking my prompting into consideration
- **Screenshots**:  <img width="1786" height="930" alt="Screenshot 2025-11-16 195117" src="https://github.com/user-attachments/assets/bb9d00a0-0357-4d04-a0e1-876961eb6c84" /> 
https://docs.google.com/document/d/1rPPa8tC-QdrsYjPnzPWAQRc-AMlaPlqNaJUFD9PL0OM/edit?usp=sharing
- **Lesson Learned**: I don't think it is actually looking at my inputs for who I am making the lesson for. I could improve this by increasing the concepts on the map so that they reach more of a high school level but I struggled to do so without the ability to get it to produce formulas or calculus related content.
### Failure 2: "Split" A topic that was numbered and everything ended up jumbled
- **What I Tried**: I tried to split a numbered list into different topics using the "split" functionality. I did this so that I could further expand on these concepts
- **Why It Failed**: Extracted the text by line rather than concept. It really struggled with the numbers and figuring out which box everything belonged to
- **Screenshots**: <img width="2233" height="1474" alt="image" src="https://github.com/user-attachments/assets/37444e2f-0e48-4640-b0ad-a3ab37bf3d5c" />
- **Lesson Learned**: Formatting and parsing through text for AIs can be difficult to pull out certain information. In order to extract meaning from the text, there needs to be a human there to guide AI into what belongs in certain categories
### Failure 3: Loss of context
- **What I Tried**: I tried to expand my mind-map and continue down a branch
- **Why It Failed**: Lost the context of the mapping and answered the "what" with a differnt type of "etching"
- **Screenshots**: <img width="1134" height="1366" alt="Screenshot 2025-11-24 143929" src="https://github.com/user-attachments/assets/8c8b75bb-fe92-4f16-8be3-d331986889b0" />
- **Lesson Learned**: Even though AI "looks" like it takes in context, it doesn't always get the context correct so prompting is extremely important
## Skill Code Analysis
### Challenge
I think this tool could remove a lot of challenge in learning. Rather than having to research different journals and papers and websites to understand a concept, it would all be located here. I also feel like part of learning is creating the flashcards and learning material yourself, rather than getting an AI to do it for you.
### Complexity
This completely removed complexity from the topics that I fed it. It seemed to only give surface level understanding and if a student or teacher doesn't know the concept and accepts this, they could run into trouble of missing the complex lessons behind these topics.
### Connection
Private tutors or mentors or teachers are lost in this tool. This CANNOT replace a teacher or private tutor when it comes to learning a concept. Nor can it replace a thought-out lesson plan. Humans are needed to build that mentor-mentee bond and this completely eliminates it.
## Bottom Line
**Who Should Use This**: Teachers who need conceptual lesson plans or companies who want to put SOPs or Safety training into easy quizzes and conceptual training content
**Who Should Avoid This**: Anybody trying learn or teach anything involving formulas. It can only do concepts
**Hidden Costs**: Learning curve, time, ethics (really encourages uploading PDFs and other peoples content
**My Verdict**: I would not use this professionally because it seems more catered to younger people trying to learn concepts. It also can only give the surface level understanding of things, rather than drilling into the math and physics behind what it's talking about. It seems to encourage pretty science-ortiented content but lacks the ability to produce formulas and quizzes or study material with practice problems. It doesn't seem to be good for what it intends to be good at but I could see this logic excelling for a quality department trying to train new employees on documentation like SOPs and safety. It could be a good way of generating content and lesson plans to ensure that your employees are up-to-date on training.
## Evidence Gallery
<img width="486" height="750" alt="image" src="https://github.com/user-attachments/assets/b61debbb-186a-4393-b104-17ff58b3d7c7" />
<img width="486" height="750" alt="image" src="https://github.com/user-attachments/assets/977cde5f-5d07-43b8-9cce-9ddcc167a595" />
<img width="652" height="1255" alt="image" src="https://github.com/user-attachments/assets/3773a2a7-8faa-4be3-8318-28e949fd9f81" />
<img width="608" height="855" alt="image" src="https://github.com/user-attachments/assets/052fc25d-553c-4961-b731-69ff44afafc9" />
<img width="1987" height="888" alt="image" src="https://github.com/user-attachments/assets/63d0fade-c112-4327-9c70-395b25094203" />

## References
- https://www.heuristi.ca/posts/how-to-use-mind-maps-for-studying
- https://skywork.ai/skypage/en/Heuristica%20AI%3A%20A%20Guide%20to%20the%20Future%20of%20Visual%20Learning/1976174108923195392
- (https://youtu.be/a5VDklCa7lU?si=EAEH4eVWfm8zF7yP)
- MindMeister (https://www.mindmeister.com/?utm_source=Google_Ads&utm_medium=Paid_Search&utm_campaign=US_en_PBPQ_GA_SS_MM&utm_term=mindmeister&utm_campaign=US_en_PBPQ_GA_SS_MM&utm_source=adwords&utm_medium=ppc&hsa_acc=1500715290&hsa_cam=1566647495&hsa_grp=64812290772&hsa_ad=580495471095&hsa_src=g&hsa_tgt=kwd-3659949928&hsa_kw=mindmeister&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=1566647495&gbraid=0AAAAAD7Bz2PgYMy4WvWLvsdNbsDcjq_WO&gclid=Cj0KCQiAiebIBhDmARIsAE8PGNIoCEB9lP3WxlowDifhdYDcYGkPhOj9NYK6gNT4GxKnAiXdImfIKq0aAufDEALw_wcB)
- Coggle (https://coggle.it/)
- Notion.ai (https://www.notion.com/product/ai)
