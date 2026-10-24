# Expanding Cards: Browser Interaction Exercise

A small HTML, CSS, and JavaScript exercise that turns a row of photographs into an interactive gallery. Selecting a card expands it and reveals its caption while collapsing the previously selected card.

## Problem and approach

The exercise explores how to manage a single active UI selection with minimal code. JavaScript changes CSS classes; CSS controls the animation and presentation. There is no framework, server application, or build step.

## Implementation

| File | Responsibility |
| --- | --- |
| [index.html](index.html) | Defines five image panels and their captions. |
| [script.js](script.js) | Registers click handlers, clears the previous selection, and activates the selected panel. |
| [style.css](style.css) | Defines the flex layout, panel expansion, and caption transitions. |

The initial panel is active when the page loads. Images are loaded from Unsplash and the font is loaded from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the repository directory:

```bash
python3 -m http.server 8000
```

Visit `http://localhost:8000`. Select several panels to check that only one remains expanded.

## Portfolio focus

DOM event handling, class-based UI state, CSS flexbox, and transitions. This is a course practice exercise focused on a single interaction. The mobile media query is unfinished, so small-screen behavior remains an improvement area.
