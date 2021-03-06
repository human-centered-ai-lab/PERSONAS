
<h1 id="step-by-step"> Developing Personas for AI: Step-by-Step </h1>

In principle, there exist two fundamentally different approaches for creating personas: data-driven persona development and manual persona development. Data-driven persona development needs large amounts of user data (big data) to be useful, and thus for many use cases manual persona development using merely qualitative data is a better choice <sup name="a2">[[2]](https://github.com/human-centered-ai-lab/PERSONAS#footnote2)</sup>. 
In this repository we describe our approach for manual persona development to support human-centered design and development of AI applications. We give clear explanations of the recommended methods and practical hints for implementation. For each step in the persona development process, we provide illustrative examples from the field of Digital Pathology as well as useful, ready-to-use tools. 

---

**License information:**  
We have made available all these material under [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license.  
You can **use, redistribute, and adapt** the material for non-commercial purposes, as long as you give appropriate credit by **citing our paper:**  _A. Holzinger, M. Kargl, B. Kipperer, P. Regitnig, M. Plass and H. Müller, "Personas for Artificial Intelligence (AI) an Open Source Toolbox", in IEEE Access, vol. 10, pp. 23732-23747, 2022,_ [doi: 10.1109/ACCESS.2022.3154776](https://doi.org/10.1109/ACCESS.2022.3154776).

---
---


## 5-Steps Towards User Personas for AI:
* [Step 1: Identification of (Potential) User Groups](#step-one)
* [Step 2: Collection of Information about the Users](#step-two)
* [Step 3: Consolidation and Analysis of the Collected Information](#step-three)
* [Step 4: Creating the Foundation for Personas](#step-four)
* [Step 5: Visualising Personas](#step-five)

---


<h2 id="step-one"> Step 1: Identification of (Potential) User Groups </h2>

**Aim:** Create a comprehensive list of groups of users, who will (potentially) use the AI application. Each of these user groups is the seed for a distinct persona.

**Method:** We recommend to use the well-known method of _brainstorming_ for collecting ideas regarding potential user groups. After the brainstorming session, discuss and evaluate the results, and agree on a list of user groups to form the starting point for the creation of personas.

**Material:**
* [Impulses for Brainstorming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Developing_Personas_For_AI-Step-By-Step/brainstorming-impulses.pdf)
* [Example: User Groups for AI Application in Digital Pathology](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example_identified-user-groups.pdf)


---
<h2 id="step-two"> Step 2: Collection of Information about (Potential) Users </h2>

**Aim:**  The aim of this task is threefold: (1) Get to know (potential) users personally --> Learn about their goals, motivations, frustrations, hopes, skills, education, knowledge, personal traits and aspirations. (2) Get to know (potential) use cases --> Learn about the users' tasks and find out in which context the AI application would probably be used. (3) Learn about the users' attitudes regarding AI applications, and find out under which conditions they would trust / follow machine decisions.  
The goal is to collect relevant information regarding the following six areas:
* Education, experience 
* Tasks, workflows, work context
* Skills, knowledge
* Motivations, frustrations
* Personal traits, values, learning style
* Attitudes regarding AI solutions & machine decisions

**Method:** Qualitative methods such as interviews and surveys are used for information collection. There are different approaches possible:
* ***Approach 1: Comprehensive Interviews***  
In this approach, the aim is to cover all five information areas necessary for the creation of personas within a user interview. Ideally, ethnographic interviews or contextual inquiries are conducted with users in that place, where they would use the AI application. <sup name="CooperReimann">[[Cooper, Reimann]](https://github.com/human-centered-ai-lab/PERSONAS#footnote101)</sup> Such a setting makes it possible to get a feeling of the context and framework conditions and observe the user 'in action'. However, if such on-site interviews and observations are not possible, also one-on-one interviews in another location or remote interviews via video/phone call can be used for information collection.   
IMPORTANT: Always use open questions and avoid leading questions, so that the interviewee is not inadvertently biased.
* ***Approach 2: Comprehensive Questionnaires***  
In this approach, the aim is to obtain all information necessary for the creation of personas through a survey. On the one hand, it might be tempting to try to mimic an interview and thus design a questionnaire with lots of open questions. However, experience shows that it is difficult to collect a sufficient amount of responses to such a questionnaire, since people do not like spending a lot of time and writing a lot of text when filling in a questionnaire. On the other hand, by reducing the number of open questions usually also the amount of information that can be collected with the questionnaire is reduced. Therefore, it is difficult to implement this approach in practice, and we would not recommend to choose this approach.
* ***Approach 3: Shorter Questionnaires + Additional Research***  
In this approach, only part of the necessary information is collected via questionnaires, and additional research is done to fill the information gaps. The aim is to make the questionnaire short and easy to fill in, to obtain a high amount of responses to this survey. To achieve this, wherever possible, instead of open questions multiple choice questions or ratings of statements are used, and in addition, also the scope of the questionnaire is restricted to those areas, where direct user input is indispensable and information cannot be obtained from other sources. For example, in a business domain information regarding the education needed for working in a specific job/role as well as the usual tasks, workflows and work context for a specific job/role can often be retrieved from the internet. 

**Practical Hints:** 
* _Conduct interviews:_  
Whenever possible, prefer interviews over questionnaires for information collection, since interviews provide much deeper insights and much more detailed information than questionnaires. On the one hand, the interviewer has the possibility to react on the answers of the interviewee, ask follow-up questions to gain a deeper understanding or modify the wording or order of the questions to adapt to the specific situation. Furthermore, besides the information retrieved from the answers of the interviewee, interviews provide more sources of valuable insights, such as asides made by the interviewee, the tone of voice, or aspects stressed specifically by the interviewee. This kind of 'aside information' cannot be obtained through questionnaires. In addition, by obtaining information through talking to members of the user group directly it is easier to obtain a more comprehensive view of people's complex identities and avoid stereotyping. Thus, even when it is not possible to collect all information through interviews, it is always worth the effort to conduct at least two or three interviews supplemental to a survey.
* _Get a comprehensive view:_  
Try to collect information from a sample of members of the user group as diverse as possible. For example, include people with different age, gender, abilities, education, cultural background etc. Aim for getting a comprehensive view on the user group, and try to catch details and facettes that are easily overlooked, when concentrating only on majorities or being led by preconceptions. Take into account the multiple identities of a person, as this helps to minimise stereotyping <sup name="a3">[[3]](https://github.com/human-centered-ai-lab/PERSONAS#footnote3)</sup>.
* _Focus on relevant information:_  
 When collecting user information and data, concentrate on those aspects, which are (or might be) relevant with respect to the AI application. A persona does not describe the whole person, but the focus is put only on the relevant aspects (such as relevant attitudes, skills...) and specific context related to the usage of the AI application. For example, in the context of a specific AI application it might be relevant, whether or not the user plays the piano, has got a dog, likes hiking or is married, while in the context of another AI application these aspects might not be relevant.
* _Combine the 'direct' and 'indirect' view on the user group:_  
In interviews and questionnaires members of a user group are asked about their _personal_ education, tasks, skills, knowledge, goals, motivations, values, attitudes and frustrations. This provides a 'direct' view on the members of the user group. In addition, ask also about skills, knowledge, goals, motivations and frustrations of a _typical_ member of the respective user group, which provides an 'indirect' view on that user group seen through the eyes of a peer. One benefit of this approach is that for many people 'indirect' questions make it easier to state negative feelings and aspecs such as frustrations and difficulties. In addition, asking about a _typical_ member of the group helps to level bias, which stems from the fact that those, who participate in (online) surveys, usually tend to be the more active, extrovert and open-minded members of a group.
* _Obtain valuable input from an internet research:_  
In a business domain, often you can retrieve valuable information about a specific job/role from job descriptions posted on websites of educational institutions or from job advertisements posted by companies. Interesting information regarding education, skills and careers of people working in a specific job/role can be retrieved from social media profiles. This information can be used to complete/complement information gained from members of the user group through interviews or questionnaires.

**Material:**  
* [Example Interview Guidelines](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example_interview-guideline-QM-diagnostics-institute.pdf)
* [Example Questionnaire - 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example-questionnaires/example_questionnaire-salesrepresentative.pdf)
* [Example Questionnaire - 'direct' and 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example-questionnaires/example_questionnaire-pathologist.pdf)


[&#8593; back to top (Step-by-Step guide)](#step-by-step) 

---
<h2 id="step-three"> Step3: Consolidation & Analysis of the Collected Information </h2>

**Aim:** The aim of this task is threefold: (1) Get an overview of the information collected. (2) Distill the important findings from the heap of information collected. (3) Decide, based on these findings, which personas to develop.

**Method:** 
* _Central Information Storage:_ First, to get an overview of the information collected, gather all collected information in one place. Depending on the kind and amount of information collected, such a central information storage could, for example, be a database or a simple spreadsheet.
* _Visualisation Diagrams:_ Visualisation diagrams (e.g. barcharts, scatterplots...) support consolidation and analysis of structured information, such as categorical or numerical information obtained via closed questions in an interview or questionnaire. 
* _Affinity Diagramming:_ Affinity diagramming supports consolidation and analysation of unstructured information, such as for example, statements obtained via open questions in an interview or questionnaire. To create an Affinity Diagram, first the collected information is split into single aspects. Then all these single pieces of information are grouped in clusters based on their content relationships, and finally, each of these clusters is given a label summarising the information contained in that specific cluster. 
* _Identify Subgroups of Users:_ The visualisations (barcharts, scatterplots,... or Affinity diagram) may show indications that the user group is split into several subgroups regarding certain aspects, such as for example personal traits, education, working style, attitudes regarding new technologies, etc. --> For all aspects, where the identified differences may have influence on the usage of the AI application, it must be taken care that each of these subgroups of users is represented by a distinct persona.

**Practical Hints:** 
* _Keep information traceable to its source:_  
For every piece of information preserve the connection to its origin during the whole process of organising, structuring, splitting, combining and condensing of the information. This can for example be done by assigning a brief ID to each information source and marking the information with the respective ID of its source (e.g. interviewee 1 gets the ID i001 and this ID is appended to all statements from interviewee 1).  This will help to find out grouping characteristics later on in the project. Furthermore, knowledge about the source of the information can also increase people's confidence and commitment later on, when working with a persona.

**Material:**
* [Practical Tips for Affinity Diagramming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Developing_Personas_For_AI-Step-By-Step/practical-tips-for-affinity-diagramming.pdf)

[&#8593; back to top (Step-by-Step guide)](#step-by-step) 

---
<h2 id="step-four"> Step 4: Creating the Foundation for a Persona </h2>

**Aim:** The aim of this task is to gather all information for a specific persona in a structured way. 

**Method:** To achieve this aim, a _Foundation Document_, as described in <sup name="PruittAdlin">[[Pruitt, Adlin]](https://github.com/human-centered-ai-lab/PERSONAS#footnote102)</sup>,  is created for each persona. The foundation document contains all information about a persona in a structured way. The foundation document serves two purposes: (1) The structured representation of all the information collected for a persona facilitates checking for completeness --> If important pieces of information for a persona are missing, additional research can be done to fill these gaps. (2) The foundation document is the basis for any further usage of the persona, such as for example visualisation of the persona in a persona-sheet (as described in the next step), or elaboration of use cases and scenarios for the persona.

In the literature, there are many different templates and structures proposed for persona foundation documents. We have structured the foundation documents created for user personas of AI applications in computational pathology into the following sections:
* work (tasks, workflows, context)
* education/career
* knowledge/skills
* personal traits
* motivational factors
* frustrations/hurdles
* goals/values
* attitudes regarding AI solutions

**Material:**
* [Example: Foundation Document for Persona "Quality Manager at Diagnostics Institute"](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example-foundation-document_QM-diagnostics-institute.pdf)

[&#8593; back to top (Step-by-Step guide)](#step-by-step) 

---
<h2 id="step-five">Step 5: Visualising a Persona </h2>

**Aim:** The aim of this task is to make the fictional persona a tangible character to help people empathize with the persona.

**Method:** To achieve this, a _Persona Sheet_ is created. A persona sheet is the visualisation of a persona in a nice 1-page layout. The persona sheet includes narrative text about the persona's interests, values, lifestyle, attitudes and behavioural patterns based on the information from the persona's foundation document. However, in order to make the persona more realistic, also a fictional picture of the persona, a ficional name, age, and some other fictional parts (for example regarding hobbies or family) are added to the persona sheet. All these fictional parts must be chosen carefully. It must be taken care that these fictional information parts fit to the character and support communication of the persona's characteristics as described in the persona's foundation document.

<img src="https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Developing_Personas_For_AI-Step-By-Step/images/persona-pathologist1.png" alt="example persona sheet in portrait format" width="200"> <img src=https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Developing_Personas_For_AI-Step-By-Step/images/persona-softwaredeveloper.png alt="example persona sheet in landscape format" height="200">


**Practical Hint:**  
A central part of the persona sheet is the fictional picture of the persona, visualising the persona as a tangible person. A realistic picture increases empathy with the persona <sup name="a4">[[4]](https://github.com/human-centered-ai-lab/PERSONAS#footnote4)</sup>. However, how people perceive a persona picture is strongly dependent on their gender or cultural background, and details conveyed by this picture (such as age, gender, social status, cultural background...) can activate stereotypes <sup name="a5">[[5]](https://github.com/human-centered-ai-lab/PERSONAS#footnote5)</sup>. Therefore, it is of utmost importance that the picture is selected carefully, so to avoid stereotyping and help to convey the characteristic aspects of the persona, as described in the persona's foundation document.   
For visualising a persona, do not take a picture of a real user or a picture of a person from your network (e.g. colleagues, family or friends). You could take a picture from internet, which is published under a license that allows usage for this purpose.  However, we have found that it is rather difficult to get such photos, which are suitable for persona visualisation. To solve this problem, we have created a set of fictional pictures, which are suitable for visualisation of personas for AI, using the code from [thispersondoesnotexist.com](https://thispersondoesnotexist.com/).



**Material:**  
* [Examples of persona sheets created for personas in Digital Pathology](https://github.com/human-centered-ai-lab/PERSONAS/tree/main/Examples_For_AI_In_Digital_Pathology/example-personasheets)
* [Templates for creating persona sheets](https://github.com/human-centered-ai-lab/PERSONAS/tree/main/Persona_Templates)
* [Set of Faces for Persona Visualisation](https://github.com/human-centered-ai-lab/PERSONAS/tree/main/Resources/Faces)


[&#8593; back to top (Step-by-Step guide)](#step-by-step) 

---
---
<h1 id="resources"> Resources </h1>

* **Development Process of Personas for AI**  
Paper:  _A. Holzinger, M. Kargl, B. Kipperer, P. Regitnig, M. Plass and H. Müller, "Personas for Artificial Intelligence (AI) an Open Source Toolbox", in IEEE Access, vol. 10, pp. 23732-23747, 2022,_ [doi: 10.1109/ACCESS.2022.3154776](https://doi.org/10.1109/ACCESS.2022.3154776)
* **Step 1: Identification of (Potential) User Groups**  
[Impulses for Brainstorming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Developing_Personas_For_AI-Step-By-Step/brainstorming-impulses.pdf)  
[Example: User Groups for AI Application in Digital Pathology](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example_identified-user-groups.pdf)  
* **Step 2: Collection of Information about the (Potential) Users**  
[Example Interview Guidelines](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example_interview-guideline-QM-diagnostics-institute.pdf)  
[Example Questionnaire - 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example-questionnaires/example_questionnaire-salesrepresentative.pdf)  
[Example Questionnaire - 'direct' and 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example-questionnaires/example_questionnaire-pathologist.pdf)  
* **Step 3: Consolidation & Analysis of the Collected Information**  
[Practical Tips for Affinity Diagramming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Developing_Personas_For_AI-Step-By-Step/practical-tips-for-affinity-diagramming.pdf)  
* **Step 4: Creating the Foundation for a Persona**  
[Example: Foundation Document for Persona "Quality Manager at Diagnostics Institute"](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/Examples_For_AI_In_Digital_Pathology/example-foundation-document_QM-diagnostics-institute.pdf)  
* **Step 5: Visualising a Persona**  
[Examples of persona sheets created for personas in Digital Pathology](https://github.com/human-centered-ai-lab/PERSONAS/tree/main/Examples_For_AI_In_Digital_Pathology/example-personasheets)  
[Templates for Creating Persona Sheets](https://github.com/human-centered-ai-lab/PERSONAS/tree/main/Persona_Templates)   
[Set of Faces for Persona Visualisation](https://github.com/human-centered-ai-lab/PERSONAS/tree/main/Resources/Faces)



[&#8593; back to top (Step-by-Step guide)](#step-by-step) 


---
---
# License
All material is made available under [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license by Human-Centered AI Lab / Research and Diagnostics Institute of Pathology at Medical University Graz. You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper:** _ _A. Holzinger, M. Kargl, B. Kipperer, P. Regitnig, M. Plass and H. Müller, "Personas for Artificial Intelligence (AI) an Open Source Toolbox", in IEEE Access, vol. 10, pp. 23732-23747, 2022,_ [doi: 10.1109/ACCESS.2022.3154776](https://doi.org/10.1109/ACCESS.2022.3154776).

