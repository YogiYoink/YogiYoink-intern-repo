# Figma Setup Reflection

## Reflection

**How would you organize a design system in Figma to ensure consistency?**

    I’d start by creating a dedicated Foundations page for global styles like the branding colors, typography, and shadows. Then, I’d build a Component Library for things like inputs, buttons, and navigation bars. Keeping everything in one library means that if we decide to change the shade of the the main color, we only have to do it once to update the entire app. I’d also use Variants to manage different states of components (like hover, active, disabled) to keep things organized and easy to update. Finally, I’d set up clear naming conventions and documentation within Figma so that everyone on the team can easily find and understand how to use the components.

**If a developer needs details about a design component, how would you provide that using Figma?**

    I would point them to the Inspect panel in Dev Mode. If it's a complex component, I’d also include annotation notes right next to the design to explain specific behaviors—like what happens when a user hovers over a button or how the layout shifts on a smaller screen. I’d make sure to include all the necessary details like padding, margins, and any interactions that are important for the developer to know. If there are any animations or transitions, I’d create a prototype in Figma to show how it should work in action. This way, the developer has both the visual design and the functional details they need to implement the component correctly.

**What challenges might arise when collaborating in Figma, and how can you avoid them?**

    The biggest challenge with using Figma in a team is when too many people are in one file. It's easy for files to get messy or for someone to accidentally break a component when everyone is working at once. To fix this, we can use a structured design system with components and auto-layout, which act like a set of rules that keep everything consistent and responsive. By using Dev Mode and clearly labeled sections like "Ready for Dev," we stop the back-and-forth confusion and make sure the developers have exactly what they need to build the app without having to guess our design intent. This way, we can all work together smoothly without stepping on each other’s work or creating a mess in the Figma file.
