# MindCraft
## 💡Inspiration
Our journey began as avid gamers, deeply passionate about the Minecraft universe. We thought of ways to transcend the traditional gaming experience. Instead of being tethered to a keyboard and mouse, we envisioned a world where our bodies could seamlessly merge with the digital realm. With the introduction of AdHawk MindLink glasses and the power of OpenCV technology, this vision transformed into a compelling reality. Our desire was simple yet profound: to unlock a new dimension of play, where players could use their entire body, from limbs to eyes, to interact with the virtual world. This immersive project encapsulates our unwavering commitment to pushing the boundaries of technology and redefining the human-gaming interface.

## 🎮 What it does
Imagine stepping into your favorite virtual world, but instead of relying solely on a controller, you become the controller. Our project enables you to control in-game actions in Minecraft not just with your hands, but with your entire body including your eyes! You can jump, walk, build and destroy by simply moving as if you are doing it in real life. You can turn around just by moving your eyes around on the screen. It's a seamless blend of reality and the virtual, where the boundaries between player and game blur. 

## 🤖 How we built it
**OpenCV, Python, MediaPipe:** Created a script to translate live video camera feed into in-game Minecraft actions.

**AdHawk MindLink Glasses, AdHawk API:** Used the glasses and the AdHawk API to track eye movement on the screen to rotate the player's view.

**Xbox Kinect Sensor:** The sensor takes in the live camera feed into the computer.

## 🤔 Challenges we ran into
* Adhawk Hardware Calibration: The calibration process for the Adhawk hardware and its associated API proved to be a significant challenge. Understanding how to calibrate the hardware effectively required time and effort, especially given its complexity.
* Learning Curve with MediaPipe and OpenCV: Integrating MediaPipe and OpenCV into the project introduced a learning curve. As team members had limited prior experience with computer vision, the project became an opportunity to learn and experiment with new tools and libraries.
* Coordination of Body Movements: Ensuring that the system accurately responded to body movements, especially distinguishing between jumps and walks, presented an ongoing challenge. Balancing these actions to provide a seamless and intuitive gaming experience required fine-tuning and adjustments.

## 🏆 Accomplishments that we're proud of
* Successfully integrated Adhawk MindLink glasses with MediaPipe, OpenCV, and gaming controls when it was our first time working with these technologies.
* Developed precise gesture recognition algorithms, enabling the system to accurately distinguish between walking and jumping, and place and destroy, enhancing gameplay accuracy and immersion.

## 🧠 What we learned
* Developed proficiency in using MediaPipe and OpenCV for real-time gesture recognition and body movement tracking, expanding our knowledge of computer vision. 
* Learned how to create a unique and immersive gaming experience by combining eye recognition technology and physical body movements.
* You CAN meet a group of people online and have a ton of fun.

## ❓What's next for MindCraft
* Incorporate a broader range of body movements and gestures to translate into in-game actions.
* Enhance the precision of gesture recognition and eye-tracking algorithms to ensure accurate and responsive gameplay.
* Introduce multiplayer functionality, allowing users to engage in collaborative or competitive gameplay using Adhawk MindLink glasses and body movements.
