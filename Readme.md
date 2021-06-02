# Personas for AI


In user-centered design of software applications, the **_personas_ method** is used to keep design and development of the product focused on the users' needs, abilities and preferences in order to create useful products which are usable easily. 

When it comes to artificial intelligence (AI) applications, often _causability_ <sup name="a1">[[1]](#footnote1)</sup> is added to the users' needs: Specifically in high-stake domains, such as for example in medicine,  users need to understand the rationale and certainty underlying the results delivered by an AI application. Therefore, it is essential that AI applications are designed and developed with the users in mind, in order to achieve useful AI solutions with high usability and causability.

In principle there exist two fundamentally different approaches for creating personas: data-driven persona development and manual persona development. Data-driven persona development needs large amounts of user data (big data) to be useful, and thus for many use cases manual persona development using merely qualitative data is a better choice <sup name="a2">[[2]](#footnote2)</sup>. 
In this repository we describe our approach for manual persona development.


In order to support user-centered design of AI applications, we have developed a 5-steps approach for developing user personas for AI. Furthermore, based on our experience from practical implementation of the personas development process, we have created free material and tools to facilitate development of user personas for AI. This repository "Personas for AI" contains:
* a step-by-step guide for personas development
* illustrative examples from practical implementation in the field of Computational Pathology
* clear descriptions of the recommended methods
* useful tools for practical implementation

We have made available all these material under Creative [Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license. You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper** and **indicating any changes** that you have made.

---
---
# Developing Personas for AI: Step-by-Step
We have elaborated a 5-steps process for the development of user personas for AI:
1. Step 1: Identification of (Potential) User Groups
2. Step 2: Collection of Information about the Users
3. Step 3: Consolidation and Analysis of the Collected Information
4. Step 4: Creating the Foundation for Personas
5. Step 5: Visualising Personas

## Step 1: Identification of (Potential) User Groups
**Aim:** Create a comprehensive list of groups of users, who will (potentially) use the AI application. Each of these user groups is the seed for a distinct persona.

**Method:** We recommend to use the well-known method of _brainstorming_ for collecting ideas regarding potential user groups. After the brainstorming session discuss and evaluate the results, and agree on a list of user groups, to form the starting point for the creation of personas.

**Material:**
* [Impulses for Brainstorming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/brainstorming-impulses.pdf)
* [Example: User Groups for AI Application in Computational Pathology](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/example_identified-user-groups.pdf)

## Step 2: Collection of Information about the (Potential) Users
**Aim:** The aim of this task is twofold: (1) Get to know (potential) users personally --> Learn about their goals, motivations, frustrations, hopes, skills, education, knowledge, personal traits and aspirations. (2) Get to know (potential) use cases --> Learn about the users' tasks and find out in which context the AI application would probably be used. 
The goal is to collect relevant information regarding the following five areas:
* education, experience 
* tasks, workflows, work context
* skills, knowledge
* motivations, frustrations
* personal traits, values, learning style

**Method:** Qualitative methods such as interviews and surveys are used for information collection. There are different approaches possible:
* ***Approach 1: Comprehensive Interviews***  
In this approach, the aim is to cover all five information areas necessary for the creation of personas within a user interview. Ideally, ethnographic interviews or contextual inquiries are conducted with users in that place, where they would use the AI application. <sup name="a3">[[3]](#footnote3)</sup> Such a setting makes it possible to get a feeling of the context and framework conditions and observe the user 'in action'. However, if such on-site interviews and observations are not possible, also one-on-one interviews in another location or remote interviews via video/phone call can be used for information collection.   
IMPORTANT: Always use open questions and avoid leading questions, so that the interviewee is not inadvertently biased.
* ***Approach 2: Comprehensive Questionnaires***  
In this approach, the aim is to obtain all information necessary for the creation of personas through a survey. On the one hand, it might be tempting to try to mimic an interview and thus design a questionnaire with lots of open questions. However, experience shows that it is difficult to collect a sufficient amount of responses to such a questionnaire, since people do not like to spend a lot of time and write much text when filling in a questionnaire. On the other hand, by reducing the number of open questions usually also the amount of information that can be collected with the questionnaire is reduced. Therefore, it is difficult to implement this approach in practice, and we would not recommend to choose this approach.
* ***Approach 3: Shorter Questionnaires + Additional Research***  
In this approach, only part of the necessary information is collected via questionnaires, and additional research is done to fill the information gaps. The aim is to make the questionnaire short and easy to fill in, to obtain a high amount of responses to this survey. To achieve this, wherever possible instead of open questions multiple choice questions or ratings of statements are used, and in addition, also the scope of the questionnaire is restricted to those areas, where direct user input is indispensable and information cannot be obtained from other sources. For example, in a business domain information regarding the education needed for working in a specific job/role as well as the usual tasks, workflows and work context for a specific job/role can often be retrieved from the internet. 

**Practical Hints:** 
* _Conduct interviews:_  
Whenever possible, prefer interviews over questionnaires for information collection, since interviews provide much deeper insights and much more detailed information than questionnaires. On the one hand, the interviewer has the possibility to react on the answers of the interviewee, ask follow-up questions to gain a deeper understanding or modify the wording or order of the questions to adapt to the specific situation. Furthermore, besides the information retrieved from the answers of the interviewee, interviews provide more sources of valuable insights, such as asides made by the interviewee, the tone of voice, or aspects stressed specifically by the interviewee. This kind of 'aside information' cannot be obtained through questionnaires. Thus, even when it is not possible to collect all information through interviews, it is always worth the effort to conduct at least one or two interviews supplemental to a survey.
* _Focus on relevant information:_  
 When collecting user information and data, concentrate on those aspects, which are (or might be) relevant with respect to the AI application. A persona does not describe the whole person, but the focus is put only on the relevant aspects (such as relevant attitudes, skills...) and specific context related to the usage of the AI application. For example, in the context of a specific AI application it might be relevant, whether or not the user plays the piano, has got a dog, likes hiking or is married, while in the context of another AI application these aspects might not be relevant.
* _Combine 'direct' and 'indirect' view on the user group:_  
In interviews and questionnaires members of a user group are asked about their _personal_ education, tasks, skills, knowledge, goals, motivations, values and frustrations. This provides a 'direct' view on the members of the user group. In addition, ask also about skills, knowledge, goals, motivations and frustrations of a _typical_ member of the respective user group, which provides an 'indirect' view on that user group seen through the eyes of a peer. One benefit of this approach is, that for many people 'indirect' questions make it easier to state negative feelings and aspecs like frustrations and difficulties. In addition, asking about a _typical_ member of the group helps to level bias, which stems from the fact that those, who participate in (online) surveys, usually tend to be the more active, extrovert and open-minded members of a group.
* _Valuable input from internet research:_  
In a business domain, often you can retrieve valuable information about a specific job/role from job descriptions posted on websites of educational institutions or from job advertisements posted by companies. Interesting information regarding education, skills and careers of people working in a specific job/role can be retrieved from social media profiles. This information can be used to complete/complement information gained from members of the user group through interviews or questionnaires.

**Material:**  
* [Example Interview Guidelines](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/example_interview-guideline-QM-diagnostics-institute.pdf)
* [Example Questionnaire - 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/example_questionnaire-salesrepresentative.pdf)
* [Example Questionnaire - 'direct' and 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/example_questionnaire-pathologist.pdf)

  


---
---
# Licenses
All material is made available under Creative [Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license by Human-Centered AI Lab / Research and Diagnostics Institute of Pathology at Medical University Graz. You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper** and **indicating any changes** that you have made.

---
---
# Acknowledgements
Parts of this work have received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No. 857122 (CY-Biobank), No. 824087 (EOSC-Life) and No. 874662 (HEAP). This publication reflects only the authors' view and the European Commission is not responsible for any use that may be made of the information it contains. Parts of this work have received funding from the Austrian Research Promotion Agency (FFG) under grant agreement No. 879881 (EMPAIA) and by the Austrian Science Fund (FWF), Project: P-32554 explainable Artificial Intelligence.

---
---
# Further Reading

<a name="footnote1">[[1]](#a1)</a> A. Holzinger, Explainable AI and multi-modal causability in medicine, i-com19(3). [doi:10.1515/icom-2020-0024](https://doi.org/10.1515/icom-2020-0024)

<a name="footnote2">[[2]](#a2)</a> J. Salminen, K. Guan, S.-G. Jung, B. J. Jansen, A survey of 15
years of data-driven persona development, International Journal of Human Computer Interaction (2021) 1-24 [doi:10.1080/10447318.2021.1908670](https://doi.org/10.1080/10447318.2021.1908670)

<a name="footnote3">[[3]](#a3)</a> A. Cooper, R. Reimann, About Face 2.0 - The Essentials of Interaction
Design, John Wiley & Sons, 2003. Published online 2006: [https://flylib.com/books/en/2.153.1](https://flylib.com/books/en/2.153.1/)