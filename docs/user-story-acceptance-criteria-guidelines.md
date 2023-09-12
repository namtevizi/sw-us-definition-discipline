# Definition of acceptance criteria
Now, we need to make sure that user stories are completed correctly and accommodate the client’s demands.

Acceptance criteria are the conditions that a software product must satisfy to be accepted by a user, customer, or, in the case of system-level functionality, the consuming system.

Acceptance criteria are a set of statements, each with a clear pass/fail result, that can be measured and specify both functional and non-functional requirements.

Writing acceptance criteria is important not only for establishing what the client expects of the product but for the development process. Naturally, different people see the same problem from different angles. Well-defined acceptance criteria provide a uniform view of the functionality you plan to implement.

Anyone should be able to walk up to a Scrum board, grab a product backlog item, read the acceptance criteria, and clearly see everything that needs to be completed for that particular item to be moved to the done column. Acceptance criteria tell you what needs to be done for a particular part of a product to be finished.

# Why do we need acceptance criteria?
## Defining boundaries
Acceptance criteria help the development team define the boundaries of a user story. They serve as a form of confirmation that the app is working as expected, which means the user story is complete.

## Reaching consensus
Acceptance criteria allow the development team to be on the same page as the client. They inform the development team about exactly what conditions must be met and ensure the client knows what to expect from the application.

## Streamlining acceptance testing
Acceptance criteria are the foundation of user story acceptance testing. Every acceptance criterion should be tested independently and have clear scenarios for success or failure.

## Planning and estimating
Acceptance criteria allow you to distribute user stories across tasks so they’re properly assessed and scheduled.

## Describing negative scenarios
Acceptance criteria may require the system to identify a weak password and prevent a user from continuing, for instance. Entering an incorrect password format is an example of a negative scenario in which a user enters incorrect data or behaves unexpectedly. Acceptance criteria identify these scenarios and explain how the system should respond to them.

# Who writes acceptance criteria?
Writing acceptance criteria helps to establish a common understanding between the product owner and the development team with regard to solving a customer’s problem or creating product capabilities. But who should write acceptance criteria? Since acceptance criteria relate to the client and the team, they should be written either by the client or a team member.

Business analysts should write all the acceptance criteria for user stories. Business analysts understand the client’s needs and what developers need to know to meet the project requirements.

Acceptance criteria are documented and confirmed before the start of the project, as the team and the client need to agree on what outcomes will meet the client’s requirements.

# Main challenges of writing acceptance criteria
The main challenge of writing good acceptance criteria is to keep a balance between detail and broadness. As they say, it’s hard to make something simple, so you need to keep your AC documentation concise and clear, but not restrictive.

Let’s talk about some common mistakes and their solutions, so you can come up with your own best way to write acceptance criteria.

Writing acceptance criteria as the development goes. You need to have AC documentation in place before the development process starts so that all the team members are on the same page regarding user needs. Developers need to decide on technical solutions based on the acceptance criteria, and they should be agreed upon beforehand.

Narrowing the AC down too much. Your acceptance criteria should be concrete, but not too narrow. Remember, that they only indicate the direction and not the means of getting there, so leave enough freedom for your developers to come up with the solution.

Going too deep into technical details. Write your acceptance criteria in simple language that’s commonly understood among your technical specialists, stakeholders, designers, and other members of your team.

Using passive voice and negative constructions. Write your AC as if a user was talking with you. For example, “I want to be able to find my destination on a map and check the working hours directly from there”. Avoid using “not” and write positive sentences wherever it’s possible.

# Examples of user stories with acceptance criteria
Now that you have a clear understanding of what user stories and acceptance criteria are, let’s take a look at some examples.

## Example 1
### User story
- As a user, I want to be able to register for the service so that I can start shopping online.

### Acceptance criteria
- Users can only submit a form by filling in all the required fields.
- The email the user provides must not be provided by free email service.
- Submissions from the same IP can only be made three times within 30 minutes.
- Users receive notification emails after successfully registering.

## Example 2
### User story
- As a user, I am able to access notification on my device immediately after receiving it.

### Acceptance criteria
- Swiping/tapping a notification takes the user directly to the message.
- View shows conversation — if the new message was a reply, then it’s displayed above the original.
- The message count is updated.
- A message is marked read after it’s displayed.

# Types of acceptance criteria
There are many types of selection criteria. However, the following types are the most popular.

## Scenario-oriented acceptance criteria.
This type of acceptance criteria is presented as a scenario and illustrates each criterion. Moreover, they are widely used by Agile teams because they allow them to fulfill requirements and use scripts for manual and automated acceptance testing.

## Rules-oriented acceptance criteria
In contrast to the scenario-based eligibility criteria, the rule-based eligibility criteria scenarios are presented as a list.

# 7 tips on writing good acceptance criteria
- Document it before the development process starts
- Don't make acceptance criteria too narrow
- Keep your acceptance criteria achievable
- Avoid too broad of acceptance criteria
- Avoid technical details
- Reach consensus
- Write testable acceptance criteria

Acceptance criteria aren’t easy to write. Despite the simple format, writing the text is a challenge. Here are seven tips to help you avoid common mistakes while writing acceptance criteria or reviewing criteria written by a member of your team.

## Document criteria before the development process starts
In this way, the team is more likely to catch all of the client’s needs in advance. Initially, it’s enough to set criteria for a small number of user stories to complete backlogs for two sprints. The documented acceptance criteria are then used by developers to plan the technical process.

## Don’t make acceptance criteria too narrow
Acceptance criteria that’s too specific leaves developers little room to maneuver. To avoid this, remember that acceptance criteria should be an expression of intent, not a final decision. Moreover, narrow acceptance criteria may not take into account all user actions.

## Keep your criteria achievable
Effective acceptance criteria define a reasonable minimum amount of functionality that you can provide. But if you keep describing all the little details, there’s a risk that your team will get stuck on hundreds of small tasks.

## Avoid too broad of acceptance criteria
Broad acceptance criteria make a user story vague. Effective acceptance criteria must outline the scope of work so that developers can properly plan and estimate their efforts.

## Avoid technical details
Acceptance criteria should be written in plain language. Your stakeholders and managers may not have technical backgrounds, so using plain language will make the criteria understandable for everyone.

## Reach consensus
The same problem can be solved in different ways by team members and stakeholders depending on their points of view. Make sure you communicate your acceptance criteria to stakeholders and team members and reach a mutual agreement.

## Write testable acceptance criteria
This will give testers the opportunity to ensure that all requirements are met and will allow developers to know if the user story is complete.

# How to write acceptance criteria
Here are five general rules that will help you solve problems with the wording of acceptance criteria. These rules will let you save valuable time and establish an understanding between the product owner and the development team.

## Rule #1: Avoid “not”
“Not” means “in no case,” and therefore no amount of time will be enough to verify compliance with such a condition. If you rewrite the requirement without using “not,” it will be clearer and, most importantly, verifiable.

### Example:
#### User Story

- Don’t: As a user, I do not want to have to enter my password every time I access my account.
- Do: As a user, I want my password to be remembered and automatically filled in so that I can access my account without re-entering my password.

#### Acceptance criteria

- Don’t: The system must not fail.
- Do: The system should have availability of no less than 90%.

#### Exception
You can use “not” in acceptance criteria to introduce a logical objection, such as “the login form should not be red.” In most cases, this will apply to non-functional requirements. In this example, we formulate a constraint that can be easily verified if the range of shades of red is clearly defined (for example, specified in RGB format).

## Rule #2: Use active voice
Active voice is when the subject in a sentence is the performer of the action. If the entity responsible for executing the action is not clearly indicated, it will be unclear who or what should perform the action, and it will be more difficult for you to verify whether a requirement is fulfilled.

### Example:
#### User story

- Don’t: As an online shopper, I want filters to be applied so that I can find what I want.
- Do: As a user, I want to apply search filters so that I can find items.

#### Acceptance criteria

- Don’t: The identity of the customer should be confirmed. (It is unclear who or what is responsible for confirming the identity of the customer.)
- Do: The Accounting_System should confirm the Customer_Indentity. (Note that the definitions of the terms “Accounting_System” and “Customer_Indentity” should be added to the glossary.)

## Rule #3: Avoid using pronouns (especially undefined ones)
Use nouns instead of pronouns when referring to items referenced in other requirements. Pronouns should be avoided because they may introduce ambiguity.

This is especially important when acceptance criteria are stored in requirement management tools (such as Jira) as separate statements that are not necessarily organized. Always use nouns instead of pronouns and you’ll avoid this problem.

### Example:
#### User story

- Don’t: As a site member, I want to share information about myself so that others can see it.
- Do: As a site member, I want to add a profile description so that others can learn about me.

#### Acceptance criteria

- Don’t: The controller should send the driver the itinerary for the day. It should be delivered at least 8 hours prior to the shift.
- Do: The Controller should send the Driver_Itinerary for the day to the Driver at least 8 hours prior to the Driver_Shift.

## Rule #4: Avoid conjunctions
Conjunctions are words and phrases such as “and,” “or,” “but,” and “as well as” that combine simple sentences into complex ones. Their use in requirements is usually a sign that a requirement can be broken down into several separate requirements.

### Example:
#### User story

- Don’t: As a UI designer, I want to create and view an issue so that I know what to test.
- Do: As a UI designer, I want to create an issue so that I know what to test. / As a UI designer, I want to view an issue so that I know what to test.

#### Acceptance criteria

- Don’t: The user should either be trusted or not trusted.
- Do: The Security_System should categorize each User as either Trusted or Not_Trusted.

#### Exception
“And,” “or,” and “not” can be used to describe logical conditions and add qualifiers.

## Rule #5: Avoid unattainable absolutes
An absolute (such as 100% availability) is unattainable. Think about how to check the indicator: will it be possible to prove that the level of system availability is exactly 100%? And even if such a system could be created, can you afford it?

Avoid the words “all,” “always,” and “never,” as checking such absolute requirements will require an infinite number of tests.

### Example:
#### User story

- Don’t: As a traveler, I want to know my precise location updated in real time so that I don’t get lost. (“Real time” can be interpreted in different ways. For example, it can be seen as an absolute (the absence of any delay), which cannot be achieved and which is not verifiable.)
- Do: As a traveler, I want to know my precise location, updated every second, so that I don’t get lost.

#### Acceptance criteria

- Don’t: The system should have 100% availability. (100% is an absolute that cannot be reached and cannot be verified.)
- Do: The system should have an availability of at least 98%.

# Quick summary of acceptance criteria
We hope this article has shed light on the best ways to write acceptance criteria and user stories. Here are the key takeaways:

- Acceptance criteria are the conditions a software product must satisfy to be accepted by a user, customer, or in the case of system-level functionality, the consuming system.
- Acceptance criteria should be documented and completed before the start of a project, as the team and the customer must agree on what results will meet the client’s requirements.
- Remember that acceptance criteria should be an expression of intent, not a final decision.
- Effective acceptance criteria define a reasonable minimum amount of functionality.
- Good acceptance criteria must outline the scope of work so developers can properly plan and estimate their efforts.
- Acceptance criteria should be written in plain language.
- Make sure you communicate your acceptance criteria to stakeholders and team members and reach a mutual agreement.
- While writing acceptance criteria, avoid using “not,” conjunctions, and unattainable absolutes. Formulate sentences using active voice.

# References
- https://www.mobindustry.net/blog/how-to-write-acceptance-criteria-examples-and-best-practices/
