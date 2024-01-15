---
title: "Notes on data analytics"
author: "Chiawei Wang"
date: "December 2023"
date-format: "MMMM YYYY"
format: html
page-layout: full
toc: true
toc-location: left
number-sections: true
---

`This document compiles information from Google Data Analytics for academic purposes`[^1]

[^1]: [Google Data Analytics](https://www.coursera.org/professional-certificates/google-data-analytics) includes over 180 hours of instruction and hundreds of practice-based assessments, which will help you simulate real-world data analytics scenarios that are critical for success in the workplace. The content is highly interactive and exclusively developed by Google employees with decades of experience in data analytics. Through a mix of videos, assessments, and hands-on labs, you'll get introduced to analysis tools and platforms and key analytical skills required for an entry-level job.

Data analytics is the collection, transformation and organization of data in order to draw conclusions, make predictions and drive informed decision making.

## Foundations of data analytics

### Thinking about analytical thinking

-   **Curiosity**: a desire to know more about something, asking the right questions
-   **Understanding context**: understanding where information fits into the **big picture**
-   **Having a technical mindset**: breaking big things into smaller steps
-   **Data design**: thinking about how to organize data and information
-   **Data strategy**: thinking about the people, processes, and tools used in data analysis

### Variations of the data life cycle

The data life cycle provides a generic or common framework for how data is managed.

1.  **Plan**: Decide what kind of data is needed, how it will be managed, and who will be responsible for it.
2.  **Capture**: Collect or bring in data from a variety of different sources.
3.  **Manage**: Care for and maintain the data. This includes determining how and where it is stored and the tools used to do so.
4.  **Analyze**: Use the data to solve problems, make decisions, and support business goals.
5.  **Archive**: Keep relevant data stored for long-term and future reference.
6.  **Destroy**: Remove data from storage and delete any shared copies of the data.

### Six phases of data analysis

Analysts use data-driven decision-making and follow a step-by-step process:

1.  **Ask** questions and define the problem
2.  **Prepare** data by collecting and storing the information
3.  **Process** data by cleaning and checking the information
4.  **Analyze** data to find patterns, relationships and trends
5.  **Share** data with your audience
6.  **Act** on the data and use the analysis results

![Data analysis process](https://github.com/x-square/visual-resources/blob/main/data-analysis-process.png?raw=true)

### Structured query language

SQL (structured query language) is designed for managing and manipulating relational databases. It is used for tasks such as querying data, updating records, inserting new data and deleting information from databases.

-   **SELECT** to choose the columns you want to return
-   **FROM** to choose the tables where the columns you want are located
-   **WHERE** to filter for certain information

![Example of SQL syntax](https://github.com/x-square/visual-resources/blob/main/sql-syntax.png?raw=true)

BigQuery is Google's fully managed, serverless data warehouse that works across clouds and enables scalable analysis. It supports querying using a dialect of SQL.

> [!tip]
> -   \% is used as a wildcard to match one or more characters
> -   \<\> means does not equal

### The power of data in business

Issue

:   A topic or subject to investigate

Question

:   Designer to discover information

Problem

:   An obstacle or complication that needs to be worked out

Business task

:   The question or problem data analysis answers for a business e.g. analyse weather data from the last decade to identify predictable patterns

Data-driven decision-making

:   Using facts to guide bushiness strategy

### Exploring your next job

![Decoding job description for data professionals](https://github.com/x-square/visual-resources/blob/main/data-job-description.png?raw=true)

## Ask questions to make data-driven decisions

### Solve problems with data

Data analytics is so much more than just plugging information into a platform to find insights. It is about solving problems. To get to the root of these problems and find practical solutions, there are lots of opportunities for creative thinking. No matter the problem, the first and most important step is understanding it.

![Analysts typically work with six problem types](https://github.com/x-square/visual-resources/blob/main/problem-types-six.png?raw=true)

Examples are summarized below for review:

#### Making predictions

A company that wants to know the best advertising method to bring in new customers is an example of a problem requiring analysts to make predictions. Analysts with data on location, type of media, and number of new customers acquired as a result of past ads can't guarantee future results, but they can help predict the best placement of advertising to reach the target audience.

#### Categorising things

An example of a problem requiring analysts to categorize things is a company's goal to improve customer satisfaction. Analysts might classify customer service calls based on certain keywords or scores. This could help identify top-performing customer service representatives or help correlate certain actions taken with higher customer satisfaction scores.

#### Spotting something unusual

A company that sells smart watches that help people monitor their health would be interested in designing their software to spot something unusual. Analysts who have analyzed aggregated health data can help product developers determine the right algorithms to spot and set off alarms when certain data doesn't trend normally.

#### Identifying themes

Designers often collaborate with analysts to analyze user interaction data. Analysts play a crucial role in categorising and identifying themes within the data, particularly in usability improvement projects. Themes, such as user beliefs, practices and needs, help researchers delve into specific aspects of the data, offering valuable insights for prioritising product features. While categorising involves assigning items to categories, identifying themes goes a step further, grouping categories into broader themes.

#### Discovering connections

A third-party logistics company working with another company to get shipments delivered to customers on time is a problem requiring analysts to discover connections. By analyzing the wait times at shipping hubs, analysts can determine the appropriate schedule changes to increase the number of on-time deliveries.

#### Finding patterns

Minimising downtime caused by machine failure is an example of a problem requiring analysts to find patterns in data. For example, by analyzing maintenance data, they might discover that most failures happen if regular maintenance is delayed by more than a 15-day window.

### SMART questions

Companies in lots of industries today are dealing with rapid change and rising uncertainty. Even well-established businesses are under pressure to keep up with what is new and figure out what is next. To do that, they need to ask questions. Asking the right questions can help spark the innovative ideas that so many businesses are hungry for these days.

No matter how much information you have or how advanced your tools are, your data won't tell you much if you don't start with the right questions. Think of it like a detective with tons of evidence who doesn't ask a key suspect about it.

![Examples of SMART questions](https://github.com/x-square/visual-resources/blob/main/smart-questions.png?raw=true)

### Data trials and triumphs

#### Coke launch failure

In 1985, New Coke was launched, replacing the classic Coke formula. The company had done taste tests with 200,000 people and found that test subjects preferred the taste of New Coke over Pepsi, which had become a tough competitor. Based on this data alone, classic Coke was taken off the market and replaced with New Coke. This was seen as the solution to take back the market share that had been lost to Pepsi.

But as it turns out, New Coke was a massive flop and the company ended up losing tens of millions of dollars. How could this have happened with data that seemed correct? It is because the data wasn't complete, which made it inaccurate. The data didn't consider how customers would feel about New Coke replacing classic Coke. The company's decision to retire classic Coke was a data-driven decision based on incomplete data.

#### Mars orbiter loss

In 1999, NASA lost the \$125 million Mars Climate Orbiter, even though it had good data. The spacecraft burned to pieces because of poor collaboration and communication. The Orbiter's navigation team was using the SI or metric system (newtons) for their force calculations, but the engineers who built the spacecraft used the English Engineering Units system (pounds) for force calculations.

No one realized a problem even existed until the Orbiter burst into flames in the Martian atmosphere. Later, a NASA review board investigating the root cause of the problem figured out that the issue was isolated to the software that controlled the thrusters. One program calculated the thrusters' force in pounds; another program looking at the data assumed it was in newtons. The software controllers were making data-driven decisions to adjust the thrust based on 100% accurate data, but these decisions were wrong because of inaccurate assumptions when interpreting it. A conversion of the data from one system of measurement to the other could have prevented the loss. Note that the data-informed approach can be considered in this case.

> [!tip]
> -   **Data-inspired** approach (subjective) involves drawing inspiration and insights from data but doesn't necessarily dictate decisions. It acknowledges that data can provide valuable perspectives and ideas, serving as a source of inspiration for further exploration or consideration.
> -   **Data-informed** approach (inter-subjective) plays a more significant role in decision-making. Decisions are influenced by data, which is used to guide and support the decision-making process. However, other factors, such as experience or intuition, may still be taken into account.
> -   **Data-driven** approach (objective) places data at the forefront of decision-making. Decisions are primarily based on the analysis and interpretation of data. This approach emphasizes using data to measure outcomes, predict trends, and guide strategic choices. It often involves relying heavily on quantitative evidence to inform decisions.
  
### Qualitative and quantitative data in business

Qualitative data

:   Subjective or explanatory measures of qualities and characteristics

Quantitative data

:   Specific and objective measures of numerical facts

We can take a closer look at the data types and data collection tools. Imagine that you are a data analyst for a chain of movie theaters. Your manager wants you to track trends in:

-   Movie attendance over time
-   Profitability of the concession stand
-   Evening audience preferences

In our scenario, we assume quantitative data already exists to monitor all three trends. Since we know that the movie theater is planning to raise ticket prices for evening showtimes in a few months, we will also include a question in the survey to get an idea of customers' price sensitivity.

Your final online survey might include these questions for qualitative data:

-   What went into your decision to see a movie in our theater today? (movie attendance)
-   What do you think about the quality and value of your purchases at the concession stand? (concession stand profitability)
-   Which showtime do you prefer, 8:00 PM or 8:30 PM, and why do you prefer that time? (evening movie-goer preferences)
-   Under what circumstances would you choose a matinee over a night time showing? (ticket price increase)

Data analysts will generally use both types of data in their work. Usually, qualitative data can help analysts better understand their quantitative data by providing a reason or more thorough explanation. In other words, quantitative data generally gives you the what, and qualitative data generally gives you the why. By using both quantitative and qualitative data, you can learn when people like to go to the movies and why they chose the theater. Maybe they really like the reclining chairs, so your manager can purchase more recliners. Maybe the theater is the only one that serves root beer. Maybe a later show time gives them more time to drive to the theater from where popular restaurants are located. Maybe they go to matinees because they have kids and want to save money. You wouldn't have discovered this information by analyzing only the quantitative data for attendance, profit, and showtimes.

### Connecting the data dots

When thinking about the benefits and challenges of big data, it helps to think about the four Vs:

| Volume         | Variety                 | Velocity                           | Veracity                            |
|------------------|------------------|------------------|-------------------|
| Amount of data | Different kinds of data | How fast the data can be processed | Quality and reliability of the data |

: Four Vs for big data

### Structured thinking and scope of work

Structured thinking is the process of recognizing the currect problem or situation, organizing available information, revealing gaps and opportunities, and identifying the options.

Scope of work is an agreed-upon outline of the work you're going to perform on a project:

-   **Deliverables** are items or tasks you will complete before you can finish the project.
-   **Timelines** include due dates for when deliverables, milestones, and or reports are due.
-   **Milestones** are significant tasks you will confirm along your timeline to help everyone know the project is on track.
-   **Reports** notify everyone as you finalize deliverables and meet milestones.

![Example of scope of work](https://github.com/x-square/visual-resources/blob/main/scope-of-work.png?raw=true)

![Example of scope of work in the spreadsheet](https://github.com/x-square/visual-resources/blob/main/scope-of-work-spreadsheet.png?raw=true)

### Importance of context

Context is the condition in which something exists or happens. Context is important in data analytics because it helps us sift through huge amounts of disorganized data and turn it into something meaningful. The fact is, data has little value if it is not paired with context.

Context can turn raw data into meaningful information. It is very important for data analysts to contextualize their data. This means giving the data perspective by defining it. To do this, you need to identify:

-   **Who** the person or organization that created, collected and or funded the data collection
-   **What** the things in the world that data could have an impact on
-   **Where** the origin of the data
-   **When** the time when the data was created or collected
-   **Why** the motivation behind the creation or collection
-   **How** the method used to create or collect it

Here are some questions to help you get started:

-   What is the problem?
-   Can it be solved with data? If so, what data?
-   Where is this data? Does it exist, or do you need to collect it?
-   Are you using private data that someone will need to give you access to, or publicly available data?
-   Who are the relevant sponsors and stakeholders for this project? Who is involved, and how?
-   What are the boundaries for your project? What do you consider in-scope? What do you consider out-of-scope?
-   Is there any other information you think is relevant to the project?
-   Is there any information you need or questions you need answered before you can begin?

### Working with stakeholders

Your data analysis project should answer the business task and create opportunities for data-driven decision-making. That's why it is so important to focus on project stakeholders. As a data analyst, it is your responsibility to understand and manage your stakeholders' expectations while keeping the project goals front and center.

You might remember that stakeholders are people who have invested time, interest, and resources into the projects that you are working on. This can be a pretty broad group, and your project stakeholders may change from project to project. But there are three common stakeholder groups that you might find yourself working with: the executive team, the customer-facing team, and the data science team.

Let's get to know more about the different stakeholders and their goals. Then we'll learn some tips for communicating with them effectively.

#### Executive team

The executive team provides strategic and operational leadership to the company. They set goals, develop strategy, and make sure that strategy is executed effectively. The executive team might include vice presidents, the chief marketing officer, and senior-level professionals who help plan and direct the company's work. These stakeholders think about decisions at a very high level and they are looking for the headline news about your project first. They are less interested in the details. Time is very limited with them, so make the most of it by leading your presentations with the answers to their questions. You can keep the more detailed information handy in your presentation appendix or your project documentation for them to dig into when they have more time.

For example, you might find yourself working with the vice president of human resources on an analysis project to understand the rate of employee absences. A marketing director might look to you for competitive analyses. Part of your job will be balancing what information they will need to make informed decisions with their busy schedule.

But you don't have to tackle that by yourself. Your project manager will be overseeing the progress of the entire team, and you will be giving them more regular updates than someone like the vice president of HR. They are able to give you what you need to move forward on a project, including getting approvals from the busy executive team. Working closely with your project manager can help you pinpoint the needs of the executive stakeholders for your project, so don't be afraid to ask them for guidance.

#### Customer-facing team

The customer-facing team includes anyone in an organization who has some level of interaction with customers and potential customers. Typically they compile information, set expectations, and communicate customer feedback to other parts of the internal organization. These stakeholders have their own objectives and may come to you with specific asks. It is important to let the data tell the story and not be swayed by asks from your stakeholders to find certain patterns that might not exist.

Let's say a customer-facing team is working with you to build a new version of a company's most popular product. Part of your work might involve collecting and sharing data about consumers' buying behavior to help inform product features. Here, you want to be sure that your analysis and presentation focuses on what is actually in the data, not on what your stakeholders hope to find.

#### Data science team

Organizing data within a company takes teamwork. There's a good chance you'll find yourself working with other data analysts, data scientists, and data engineers. For example, maybe you team up with a company's data science team to work on boosting company engagement to lower rates of employee turnover. In that case, you might look into the data on employee productivity, while another analyst looks at hiring data. Then you share those findings with the data scientist on your team, who uses them to predict how new processes could boost employee productivity and engagement. When you share what you found in your individual analyses, you uncover the bigger story. A big part of your job will be collaborating with other data team members to find new angles of the data to explore.

Here's a view of how different roles on a typical data science team support different functions:

![Data science team supports different functions](https://github.com/x-square/visual-resources/blob/main/data-science-cross-functions.png?raw=true)

#### Working effectively with stakeholders

When you're working with each group of stakeholders from the executive team, to the customer-facing team, to the data science team, you'll often have to go beyond the data. Use the following tips to communicate clearly, establish trust, and deliver your findings across groups.

Discuss goals

:   Stakeholder requests are often tied to a bigger project or goal. When they ask you for something, take the opportunity to learn more. Start a discussion. Ask about the kind of results the stakeholder wants. Sometimes, a quick chat about goals can help set expectations and plan the next steps.

Feel empowered to say no

:   When faced with urgent data analysis requests from a marketing director for a **high-priority project**, assess feasibility and push back if necessary. Stakeholders may not fully understand the time and effort involved, so clarify expectations by asking about their goals. Be confident in saying no if you can't meet the timeline, and guide them towards more realistic options. Prioritize effectively, communicate limitations, and empower stakeholders to reset expectations based on achievable timelines. Feel empowered to say **no**, but provide context for better understanding.

Plan for the unexpected

:   Before you start a project, make a list of potential roadblocks. Then, when you discuss project expectations and timelines with your stakeholders, give yourself some extra time for problem-solving at each stage of the process.

Know your project

:   Keep track of your discussions about the project over email or reports, and be ready to answer questions about how certain aspects are important for your organization. Get to know how your project connects to the rest of the company and get involved in providing the most insight possible. If you have a good understanding about why you are doing an analysis, it can help you connect your work with other goals and be more effective at solving larger problems.

Start with words and visuals

:   It is common for data analysts and stakeholders to interpret things in different ways while assuming the other is on the same page. This **illusion of agreement** shown as follows has been historically identified as a cause of projects going back-and-forth a number of times before a direction is finally nailed down. To help avoid this, start with a description and a quick visual of what you are trying to convey. Stakeholders have many points of view and may prefer to absorb information in words or pictures. Work with them to make changes and improvements from there. The faster everyone agrees, the faster you can perform the first analysis to test the usefulness of the project, measure the feedback, learn from the data, and implement changes.

Communicate often

:   Your stakeholders will want regular updates on your projects. Share notes about project milestones, setbacks, and changes. Then use your notes to create a shareable report. Another great resource to use is a change-log, which is a tool that will be explored further throughout the program. For now, just know that a is a file containing a chronologically ordered list of modifications made to a project. Depending on the way you set it up, stakeholders can even pop in and view updates whenever they want.

![Example of illusion of agreement via Typical Project Life](https://github.com/x-square/visual-resources/blob/main/typical-project-life.png?raw=true)

### Data scenarios and responses

When you communicate your analysis and recommendations as a data analyst, it's vital to keep your audience in mind. :

-   Who is our audience?
    -   Kiri, Product Development Project Manager
-   What do they already know?
    -   Kiri received updates about our project from its planning stages, including the most recent project report, sent two weeks ago.
-   What do they need to know?
    -   Kiri needs an update on the analysis project’s progress and needs to know that the executive team approved changes to the data and timeline. You know that adding a new variable to the analysis will impact the current project timeline. Kiri will need to change the project’s milestones and completion date.
-   How can we best communicate what they need to know?
    -   You can start by sending an email update to Kiri with the latest timeline for the project, but a meeting might be necessary if she wants to talk through her concerns about missing a deadline.

![Sample of updated timeline email](https://github.com/x-square/visual-resources/blob/main/email-timelime.png?raw=true)

![Sample of project follow-up email](https://github.com/x-square/visual-resources/blob/main/email-follow-up.png?raw=true)

### Limitations of data

Data is powerful, but it has its limitations. Has someone's personal opinion found its way into the numbers? Is your data telling the whole story? Part of being a great data analyst is knowing the limits of data and planning for them.

-   Case of incomplete or non-existent data
    -   If your data is incomplete or missing, you may realize during analysis that you lack sufficient information for a conclusion or may be addressing a different issue. For instance, if seeking employees with a specific certificate, but certification records only cover the last two years, you can still use the data, but highlight the analysis limitations. You could explore alternative data sources, like contacting the training company, but transparently communicate the incomplete dataset until additional data is obtained.
-   Don't miss misaligned data
    -   When collecting data from various teams and existing spreadsheets, be aware that different teams may apply distinct business rules. For instance, one team may define a metric based on all trainees who registered, while another team counts only those who completed the program. Standardizing measurement approaches early on ensures consistency, reliability, and accuracy in the data. This practice facilitates meaningful and insightful comparisons between teams.
-   Deal with dirty data
    -   Dirty data, containing errors, can result in productivity loss, unnecessary spending, and poor decision-making. Data cleaning, the process of fixing or removing incorrect, corrupted, and incomplete data, helps prevent these issues. Learning how to clean data is crucial to avoid data disasters, and this will be covered later in the training.
-   Tell a clear story
    -   Compare the same types of data
    -   Visualize with care
    -   Leave out needless graphs
    -   Test for statistical significance
    -   Pay attention to sample size
-   Be the judge
    -   In organizations, data analysts play a key role in making informed judgments. Understanding data limitations enables making decisions based on accurate information. Incomplete or uncleaned data can be misleading. Ensure data completeness and consistency by cleaning it before analysis, saving time and effort.

### Leading great meetings

![Example of meeting agenda](https://github.com/x-square/visual-resources/blob/main/meeting-agenda.png?raw=true)

## Prepare data for exploration

### Selecting the right data

![How to collect the right data?](https://github.com/x-square/visual-resources/blob/main/data-collection-considerations.png?raw=true)

### Data modelling levels and techniques

Data modelling is the process of creating diagrams that visually represent how data is organized and structured. These visual representations are called data models. You can think of data modelling as a blueprint of a house. At any point, there might be electricians, carpenters, and plumbers using that blueprint. Each one of these builders has a different relationship to the blueprint, but they all need it to understand the overall structure of the house. Data models are similar. Different users might have different data needs, but the data model gives them an understanding of the structure as a whole.

There are a lot of approaches when it comes to developing data models, but two common methods are the **Entity Relationship Diagram** (ERD) and the **Unified Modelling Language** (UML) diagram. ERDs are a visual way to understand the relationship between entities in the data model. UML diagrams are very detailed diagrams that describe the structure of a system by showing the system's entities, attributes, operations, and their relationships. As a junior data analyst, you will need to understand that there are different data modelling techniques, but in practice, you will probably be using your organization's existing technique.

![Example of ERD](https://github.com/x-square/visual-resources/blob/main/diagram-erd.png?raw=true)

![Example of UML](https://github.com/x-square/visual-resources/blob/main/diagram-uml.png?raw=true)

### Understanding Boolean logic

Data analysts use Boolean statements to do a wide range of data analysis tasks, such as creating queries for searches and checking for conditions when writing programming code.

Imagine you are shopping for shoes, and are considering certain preferences:

-   You will buy the shoes only if they are pink **and** grey
-   You will buy the shoes if they are entirely pink **or** entirely grey, **or** if they are pink and grey
-   You will buy the shoes if they are grey, but **not** if they have any pink

### Databases in data analytics

Databases enable analysts to manipulate, store, and process data. This helps them search through data a lot more efficiently to get the best insights.

#### Relational databases

A **relational** database is a database that contains a series of tables that can be connected to show relationships. Basically, they allow data analysts to organize and link data based on what the data has in common.

In a **non-relational** table, you will find all of the possible variables you might be interested in analyzing all grouped together. This can make it really hard to sort through. This is one reason why relational databases are so common in data analysis. They simplify a lot of analysis processes and make data easier to find and use across an entire database.

#### Key to relational databases

Tables in a relational database are connected by the fields they have in common. You might remember learning about primary and foreign keys before. As a quick refresher, a **primary key** is an identifier that references a column in which each value is unique. In other words, it's a column of a table that is used to uniquely identify each record within that table. The value assigned to the primary key in a particular row must be unique within the entire table. For example, if customer_id is the primary key for the customer table, no two customers will ever have the same customer_id.

By contrast, a **foreign key** is a field within a table that is a primary key in another table. A table can have only one primary key, but it can have multiple foreign keys. These keys are what create the relationships between tables in a relational database, which helps organize and connect data across multiple tables in the database.

Some tables don't require a primary key. For example, a revenue table can have multiple foreign keys and not have a primary key. A primary key may also be constructed using multiple columns of a table. This type of primary key is called a composite key. For example, if customer_id and location_id are two columns of a **composite key** for a customer table, the values assigned to those fields in any given row must be unique within the entire table.

![Example of database keys](https://github.com/x-square/visual-resources/blob/main/database-keys.png?raw=true)

## Process data from dirty to clean

### Well-aligned objectives and data

You can gain powerful insights and make accurate conclusions when data is well-aligned to business objectives. As a data analyst, alignment is something you will need to judge. Good alignment means that the data is relevant and can help you solve a business problem or determine a course of action to achieve a given business objective.

#### Business case A

Imagine account managers at Impress Me, an online content subscription service, want to know how soon users view content after their subscriptions are activated.

To start off, the data analyst verifies that the data exported to spreadsheets is clean and confirms that the data needed (when users access content) is available. Knowing this, the analyst decides there is good alignment of the data to the business objective. All that is missing is figuring out exactly how long it takes each user to view content after their subscription has been activated.

![Example of relevant data in spreadsheet](https://github.com/x-square/visual-resources/blob/main/data-spreadsheet.png?raw=true)

#### Business case B

Imagine Cloud Gate, a software company, recently hosted a series of public webinars as free product introductions. The data analyst and webinar program manager want to identify companies that had five or more people attend these sessions. They want to give this list of companies to sales managers who can follow up for potential sales.

| **Name**          | **Research methods** | **Additional information**                   |
|-------------------|-------------------|----------------------------------|
| **Email Address** | `xxxxx@company.com`  | Required information attendees had to submit |
| **Company**       | \<company name\>     | Optional information attendees could provide |

: Webinar attendance data includes the fields

The webinar attendance data seems to align with the business objective. But the data analyst and program manager decide that some **data cleaning** is needed before the analysis. They think data cleaning is required because:

-   The company name wasn't a mandatory field. If the company name is blank, it might be found from the email address. For example, if the email address is `username@google.com`, the company field could be filled in with Google for the data analysis. This data cleaning step assumes that people with company-assigned email addresses attended a webinar for business purposes.
-   Attendees could enter any name. Since attendance across a series of webinars is being looked at, they need to validate names against unique email addresses. For example, if Joe Cox attended two webinars but signed in as Joe Cox for one and Joseph Cox for the other, he would be counted as two different people. To prevent this, they need to check his unique email address to determine that he was the same person. After the validation, Joseph Cox could be changed to Joe Cox to match the other instance.

#### Business case C

Imagine an after-school tutoring company, A+ Education, wants to know if there is a minimum number of tutoring hours needed before students have at least a 10% improvement in their assessment scores.

The data analyst thinks there is good alignment between the data available and the business objective because:

-   Students log in and out of a system for each tutoring session, and the number of hours is tracked
-   Assessment scores are regularly recorded

After looking at the data, the data analyst discovers that there are **other variables** to consider. Some students had consistent weekly sessions while other students had scheduled sessions more randomly even though their total number of tutoring hours was the same. The data doesn't align as well with the original business objective as first thought, so the analyst adds a **data constraint** to focus only on the students with consistent weekly sessions. This modification helps to get a more accurate picture about the enrolment time needed to achieve a 10% improvement in assessment scores.

### What to do when you find an issue with your data

When you are getting ready for data analysis, you might realize you don't have the data you need or you don't have enough of it. In some cases, you can use what is known as proxy data in place of the real data. Think of it like substituting oil for butter in a recipe when you don't have butter. In other cases, there is no reasonable substitute and your only option is to collect more data.

![Decision tree of how to deal with data errors or not enough data](https://github.com/x-square/visual-resources/blob/main/data-errors-not-enough.png?raw=true)

### Calculating sample size

| **Terminology**              | **Definitions**                                                                                                                                                                                                                                                                                                                                                                      |
|--------------------------|----------------------------------------------|
| **Population**               | The entire group that you are interested in for your study. For example, if you are surveying people in your company, the population would be all the employees in your company.                                                                                                                                                                                                     |
| **Sample**                   | A subset of your population. Just like a food sample, it is called a sample because it is only a taste. So if your company is too large to survey every individual, you can survey a representative sample of your population.                                                                                                                                                       |
| **Margin of error**          | Since a sample is used to represent a population, the sample's results are expected to differ from what the result would have been if you had surveyed the entire population. This difference is called the margin of error. The smaller the margin of error, the closer the results of the sample are to what the result would have been if you had surveyed the entire population. |
| **Confidence level**         | How confident you are in the survey results. For example, a 95% confidence level means that if you were to run the same survey 100 times, you would get similar results 95 of those 100 times. Confidence level is targeted before you start your study because it will affect how big your margin of error is at the end of your study.                                             |
| **Confidence interval**      | The range of possible values that the population's result would be at the confidence level of the study. This range is the sample result plus and minus the margin of error. Briefly, `confidence interval = sample mean ± margin of error`.                                                                                                                                         |
| **Statistical significance** | The determination of whether your result could be due to random chance or not. The greater the significance, the less due to chance.                                                                                                                                                                                                                                                 |

: Statistical terms and definitions

When figuring out a sample size, here are things to keep in mind:

-   Don't use a sample size less than 30. It has been statistically proven that 30 is the smallest sample size where an average result of a sample starts to represent the average result of a population.
    -   This recommendation is based on the **Central Limit Theorem** in the field of probability and statistics. As sample size increases, the results more closely resemble the normal (bell-shaped) distribution from a large number of samples.
    -   A sample of 30 is the smallest sample size for which the Central Limit Theorem is still valid. Researchers who rely on **regression analysis** – statistical methods to determine the relationships between controlled and dependent variables – also prefer a minimum sample of 30.
-   The confidence level most commonly used is 95%, but 90% can work in some cases.
-   Increase the sample size to meet specific needs of your project
    -   For a higher confidence level, use a larger sample size
    -   To decrease the margin of error, use a larger sample size
    -   For greater statistical significance, use a larger sample size

### All about margin of error

#### Margin of error in baseball

Imagine you are playing baseball and that you are up at bat. The crowd is roaring, and you are getting ready to try to hit the ball. The pitcher delivers a fast ball travelling about 90-95mph, which takes about 400 milliseconds (ms) to reach the catcher's glove. You swing and miss the first pitch because your timing was a little off. You wonder if you should have swung slightly earlier or slightly later to hit a home run. That time difference can be considered the margin of error, and it tells us how close or far your timing was from the average home run swing.

#### Margin of error in marketing

For example, suppose you are conducting an A/B test to compare the effectiveness of two different email subject lines to entice people to open the email. You find that subject line A: `Special offer just for you` resulted in a 5% open rate compared to subject line B: `Don't miss this opportunity` at 3%.

Does that mean subject line A is better than subject line B? It depends on your margin of error. If the margin of error was 2%, then subject line A's actual open rate or confidence interval is somewhere between 3% and 7%. Since the lower end of the interval overlaps with subject line B's results at 3%, you can't conclude that there is a statistically significant difference between subject line A and B. Examining the margin of error is important when making conclusions based on your test results.

### What is dirty data?

![Types of dirty data](https://github.com/x-square/visual-resources/blob/main/data-dirty.png?raw=true)

#### Business impact of dirty data

Here are a few impacts cited for certain industries from a previous search:

-   [Banking](https://sloanreview.mit.edu/article/seizing-opportunity-in-data-quality): Inaccuracies cost companies between 15% and 25% of revenue
-   [Digital commerce](https://www.demandgen.com/dirty-data-what-is-it-costing-you): Up to 25% of B2B database contacts contain inaccuracies
-   [Marketing and sales](https://www.dqglobal.com/blog/why-bad-data-is-wasting-your-marketing-efforts): 99% of companies are actively tackling data quality in some way
-   [Healthcare](https://www.techtarget.com/searchhealthit): Duplicate records can be 10% and even up to 20% of a hospital's electronic health records

### Common data-cleaning pitfalls\]

![Errors you might come across while cleaning your data](https://github.com/x-square/images/blob/main/data-cleaning-errors.png?raw=true)

### Workflow automation

| **Task**                                      | **Can it be automated?** | **Why?**                                                                                                                                                                                                                                                                                                          |
|-------------------|-------------------|----------------------------------|
| Communicating with your team and stakeholders | No                       | Communication is key to understanding the needs of your team and stakeholders as you complete the tasks you are working on. There is no replacement for person-to-person communications.                                                                                                                          |
| Presenting your findings                      | No                       | Presenting your data is a big part of your job as a data analyst. Making data accessible and understandable to stakeholders and creating data visualizations can't be automated for the same reasons that communications can't be automated.                                                                      |
| Preparing and cleaning data                   | Partially                | Some tasks in data preparation and cleaning can be automated by setting up specific processes, like using a programming script to automatically detect missing values.                                                                                                                                            |
| Data exploration                              | Partially                | Sometimes the best way to understand data is to see it. Luckily, there are plenty of tools available that can help automate the process of visualising data. These tools can speed up the process of visualizing and understanding the data, but the exploration itself still needs to be done by a data analyst. |
| Modelling the data                            | Yes                      | Data modelling is a difficult process that involves lots of different factors Luckily there are tools that can completely automate the different stages.                                                                                                                                                          |

: What can be automated?

### Workflow automation

Engineers use **engineering change orders** to keep track of new product design details and proposed changes to existing products. Writers use document revision histories to keep track of changes to document flow and edits. And data analysts use changelogs to keep track of data transformation and cleaning.

![Example of changelogs](https://github.com/x-square/visual-resources/blob/main/changelogs.png?raw=true)

### Adding softs skills to your resume

-   Analyze your previous work experience and find opportunities to insert a soft skill. For example, if you worked in a restaurant, you could emphasize your communication and adaptability skills that you utilized to effectively function during peak hours.
-   Call attention to your problem-solving, presentation, research, and communication skills in previous projects or relevant coursework.
-   Add a mix of soft and professional skills in the skills or summary section of your resume.

![Common soft skills you will find in an entry-level data analyst resume](https://github.com/x-square/visual-resources/blob/main/data-analyst-soft-skills.png?raw=true)

## Analyze data to answer questions

### Keeping data organized with sorting and filters

The organization of datasets is really important for data analysts. Most of the datasets you will use will be organized as tables. Tables are helpful because they let you manipulate your data and categorize it. Having distinct categories and classifications lets you focus on, and differentiate between, your data quickly and easily.

Data analysts also need to format and adjust data when performing an analysis. **Sorting** and **filtering** are two ways you can keep things organized when you format and adjust data to work with it. For example, a filter can help you find errors or outliers so you can fix or flag them before your analysis. **Outliers** are data points that are very different from similarly collected data and might not be reliable values. The benefit of filtering the data is that after you fix errors or identify outliers, you can remove the filter and return the data to its original organization.

Sorting is when you arrange data into a meaningful order to make it easier to understand, analyze, and visualize. It ranks your data based on a specific metric you choose. You can sort data in spreadsheets, SQL databases (when your dataset is too large for spreadsheets), and tables in documents.

Filtering is used when you are only interested in seeing data that meets a specific criteria, and hiding the rest. Filtering is really useful when you have lots of data. You can save time by zeroing in on the data that is really important or the data that has bugs or errors. Most spreadsheets and SQL databases allow you to filter your data in a variety of ways. Filtering gives you the ability to find what you are looking for without too much effor

### Converting data in spreadsheets

As a data analyst, there are lots of scenarios when you might need to convert data in a spreadsheet:

-   [String to date](https://www.ablebits.com/office-addins-blog/excel-convert-text-date/#:~:text=Excel%20DATEVALUE%20function%20%2D%20change%20text,Excel%20recognizes%20as%20a%20date.&text=So%2C%20the%20formula%20to%20convert,stored%20as%20a%20text%20string.)
-   [String to numbers](https://www.ablebits.com/office-addins-blog/excel-convert-text-to-number/)
-   [Combining columns](https://support.microsoft.com/en-us/office/combine-text-from-two-or-more-cells-into-one-cell-81ba0946-ce78-42ed-b3c3-21340eb164a6)
-   [Number to percentage](https://support.microsoft.com/en-us/office/format-numbers-as-percentages-de49167b-d603-4450-bcaa-31fba6c7b6b4)

> [!tip]
> Keep in mind that you may have lots of columns of data that require different formats. Consistency is key, and best practice is to make sure an entire column has the same format.

### Types of data validation

As a junior data analyst, you might not perform all of these validations. But you could ask if and how the data was validated before you begin working with a dataset. Data validation helps to ensure the integrity of data. It also gives you confidence that the data you are using is clean.

-   Data type
    -   **Purpose**: Check that the data matches the data type defined for a field.
    -   **Example**: Data values for school grades 1-12 must be a numeric data type.
    -   **Limitations**: The data value 13 would pass the data type validation but would be an unacceptable value. For this case, data range validation is also needed.
-   Data range
    -   **Purpose**: Check that the data falls within an acceptable range of values defined for the field.
    -   **Example**: Data values for school grades should be values between 1 and 12.
    -   **Limitations**: The data value 11.5 would be in the data range and would also pass as a numeric data type. But, it would be unacceptable because there aren't half grades. For this case, data constraint validation is also needed.
-   Data constraints
    -   **Purpose**: Check that the data meets certain conditions or criteria for a field. This includes the type of data entered as well as other attributes of the field, such as number of characters.
    -   **Example**: Data values for school grades 1-12 must be whole numbers.
    -   **Limitations**: The data value 13 is a whole number and would pass the content constraint validation. But, it would be unacceptable since 13 isn't a recognized school grade. For this case, data range validation is also needed.
-   Data consistency
    -   **Purpose**: Check that the data makes sense in the context of other related data.
    -   **Example**: Data values for product shipping dates can't be earlier than product production dates.
    -   **Limitations**: Data might be consistent but still incorrect or inaccurate. A shipping date could be later than a production date and still be wrong.
-   Data structure
    -   **Purpose**: Check that the data follows or conforms to a set structure.
    -   **Example**: Web pages must follow a prescribed structure to be displayed properly.
    -   **Limitations**: A data structure might be correct with the data still incorrect or inaccurate. Content on a web page could be displayed properly and still contain the wrong information.
-   Code validation
    -   **Purpose:** Check that the application code systematically performs any of the previously mentioned validations during user data input.
    -   **Example:** Common problems discovered during code validation include more than one data type allowed, data range checking not done, or ending of text strings not well defined.
    -   **Limitations:** Code validation might not validate all possible variations with data input.

## Share data through the art of visualization

### Effective data visualizations

A data visualization, sometimes referred to as a data viz, allows analysts to properly interpret data. A good way to think of data visualization is that it can be the difference between utter confusion and really grasping an issue. Creating effective data visualizations is a complex task; there is a lot of advice out there, and it can be difficult to grasp it all. In this reading, you are going to learn some tips and tricks for creating effective data visualizations. First, you'll review two frameworks that are useful for thinking about how you can organize the information in your visualization. Second, you'll explore pre-attentive attributes and how they can be used to affect the way people think about your visualizations. From there, you'll do a quick review of the design principles that you should keep in mind when creating your visualization. You will end the reading by reviewing some practices that you can use to avoid creating misleading or inaccurate visualizations.

#### McCandless method

-   **Information**: the data you are working with
-   **Story**: a clear and compelling narrative or concept
-   **Goal**: a specific objective or function for the visual
-   **Visual** form: an effective use of metaphor or visual expression

### Correlation and causation

Correlation in statistics is the measure of the degree to which two variables move in relationship to each other. An example of correlation is the idea that `as the temperature goes up, ice cream sales also go up`. It is important to remember that correlation doesn't mean that one event causes another. But, it does indicate that they have a pattern with or a relationship to each other. If one variable goes up and the other variable also goes up, it is a positive correlation. If one variable goes up and the other variable goes down, it is a negative or inverse correlation. If one variable goes up and the other variable stays about the same, there is no correlation.

Causation refers to the idea that an event leads to a specific outcome. For example, `when lightning strikes, we hear the thunder`. The sound wave is caused by the air heating and cooling from the lightning strike. Lightning causes thunder.

![Examples of correlation and causation](https://github.com/x-square/visual-resources/blob/main/correlation-causation.png?raw=true)

When you make conclusions from data analysis, you need to make sure that you don't assume a causal relationship between elements of your data when there is only a correlation. When your data shows that outdoor temperature and ice cream consumption both go up at the same time, it might be tempting to conclude that hot weather causes people to eat ice cream. But, a closer examination of the data would reveal that every change in temperature doesn't lead to a change in ice cream purchases. In addition, there might have been a sale on ice cream at the same time that the data was collected, which might not have been considered in your analysis.

For example, pellagra is a disease with symptoms of dizziness, sores, vomiting, and diarrhea. In the early 1900s, people thought that the disease was caused by unsanitary living conditions. Most people who got pellagra also lived in unsanitary environments. But, a closer examination of the data showed that pellagra was the result of a lack of niacin (Vitamin B3). Unsanitary conditions were related to pellagra because most people who couldn't afford to purchase niacin-rich foods also couldn't afford to live in more sanitary conditions. But, dirty living conditions turned out to be a correlation only.

### The wonderful world of visualizations

-   **Line chart** is used to track changes over short and long periods of time. When smaller changes exist, line charts are better to use than bar graphs. Line charts can also be used to compare changes over the same period of time for more than one group.
-   **Column charts** e.g. bar chart use size to contrast and compare two or more values, using height or lengths to represent the specific values.
-   **Heatmaps** also use color to compare categories in a data set. They are mainly used to show relationships between two variables and use a system of color-coding to represent different values. The following heatmap plots temperature changes for each city during the hottest and coldest months of the year.
-   **Pie chart** is a circular graph that is divided into segments representing proportions corresponding to the quantity it represents, especially when dealing with parts of a whole.
-   **Scatter plots** show relationships between different variables. Scatter plots are typically used for two variables for a set of data, although additional variables can be displayed.
-   **Distribution graph** e.g. histogram displays the spread of various outcomes in a dataset.

Meaningful patterns can take many forms, such as:

-   **Change** is a trend or instance of observations that become different over time. A great way to measure change in data is through a line or column chart.
-   **Clustering** is a collection of data points with similar or different values. This is best represented through a distribution graph.
-   **Relativity** is an observation considered in relation or in proportion to something else. You have probably seen examples of relativity data in a pie chart.
-   **Ranking** is a position in a scale of achievement or status. Data that requires ranking is best represented by a column chart.
-   **Correlation** shows a mutual relationship or connection between two or more things. A scatter plot is an excellent way to represent this type of data pattern.

### Data grows on decision trees

A decision tree is a decision-making tool that allows you, the data analyst, to make decisions based on key questions that you can ask yourself. Each question in the visualization decision tree will help you make a decision about critical features for your visualization. Below is an example of a basic decision tree to guide you towards making a data-driven decision about which visualization is the best way to tell your story. Please note that there are many different types of decision trees that vary in complexity, and can provide more in-depth decisions.

![Best way to represent data](https://github.com/x-square/visual-resources/blob/main/data-dicision-tree.png?raw=true)

Start off by evaluating the type of data you have and go through a series of questions to determine the best visual source:

-   Does your data have only one numeric variable?
-   Are there multiple datasets?
-   Are you measuring changes over time?
-   Do relationships between the data need to be shown?

### Principles of design

There are nine basic principles of design that data analysts should think about when building their visualizations.

![Nine principles of design](https://github.com/x-square/visual-resources/blob/main/design-principles-nine.png?raw=true)

`Any questions, please reach out`

Chiawei Wang, PhD\
Cognitive Scientist\
[chw.wng\@outlook.com](mailto:chw.wng@outlook.com)
