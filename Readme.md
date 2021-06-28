# Personas for AI

**_Personas_** have been successful for over two decades in supporting the development of classic user interfaces by mapping users' mental models to specific contexts.  You can find more information about the personas method in <sup name="Nielsen">[[Nielsen]](#footnoteNielsen)</sup>.

However, the rapid proliferation of AI applications makes it necessary to create new approaches for future human-AI interfaces. Human-AI interfaces differ from classical human-computer interfaces in many ways, e.g., in that they acquire some degree of human-like cognitive, self-executing, and self-adaptive capabilities and autonomy, and generate unexpected outputs, requiring interactions that are non-deterministic. Furthermore, the most successful AI approaches are so-called "black-box" systems, where the technology and machine learning process are opaque to the user and the AI output is non-intuitive. Thus, when it comes to artificial intelligence (AI) applications, often _causability_ <sup name="a1">[[1]](#footnote1)</sup> is added to the users' needs: Specifically in high-stake domains, such as for example in medicine,  users need to understand the rationale and certainty underlying the results delivered by an AI application. Therefore, in order to achieve useful AI solutions with high usability and causability **it is essential that AI applications are designed and developed with the users in mind** (human-centered AI). To support such human-centered design and development of AI applications and to help foster the development of novel human-AI interfaces that will be urgently needed in the future, we provide this open available "Personas for AI toolbox". 

In principle there exist two fundamentally different approaches for creating personas: data-driven persona development and manual persona development. Data-driven persona development needs large amounts of user data (big data) to be useful, and thus for many use cases manual persona development using merely qualitative data is a better choice <sup name="a2">[[2]](#footnote2)</sup>. 
In this repository we describe our approach for manual persona development to support human-centered design and development of AI applications. 

We have elaborated a 5-steps approach for developing user personas for AI. Furthermore, based on our experience from practical implementation of the personas development process, we have created free material and tools to facilitate development of user personas for AI. This repository "Personas for AI" contains:
* a step-by-step guide for personas development
* illustrative examples from practical implementation in the field of Digital Pathology
* clear descriptions of the recommended methods
* useful tools for practical implementation

We have made available all these material under Creative [Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license. You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper _"Holzinger et al (2021), Personas for AI: An Open-Source Toolbox"_**.

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
* [Impulses for Brainstorming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/brainstorming-impulses.pdf)
* [Example: User Groups for AI Application in Computational Pathology](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_identified-user-groups.pdf)

## Step 2: Collection of Information about the (Potential) Users
**Aim:** The aim of this task is threefold: (1) Get to know (potential) users personally --> Learn about their goals, motivations, frustrations, hopes, skills, education, knowledge, personal traits and aspirations. (2) Get to know (potential) use cases --> Learn about the users' tasks and find out in which context the AI application would probably be used. (3) Learn about the users' attitudes regarding AI applications, and find out under which conditions they would trust / follow machine decisions.  
The goal is to collect relevant information regarding the following six areas:
* education, experience 
* tasks, workflows, work context
* skills, knowledge
* motivations, frustrations
* personal traits, values, learning style
* attitudes regarding AI solutions & machine decisions

**Method:** Qualitative methods such as interviews and surveys are used for information collection. There are different approaches possible:
* ***Approach 1: Comprehensive Interviews***  
In this approach, the aim is to cover all five information areas necessary for the creation of personas within a user interview. Ideally, ethnographic interviews or contextual inquiries are conducted with users in that place, where they would use the AI application. <sup name="Cooper, Reimann">[[Cooper, Reimann]](#footnoteCooperReimann)</sup> Such a setting makes it possible to get a feeling of the context and framework conditions and observe the user 'in action'. However, if such on-site interviews and observations are not possible, also one-on-one interviews in another location or remote interviews via video/phone call can be used for information collection.   
IMPORTANT: Always use open questions and avoid leading questions, so that the interviewee is not inadvertently biased.
* ***Approach 2: Comprehensive Questionnaires***  
In this approach, the aim is to obtain all information necessary for the creation of personas through a survey. On the one hand, it might be tempting to try to mimic an interview and thus design a questionnaire with lots of open questions. However, experience shows that it is difficult to collect a sufficient amount of responses to such a questionnaire, since people do not like to spend a lot of time and write much text when filling in a questionnaire. On the other hand, by reducing the number of open questions usually also the amount of information that can be collected with the questionnaire is reduced. Therefore, it is difficult to implement this approach in practice, and we would not recommend to choose this approach.
* ***Approach 3: Shorter Questionnaires + Additional Research***  
In this approach, only part of the necessary information is collected via questionnaires, and additional research is done to fill the information gaps. The aim is to make the questionnaire short and easy to fill in, to obtain a high amount of responses to this survey. To achieve this, wherever possible instead of open questions multiple choice questions or ratings of statements are used, and in addition, also the scope of the questionnaire is restricted to those areas, where direct user input is indispensable and information cannot be obtained from other sources. For example, in a business domain information regarding the education needed for working in a specific job/role as well as the usual tasks, workflows and work context for a specific job/role can often be retrieved from the internet. 

**Practical Hints:** 
* _Conduct interviews:_  
Whenever possible, prefer interviews over questionnaires for information collection, since interviews provide much deeper insights and much more detailed information than questionnaires. On the one hand, the interviewer has the possibility to react on the answers of the interviewee, ask follow-up questions to gain a deeper understanding or modify the wording or order of the questions to adapt to the specific situation. Furthermore, besides the information retrieved from the answers of the interviewee, interviews provide more sources of valuable insights, such as asides made by the interviewee, the tone of voice, or aspects stressed specifically by the interviewee. This kind of 'aside information' cannot be obtained through questionnaires. In addition, by obtaining information through talking to members of the user group directly it is easier to obtain a more comprehensive view of people's complex identities and avoid stereotyping. Thus, even when it is not possible to collect all information through interviews, it is always worth the effort to conduct at least two or three interviews supplemental to a survey.
* _Get a comprehensive view:_  
Try to collect information from a sample of members of the user group as diverse as possible. For example, include people with different age, gender, abilities, education, cultural background etc. Aim for getting a comprehensive view on the user group, and try to catch details and facettes that are easily overlooked, when concentrating only on majorities or being led by preconceptions. Take into account the multiple identities of a person, as this helps to minimise stereotyping <sup name="a3">[[3]](#footnote3)</sup>.
* _Focus on relevant information:_  
 When collecting user information and data, concentrate on those aspects, which are (or might be) relevant with respect to the AI application. A persona does not describe the whole person, but the focus is put only on the relevant aspects (such as relevant attitudes, skills...) and specific context related to the usage of the AI application. For example, in the context of a specific AI application it might be relevant, whether or not the user plays the piano, has got a dog, likes hiking or is married, while in the context of another AI application these aspects might not be relevant.
* _Combine 'direct' and 'indirect' view on the user group:_  
In interviews and questionnaires members of a user group are asked about their _personal_ education, tasks, skills, knowledge, goals, motivations, values, attitudes and frustrations. This provides a 'direct' view on the members of the user group. In addition, ask also about skills, knowledge, goals, motivations and frustrations of a _typical_ member of the respective user group, which provides an 'indirect' view on that user group seen through the eyes of a peer. One benefit of this approach is, that for many people 'indirect' questions make it easier to state negative feelings and aspecs like frustrations and difficulties. In addition, asking about a _typical_ member of the group helps to level bias, which stems from the fact that those, who participate in (online) surveys, usually tend to be the more active, extrovert and open-minded members of a group.
* _Obtain valuable input from internet research:_  
In a business domain, often you can retrieve valuable information about a specific job/role from job descriptions posted on websites of educational institutions or from job advertisements posted by companies. Interesting information regarding education, skills and careers of people working in a specific job/role can be retrieved from social media profiles. This information can be used to complete/complement information gained from members of the user group through interviews or questionnaires.

**Material:**  
* [Example Interview Guidelines](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_interview-guideline-QM-diagnostics-institute.pdf)
* [Example Questionnaire - 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_questionnaire-salesrepresentative.pdf)
* [Example Questionnaire - 'direct' and 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_questionnaire-pathologist.pdf)

  
## Step3: Consolidation \& Analysis of the Collected Information
**Aim:** The aim of this task is threefold: (1) Get an overview of the information collected. (2) Distill the important findings from the heap of information collected. (3) Decide, based on these findings, which personas to develop.

**Method:** 
* _Central Information Storage:_ First, to get an overview of the information collected, gather all collected information in one place. Depending on the kind and amount of information collected, such a central information storage could for example be a database or a simple spreadsheet.
* _Visualisation Diagrams:_ Visualisation diagrams (e.g. barcharts, scatterplots...) support consolidation and analysis of structured information, such as categorical or numerical information obtained via closed questions in an interview or questionnaire. 
* _Affinity Diagramming:_ Affinity diagramming supports consolidation and analysation of unstructured information, such as for example statements obtained via open questions in an interview or questionnaire. To create an Affinity Diagram first the collected information is split into single aspects. Then all these single pieces of information are grouped in clusters based on their content relationships, and finally each of these clusters is given a label summarising the information contained in that specific cluster. 
* _Identify Subgroups of Users:_ The visualisations (barcharts, scatterplots,... or Affinity diagram) may show indications that the user group is split into several subgroups regarding certain aspects, such as for example personal traits, education, working style, attitudes regarding new technologies, etc. --> For all aspects, where the identified differences may have influence on the usage of the AI application, it must be taken care that each of these subgroups of users is represented by a distinct persona.

**Practical Hints:** 
* _Keep information traceable to its source:_  
For every piece of information preserve the connection to its origin during the whole process of organising, structuring, splitting, combining and condensing of the information. This can for example be done by assigning a brief ID to each information source and marking the information with the respective ID of its source (e.g. interviewee 1 gets the ID i001 and this ID is appended to all statements from interviewee 1).  This will help to find out grouping characteristics later on in the project. Furthermore, knowledge about the source of the information can also increase people's confidence and commitment later on, when working with a persona.

**Material:**
* [Practical Tips for Affinity Diagramming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/practical-tips-for-affinity-diagramming.pdf)


## Step 4: Creating the Foundation for a Persona
**Aim:** The aim of this task is to gather all information for a specific persona in a structured way. 

**Method:** To achieve this aim, a _Foundation Document_ is created for each persona. The foundation document contains all information about a persona in a structured way. The foundation document serves two purposes: (1) The structured representation of all the information collected for a persona facilitates checking for completeness --> If important pieces of information for a persona are missing, additional research can be done to fill these gaps. (2) The foundation document is the basis for any further usage of the persona, such as for example visualisation of the persona in a persona-sheet (as described in the next step), or elaboration of use cases and scenarios for the persona.

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
* [Example: Foundation Document for Persona "Quality Manager at Diagnostics Institute"](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/example/example-foundation-document_QM-diagnostics-institute.pdf)


## Step 5: Visualising a Persona
**Aim:** The aim of this task is to make the fictional persona a tangible character to help people empathize with the persona.

**Method:** To achieve this, a _Persona Sheet_ is created. A persona sheet is the visualisation of a persona in a nice 1-page layout. The persona sheet includes narrative text about the persona's interests, values, lifestyle, attitudes and behavioural patterns based on the information from the persona's foundation document. However, in order to make the persona more realistic, also a fictional picture of the persona, a ficional name, age, and some other fictional parts (for example regarding hobbies or family) are added to the persona sheet. All these fictional parts must be chosen carefully. It must be taken care that these fictional information parts fit to the character and support communication of the persona's characteristics as described in the persona's foundation document.

**Practical Hint:**  
A central part of the persona sheet is the fictional picture of the persona, visualising the persona as a tangible person. A realistic picture increases empathy with the persona <sup name="a4">[[4]](#footnote4)</sup>. However, how people perceive a persona picture is strongly dependent on their gender or cultural background, and details conveyed by this picture (such as age, gender, social status, cultural background...) can activate stereotypes <sup name="a5">[[5]](#footnote5)</sup>. Therefore, it is of utmost importance that the picture is selected carefully, so to avoid stereotyping and help to convey the characteristic aspects of the persona, as described in the persona's foundation document.   
For visualising a persona, do not take a picture of a real user or a picture of a person from your network (e.g. colleagues, family or friends). You could take a picture from internet, which is published under a license that allows usage for this purpose.  However, we have found that it is rather difficult to get such photos, which are suitable for persona visualisation. To solve this problem, we have created a set of fictional pictures, which are suitable for visualisation of personas for AI, using the code from [thispersondoesnotexist.com](https://thispersondoesnotexist.com/).

<img src="https://github.com/human-centered-ai-lab/PERSONAS/blob/main/images/persona-pathologist1.png" alt="example persona sheet in portrait format" width="200"> <img src="https://github.com/human-centered-ai-lab/PERSONAS/blob/main/images/persona-softwaredeveloper.png" alt="example persona sheet in landscape format" height="200">


**Material:**  
* Examples of Persona Sheets:
    * example: Persona Pathologist 1 [(persona sheet in portrait format) ](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist_portrait.pdf) [(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist1_landscape.pdf)
    * example: Persona Pathologist 2 [(persona sheet in portraint format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist2_portrait.pdf) [(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist2_landscape.pdf)
    * example: Persona Researcher in Pathology [(persona sheet in portrait format) ](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-researcher_in_pathology_portrait.pdf)[(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-researcher_in_pathology_landscape.pdf)
    * example: Persona Software Developer [(persona sheet in portrait format) ](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-softwaredeveloper_portrait.pdf)[(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-softwaredeveloper_landscape.pdf)
* Templates for Creating Persona Sheets:  
    * LaTeX templates: (To use the LaTeX templates, download the zip-file and import it as a new project into [overleaf](https://www.overleaf.com).)
        * [LaTeX template (portrait format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/latex-template-persona-for-ai-portrait-v01.zip)
        * [LaTeX template (landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/latex-template-persona-for-ai-landscape-v03.zip)
* Set of Pictures for Persona Visualisation

# Resources

* **Development Process of Personas for AI**  
Paper Holzinger et al (2021) "Personas for AI: An Open-Source Toolbox"
* **Step 1: Identification of (Potential) User Groups**  
[Impulses for Brainstorming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/brainstorming-impulses.pdf)  
[Example: User Groups for AI Application in Computational Pathology](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_identified-user-groups.pdf)  
* **Step 2: Collection of Information about the (Potential) Users**  
[Example Interview Guidelines](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_interview-guideline-QM-diagnostics-institute.pdf)  
[Example Questionnaire - 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_questionnaire-salesrepresentative.pdf)  
[Example Questionnaire - 'direct' and 'indirect view'](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example_questionnaire-pathologist.pdf)  
* **Step 3: Consolidation \& Analysis of the Collected Information**  
[Practical Tips for Affinity Diagramming](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/practical-tips-for-affinity-diagramming.pdf)  
* **Step 4: Creating the Foundation for a Persona**  
[Example: Foundation Document for Persona "Quality Manager at Diagnostics Institute"](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-foundation-document_QM-diagnostics-institute.pdf)  
* **Step 5: Visualising a Persona**  
Examples of Persona Sheets: 
   * example: Persona Pathologist 1 [(persona sheet in portrait format) ](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist_portrait.pdf) [(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist1_landscape.pdf)
   * example: Persona Pathologist 2 [(persona sheet in portraint format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist2_portrait.pdf) [(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-pathologist2_landscape.pdf)
   * example: Persona Researcher in Pathology [(persona sheet in portrait format) ](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-researcher_in_pathology_portrait.pdf)[(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-researcher_in_pathology_landscape.pdf)
    * example: Persona Software Developer [(persona sheet in portrait format) ](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-softwaredeveloper_portrait.pdf)[(persona sheet in landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/examples/example-personasheet-softwaredeveloper_landscape.pdf)

    Templates for Creating Persona Sheets: 
    * LaTeX templates: (To use the LaTeX templates, download the zip-file and import it as a new project into [Overleaf](https://www.overleaf.com).)
        * [LaTeX Template (portrait format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/latex-template-persona-for-ai-portrait-v01.zip) 
        * [LaTeX Template (landscape format)](https://github.com/human-centered-ai-lab/PERSONAS/blob/main/tools/latex-template-persona-for-ai-landscape-v03.zip)  

    Set of Pictures for Persona Visualisation  



---
---
# Licence
All material is made available under [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license by Human-Centered AI Lab / Research and Diagnostics Institute of Pathology at Medical University Graz. You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper _Holzinger et al (2021) "Personas for AI: An Open-Source Toolbox"_**.

---
---
# Acknowledgements
Parts of this work have received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No. 857122 (CY-Biobank), No. 824087 (EOSC-Life) and No. 874662 (HEAP). This publication reflects only the authors' view and the European Commission is not responsible for any use that may be made of the information it contains. Parts of this work have received funding from the Austrian Research Promotion Agency (FFG) under grant agreement No. 879881 (EMPAIA) and by the Austrian Science Fund (FWF), Project: P-32554 explainable Artificial Intelligence.

---
---
# Further Reading

## Papers

<a name="footnote1">[[1]](#a1)</a> A. Holzinger, Explainable AI and multi-modal causability in medicine, i-com19(3). [doi:10.1515/icom-2020-0024](https://doi.org/10.1515/icom-2020-0024)

<a name="footnote2">[[2]](#a2)</a> J. Salminen, K. Guan, S.-G. Jung, B. J. Jansen, A survey of 15
years of data-driven persona development, International Journal of Human Computer Interaction (2021) 1-24. [doi:10.1080/10447318.2021.1908670](https://doi.org/10.1080/10447318.2021.1908670)

<a name="footnote3">[[3]](#a3)</a> N. Marsden, M. Pröbster, Personas and identity: Looking at multiple identities to inform the construction of personas, in: Conference on Human
Factors in Computing Systems CHI 2019 - Proceedings, Association for Computing Machinery, 2019. [doi:10.1145/3290605.3300565](https://doi.org/10.1145/3290605.3300565)

<a name="footnote4">[[4]](#a4)</a> J. Salminen, S.-G. Jung, J. M. Santos, A. M. S. Kamel, B. J. Jansen, Picturing it!: The effect of image styles on user perceptions of personas, in:
Proceedings CHI '21, Association for Computing Machinery (ACM), 2021,
pp. 1-16. [doi:10.1145/3411764.3445360](https://doi.org/10.1145/3411764.3445360)

<a name="footnote5">[[5]](#a5)</a> M. Pröbster, J. Hermann, N. Marsden, Personas and persons - an empirical study on stereotyping of personas, ACM International Conference
Proceeding Series (2019) 137-146. [doi:10.1145/3340764.3340771](https://doi.org/10.1145/3340764.3340771)


## Books

<a name="Nielsen">[[Nielsen]](#Nielsen)</a> L. Nielsen, Personas - User Focused Design, Springer-Verlag London, 2019. [doi: 10.1007/978-1-4471-7427-1](https://doi.org/10.1007/978-1-4471-7427-1)

<a name="Cooper, Reimann">[[Cooper, Reimann]](#CooperReimann)</a> A. Cooper, R. Reimann, About Face 2.0 - The Essentials of Interaction Design, John Wiley & Sons, 2003. Published online 2006: [https://flylib.com/books/en/2.153.1](https://flylib.com/books/en/2.153.1/)