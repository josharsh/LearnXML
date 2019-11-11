# Document Type Declaration(DTD)
A DTD is a Document Type Definition. A DTD defines the structure and the legal elements and attributes of an XML document.

## Types of DTD:
* Internal DTD
* External DTD

#### Internal DTD Example

~~~xml
<?xml version="1.0"?>
<!Doctype Email [
  <!ELEMENT Email(to,from,heading,body)>
  <!ELEMENT to(#PCDATA)>
  <!ELEMENT from(#PCDATA)>
  <!ELEMENT heading(#PCDATA)>
  <!ELEMENT body(#PCDATA)>
  ]>
 <Email>
  <to> Teknoturf</to>
  <from> IBM </from>
  <heading>XML Technology</heading>
  <body>Hello There</body>
 </Email>
~~~
