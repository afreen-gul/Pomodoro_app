# ANSWERS

## 1. How to run

### Run locally

1. Clone or download the repository
2. Open the project folder
3. Open `index.html` in any modern browser

No additional installation or dependencies are required because the project is built using vanilla HTML, CSS, and JavaScript.

### Deployed URL

https://pomodoro-l3cq2epl3-afreen-gul-s-projects.vercel.app

---

## 2. Stack & design choices

### Frontend stack

I chose vanilla HTML, CSS, and JavaScript because I wanted to focus on understanding core frontend concepts without relying on frameworks. Since I am still learning frontend development, this project helped me practice DOM manipulation, timers, event handling, responsive layouts, and basic UI structuring directly in JavaScript.

### Design decision 1

I placed the timer section at the center of the screen and made it the largest visual element because the timer is the primary action of the app. I wanted users to immediately focus on the countdown without distractions. This affects the main timer container and overall layout hierarchy.

### Design decision 2

I used large buttons with enough spacing between them instead of placing controls too close together. This improves usability on smaller screens and reduces accidental clicks on mobile devices. This affects the Start, Pause, and Reset controls.

---

## 3. Responsive & accessibility

### Responsive behavior

On a 360px-wide mobile screen, the layout stacks vertically and the buttons become easier to tap with enough spacing between controls. Text sizes are adjusted to remain readable without horizontal scrolling.

On a 1440px laptop screen, the timer remains centered while extra spacing prevents the UI from looking stretched across the entire screen.

### Accessibility consideration handled

I used semantic HTML elements like buttons instead of clickable divs so keyboard users can navigate the controls properly using the Tab key.

### Accessibility consideration skipped

I did not fully implement screen reader announcements for timer updates. With more time, I would add ARIA live regions so screen readers could announce timer state changes more clearly.

---

## 4. AI usage

I used ChatGPT to help with:
- Understanding Git and GitHub commands
- Fixing push and repository issues
- Improving responsive CSS structure
- Reviewing layout ideas for the Pomodoro timer
- Writing and improving documentation

One specific change I made to AI-generated output was in the layout styling. The initial suggestion centered all elements with fixed spacing, but on smaller screens the buttons looked cramped. I modified the CSS by adjusting spacing, button sizing, and layout behavior to improve usability on mobile devices.

I also rewrote parts of the generated documentation so it better reflected my actual learning process and beginner-level implementation instead of sounding overly polished.

---

## 5. Honest gap

The biggest gap in my submission is that the project currently has a simple feature set and limited customization options. If I had another day, I would improve the UI animations, add selectable timer durations, include sound notifications, and improve accessibility support for screen readers and keyboard navigation.