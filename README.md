- In "Delivery Driver," players navigate a vehicle to pick up brown packages and deliver them to customer(Blue) locations within a dynamic environment.

 Unity Game Development & Design:

- Scene & Level Design: Focused on creating intuitive road layouts and environmental elements, ensuring a smooth gameplay flow from a top-down perspective.

- Player Control & Movement: Implemented responsive vehicle controls using Transform.Translate() and Transform.Rotate() for fluid driving.

- Physics & Collisions:Rigidbody Dynamics: Utilized Rigidbody components for realistic vehicle physics and interactions.

- Colliders: Extensively used OnCollisionEnter2D() for "crash" detection and OnTriggerEnter2D() for core gameplay mechanics like package pickup and customer delivery.

- Game Logic & Visual Feedback: Developed a robust package pickup and delivery system. Implemented dynamic car color changes upon picking up packages and delivering to customers, 

- providing clear visual cues. It does include small amount of time delay to make it look realistic.

- Boost Mechanic( Red Circular object elements) : Incorporated a "boost" feature to temporarily increase vehicle speed. 

- Camera Systems: Designed a smooth Follow Camera that tracks the player's car, maintaining optimal visibility.

C# Programming Skills:

- Conditional Logic: Applied If statements extensively for game logic, such as detecting tags (other.tag) for packages and customers, and triggering specific behaviors.

- Component Interaction: Mastered GetComponent() to dynamically access and manipulate components like SpriteRenderer for visual changes.

- Time Management: Utilized Time.deltaTime to ensure frame-rate independent movement and actions. So, the game is optimized on both high and low end devices!!

- Input Handling: Implemented Input.GetAxis() for responsive player controls.

- Object Lifecycle Management: Used Destroy() for removing game objects from the scene.

- Inspector Integration: Leveraged [SerializeField] to expose variables in the Unity Inspector, enabling efficient game balancing and tweaking.

- The AI “driver” learns how to deliver packages in minimal time while avoiding obstacles.

- We can train it in a background mode or simulate it in Unity using a simplified environment.

Compare AI vs human player performance in terms of time, collisions, and efficiency.
