# Get Started

This Page walks users through 4 steps using the calculator

Each of the 4 Steps uses a GetStartedCard Paper component in a SectionContainer component with the id of the step:


```jsx

<SectionContainer id="step-#">
  <GetStartedStep
    title="STEP TITLE"
    bodyText="STEP BODY TEXT" // Accepts a markdown string
    ctaText='Access Calculator'
    ctaLink='/calculator/landing-0'
    >

      {children}

  </GetStartedStep>
</SectionContainer>

```

> Plus any styling necessary using `sx` prop.

## Reusable Components

- All text uses MuiMarkdown
- The FactCard Component is used in Steps 1 & 3
- The accordion builder is used in Steps 1 & 4
- The CTA button and link are only used currently in Step 2
- Each Standalone child component is itself wrapped in a SectionContainer component to maintain consistent spacing

## Content

- content is pulled from /content/get-started.js


