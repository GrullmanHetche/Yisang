# Yisang — Poetry as an Interactive Space

An interactive web presentation created for a **Korean literature class**, exploring the spatial imagery in the poetry of **Yi Sang (이상, 李箱)**.

[View the presentation](https://yisang-nu.vercel.app)

## Why I built it

The presentation brings literary discussion into an interface that an audience can explore. Instead of describing every spatial concept in words, it lets viewers move between poem excerpts, short explanations, and animated diagrams.

The focus is on *삼차각설계도* and *건축무한육면각체*: using the web to communicate a reading of their relationships with geometry, light, and dimensional space.

## What you can explore

- **Annotated poem excerpts:** hover over highlighted terms to reveal explanations of the concepts used in the presentation.
- **Step-by-step spatial diagrams:** use four buttons to move through a visual interpretation of dimensional expansion.
- **An interactive spectrum:** adjust a slider to unfold a colored grid into a depth-based composition. An automatic sequence introduces the interaction.
- **A rotating tesseract projection:** pause or resume the animation and change its speed to inspect a four-dimensional hypercube projected onto the screen.
- **A guided reading sequence:** move from the opening scene through the poems, three visualizations, and a concluding set of ideas.

## Built with

**HTML · CSS · JavaScript · Canvas 2D API**

Everything lives in one `index.html`. The visualizations use custom drawing and projection code, with `requestAnimationFrame` driving the animated scenes. There is no frontend framework or build step. Typography is loaded from Google Fonts.

## Run locally

Open `index.html` in a modern browser, or serve the folder with a local static server:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Reading context

The diagrams communicate the literary interpretation developed for the presentation. The tesseract is a geometric visualization used alongside that reading.

The page cites the following reference:

> 오상현·이수정, 「이상 시의 4차원 시공간 설계 및 건축」, 2021.

The interface and explanatory material are in Korean. Keyword annotations currently use mouse-hover interaction.

## What this project explores

How can an interface make an abstract idea easier to discuss? This project connects literary analysis with visual explanation, using interaction to give the audience a way to follow—and revisit—the presentation's argument.
