# Workflow

## Sketch Workflow
- To avoid slight color variations when using the color picker in Sketch, be sure to pick the color at the center of an element.
- Organize your designs using **Pages** and **Artboards**. You will find these features useful once you're working on a design file with multiple screens with multiple variants.
- Use proper numbering and naming for **Pages** and **Artboards** just as you would for Photoshop layers.
- I make it a habit to keep a screen together with its variants in a separate **Page**. Here are's an example:

   A **Page** named **Editing Room** will contain the following screen designs:
   
   **_Editing Room_** - Main design, in this case, for the "Editing Room".  
   **_Editing Room - Comments_** - A variant of the "Editing Room" with the comments section visible.  
   **_Editing Room - Chapters_** - A variant of the "Editing Room" with the chapters section visible.  
   **_Editing Room - Comments (Mobile)_** - The mobile design for the Editing Room with the comments section visible.  
   **_Editing Room - Chapters (Tablet)_** - The tablet design for the Editing Room with the chapters section visible.  

- Group layers. If possible, convert them to Symbols. Keep everything neat and tidy!
- Use [Craft](https://www.invisionapp.com/craft) and [Auto Layout](https://animaapp.github.io/Auto-Layout/). It will make your life easier!

## Sketch-Zeplin Workflow
- Be sure there are no rogue text fields in your design as this tends to show up in Zeplin
- In Zeplin, name all the colors used in the design
- Avoid using phone templates. Stick to artboards. The output is easier to use in prototyping apps such as Invision.
- As much as possible, make all icons and images exportable in Sketch so that it will be easier to export assets in Zeplin.

## Frontend Coding Workflow
- Make it a habit to use a different *default* browser everyday. Do not stick to one browser.
- Always check your work using your browser's responsive design mode.
- Always check your work using your mobile phone.
- Safari is the new IE. Use Safari more often.
- When working on Rails Projects, use `rails s -b 0.0.0.0` instead of `rails s` so that you can view your project using your mobile devices.
