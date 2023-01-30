# Get Started

![card](assets/card-1.png)

```jsx
// Initial thoughts on how this might
// be built -

<Paper>
  <img/>
  <MuiMarkdown>{content}<MuiMarkdown>
</Paper>

```

> Plus any styling necessary using `sx` prop.

## Section styling

Take note of the way sections are organized on the root/index page. Try to implement it using the same or similar components. It will probably look different from the current design, but it will make it easier to move to a more unified style later.

The main difference is that the home page has each major section in a different "paper" component, whereas the Get Started page uses dividers. Design currently prefers the paper/card look.

## Court Forms Section

There's some code existing for this. The Grid component may need to be adjusted for proper breakpoints. But the basic idea is to put the content in the `/content/get-started.js` file inside the `courtForms` array.

The `details` property takes in a Markdown string.

As a sidenote, the "Vacation packet from Northwest Justice Project" link is broken, so we'll need to find a new link or resource for this.
