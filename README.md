# Bubble-Loader-Animation
The <strong>Bubble Loader Animation</strong> is a simple yet visually appealing loading indicator designed using HTML and CSS. It consists of six circular elements, or "bubbles," that animate in a rhythmic, pulsating manner to create a dynamic loader effect. These bubbles alternate between expanding and contracting sizes, creating a lively and fluid motion that can be used as a loading icon for websites or web applications.

<h1>Key Features:</h1>
<h2>HTML Structure:</h2>

<li>The loader is made up of six div elements, each with class names from .box-1 to .box-6. These represent the individual bubbles.</li>
The div elements are placed within a container div with the class .loader, which ensures proper alignment and positioning.
CSS Styling:

The background color of the body is set to a dark shade (rgb(49, 48, 48)), creating a contrasting backdrop for the bright, animated bubbles.
Each bubble is styled with a circular shape using the border-radius: 50% property and given distinct colors—orange (rgb(255, 119, 0)) and green (rgb(148, 216, 80)).
The layout is flex-based, centering the loader on the page with equal spacing between the bubbles using display: flex along with align-items: center and justify-content: center.
Animations:

Two different animations are applied to the bubbles. The .box-1, .box-3, and .box-5 elements follow one animation (box1), which makes them grow from a smaller to a larger size.
The .box-2, .box-4, and .box-6 elements follow another animation (box2), which shrinks them from a larger to a smaller size.
Both animations run infinitely in an alternate fashion, giving the loader a smooth pulsating effect.
Applications:
This Bubble Loader Animation is perfect for displaying during data loading processes on a website or as a preloader before page content appears. It adds a professional and engaging touch to user experience during waiting periods.