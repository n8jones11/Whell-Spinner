Agentforce Pitching Selector
A fun, interactive roulette wheel to randomly select teams for pitching, built with HTML5 Canvas, CSS, and vanilla JavaScript.

📜 Features
🎡 Dynamic spinning wheel with custom team segments

🎨 Custom colours, fonts (ITCAvantGardeStd-Demi), and styling

🎉 Confetti celebration on team selection

📝 Selection history list tracking order of picks

📱 Fully responsive for desktop, tablet, and mobile screens

🔊 Click sound effect during spinning

🛠 Easy to customise gaps, colours, speeds, and teams

📂 Project Structure
plaintext
Copy
Edit
/ (root)
 ├── index.html        # Main HTML file (wheel, logic, and layout)
 ├── ITCAvantGardeStd-Demi.otf # Font file used for title
 ├── confetti.gif      # Confetti animation shown on team selection
 ├── click.m4a         # Click sound played during spinning
 └── README.md         # Project documentation
🚀 Getting Started
Clone or download the repository.

Make sure the following files are placed in the same folder:

index.html

ITCAvantGardeStd-Demi.otf

confetti.gif

click.m4a

Open index.html in any modern web browser.

No additional setup required.

🎨 Customisation
You can easily tweak the following:

Spacing between elements: Adjust the gap in the CSS under the body selector.

Number of teams: Buttons allow selection of 3, 4, or 5 teams.

Wheel size: Change the <canvas> width and height.

Spin speed: Modify the initialVelocity or spin duration in the JavaScript.

Background or branding: Replace the background image URL or logo.

📱 Mobile Optimisation
Responsive layouts are handled with CSS media queries. On screens smaller than 768px:

Canvas scales to 90% width

Result box adapts to screen size

Logo size reduces for better fit
