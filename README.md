# CSCI 5828 - Foundations of Software Engineering

## Homework 2 - No Silver Bullet

Review the material in Lectures 1 and 2 and read the *No Silver Bullet* article. Based on that review and your own experience, answer the questions below.

### Questions

1. Define the term *essential difficulties* as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.
2. Define the term *accidental difficulties* as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.
3. List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.
4. Define what Brooks means by a *silver bullet* and reconstruct his argument as to why he believes there is no silver bullet for software engineering. In the lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.
5. In the lecture, we discussed the importance of the following concepts to software engineers: *abstractions, conversations, specification, translation, and iteration.* Define each of these concepts as they are related to software engineering and discuss their importance.

Use this assignment to practice your Markdown skills. Once you're done, upload your responses to Canvas in a Markdown file with the `.md` file extension.

---

## Answers

### Q1. Essential Difficulties
The term *essential difficulties* as defined by Brooks are the difficulties present in the software itself, as compared to *accidental difficulties*, which are the difficulties present in the development stages of the software. Essential difficulties are existing difficulties in the software. They cannot be removed by updating the technology or development methods.

Brooks suggests that there will not be any revolutionary developments for improving software development. This is because the developments in software engineering will focus more on solving accidental difficulties rather than essential difficulties. This would result in incremental developments rather than revolutionary changes.

One example of essential difficulty is *complexity*. As developers keep adding more functionalities and details, the software keeps becoming more complex. This leads to several challenges in the designing, testing, and maintenance phases, such that even a small change in any of these phases can lead to more complications in the software.

### Q2. Accidental Difficulties
As defined by Brooks, *accidental difficulties* are the difficulties that arise in software development due to factors like developer tools used, hardware, programming languages used for development, etc. Accidental difficulties differ from essential difficulties because they occur due to faults in the development process and not the software itself, and can be eliminated by updating the technology, developer tools and environments, and changing programming languages.

The author further emphasizes that while there have been major developments to solve the accidental difficulties, like high-level programming languages, time-sharing, and integrated programming environments, which have helped in mostly eradicating accidental difficulties, there have been next to no advancements towards solving essential difficulties. This is the main reason why there has been no breakthrough (or *no silver bullet*) in revolutionizing software development altogether.

An example of accidental difficulty is low-level languages. Developers used to code in low-level, assembly languages that dealt directly with the system’s memory units and registers. Later, languages like Ada were introduced. This was a high-level language that increased the efficiency of the code and reduced the number of errors. The code written in high-level languages was much more readable than the low-level one. Hence, the introduction of high-level programming languages solved accidental difficulties by improving the efficiency and readability of the written code.

### Q3. Four Essential Difficulties

1. **Complexity**: Software systems are complex in nature. They differ in complexity from other human constructs like buildings and automobiles because no two parts are alike. The larger the software, the more the complexities.
   - **Examples**:
     - *Banking Software*: Banking software is required to handle multiple transactions, records, and fraud detections throughout multiple regions in the world, with each customer having different requirements.
     - *Self-driving cars*: The AI in self-driving cars has to handle numerous complexities to ensure the safety of passengers, vehicles, and traffic. These complexities include regulated speeding, braking, and autonomous navigation systems.

2. **Conformity**: Brooks states that software developers do not face complexities alone. Even physicists have to deal with highly complicated structures at the quantum level. However, software engineers have to work with arbitrary complexities that may not have any reason but must conform to requirements.
   - **Example**: A website developed should handle multiple user requirements, security protocols, operating systems (OS), and search engines.

3. **Changeability**: Software is constantly subject to changes due to user demands and ease of modifications.
   - **Examples**:
     - *Mobile Applications*: Mobile apps frequently go through numerous updates for adding new features while ensuring compatibility with previous versions.
     - *Streaming Platforms*: Platforms like Netflix and Amazon Prime update their software to improve recommendation systems, payment gateways, and new features.

4. **Invisibility**: Software has no inherent structure and lacks visual representation.
   - **Examples**:
     - *Blockchains*: Decentralized blockchain networks make tracking failed transactions and debugging them challenging.
     - *Operating Systems*: Operating systems interact on a large scale with registers, memory units, and processors, making them difficult to visualize.

### Q4. No Silver Bullet
Brooks defined the term *silver bullet* as a single major breakthrough in software engineering, whether technological, procedural, or methodological, that would revolutionize software engineering. However, Brooks argues that no such breakthrough will happen, and instead, progress will be gradual.

Brooks constructs his argument by distinguishing between accidental and essential difficulties. Essential difficulties are inherent in the software itself, while accidental difficulties arise from external factors like programming languages and environments. Developers tend to focus on solving accidental difficulties first, leading to technological advancements but no fundamental revolution.

- **Computer Science vs. Software Engineering**:
  - *Computer Science* is analogous to chemistry, emphasizing theoretical aspects and algorithms.
  - *Software Engineering* is akin to chemical engineering, applying concepts to build scalable systems.

### Q5. Fundamental Concepts

1. **Abstraction**: Hiding irrelevant details to simplify development and make code more readable and reusable.
2. **Conversations**: Communication between stakeholders, including users, developers, and analysts, ensuring collaboration and clarity in the development process.
3. **Specification**: Defining system functionalities and constraints, providing a roadmap for development and testing.
4. **Translation**: Converting high-level programming languages into low-level executable code or translating code between different languages for cross-platform compatibility.
5. **Iteration**: Continuous improvements throughout development, testing, and user feedback phases to enhance software reliability and usability.
