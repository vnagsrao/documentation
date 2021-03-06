{% include_relative _breadcrumb.html current="assertTextPresent(pdf,text)" %}


### Description
This command asserts the given text is present in `pdf`.


### Parameters
- **pdf** \- the PDF file to validate
- **text** \- the text expected to be found in `pdf`


### Example
**Script**:<br/>
![script](image/assertTextPresent_01.png)

**Result:**<br/>
![output](image/assertTextPresent_02.png)


### See Also
- [`assertPatternPresent(pdf,regex)`](assertPatternPresent(pdf,regex))
- [`assertPatternNotPresent(pdf,regex)`](assertPatternNotPresent(pdf,regex))
- [`assertTextNotPresent(pdf,text)`](assertTextNotPresent(pdf,text))
