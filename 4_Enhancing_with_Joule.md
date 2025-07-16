# 4. Enhancing the Created App with Joule

Now that Joule has generated a foundational application, let's use its capabilities to modify and add new features.

---

## Accessing Joule for Code Modifications

Within SAP Business Application Studio, Joule AI can be invoked directly from the editor or a dedicated pane. And we are going to try and modifie the current element App by adding a new UI5 Page that contains the activities. 

---

##  Add New UI5 Freestyle Page

Let's enhance the user interface by adding a Freestyle page with a detail view of activities per lead. 

1. Generate CAP Data Model for Activities or add manually

2. Select command `/


---

## Modify Test Data & Add Business Logic

Joule can also help us implement business logic and modify mock data for testing.

* **Modify Test Data:**
    * Prompt Joule: "Modify the existing test data to include sample values for 'Activities'.

* **Add Conditional Priority Logic:**
    * Let's add a rule: If the 'Expected Closure Date' for a lead is within the next 30 days, set its 'Priority' to 'High'.
    * Prompt Joule: "Implement logic so that when the 'Expected Closure Date' for a lead is added or updated, if it falls within the next 30 days from today, automatically set the 'Priority' of that lead to 'High'."
    * Joule will likely suggest changes to your CAP service logic or UI5 controller. Review and apply.

---

## Next Step

You've successfully used Joule to refine and add logic to a generated application. Next, we'll see how Joule can assist in developing custom Freestyle UI5 applications from existing projects.

[Go to 5. Freestyle App Development with Joule >>](5_Freestyle_App_Development_with_Joule.md)