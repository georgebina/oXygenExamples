# oXygenExamples
Different samples for oXygen





Displays the steps of a task as a table ([taskTable](https://github.com/georgebina/oXygenExamples/tree/master/taskTable))
---
The steps element needs to contain `@outputclass='table'` to activate this
Here it is the CSS that provides this [taskTable.css](https://github.com/georgebina/oXygenExamples/blob/master/taskTable/taskTable.css) 

Here it is a sample task that uses this CSS in the [oXygen XML Web Author](http://www.oxygenxml.com/webauthor/):

[sample.dita](https://www.oxygenxml.com/webapp-demo-aws/app/oxygen.html?url=github%3A%2F%2FgetFileContent%2Fgeorgebina%2FoXygenExamples%2Fmaster%2FtaskTable%2Fsample.dita).


For XHTML output a [different CSS](https://github.com/georgebina/oXygenExamples/blob/master/taskTable/taskTableHTML.css) should be used, passed as the `args.css` parameter to the transformation and setting also the `args.copycss` to `yes`. 
A transformation for the [test.ditamap](https://github.com/georgebina/oXygenExamples/blob/master/taskTable/test.ditamap) file is already configured in the sample oXygen project, the [taskTableProject.xpr](https://github.com/georgebina/oXygenExamples/blob/master/taskTable/taskTableProject.xpr) file. Here it is how the 
HTML result looks like:
[out/xhtml/sample.html](https://rawgit.com/georgebina/oXygenExamples/master/taskTable/out/xhtml/sample.html).



