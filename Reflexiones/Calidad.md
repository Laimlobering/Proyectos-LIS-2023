# Quality models proposed by McCall and Boehm


## Quality Model proposed by McCall:

The model proposed by Jim McCall is mainly focused on the relationship between users and developers since it focuses on several quality factors that reflect both the users perspectives and the priorities that software developers have, it has three main perspectives to identify the quality of a software, these perspectives are: product review, product transition and product operations. The quality factors that count each of these will be explained below.

**Revision:**
1.	Maintainability: It is the capacity that the software has to detect errors during the maintenance phase in order to correct them.
2.	Flexibility: It refers to the ability to make changes in the operating environment.
3.	Testability: Ease of testing the program to ensure that it is error free and meets the required specifications.

**Transition:**
1.	Portability: This factor refers to the ability of the software to be adapted or transferred to another environment, while maintaining its functionality.
2.	Reusability: This refers to the ease with which the software can be reused in another context or in parts of a system.
3.	Interoperability: The ease with which the system can integrate and interact efficiently with other systems.

**Operations:** 
1.	Correctness: this part focuses on whether the software fulfills the required functions in a correct way 2.
2.	Efficiency: This refers to the efficiency of the software in terms of execution and use of resources.
3.	Integrity: It is the protection that the software has against unauthorized access, protecting the software and the associated data.
4.	Reliability: This factor has to do with the correct execution of the program, that is to say, that it works without failures. 
5.	Usability: It is basically the ease of use of the software, so that it is not complicated to learn to use it and the user does not have problems with its use.

Now then, this model details three types of quality characteristics ordered in a hierarchical way which are: 
1.	The 11 factors explained above (to be specified): these describe the way in which users view the software.
2.	23 quality criteria (to be built): contrary to the previous one, these describe the way developers see the software.
3.	Metrics (to be controlled): These are defined and used to give a scale and a method of measurement.
Below we can see an image that represents the perspectives of this model along with their corresponding quality factors and criteria.

![McCallModel](https://github.com/Laimlobering/Proyectos-LIS-2023/blob/PD-3/Assets/Modelo%20de%20McCall.jpg)


## Quality Model proposed by Boehm

The quality model proposed by Barry W. Boehm is a model that quantifies the qualities of software by means of a series of attributes, unlike McCall's model, this one includes attributes related to hardware, although in the explanation of attributes we can appreciate several factors that are found in McCall's model in the same way. This has three levels of quality attributes divided according to their characteristics, the first are the primary uses that would be high-level characteristics, then the intermediate constructs that are the medium-level characteristics and finally the primitives that are, as their name implies, the primitive characteristics. 

The high-level features address the three main questions that a person has when buying software:

1.	As-is utility: How well it can be used in its current state.
2.	Maintainability: This refers to the software's ability to detect errors during the maintenance phase in order to correct them.
3.	Portability: The ability of the software to be adapted or transferred to another environment, maintaining its functionality.

The medium level features have 7 elements which are associated with the high level features explained above, these elements are:

1.	Portability (General utility characteristic): refers to the ability of a software to operate in different environments or platforms without the need for significant modifications.
2.	Reliability (As-is utility): refers to the ability of a system to perform its functions accurately and without errors.
3.	Efficiency (As-is utility): refers to the system's ability to perform its functions quickly and with an efficient use of resources.
4.	Usability (As-is utility, Human Engineering): refers to the ease with which users can interact with the system to achieve their objectives.
5.	Testability (Maintainability characteristic): is a characteristic related to the ease with which the software can be verified to ensure that it meets the specified requirements.
6.	Understandability (Maintainability characteristic): refers to the clarity and understanding of the software code and documentation.
7.	Flexibility (Maintainability Characteristic, Modifiability): refers to the ability of the software to adapt to changes.

Boehm further classified the features into primitive constructs, which include device independence, accuracy, completeness, consistency, device efficiency, accessibility, communicability, self-description, readability, structurability, conciseness, and improvability. For example, "Testability" is broken down into accessibility, communicability, structurability and self-description. Below is an image to represent this:

![Diagrama de Gantt](https://github.com/Laimlobering/Proyectos-LIS-2023/blob/PD-3/Assets/Modelo%20de%20Bohem.jpg)

 
## ¿Which of these two quality models is more appropriate for our software project?

Given the nature of our cooking application, where accuracy and adaptability are critical, McCall's quality model stands out for us. Its focus on operational and review features more closely aligns with the need to deliver accurate and easily understandable recipes. The emphasis on maintainability and testability is crucial to conform to user preferences and ensure the continued quality of the content it delivers.

While the Boehm quality model addresses valuable aspects such as portability and efficiency, the McCall model's ability to more specifically address accuracy and completeness of recipes makes it more relevant to our specific project. Adaptability and accuracy are essential parts of the scope of what would be an application that gives recipes based on specific filters, and the McCall quality model highlights these key areas in a more specific and detailed way.

## References:

McCall Software Quality Model |Professionalqa.com. (s. f.). https://www.professionalqa.com/mc-call-software-quality-model

Berander, P., Damm, L., Eriksson, J., & Lundberg, L. (2005). Software Quality Attributes and Trade-offs Authors: ResearchGate. https://www.researchgate.net/publication/238700270_Software_quality_attributes_and_trade-offs_Authors#pf6

GeeksforGeeks. (2023, 11 septiembre). McCall s quality model. https://www.geeksforgeeks.org/mccalls-quality-model/

GeeksforGeeks. (2023a, julio 18). Boehm s Software Quality model. https://www.geeksforgeeks.org/boehms-software-quality-model/

Quality — the software engineering. (s. f.). https://dev.astrotech.io/sonarqube/quality-models.html





