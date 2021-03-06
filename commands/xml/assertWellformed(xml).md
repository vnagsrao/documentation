{% include_relative _breadcrumb.html current="assertWellformed(xml)" %}


### Description
This command is used to assert if the given xml file is well formed in the structure.


### Parameters
- **xml** - the XML content or file


### Example
In the given xml file the complex element tag `<TimecardProperty>` is not properly closed.  So the assertion should 
fail.<br/>
![](image/assertWellFormed_01.png)

**Script**:<br/>
![](image/assertWellFormed_02.png)

**Result**:<br/>
![](image/assertWellFormed_03.png)


### See Also
- [`assertValue(xml,xpath,expected)`](assertValue(xml,xpath,expected))