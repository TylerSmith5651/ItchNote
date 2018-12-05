# Initial Commit | December 4th, 2018 | Lets get this party started
  
  This Developer Log will act as a record of the app's development, and as a Journal to record my thoughts about the project.

# Brainstorming 1 | December 4th, 2018 | Initial Thoughts
I want a note-taking app that provides a custom feel for each of my projects. I am in a different headspace with each project that I'm inspired by, and having an organizational structure and style that reinforces that mindset can make a difference. To this end, I would like to create an Android app for my Google Pixel 2 XL that allows me to really customize the way I can organize my thoughts.

## Features: 
### Symbols
Instead of employing the use of tags to organize notes, users can mark notes and sub-sections of notes with **symbols**
* **Symbols** act like tags for search purposes, but they can also apply **templates** to quickly organize a section of your notes
* Users can create custom **symbols** and custom **templates** to tailor the project's organization to their liking
* Multiple symbols can be used to mark the same entry. Only the first **symbol** attached to the entry can throw a template, and only one template can be active on an individual entry at a time. 
* Example 1: You are typing out your notes for tonight's D&D session and after writing a quick recap you need to write out some info about what encounters your adventuring party might suffer this evening. 
You create a new Bullet in the Session note, and attach your Encounter **symbol** to it. This automatically loads in the **template** that you assigned to the Encounter **symbol**, the Encounter **template**, which creates a custom table with fields for Encounter Name, Session #, Linked NPCs, etc. You fill out all the basic details of your session's first encounter with the **template**, and then you can write any other details you would like to include after the **template** is filled out. 
You write: "If the party manages to bring back the head of the man who wronged *Lord Arifel* he will reward them with a *Ring of Shielding*. If he suspects foul play, he is quick to anger and threatens to "beat you lousy bandits bloody" if you do not leave his sight immediately."
You can hold-click on the reference to *Lord Arifel* to bring yourself to his entry, whether it is in the same note or in an earlier one. 
You add an Item **Symbol** Bullet with fields for Item Value, Weight, and Magical Effects, and create an entry for the *Ring of Shielding*. You write that it gives the wearer a  bonus of +1 to their Armor Class, and it requires attunement to gain its effect.  
Boom. you've just created a well organized encounter with little pause for determining how you will need to organize your thoughts.

### Templates
**Templates** are organized lists of fields that let users quickly add a structured entry to their notes. 
**Templates** will exist as Arrays that list a number of different field types in a specific order. That list is used to create a custom table that can be filled. These **Templates** also allow for more filtering opportunities because you can compare individual fields against the answers for that field. Only the first symbol attached to a Bullet can throw a **template**, and only one **template** can be placed on a Bullet at a time. When you need to search through your Encounters, you can sort by the Encounter **symbol**, and then sort the Encounters by the values stored in their **template** fields. You could easily find this encounter by looking in the Encounter list and finding Encounters that include *Lord Arifel*, or are part of Session *#18*. 

  * Example 1: If you have a project based around writing a novel, you might have a custom **template** for character information that includes a field for their Name, Age, Motivations, and Allies. You create a new bulletpoint in the entry you are writing and assign your character **symbol** to it, which attaches the Character Info **template** automatically below the new entries name. Now, when you need to filter your notes to display only character entries, you can filter a list of them in one convenient place instead of having to hop around to different notes looking for them.
  
### Styles
Projects should feel different from one another in **style**. Writing a fantasy novel requires a different environment than typing up an accounting report. The project's **style** should reflect the headspace you want to be in when you create content for that project. 
Style really affects the way I see my notes. Writing a grocery list in a leather journal that looks hand-written, Writing Code samples in a minimalist format, entering data logs into a sci-fi terminal. How you percieve the data you create is just as important as the data itself. Some default project **styles** will exist, but this app is built to encourage the creation of custom **styles**.
* Project **styles** will be saved as a custom CSS document, and this document can be edited to change the **style** of the project. 
* Figure out how to support users who want to import their own fonts and **symbols**.

### Smart View
It is annoying when the block of text you are typing extends below the Android keyboard, and I would like this app to have a view that follows the cursor in a smart way. 
  * Smart View should make sure to keep the cursor well above the keyboard, in the center of the space that isnt taken up by the keyboard
  * The view will shift in scale if the font size increases or decreases. So when you shift into paragraph format after typing out an H1 line, the view will zoom in to accomodate the smaller sized text. 
* While typing, the view stays loosely centered on the text being typed. The Smart View should not follow every single time the cursor moves down a line. Instead it should move up or a down a bit when the cursor gets too close to the edge.  
  
  
  
  
  
  
  
