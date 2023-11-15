## Countdown Timer
This is a simple countdown timer implemented using HTML, CSS, and JavaScript. The timer starts at 15 minutes and counts down to zero. When the time is up, it displays "Time's Up" and changes the background color. Additionally, a sound effect is played when the timer reaches 5 seconds remaining.

## Features
Pause/Continue: You can pause the timer and continue from where you left off.
Restart: You can restart the timer to its initial 15-minute countdown.

## Usage
Open index.html in a web browser.
The countdown timer will start automatically.
Use the "Pause," "Continue," and "Restart" buttons to control the timer.

## Styling
The timer is styled with a black background and red text. The buttons are circular with a red background and white text.

## Customization
You can customize the initial countdown time and the styling as needed. Adjust the countDownDate variable in the script to set a different starting time.

javascript

var countDownDate = new Date().getTime() + 15 * 60 * 1000; // Set the time in milliseconds
Feel free to modify the HTML, CSS, and JavaScript to suit your requirements.

## Sound Effect
The timer includes a sound effect (5to1.mp3) that plays when there are 5 seconds remaining. Make sure the audio file is in the same directory as the HTML file, and you can replace it with your own sound file.
