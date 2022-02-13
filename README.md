# Advanced-System-Design

My primary goal here is to share the fundamentals of system design. How and why it is important.
How you can learn from the system which is developed in past by some of the great distributed system archietcts.

In this area, as of now covering major paper for distributed system.


Disclaimer:  The document shared here don't have any relation with my current organizational work. 
Also there is no intention for any commercial value of these documents.


Steps to be followed in System Design Interview:
#systemdesign #thumbrule
Sometime back , someone asked me to share thumb rule for proceeding in system design discussion, here are some standard rules 
[Assuming discussion time #45min ]
System Design, Distributed System discussion 
Steps to be followed:
1. First Section of your discussion is for understanding the Requirement.[07 min max]
- Explore and analyze the brief requirement shared from interviewer
-- List down some of the critical features of the system with your interviewer
-- Carefully try to list it. 
  @Note here, some time your interviewer interested in knowing that how well you are able to define the abstract requirement given to you.
-- Also, try to bring some of the requirement to handle the NFR(Quality Attribute) of the system
2. second Section - High Level building blocks for catering the requirement listed in section 1 [10 min max]
- without much bothering the scale, service communication, Security and Logging
- High level blocks, and interaction
- High Level service / API of your system to share the required features for your system users
- Post API list , you are in position for your system persistent requirement
-- So by now you are clear with your data and their persistent storage requirement.
-- Then, you are also clear about the database type, storage type requirement
-- For Ex: if your data structured or Non structured, do you need SQL DB or NoSQL DB etc.
-- Then you are also sure , how your independent services are going to interact or exchange the information?

3. Third Section - Work on Scale, Availability, Latency, Throughput, Fault Tolerant handling in your system?
[13 ~ 15 min max]
In this section you will focus on system non function requirement
- Identify the area where we required architectural choices?
- Handle the all area which is mentioned here in this point within your System design choices

4. System Integration, Deployment and Maintenance requirement [03 min max]
- How well and robust logging of your system designed?
- How you considered security of your overall system?

5. Future Enhancement or Work Area [02 min max]
- Additional feature (Good To have kind of feature)
- Handling required for technical debt of your system

6. Open for constructive feedback from your reviewer and handle them honestly [05 min]

"Keep Learning , Keep Progressing"

Thank you!



