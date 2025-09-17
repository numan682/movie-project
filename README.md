# Iron Man Webpage

![Iron Man Logo](https://i.pinimg.com/736x/83/e6/11/83e61132cc718e6e153e2c5cb58c642e.jpg)

A single-page, responsive, and visually stunning tribute to the movie *Iron Man*. This project was built from scratch to showcase advanced web development techniques, including dynamic video backgrounds, on-scroll animations, and a responsive design.

### **Live Project**
You can view the live project here: [https://assignment.jhnuman.com](https://assignment.jhnuman.com)

---

## **About the Project**

This webpage was created as an exercise in building a high-impact, single-page website with a focus on immersive visuals. The goal was to go beyond basic static pages and create an experience that feels as dynamic as the movie it represents. Every aspect, from the color palette to the animations, was meticulously chosen to evoke the high-tech, sleek aesthetic of the Iron Man universe.

## **Features**

* **Dynamic Video Backgrounds**: The hero and plot sections feature looping YouTube videos that run silently in the background, creating a cinematic and engaging atmosphere. The videos are carefully embedded to be responsive and cover the entire section, regardless of screen size.
* **Parallax Effect**: A subtle parallax effect is used to make the background appear to move at a different speed than the foreground content, adding a sense of depth and dimension as the user scrolls.
* **On-Scroll Animations**: Content sections, including the movie details, plot, and cast, fade and slide into view as the user scrolls down the page. This is handled by a custom JavaScript **Intersection Observer** that adds a touch of modern flair to the user experience.
* **Fully Responsive Design**: The entire webpage is built with a mobile-first approach. Using CSS Flexbox and Media Queries, the layout adapts seamlessly from large desktop monitors to tablets and small mobile phone screens, ensuring a consistent and optimal viewing experience for all users.
* **Interactive Elements**: Hover effects on the cast cards and info boxes add a layer of interactivity and visual feedback.

---

## **Design and Implementation**

The design is built on a custom color palette of **Iron Man Red (`#e50914`)** and **Arc Reactor Gold (`#f7b731`)**. A dark, clean aesthetic provides a high-contrast backdrop that makes the content and hero visuals pop.

The core technologies used are:

* **HTML5**: For the semantic structure of the webpage.
* **CSS3**: For all the styling, including advanced techniques like video scaling, transitions, and keyframe animations.
* **JavaScript**: A lightweight, external script handles the Intersection Observer for the on-scroll animations and smooth scrolling.

### **Code Structure**
The project is organized into three main files for clarity and maintainability:
* `index.html`: The main page structure.
* `style.css`: All custom CSS rules and animations.
* `script.js`: The JavaScript logic for dynamic effects.

This separation of concerns makes the codebase clean and easy to manage for future updates or modifications.

---

## **How to Run Locally**

To run this project on your local machine, follow these simple steps:
1.  **Clone the repository**:
    ```bash
    git clone https://github.com/numan682/movie-project.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd movie-project
    ```
3.  **Open `index.html`**:
    Simply open the `index.html` file in your favorite web browser.
