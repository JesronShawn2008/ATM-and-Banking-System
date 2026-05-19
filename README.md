# ATM-AND-BANKING-SYSTEM
# Reg No: 212225100019
# Name: Jesron Shawn C J
# Date: 19/05/2026


# AIM:
To develop the ATM and Banking System using Star UML

# Problem Statement:
1.Banks need to provide fast, secure, and self-service access to basic banking functionalities.

2.Manual banking for simple tasks (like cash withdrawal or balance inquiry) leads to long queues and inefficient use of bank staff.

3.There is a lack of consistent and secure user authentication in some older systems.

4.Existing ATM systems may not be user-friendly or may lack multilingual support.

5.Customers require 24/7 access to basic banking services without depending on bank working hours.

6.A reliable ATM software system is needed to:

7.Allow users to securely access their accounts using ATM cards and PIN.

8.Enable operations like cash withdrawal, balance inquiry, mini statement printing, and PIN change.

9.Ensure real-time processing and data consistency with the core banking system.

10.Provide a simple and intuitive user interface.


# UML DIAGRAMS

# USE CASE DIAGRAM

A use case diagram is a graphical depiction of a user's possible interactions with a system. The use cases are represented by either circles or ellipses. The actors are often shown as stick figures.

UML is the modeling toolkit that you can use to build your diagrams. Use cases are represented with a labeled oval shape.

Stick figures represent actors in the process, and the actor's participation in the system is modeled with a line between the actor and use case.
# UML use case diagrams are ideal for:

Representing the goals of system-user interactions

Defining and organizing functional requirements in a system

Specifying the context and requirements of a system

→ Modeling the basic flow of events in a sina use case.

[Use Case ATM (1).drawio](https://github.com/user-attachments/files/28023799/Use.Case.ATM.1.drawio)
<mxfile host="app.diagrams.net">
  <diagram name="Page-1" id="DrYduVZ9X2-_5gO6Vv_p">
    <mxGraphModel dx="1030" dy="562" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" background="none" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="tPzEjVvB05X2xSHMKq8J-5" parent="1" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;" value="BANK SERVER&lt;div&gt;&lt;br&gt;&lt;/div&gt;" vertex="1">
          <mxGeometry height="60" width="30" x="660" y="190" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-7" parent="1" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;" value="ATM TECHNICIAN&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;&lt;br&gt;&lt;/div&gt;" vertex="1">
          <mxGeometry height="60" width="30" x="110" y="430" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-8" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Authentication" vertex="1">
          <mxGeometry height="60" width="90" x="320" y="20" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-11" parent="1" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;" value="CUSTOMER&lt;div&gt;&lt;br&gt;&lt;/div&gt;" vertex="1">
          <mxGeometry height="60" width="30" x="100" y="100" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-12" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Cash Withdrawal" vertex="1">
          <mxGeometry height="60" width="100" x="315" y="100" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-13" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Balance Inquiry" vertex="1">
          <mxGeometry height="60" width="100" x="315" y="170" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-14" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Fund Transfer" vertex="1">
          <mxGeometry height="50" width="100" x="315" y="250" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-15" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Cash Replenishment" vertex="1">
          <mxGeometry height="60" width="100" x="320" y="350" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-16" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Hardware Maintenance" vertex="1">
          <mxGeometry height="50" width="100" x="322.5" y="420" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-17" parent="1" style="ellipse;whiteSpace=wrap;html=1;" value="Software Updates" vertex="1">
          <mxGeometry height="60" width="95" x="327.5" y="480" as="geometry" />
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-19" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="tPzEjVvB05X2xSHMKq8J-8" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="150" as="sourcePoint" />
            <mxPoint x="300" y="60" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-20" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="tPzEjVvB05X2xSHMKq8J-12" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="160" as="sourcePoint" />
            <mxPoint x="300" y="130" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-21" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="tPzEjVvB05X2xSHMKq8J-13" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="170" as="sourcePoint" />
            <mxPoint x="290" y="200" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-22" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="tPzEjVvB05X2xSHMKq8J-14" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="180" as="sourcePoint" />
            <mxPoint x="290" y="270" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-23" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-8" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="430" y="50" as="sourcePoint" />
            <mxPoint x="640" y="220" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-24" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-12" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="430" y="130" as="sourcePoint" />
            <mxPoint x="630" y="230" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-25" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-13" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="430" y="200" as="sourcePoint" />
            <mxPoint x="620" y="250" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-26" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-14" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="430" y="280" as="sourcePoint" />
            <mxPoint x="620" y="270" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-27" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="tPzEjVvB05X2xSHMKq8J-15" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="450" as="sourcePoint" />
            <mxPoint x="450" y="250" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-28" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;" target="tPzEjVvB05X2xSHMKq8J-16" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="460" as="sourcePoint" />
            <mxPoint x="450" y="250" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-29" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="tPzEjVvB05X2xSHMKq8J-17" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="160" y="470" as="sourcePoint" />
            <mxPoint x="450" y="250" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-30" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-15" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="400" y="300" as="sourcePoint" />
            <mxPoint x="630" y="290" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-31" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-16" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="400" y="300" as="sourcePoint" />
            <mxPoint x="640" y="300" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-32" edge="1" parent="1" source="tPzEjVvB05X2xSHMKq8J-17" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="400" y="300" as="sourcePoint" />
            <mxPoint x="650" y="310" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-34" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="200" as="sourcePoint" />
            <mxPoint x="200" y="560" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-35" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="200" as="sourcePoint" />
            <mxPoint x="560" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-36" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="560" y="560" as="sourcePoint" />
            <mxPoint x="560" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tPzEjVvB05X2xSHMKq8J-37" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;" value="">
          <mxGeometry height="50" relative="1" width="50" as="geometry">
            <mxPoint x="200" y="560" as="sourcePoint" />
            <mxPoint x="560" y="560" as="targetPoint" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>








# CLASS DIAGRAM

The Unified Modeling Language (UML) can help you model systems in various ways. One of the more popular types in UML is the class diagram. Popular

among software engineers to document software architecture, class diagrams are a type of structure diagram because they describe what must be present in the system being modeled. No matter your level of familiarity with UML or class diagrams, our UML software is designed to be simple and easy to use.

Class diagrams offer a number of bend is for any organization. Use UML class diagrams to:

Better understand the general overview of the schematics of an application.

Visually express any specific needs of a system and disseminate that information throughout the business.

Create detailed charts that…



# COMMUNICTION DIAGRAM:

A communication diagram offers the same information as a sequence diagram, but while a sequence diagram emphasizes the time and order of events, a communication diagram emphasizes the messages exchanged between objects in an application. Sequence diagrams can fall short of offering the "big picture."

Communication diagrams offer benefits similar to sequence diagrams, but they will offer a better understanding of how components communicate and interact with each other rather than solely emphasizing the sequence of events. They can be a useful reference for businesses, organizations, and engineers who need to visualize and understand the physical communications within a program. Try drawing a sequence diagram to:




# PACKAGE DIAGRAM:

Package diagrams are structural diagrams used to show the organization and arrangement of various model elements in the form of packages. A package is a grouping of related UML elements, such as diagrams, documents, classes, or even other packages. Each element is nested within the package, which is depicted as a file folder within the diagram, then arranged hierarchically within the diagram. Package diagrams are most commonly used to provide a visual

organization of the layered architecture within any UML classifier, such as a software system.

A well-designed package diagram provides numerous benefits to those looking to create a visualization of their UML system or project.








# ACTIVITY DIAGRAM:

The Unified Modeling Language includes several subsets of diagrams, including structure diagrams, interaction diagrants, and behavior diagrams. Activity diagrams, along with use case and state machine diagrams, are considered behavior diagrams because they describe what must happen in the system being modeled.

Stakeholders have many issues to manage, so it's important to communicate with clarity and brevity. Activity diagrams help people on the business and development sides of an organization come together to understand the same process and behavior.

Activity diagrams present a number of benefits to users. Consider creating an activity diagram to:

Demonstrate the logic of an algorithm.

Describe the steps performed in a UML use case.





# SEQUENCE DIAGRAM

A sequence diagram is a type of intera jon diagram because it describes how- and in what order a group of objects works together. These diagrams are used by software developers and business professionals to understand requirements for

a new system or to document an existing process. Sequence diagrams are sometimes known as event diagrams or event scenarios.


# BENEFITS OF SEQUENCE DIAGRAM

Sequence diagrams can be useful references for businesses and other organizations. Try drawing a sequence diagram to:

Represent the details of UML use cases.

Model the logic of a sophisticated procedure, function, or operation. See how objects and components interact with each other to complete a process.

Plan and understand the detailed functionality of an existing or future scenario.






# RESULT

Thus the project to develop ATM and Banking system was developed using Star UML Software is done successfully.

