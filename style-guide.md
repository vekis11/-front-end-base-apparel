# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Desaturated Red: hsl(0, 36%, 70%)
- Soft Red: hsl(0, 93%, 68%)

### Neutral

- Dark Grayish Red: hsl(0, 6%, 24%)

### Gradients

- Linear, 135deg, from hsl(0, 0%, 100%), to hsl(0, 100%, 98%)
- Linear, 135deg, from hsl(0, 80%, 86%), to hsl(0, 74%, 74%)

## Typography

### Body Copy

- Font size: 16px

### Font

- Family: [Josefin Sans](https://fonts.google.com/specimen/Josefin+Sans)
- Weights: 300, 400, 600

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma.

/* Resetting some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  background-color: #f3f4f6;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  text-align: center;
}

header {
  margin-bottom: 30px;
}

h1 {
  font-size: 2.5rem;
  color: #1e40af;  /* Primary Color */
  margin-bottom: 10px;
}

p {
  font-size: 1.2rem;
  color: #333;
}

.signup {
  background-color: #fff;
  padding: 40px;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  width: 100%;
  max-width: 400px;
}

.signup h2 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 20px;
}

input[type="email"] {
  width: 100%;
  padding: 10px;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 4px;
  margin-bottom: 20px;
}

button {
  width: 100%;
  padding: 12px;
  background-color: #ef4444;  /* Accent Red */
  color: white;
  font-size: 1rem;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #dc2626;  /* Darker Red */
}

button:focus {
  outline: none;
  box-shadow: 0 0 0 4px rgba(255, 255, 255, 0.6);
}

.error-message {
  color: #ef4444;
  font-size: 0.9rem;
  margin-top: 10px;
}

footer {
  margin-top: 40px;
  font-size: 0.8rem;
  color: #666;
}

/* Responsive Design */
@media (max-width: 600px) {
  h1 {
    font-size: 2rem;
  }

  .signup {
    padding: 20px;
  }
}
