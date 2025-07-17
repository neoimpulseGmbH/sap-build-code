# 3. Joule & Project Accelerator

Joule AI's **Project Accelerator** is a powerful feature that allows you to generate application code based on natural language descriptions or images.

---

## Hint for Best Performance

* **One App Per Accelerator:** For optimal results and clarity, focus on generating one specific application or a distinct module per Project Accelerator run.
* **English Input:** Providing your prompts and images in **English** generally yields the best and most accurate results.

---

## Preparation

Before we can generate we need to get rid of the pre created template project that the Build Code platform creates. 

Go to files select all files with CTRL+A and press delete. 

![alt text](image-6.png)

Now we have a clean empty workspace in which we can start our project generation.

---

## Create Project from Scratch with Joule

Let's use the **Project Accelerator** to kickstart our application based on a user story. 

1.  Go to **Guide Center/Guides/Generative AI-Powered Development** and choose **SAP Fiori UI** 

![alt text](image-8.png)

Alternatively open **Project Accelerator** right away in via your search

![alt text](image-7.png)

2. Go to the following [user story](99_User_Story.md), read and copy it 

3. Did you start Joule through the Guide Center?
No? Then march on to Step 4!
Yes? Great — now sit back and watch the magic unfold when you prompt the copied user story.

![alt text](image-9.png)

Congratulations you also need to open the **Project Accelerator**. Why? Nobody knows. 

4. You have already chosen the right tool to get started. Now prompt the whole user story into the **Application requirements** and press **Generate**

![alt text](image-10.png)

5. Once the Application Information board appears, your app is ready for inspection. Click **Preview Application** to launch it, then select `CDS watch`.

![alt text](image-11.png)

![alt text](image-12.png)

6. Now that you've tried out your app, it's time to investigate what actually happened behind the scenes. Take a look at the project structure, and don’t forget to check out `manifest.json` and `annotations.cds`. Notice anything interesting?

7. As a last try out we are going to use the image uploader to generate our app again. 
    - Open the project accelerator again. 
    - Download the entity [image](/CRM.png)
    - Drop in your project files
    - Upload image in Accelerator 
    - Generate
    - Inspect

---

## Key Takeaway

### 👑 Context is King!

he more context and detailed feature descriptions you feed to **Joule**, the smarter and more spot-on your generated app will be.  
Think of it like briefing a developer — the better the brief, the better the build. 🛠️✨

So, what should you include? 📋

- A clear **User Story** in one or two sentences — include **who** the user is and **what** they want to achieve.
- A short (non-technical is fine!) **description for each entity** involved.
- **Attribute details** — explain what each attribute represents or should contain.
- A **scenario with functionality**, ideally framed as **acceptance criteria per view/page**. Think: *“When the user clicks X, they should see Y.”*

### 🛑 Not a Chat, Just One Shot

If you’re used to chatting with other AIs to build up context step by step — forget it.  
The **Project Accelerator** gives you **one chance** to kick off your project. 🎯  
That means: if your description or picture isn’t clear or detailed enough, you’ll have to **delete everything** and start over with a better prompt. No back-and-forth, no second chances.

### 🎨 It's Fiori Elements Only

When you use the accelerator, you'll get a **Fiori Elements app**, no matter what you tell it.  
Even if you ask it sweetly for a Freestyle app — nope, it’s sticking to Fiori Elements.

What does that mean for you?  
It’s **perfect for prototypes**, **standard apps**, **small-scope solutions**, or **initial list views**. Quick and clean.

Need to go **Freestyle**? No problem (well more or less) — you’ll have to take the wheel and use **Joule directly**. *(That’s the next step.)*

---

## Next Step

You've now seen how Joule can rapidly create an application foundation. Next, we'll use Joule to adapt and enhance this generated app with a freestyle page.

[Go to 4. Enhancing with Joule >>](4_Enhancing_with_Joule.md)