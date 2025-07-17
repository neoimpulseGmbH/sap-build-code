# 4. Enhancing the Created App with Joule

Now that Joule has generated a foundational application, let's use its capabilities to modify and add new column.

---

## Accessing Joule for Code Modifications

Within SAP Business Application Studio, Joule AI can be invoked directly from the editor or a dedicated pane. And we are going to try and modify the current element App by adding a new column. 

---

## Add new column

We are missing an extra field such "First contact place". That should represent where we got that lead from. Since we are not in a real Chat with joule we need to do two things give it a command that is fixed by / and context which is either referenced by # or to the opened file.

1. Edit the data model via command `/cap-edit-model`, reference the files by `#db/schema.cds` and using a prompt like:

    *Add a property named firstContact to the Leads entity which is the description where the lead contact came from*

2. Edit test data via command `/cap-edit-data`, reference the files to edit `test/data/XY.csv` and enter a prompt

    *Add the new values for the column firstContact*

3. Adapt UI via command `

---  

## Take away

It's still **Fiori Elements**, but tweaking your app now takes a few extra steps.  
Things start to get tricky when you want to add custom logic.  

And if you're making changes with **Joule** — watch out! It's a bit fragile.  
Without a proper `/command` or the right `#context`, Joule tends to lose its way.  
It doesn’t always see the full picture of your project, so if your instructions aren’t crystal clear, it might just go off the rails.


---

## Next Step

You've successfully (or not) used Joule to refine and add logic to a generated application. Next, we'll see how Joule can assist in developing custom Freestyle UI5 applications from existing projects.

[Go to 5. Freestyle App Development with Joule >>](5_Freestyle_App_Development_with_Joule.md)