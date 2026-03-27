# Q4 - Seatwork 2:

## Steps: 

```css
    .sidebar {
      background: lightgreen;
      width: 150px;
      height: 200px;
      position: relative; top: 20px; left: 20px;
    }
```

1. Add in css {position: relative; top: 20px; left: 20px;} to .sidebar.
- Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right. Assigns a specific position for the sidebar by creating a margin of _px in the chosen direction in the top, bottom, left, and bottom sides of the sidebar.

```css
    .footer {
       opacity: 0.5;
       position: fixed; bottom: 0; width: 100%;
    }
```

2. Add in css {position: fixed; bottom: 0; width: 100%;} to .footer.
- Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative? It remains in the same position due to its tag for position is fixed. It behaves differently from relative to its normal position.

```css
    .content {
      background: lightyellow;
      width: 300px;
      height: 200px;
      position: absolute; top: 66px; left: 200px;
      z-index: 1;
    }
```

3. Add in css {position: absolute; top: 66px; left: 200px;} to .content.
- Guided Question: What is the effect of position: absolute on an element? How is it different from fixed? Absolute provides the position of its closest ancestor to the object being assigned the position: absolute. It's different from fixed because it doesn't remain on the screen even if the user scrolls, caused by it being relative to the viewport.

```css
    .notice {
        position: absolute;
        top: 60px;
        left: 400px;
        background: orange;
        padding: 10px;
        z-index: 2;
    }
```

4. Add in html {<div class="notice">Notice!</div>} and include the css below:

5. Add the z-index: 1 to .content.

## Guide questions:
1. Why does the notice appear on top of the content? What happens if you swap the z‑index values?
- The notice appears in front of the content because the z-index is changed. The higher z-index value indicates its priority to be displayed; in other words, the greater the z-index value appears the most at front.

2. Challenges:
- I don't want to do these.

3. Reflection questions:
- a. 