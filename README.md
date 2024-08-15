# Rotating Image Gallery

I'm really excited to share with you my rotating image gallery that I created using HTML, CSS, and JavaScript! It's a really cool feature that allows me to showcase a set of images on my website in a continuous loop, rotating them one by one. I think this feature adds a lot of visual interest and can make anything more engaging for visitors.

I started by creating a simple HTML structure that includes a container for the images and some navigation buttons. Then, I used CSS to style the gallery and make it look great. I added some animations and transition effects to make the images rotate smoothly and added some hover effects to the navigation buttons to make them more interactive.

Finally, I used JavaScript to add the functionality to the gallery. I wrote a script that cycles through the images and updates the display with the current image. I also added event listeners to the navigation buttons so that users can manually navigate through the gallery if they want to.

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To get started with this project, clone the repository and open the `index.html` file in your preferred web browser.

## New Things I Learned

It's great to learn about CSS custom properties! I now know that they're defined with the **`--`** prefix, and that they let you define a value once and use it multiple times throughout your CSS code. This makes your code more flexible and reusable, and simplifies updates to styles across your entire website by just changing the value of the custom property.

I've also discovered Lorem Picsum, which is a free online service that provides random placeholder images for testing or demonstration purposes. To specify the image size and aspect ratio, I can use a specific URL format. The service offers a variety of options, such as blur and grayscale effects. Overall, I think Lorem Picsum is a fantastic tool for generating placeholder images quickly and easily!

Learned about the transform-style: preserve-3d; CSS property and how it is used to preserve the 3D transformations of child elements in a 3D transformed parent element.

Learned how to utilize the perspective() function and how it determines how far away the 3D object is from the user and sets the perspective distance for 3D transforms.

For the first time, I used `addEventListener()` and learned how to use it in practice.

## Challenges I faced

One of the main challenges I faced was related to the **`setTimeout`** method that I was using to rotate the images in the gallery. Initially, I had set up the **`setTimeout`** method to rotate the images every few seconds automatically. However, I noticed that whenever I clicked on the previous or next button, it would mess up the gallery and the images would stop rotating.

After doing some research and experimenting, I learned that I needed to use the **`resetTimeout`** method in order to fix this issue. The **`resetTimeout`** method allows me to clear the current timeout and start a new one, which ensures that the images in the gallery continue to rotate smoothly, even after the user interacts with the navigation buttons.

I had to understand how to use **`resetTimeout`** and integrate it into my code to ensure that the images continued to rotate as intended, even after a user interaction. This required some experimentation and tweaking of my code, but ultimately, I was able to implement the **`resetTimeout`** method successfully and the gallery now functions smoothly.

