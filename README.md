# mobile_AR - Design and Developmnet
22c014 - Arunkumar s
22c088 - Periyanna M
22c079 - naveen M
22c142 - Vishal Abishek G

Dept of CSE , Thiagarajar College of Engineering 

 
🌿 Abstract
This project presents an Augmented Reality (AR) Plant Garden application developed using Unity and C#. By leveraging the principles of L-Systems for procedural generation, the application enables users to dynamically create, customize, and visualize virtual trees placed within their real-world environment. The HUD (Heads-Up Display) interface allows intuitive control over key parameters such as tree type, branch angle, iterations, length, width, and natural randomness (variance). Upon user command, trees are procedurally generated, scaled for enhanced visualization, and seamlessly integrated into the AR scene. The project utilizes AR Foundation to detect surfaces and anchor the generated trees accurately in physical space. This interactive experience promotes engagement, creativity, and a deeper appreciation of plant structures, showcasing the potential of combining procedural content generation with augmented reality technologies.

The AR Plant Garden lets users dynamically generate, customize, and place virtual trees into the real world using Augmented Reality. Built with Unity, C#, and AR Foundation, it combines procedural tree generation through L-Systems with intuitive user controls for an immersive and creative experience.

Key Highlights:
Real-time tree generation using L-Systems.

Dynamic user control through an easy-to-use HUD panel.

Augmented reality placement with surface detection.

Automatic tree scaling for better visual impact.
🌱 What an L-System Generator Does:
Starts with an initial string (axiom)
Example: F

Applies production rules repeatedly over several iterations
Example rule: F → F[+F]F[-F]F
After a few iterations, the string becomes more complex.

Interprets the final string as drawing instructions

F: Draw a branch segment

+: Turn right by a certain angle

-: Turn left by a certain angle

[: Save the current position and angle (push onto a stack)

]: Restore position and angle (pop from stack)

Builds a 3D tree in Unity using the instructions

The string is converted into geometry (branches, trunk, etc.)

Parameters like angle, length, width, and variance affect shape

Supports customization and interaction within an immersive environment.
![WhatsApp Image 2025-04-28 at 23 45 25_43ae8439](https://github.com/user-attachments/assets/0989dd82-05c9-4bfe-ab79-26efd983dfed)
![WhatsApp Image 2025-04-28 at 23 45 26_d7c2a748](https://github.com/user-attachments/assets/7cb58d59-7f78-41a8-b087-573e37819f52) 

