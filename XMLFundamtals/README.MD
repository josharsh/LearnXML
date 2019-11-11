# Structure of an XML document:
XML document comprises of
* XML Declaration
* Root Elements
* Child Elements

## Syntax of XML:
~~~xml
<xml version = "1.0" encoding="UTF-8" standalone="no">
<root>
  <child1>Child1</child1>
  <child2>Child2</child2>
 </root>
~~~

### XML Prolog:
An introductory part of xml document describing the XML document is called the XML prolog

## XML Syntax Rule
* XML documents must have only one root element. XML document must have only one root element that is the parent of the all other elements.
* Element must have closing tag.
* Element must be properly nested.
* XML Comments.
* XML tag case sensitive.
* XML Attribute value must be quoted.
* White-space is not preserved in XML


## XML Example:
~~~xml
<xml version = "1.0" encoding="UTF-8" standalone="no">
 <Record>
  <Student>
    <name>Harsh Joshi</name>
    <rno>R1002170</rno>
    <branch>CS</branch>
    <school>SOCS</branch>
    <dept>Cybernatics</dept>
    <cgpa>8.84</cgpa>
   </Student>
  <Student>
    <name>ABC</name>
    <rno>R10145050</rno>
    <branch>CS</branch>
    <school>SOCS</branch>
    <dept>Cybernatics</dept>
    <cgpa>8</cgpa>
   </Student>
</Record>
~~~
