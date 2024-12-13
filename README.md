**Architectural Smells and Their Impact on Software Evolution**

**Overview:**
The purpose of this study is to objectively assess how architectural smells affect software development, specifically in Python projects. Similar to code smells, architectural smells describe structural faults in software that can cause scalability concerns as the program develops, performance deterioration, and maintenance challenges. This study aims to identify and investigate these odors, evaluate their influence on software development, and offer methods for enhancing software quality.

Nine Python projects that span a range of sizes, levels of complexity, and domains—such as machine learning, mobile security, gaming, and cryptography—are included in the study. We find architectural smells like God Classes, Cyclic Dependencies, and Feature Envy by examining the coherence of the classes in these projects. We next look into how these smells affect software development, scalability, and maintainability.

**Selection of Python Projects**
**Project Size**: Small, medium, and large-scale projects.
**Community Involvement**: Varying levels of community engagement.
**Domain Diversity**: Cryptography, gaming, machine learning, and mobile security.
**Popularity & Activity**: Projects with recent activity and strong community support.

**Metrics & Tools for Architectural Smell Detection**
Architectural smells were identified using:

**Cohesion**: Measures class interdependence, with low cohesion indicating architectural smells.
Cohesion is calculated by using **cohesion -d pythonCodeDirectory/ | grep Total |sed 's/\s\{1,\}Total: \(.*\)\%$/\1/'**
**Code Smells (Radon)**: Detects cyclomatic complexity and code duplication.
Code Smell is calculated by using **radon raw .**
Tools used: Radon, Cohesion.


**Research Questions**
RQ1: Relationship between architectural smells and cohesiveness across project sizes.
RQ2: Impact of Radon-detected smells on project maintainability.
RQ3: How architectural smells evolve over time.
RQ4: Predict defect rates and code churn using cohesion and Radon data.


**Results & Discussion**
Preliminary findings suggest smaller projects exhibit higher frequencies of architectural smells like Feature Envy. The study also explores the impact of these smells on software evolution and maintainability.


