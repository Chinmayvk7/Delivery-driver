🚚 Delivery Driver – Unity 2D Game

🎮 Project Overview

Delivery Driver is a 2D top-down driving game built in Unity, where players navigate a vehicle to pick up brown packages and deliver them to blue customer locations within a dynamic environment.
The project focuses on realistic vehicle control, responsive physics, and intuitive level design, offering a fun and interactive experience that emphasizes timing, precision, and feedback-driven gameplay.

🧠 Concepts & Systems Implemented

🏙️ Scene & Level Design

• Optimized object placement and colliders to ensure smooth gameplay flow and collision handling.

• Maintained a clean top-down camera perspective for easy control and visibility.

🚗 Player Control & Movement

• Implemented responsive driving mechanics using:

Transform.Translate();

Transform.Rotate();

• Integrated frame-rate independent motion using Time.deltaTime to ensure consistent speed across all devices.

⚙️ Physics & Collisions

• Used Rigidbody2D for realistic vehicle dynamics and physics-based interactions.

Implemented:

• OnCollisionEnter2D() for crash detection

• OnTriggerEnter2D() for package pickup and delivery triggers

🎁 Game Logic & Visual Feedback

• Built a package pickup and delivery system with real-time color feedback.

Vehicle color dynamically changes:

🟫 When picking up a package

🔵 When delivering to a customer

• Added small time delays to simulate realism and smooth transitions.

⚡ Boost Mechanic

• Introduced Boost Zones (Red Circular Elements) that temporarily increase the vehicle’s speed, encouraging faster and strategic driving.

🎥 Camera System

• Designed a smooth Follow Camera that dynamically tracks the player’s car.

• Ensures consistent visibility and camera lag for a natural gameplay feel.

💻 C# Programming Concepts Applied

Conditional Logic:
• Extensively used if statements and tag detection (other.tag) to handle gameplay events like pickups, collisions, and deliveries.

Component Interaction:
• Leveraged GetComponent<>() to dynamically modify behaviors and visuals (e.g., changing car color via SpriteRenderer).

Time Management:
• Applied Time.deltaTime to ensure frame-rate independence, optimizing performance across both high- and low-end devices.

Input Handling:
• Controlled vehicle steering and acceleration using Input.GetAxis() for responsive gameplay.

🕹️ Controls

W / ↑ Arrow – Accelerate / Move Forward

S / ↓ Arrow – Reverse / Slow Down

A / ← Arrow – Turn Left

D / → Arrow – Turn Right

Spacebar – Activate Boost (Red Circle Object)

🧭 Gameplay Flow

🟫 Package Pickup → 🚗 Drive & Navigate → ⚡ Optional Boost Zones → 🔵 Customer Delivery → 💨 Reset & Repeat

🤖 AI Integration

• Integrated an AI “Driver Agent” trained via Reinforcement Learning to optimize delivery efficiency.

• The AI learns to deliver packages in minimal time while avoiding collisions.

• Training can occur in background mode or within a simplified Unity simulation.

Final performance metrics:

• Delivery time

• Collision count

• Route efficiency

• Compare AI vs Human Player results to measure adaptability and improvement.

🧰 Tools & Technologies Used

• Unity Engine (2D)

• C# Programming

• Rigidbody2D & Colliders

• TextMeshPro (UI Feedback)

• Unity Input System

• ML-Agents Toolkit for AI training
