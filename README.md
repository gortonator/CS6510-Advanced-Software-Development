# CS6510 Advanced Software Development (ASD)

## Instructors
Ian Gorton: Email: i.gortonATnortheastern.edu

Adrienne Slaughter: Email: a.slaughterATnortheastern.edu

## Teaching Assistants
Seattle - coming soon

San Jose - coming soon

Boston - coming soon

## Introduction
ASD is designed to integrate academic concepts and practical experience of software engineering by having students work as part of a sizeable agile programming team, with options to lead a subteam. The course offers students an opportunity to study, in-depth, some aspects of the development process pertinent to a complex, ill-defined set of system requirements. The goal is to have students participate in a large-scale project, taking time to reflect and analyze the work and the process, and to produce a significant demonstrable outcome in the form of a working, deployed software system.

## Project
Each class works collaboratively to build a software project for an external client. The projectdescription for Spring 2020 is [here] (https://gortonator.github.io/CS6510-Advanced-Software-Development/ClimateTree.md).

## Prerequesites
Students should have completed FSE and/or a coop/intern. These prerequisites can be waived based on individual circumstances and experience such as that gained on COOPs or in other courses such as Web Development, Data Mining/Machine learning. Please contact the Professors to discuss

## Attendance 
Students are expected to attend each class on campus. If there is avalid reason, then a student may request to attend class remotely. All classes are held via video conference across participating capus locations.

## Learning Objectives
At the end of the course, students will have acquired the following knowledge:

### Advanced Software Engineering
- Be able to design and develop distributed, multi-tier, cloud-based systems
- Be able to design RESTful APIs that are robust and high performance
- Understand the advantages of continuous development and deployment
- Have experience with continous build/intergration platforms
- Be able to quantitavely assess and evolve a software system based on metrics
- Be able to design systems for usability and scalability
- Be able to explain the advantages and pitfalls of distributed teams
- Experience in distributed systems testing

### Experiential
- practical experience with scaled agile methods and tools
- acting as team technical lead
- task definition, prioritization and planning
- automated build tools
- designing and developing components in a complex software system
- retrospectives and code reviews

## Assessment
There will be major deliverables, in week 3, 7, 11, 14. These will be based on the following criteria:

1. **Week 3**: User stories defined, development frameworks and build tools environments established, plan for first sprint in place based on prioritized defined tasks. (10%).
1. **Week 7**: Initial demonstrable prototype that supports high priority user stories; retrospective on first sprint; plan for next sprint established (15%)
1. **Week 10**: Robust implementations of high priority user stories; demonstrations of medium priority user stories; integration of components across teams (20%)
1. **Week 14**: Final implementation of high and medium priority user stories; quality of resulting architecture and design; (25%)

There will also be an individual assessment based on contribution reports each sprint from each student. (30%)

## Curriculum

<table>  

  <tr>
    <th>Week</th>
    <th> Topics </th>
    <th>Readings</th>
    <th>Homework</th>
  </tr>
  <tr>
    <td>1</td>
    <td> Introductions and project overview from Product Owners <br>
Major components to be developed <br>
Expected deliverables  <br>
Logistics of class and project <br>
Team formation 
    </td>
    <td> Overview of SCRUM and Trello <br>
http://www.scrumprimer.org/scrumprimer20.pdf <br>
http://scrumtrainingseries.com/ <br>
https://civicactions.com/blog/2012/oct/10/five_tips_for_using_trello_for_scrum <br>
http://www.tommasonervegna.com/blog/2014/1/9/10-effective-tips-for-using-trello-as-an-agile-scrum-project-management-tool <br>
http://scrumfortrello.com/ <br>
https://www.burndownfortrello.com/ 
    </td>
    <td>Each team nominates a Scrum Master/Team Lead for the first sprint. <br>
Teams  communicate to agree on a development/build/test environment <br>
Setup a Trello environment, including any extensions you choose to use, for each team and document how you will use it for SCRUM 
    </td>
  </tr>
  <tr>
    <td>2</td>
    <td>Requirements in an agile project <br>
Distributed teams and coordination <br>
Test-driven development</td>
    <td>Agile Requirements <br>
https://www.scrumalliance.org/community/articles/2012/february/agile-requirements-definition-and-management <br>
https://www.atlassian.com/agile/requirements/ <br>
Distributed Teams <br>
http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4599502&tag=1 <br>
<br>
Test Driven Development <br>
http://www.agiledata.org/essays/tdd.html#TraditionalTesting <br>
https://www.scrumalliance.org/community/articles/2011/may/my-experiments-with-tdd <br>
http://beust.com/weblog/2014/05/11/the-pitfalls-of-test-driven-development/ <br>
</td>
<td>Select a discussions board and issue tracking tool for use across all the teams <br>
Each team must generate a set of candidate user storied based on their understanding of the project requirements and interactions with the Product Owners <br>
    </td>
  </tr>
  <tr>
    <td>3</td>
    <td>Designing APIs and Interfaces <br>
Robustness and Resilience
    </td>
    <td>API Design and REST <br>
http://lcsd05.cs.tamu.edu/slides/keynote.pdf <br>
http://codeplanet.io/principles-good-restful-api-design/ <br>
http://martinfowler.com/bliki/HumaneInterface.html <br>
http://martinfowler.com/bliki/MinimalInterface.html <br>
<br>
Robustness and Resilience <br>
http://cdn.oreillystatic.com/en/assets/1/event/79/Stability%20Patterns%20Presentation.pdf <br>
http://martinfowler.com/bliki/CircuitBreaker.html <br>
https://msdn.microsoft.com/en-us/library/dn589784.aspx <br>
    </td>
    <td>Investigate the libraries you might use for communications in this project and assess candidate libraries for suitability for this project
    </td>
  </tr>
  <tr>
    <td>4</td>
    <td>Teams present their plans for the first sprint, including user stories, frameworks and development tools selected</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>5</td>
    <td>Code Quality: Importance and how to achieve it <br>
Unit testing: approaches, tools, frameworks</td>
    <td>For an overview on code quality in agile developments <br>
http://www.scaledagileframework.com/code-quality/  <br>
<br>
There’s an extensive body of work on developing quality code. Here’s some examples that are worth dipping in to, and are typical books on any good engineer’s book shelf <br>
Code Complete, by Steve McConnell. <br>
Refactoring: Improving the Design of Existing Code , by Martin Fowler. <br>
Design Patterns: Elements of Reusable Object-Oriented Software , by Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides. <br>
Object-Oriented Design Heuristics , by Arthur Riel. <br>
<br>
This material should give you some insights into unit testing approaches and tools you can use: <br>
http://martinfowler.com/bliki/UnitTest.html <br>
http://blog.stevensanderson.com/2009/08/24/writing-great-unit-tests-best-and-worst-practises/ <br>
https://msdn.microsoft.com/library/hh323702(v=vs.100).aspx <br>
http://blog.zuehlke.com/en/best-practices-in-unit-testing/ <br>
http://martinfowler.com/articles/mocksArentStubs.html </td>
    <td>
    Establish code quality standards for your teams <br>
Establish unit testing practices for your teams</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Code reviews: why, approaches, best practices</td>
    <td> http://www.ibm.com/developerworks/rational/library/11-proven-practices-for-peer-review/ <br>
https://msdn.microsoft.com/en-us/library/bb871031.aspx <br>
https://en.wikipedia.org/wiki/List_of_tools_for_code_review <br>
http://gerrithub.io/ <br>
    </td>
    <td>Choose a process and tooling to support code reviews inside your team and across teams. You’ll be graded on code quality, so don’t neglect this step.</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Teams present the outcomes from their first sprint. This involves demonstration of working code, review of backlog, and reports on development velocity and story points completed. </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>8 and 9</td>
    <td>Code a9nd System Metrics </td>
    <td> Software Metrics: A Rigorous and Practical Approach, Third Edition <br>
	Goal Question Metric Paradigm (Chapter 3) <br>
	Size Metrics (Chapter 8)
	Structure Metrics (Chapter 9)
	
	</td>
    <td>Evaluate and select tools to use to drive refactoring based on identified metrics</td>
  </tr>
  <tr>
    <td>10 onwards</td>
    <td>The classes focus on monitoring progress for each sprint and presenting and demonstrating deliverables associated with each assessment. The focus is on putting the concept discussed in the early weeks of the course into practice. </td>
    <td>
	</td>
    <td></td>
  </tr>
 </table>
