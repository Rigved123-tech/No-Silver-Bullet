# Homework 2 - No Silver Bullet

Review the material in Lectures 1 and 2 and read the [No Silver Bullet article](https://drive.google.com/file/d/1k_sbrhtbGwJsx71OApe3KXSNLffe-V6b/view?usp=drive_link). Based on that review and your own experience, answer the questions below.

- Define the term **essential difficulties** as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.

- Define the term **accidental difficulties** as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.

- List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.

- Define what Brooks means by a **silver bullet** and reconstruct his argument as to why he believes there is no silver bullet for software engineering. In the lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.

- In the lecture, we discussed the importance of the following concepts to software engineers: **abstractions**, **conversations**, **specification**, **translation**, and **iteration**. Define each of these concepts as they are related to software engineering and discuss their importance.

Use this assignment to practice your [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) skills. Once you're done, upload your responses to Canvas in a Markdown file with the **.md** file extension.

## Answers

### Q1. Essential Difficulties

The term **essential difficulties** as defined by Brooks are the difficulties present in the software itself, as compared to accidental difficulties, which are the difficulties present in the development stages of the software. Essential difficulties are existing difficulties in the software. They cannot be removed by updating the technology or development methods.

Brooks suggests that there will not be any revolutionary developments for improving software development. This is because the developments in software engineering will focus more on solving accidental difficulties, rather than essential difficulties. This would result in incremental developments, rather than revolutionary changes.

One example of essential difficulties is **complexity**. As developers keep adding more functionalities and details, the software keeps becoming more complex. This leads to facing several challenges in the designing, testing, and maintenance phases, such that even a small change in any of these phases can lead to more complications in the software.

### Q2. Accidental Difficulties

As defined by Brooks, **accidental difficulties** are the difficulties that arise in software development due to factors like developer tools used, hardware, programming languages used for development, etc. Accidental difficulties differ from essential difficulties because they occur due to faults in the development process and not the software itself, and can be eliminated by updating the technology, developer tools and environments, and changing programming languages.

The author further emphasizes that while there have been major developments to solve the accidental difficulties, like high-level programming languages, time-sharing, and integrated programming environments, which have helped in mostly eradicating accidental difficulties, there have been next to no advancements towards solving essential difficulties. This is the main reason why there has been no breakthrough (or no silver bullet) in revolutionizing software development altogether.

An example of accidental difficulties are **low-level languages**. Developers used to code in low-level, assembly languages that dealt directly with the system's memory units and registers. Later, languages like Ada were introduced. This was a high-level language that increased the efficiency of the code and reduced the number of errors. The code written in high-level languages was much more readable than the low-level one. Hence, the introduction of high-level programming languages solved accidental difficulties by improving the efficiency and readability of the written code.

### Q3. Four Essential Difficulties

The four essential difficulties listed are:

1. **Complexity**: Software systems are complex in nature. They differ in complexity from other human constructs like buildings, automobiles, because no two parts are alike. The larger the software, the more the complexities.

   **Examples**:
   - **Banking Software**: Banking software is required to daily handle multiple transactions, records, and fraud detections throughout multiple regions in the world, with each customer having different requirements.
   - **Self-driving cars**: The AI in self-driving cars has to handle numerous complexities in order to ensure the safety of the passengers, vehicles, and the traffic. These complexities include regulated speeding, braking, autonomous navigation systems, etc.

2. **Conformity**: Brooks states that software developers do not face complexities alone. Even physicists have to deal with highly complicated structures at the quantum level. But, even with these complexities, they continue to work hard believing there are hidden principles or theories. But these faiths are not applicable for software engineers. They have to work with arbitrary complexities, which may not have any reason. These complexities differ from interface to interface, protocol to protocol, but the software developed has to conform to all such requirements.

   **Example**:
   - A website developed should handle multiple user requirements, security protocols, operating systems (OS), and search engines. Hence, conformity must be practiced for software development.

3. **Changeability**: The author suggests that software is constantly subject to pressures for change, even though other commodities like buildings and automobiles are also subject to changes. But software is subject to the most amounts of changes because of the ease of doing so, as functions are malleable and the process is not so costly. The users pressure these changes the most as they test the existing functionalities and invent their new applications. Also, successful software survives beyond its normal life because of its usability.

   **Examples**:
   - **Mobile Applications**: Mobile apps have to constantly go through numerous updates for adding new features, ensuring all the time that they are compatible with the previous versions.
   - **Streaming Platforms**: Streaming platforms like Netflix, Amazon always have to keep updating their software for newer additions, updated recommendation systems, and payment gateways.

4. **Invisibility**: Software has no structure and visualizing tools. Indeed, geometric abstractions are useful: floor plans help architects and engineers to visualize spaces, diagrams of molecules give an idea about molecular structures. But software cannot be represented diagrammatically as it has no spatial occupation. One way to represent software conceptually is with graphs, to represent the flow of control, time sequence, etc. But, even with graphical representation, software remains mostly unvisualizable.

   **Examples**:
   - **Blockchains**: Blockchain networks are mostly decentralized, hence tracking failed transactions and debugging them becomes challenging.
   - **Operating Systems**: Operating systems have large-scale interactions within the registers, memory unit, and processors all the time, and are not visible to the users and developers, as they are quite complex to visualize and conceptualize.

### Q4. Silver Bullet

Brooks defined the term **silver bullet** as a single major breakthrough in software engineering, may it be technological, procedural, or methodological, that would revolutionize software engineering. Brooks then elaborates that he does not agree that there would be one major breakthrough in software engineering, rather it would see gradual progress.

Brooks constructs his argument for software engineering having no silver bullet by defining accidental and essential difficulties. Essential difficulties are the complexities that arise in the software itself, and not in the process of developing, the programming languages or environments used. Whereas, accidental difficulties constitute the external factors like programming language, environment, etc. Brooks says that developers focus on solving the accidental difficulties first, in order to update the technologies used in software engineering.

Computer science can be compared to chemistry, as it emphasizes more on the theoretical aspects, algorithms. Chemistry also emphasizes more on theory, including molecular theory and reactions.

On the other hand, software engineering can be compared to chemical engineering. Software engineering focuses on building large scalable software, just like chemical engineering is the application of chemistry concepts into industry-based processes.

### Q5. Key Concepts in Software Engineering

**Abstraction**, **conversations**, **specification**, **translation**, and **iteration** are fundamental aspects of software engineering.

- **Abstraction**: It is a practice in software engineering that requires developers to hide the irrelevant details of an application or a functionality. Abstraction is important in software development as it makes development easier by representing complicated structures in a more readable manner. It also makes the code more reusable as it can be accessed by others due to its readability.

- **Conversations**: Conversation is a mode of communication between the various stakeholders in a software development project, be it the users, developers, analysts, etc. Conversations involve discussions about the budget allocations, user requirements, decisions regarding the product design, and progress records. Conversations are essential as they facilitate understanding between the numerous stakeholders about the design process, requirements, and issues or escalations. This enables collaboration within the team members so they can tackle any difficulty efficiently.

- **Specification**: Specification refers to defining or specifying certain functionalities, or constraints that a system should follow. Specifications could either be functional (describing the action of a software), or non-functional (describing how well a software performs). Specifications provide developers a clear idea about what the software should do, making the development process easier and organized. It also provides grounds for testing, as the testing team is then aware of the scope of the software, what it can do and what it cannot.

- **Translation**: Translation involves converting high-level programming languages, design into low-level, executable code. It can also include converting the software code from one programming language to another. Translating software from one language to another enables cross-platform compatibility and can even optimize the runtime of the code during execution.

- **Iteration**: Iteration involves making constant improvements to a design during development, testing, and user-testing phases. The improvements are done gradually, in small portions. This allows the team to mitigate major failures in the design during testing, due to incremental improvisations. This allows developers to constantly update the errors then and there, based on user feedback.
