# 5. Freestyle App Development with Joule

Joule AI isn't just for generated projects; it can also be a powerful assistant when developing custom (Freestyle) UI5 applications from scratch or within existing projects.

---

## Selecting an Existing Project

For this section, we'll work with an example of an existing UI5 project.

1.  If you have a pre-existing Freestyle UI5 project or a basic UI5 application without extensive backend integration, open it in SAP Business Application Studio.
2.  **Example:** For this workshop, we might have provided a simple `FreestyleUI5App` example project. Open this project.

---

## Add a "Create" Button

Let's use Joule to add a new button to our Freestyle UI5 application.

1.  Open the `View.xml` file (or the relevant view XML) where you want to add the button.
2.  In the Joule AI chat or context menu, prompt it to add a button.
    * **Example:** "In this view, add a new `sap.m.Button` with the text 'Create' and an icon `sap-icon://add`."
3.  Joule will generate the XML snippet for the button. Review and insert it into your `View.xml` file.

---

## Generate Logic for the "Create" Button

Now, let's have Joule generate the corresponding event handler logic for our new button.

1.  Open the `Controller.js` (or `Controller.ts`) file associated with your view.
2.  In the Joule AI chat, prompt it to generate the logic for the button's press event.
    * **Example:** "Generate an event handler function for the 'Create' button's `press` event. This function should navigate to a 'Create Lead' view (assume a route named 'createLead' exists) or open a dialog for new entry creation."
3.  Joule will provide the JavaScript (or TypeScript) code for the event handler. Review and integrate it into your controller. You might need to adjust the navigation part based on your app's routing.

---

## Conclusion & Next Steps

Congratulations! You've successfully navigated through key aspects of UI5 and CAP development, harnessing the power of SAP Joule AI. You've seen how Joule can:

* **Accelerate Project Setup:** Rapidly scaffold applications from natural language.
* **Streamline Enhancements:** Add features and logic to existing apps.
* **Assist Freestyle Development:** Help with UI component creation and event handling.

We encourage you to explore Joule's capabilities further in your own projects. The more you interact with it and provide clear, precise prompts, the more valuable it becomes.

---

## Thank You!

We hope you found this workshop insightful and practical. Happy coding!