# [SDF04] CSS Magic Buttons

Get ready to create animated buttons using CSS! This project focuses on creating three unique animated buttons using CSS. With this challenge, you'll dive into the world of CSS animations, transitions, and interactivity.

## Learning Goals

By completing this project, you will learn to:

- Design engaging button animations with CSS.
- Master the use of CSS transitions and animations for interactive effects.

![alt text](./images/image.png)

## Project Overview

### Time Estimate: 2 hours

## What you Need to Do:

1. **Starter Code**: Clone the starter code from GitHub for your project. The HTML structure is provided, and you'll focus on adding styles in the `style.css` file.

    - Starter code can be found here: https://github.com/CodeSpace-Academy/Module_4_StudentNo_Classcode_Group_Name-Surname_SDF04

2. **Write your CSS Styles**: Create your animations from scratch. You're welcome to go through our curated buttons for inspiration: [View Reference](https://codepen.io/codespace-academy/pen/xxmWrjX). 

3. **Prepare Your Repository**: 
    - Save all chanes and update your GitHub repository with the final versions of all files.
    - Include a `README.md` file that outlines the project, your design choices, and any notes on challenges you faced or features you're particularly proud of.
    - Ensure your repository is set to public so it can be accessed by your code coach.

4. **Submit on LMS**:
    - Submit the link to your GitHub repository on the LMS under the SDF04 project tab.

Embark on this CSS journey to transform simple buttons into interactive, animated elements. Let your creativity shine and enjoy the process of bringing static elements to life!


## Submission Guidelines
- Submit the link to your GitHub repository on the LMS under the SDF04 project tab.

Embark on this CSS journey to transform simple buttons into interactive, animated elements. Let your creativity shine and enjoy the process of bringing static elements to life!
I selceted 3 different styles;
1) Swipe Right Button
2) Animated gradient effect
3) Hover glow effect

Overall I kept the pre-coded styling 
<!-- To create a button with an animated gradient effect for /*<button class="custom-btn btn-1"><Strong>Howzit!!</Strong></button>* -->
This CSS code defines styles for a button with the class .btn-1 along with a hover effect.
The first block of code sets the initial styles for the button with the class .btn-1.
It specifies the text color, border, letter spacing, text alignment, and position.
The transition property is used to apply a transition effect to all properties that change on hover, lasting for 0.35 seconds.
There is a pseudo-element ::after for the button, which will be used for the hover effect.
The pseudo-element is positioned absolutely relative to the button.
Initially, its width is set to 0, effectively making it invisible.
It has a background color #8a0672.
The transition property is used to animate all changes to the pseudo-element over 0.60 seconds.
<!-- /*.btn-1:hover --> This code specifies styles that will be applied when the button is hovered over.
It changes the text color to #e8cce6
<!-- /*.btn-1:hover:after -->This code specifies styles that will be applied to the ::after pseudo-element when the button is hovered over.
It expands the width of the pseudo-element to 100%, creating a visual effect.


<!-- To create a button with an animated gradient effect for /*<button class="custom-btn btn-2"><Strong>Super Star!</Strong></button>* -->
In this CSS:

The .btn-2 class is styled with common button properties such as padding, font size, border, border radius, and cursor.
The button has a gradient background created using the linear-gradient function, with colors #e76d09 and #fcfe7b in a 45-degree angle.
The background-size property is set to 200% 200%, which makes the gradient larger than the button size.
The animation property applies the gradientAnimation animation to the button, specifying a duration of 3s, easing function of ease, and an infinite iteration count.
The @keyframes rule defines the gradientAnimation, which animates the background-position property of the gradient from left to right and then back to left, creating the animated gradient effect.


<!-- Creating a hover glow effect for /* <button class="custom-btn btn-3"><Strong>Glow!</Strong></button> -->
In this CSS:
The .btn-3 class defines the basic styles for the button, such as padding, font size, border, border radius, background color, and text color. It also has position: relative to establish a positioning context for the pseudo-element.
The ::before pseudo-element is used to create the hover glow effect. It's positioned at the center of the button and has a larger size initially with some opacity.
When hovering over the button, the ::before pseudo-element shrinks to create a glowing effect.
Additionally, the button itself gains a box-shadow on hover to further enhance the glow effect.
Transitions are applied to both the box-shadow and the pseudo-element to create smooth animation effects.