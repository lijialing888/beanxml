# beanxml: Solve the bad use of JAXB
* Performance is no worse than JAXB
* Bean fields use XMLAttribute by default, no need to configure @XmlAttribute for each field
* Supports setting the order of fields, no need to set all orders, fields with order are first, and fields that are not set are listed in the back
* You can set the priority to print the parent class, followed by the subclass
