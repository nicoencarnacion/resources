# Workflow

## General Workflow
- Product design research. Involve developers. Identify your app's [core functionality](https://blog.intercom.com/the-dribbblisation-of-design/).
- Work with clients and developers to produce low fidelity [paper prototypes](https://www.uxpin.com/studio/blog/paper-prototyping-the-practical-beginners-guide/).
- Produce wireframes prototypes using Sketch and InVision to establish the flow of the app.
- Visual design. Set up your project's styleguide. Use [Symbols and Symbol Overrides](https://medium.com/ux-power-tools/this-is-without-a-doubt-the-coolest-sketch-technique-youll-see-all-day-ddefa65ea959#.fsb60f7k2) to develop a maintainable pattern library.
- Write microcopy. Do not neglect your UI's **microcopy**. Here's a great article on [microcopy](https://material.io/guidelines/style/writing.html). Trying to decide between a few different terms, and you’re not sure which term is best? Use [Google Trends](https://www.google.com/trends/). Google Trends compares how often people search for these terms on Google.
- High Fidelity Mockups using InVision or Marvel

## Sketch Tips
- To avoid slight color variations when using the color picker in Sketch, be sure to pick the color at the center of an element.
- Organize your designs using **Pages** and **Artboards**. You will find these features useful once you're working on a design file with multiple screens with multiple variants.
- Use proper naming for **Pages** and **Artboards** just as you would for Photoshop layers. I make it a habit to keep a screen together with its variants in a separate **Page**. Here's an example (you don't have to follow this style):

   A **Page** named **Editing Room** will contain the following **Artboards**:

   **_Editing Room_** - Main design, in this case, for the "Editing Room".  
   **_Editing Room - Comments_** - A variant of the "Editing Room" with the comments section visible.  
   **_Editing Room - Chapters_** - A variant of the "Editing Room" with the chapters section visible.  
   **_Editing Room - Comments (Mobile)_** - The mobile design for the Editing Room with the comments section visible.  
   **_Editing Room - Chapters (Tablet)_** - The tablet design for the Editing Room with the chapters section visible.  

- Use [Craft](https://www.invisionapp.com/craft) and [Auto Layout](https://animaapp.github.io/Auto-Layout/). This will make your life easier!
- Keep a folder in your machine with different assets organized into subfolders (e.g. food, avatars, office, etc.). This is especially useful when you're using [Craft's Data](https://www.invisionapp.com/craft), a plugin that helps you pull real content from a range of sources and place it directly in your design.
- Be sure there are no rogue text fields in your design. These tend to show up in Zeplin.
- Always setup your project's color palette in Zeplin. It's in the Styleguide tab. This will make your developers' lives easier.
- Avoid using phone templates in Sketch. Stick to Artboards. The output is easier to use in prototyping apps such as Invision and Marvel.
- As much as possible, make all icons(not font icons) and images exportable in Sketch so that it will be easier to export assets in Zeplin.
- Sketch has plugins for Zeplin, InVision and Marvel. Use those!

## Frontend Coding Tips
- Make it a habit to use a different *default* browser everyday. Do not stick to one browser.
- Always check your work using your browser's responsive design mode.
- Firefox also has **Reader View**. Use it for viewing pages with very long articles just to check if your heading hierarchy is okay.
- Always check your work using your mobile phone. When working on Rails Projects, use `rails s -b 0.0.0.0` instead of `rails s` so that you can view your project using your mobile devices.
- Safari is the new IE. Use Safari more often.
