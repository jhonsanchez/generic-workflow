# generic-workflow
Cloud native application that allows organizations to create flows according to their needs, adding fields on demand to be rendered in each step of the flow, organizations can have multiple levels in their flows and could be aproved or rejected, depending on the situation flow may vary triggered by fields values

Different types of reports can be obtained in the system, allowing users to take actions on decide if a flow is taking longer than an average flow should take

## Modules
Generic Workflow has 5 main modules 
*  Form Creation
*  Flow management
*  Reporting Services
*  Maintenance
*  Security

### Form Creation
In this module users can create forms that are going to be part of the workflow, these forms will be stored in the database and can be accesed later to get reports

![Snoopy Test](Snoopy_Peanuts.png)


*  Item 1
*  Item 2
*  Item 3
    *  Item 3a
    *  Item 3b
    *  Item 3c  

1.  Step 1
2.  Step 2
3.  Step 3
    1.  Step 3.1
    
Introducing my quote:

> Neque porro quisquam est qui 
> dolorem ipsum quia dolor sit amet, 
> consectetur, adipisci velit...

Use the backtick to refer to a `function()`.
 
There is a literal ``backtick (`)`` here.

Indent every line of the block by at least 4 spaces.

This is a normal paragraph:

    This is a code block.
    With multiple lines.

Alternatively, you can use 3 backtick quote marks before and after the block, like this:

```
This is a code block
```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```
