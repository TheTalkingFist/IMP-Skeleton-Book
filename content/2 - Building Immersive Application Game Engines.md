
In this chapter we will be focusing on the user and the digital world, ensuring that interactions are precise, intuitive, and most importantly.... functional!

---
# 2.1 Gathering User Input

When developing VR esque items we have to make the user feel like they are "there", capturing their every move. The process involves several steps which vary depending on the hardware and software being used.

  **1. Initialisation**:
	 It starts with connecting and calibrating the VR/AR hardware so the controllers and the system are on the same page.

 **2. Tracking**:
	   The system tracks the position and orientation of the controllers in real-time. This tracking allows the application to determine the precise location and orientation of the user's hands or input devices in the virtual environment.

- **3 DoF**: Only tracks the rotation(looking around). Looking up and down, left and right or tilting your head will be tracked but leaning or moving your head will not.

- **6 DoF**: On the other hand, the 6DoF will track both the X,Y,Z rotation and the X, Y, Z Position of the Head

**3. Input Event Detection**:
	  The app will constantly monitors for **button presses, thumbstick movements, and trigger pulls**. These are then mapped to actions like shooting, drawing, or grabbing

**4. Feedback**:
	  To make it "real," controllers use vibrations or physical sensations to simulate touching virtual objects. Enhancing the overall sense of immersion for the user.

**5. UX Design**:
	 The design of the user interface and interaction mechanics is crucial, Controls must be **intuitive and ergonomic**. If the button layout is confusing, the "fun" disappears immediately!

**6. Testing & Iteration**:
	  After you have done mapping the controller input, thorough testing and user feedback is crucial. As devs we should always terate on the input system to address any issues or improve the user experience.

**7. Optimisation**:
	 Good controller input = Smooth VR/AR experience. Developers should optimise the input processing to minimise latency and ensure real-time responsiveness

**8. Safety & Comfort**:
	 We should always consider user safety and comfort which are crucial for VR/AR products. Developers should implement features to prevent motion sickness and ensure that user movements are natural and ergonomic. We talk about this more in [[3 - Immersive Gameplay Testing#3.1. Risk of Motion Sickness in Virtual Reality|Chapter 3.1.]]

Section Summary:
Gathering user input through controllers is central to VR/AR, requiring seamless hardware–software integration, thoughtful UX design, and ongoing refinement to ensure intuitive interaction.

---
# 2.2 Snapping Objects in immersive and augmented environments

In VR, grabbing objects can be clumsy without a little help. **Snapping** allows for professional precision in tasks like 3D modeling or architectural visualization. This interaction technique is common in 3D modelling, gaming, and augmented reality applications.

- **Object Selection**:
	  We first have to identify the objects that users can manipulate and snap within the environment. The objects should have predefined snap points or regions where alignment or attachment can occur.

- **Snap Points & Regions**:
	  Defines snap points or regions on the objects that users can interact with. These are specific positions or areas where objects can connect, align, or attach. Also known as Magnetic snap.

	 tldr: You define specific "magnetic" areas on objects where they can easily connect or align.

- **Alignment**:
	  Specify the rules and constraints for snapping. Decide if objects should snap to specific orientations (e.g., horizontal, vertical) or specific locations (e.g., a grid, predefined attachment points).

	 tldr: You set constraints, so does the object snap to a grid, or only to specific attachment points? It will be up to you what constraints you set on the object.

- **Trigger**:
	  Determines the trigger or condition that activates the snapping functionality. This can be a button press, a gesture, or a specific interaction event that signals the user's intent to snap objects.

- **Visual & Haptic Feedback**:
	*Visual Feedback*:  Snap guide is to provide visual feedback to the user to assist in the snapping process. This may include highlighting snap points or displaying alignment guides when objects are in proximity.

    *Haptic Feedback*:  Incorporates Tactile feedback through the controllers to inform users when a successful snap occurs. Vibrations or haptic cues can confirm the alignment.

    tldr: When a user gets close to a snap point, the system provides **visual guides** (like highlights or silhouettes) and a **haptic "click"** in the controller to confirm the connection.



- **Physics Simulation**:
	If your environment supports physics-based interactions, it will simulate the behaviour of objects when they snap together. This will ensure that objects behave realistically when they connect or align.


- **Snapping Process**:
	When the snap trigger is activated, the application calculates the best alignment or attachment for the object based on the defined snap points and rules.

1.  Snap Confirmation:
   Confirms the successful snap by providing visual and haptic feedback to the user. This
   may include highlighting the aligned objects, playing a sound, or displaying a message.

2. Release Mechanism:
  This enables users to unsnap or release objects when needed. It defines how users can
  release a snapped object, whether through a button press, gesture, or other input.

3. Testing and Optimisation:
  Rigorously test the snapping mechanism to ensure it works as expected, is intuitive,
  and minimises user frustration. Optimise for performance and responsiveness.

4. User Guidance:
  Provide user guidance within the application, such as tutorials or tooltips, to help users
  understand how snapping works, especially if it's a significant interaction mechanic.

5. Customisation:
  Consider allowing users to customise snapping settings or preferences to
  accommodate different use cases or user preferences.

Section Summary:
Snapping in immersive or augmented environments improves precision and control, making object manipulation more intuitive and efficient across design, visualization, assembly, and interactive applications.

  ---
# 2.3 User Interface in Virtual Interface

The UI is the user's "home base" within the simulation. It’s not just about buttons; it’s about control. UI serves several crucial purposes to enhance the overall VR experience and facilitate interaction within the virtual environment.


- **Navigation and Interaction**:
	The user interface provides the means for users to navigate the virtual environment and interact with objects and elements within it. This includes menus, buttons, and other control elements that allow users to perform actions like selecting objects, moving, or adjusting settings.


- **Info Display**:
	VR user interfaces can display important information to users, such as contextual instructions, status indicators, waypoints, or mission objectives. This information helps users understand the environment and their objectives

	tldr: UI displays your **mission objectives, instructions, and waypoints** so you don't get lost in the digital sauce.

- **Customisation and Settings**:
	VR user interfaces enable users to customise their VR experience by adjusting settings related to graphics, audio, control preferences, and other aspects. Users can tailor the experience to their liking and comfort.

	tldr: This is where users adjust their "realism" settings, like graphics quality, audio levels, and control preferences.

- **Menu Systems**:
	VR user interfaces often incorporate menu systems that allow users to access different features, load applications, or switch between VR experiences. Menus serve as a central hub for users to manage their VR activities.

- **Object Manipulation**:
	Some VR user interfaces are designed to enable users to manipulate or configure virtual objects within the environment. Users can, for example, resize, rotate, or position objects using the interface.

	tldr: Good UI allows users to **resize, rotate, or reposition** virtual objects directly through panels.

- **Accessibility**:
	VR user interfaces can be designed with accessibility features to accommodate users with disabilities. This can include options for voice commands, gaze-based controls, or controller configurations tailored to specific needs

- **Tutorials and Onboarding**:
	User interfaces can be used to provide onboarding experiences and tutorials for new users. This helps users understand how to use the VR system and its controls effectively

- **Safety Measures**:
	In certain VR applications, user interfaces can incorporate safety measures. For example, they may display warnings about physical space limitations or alert users to the potential for motion sickness.


- **Task Switching**:
	VR user interfaces allow users to switch between different tasks or applications within the VR environment. This could involve minimising one application to access another, like how users switch between apps on a computer or smartphone.

	tldr: Just like a smartphone, VR UI allows for **task switching**, letting users move between different apps within the environment.

Section Summary:
A well-designed VR interface is intuitive, responsive, and accessible. Ensuring user comfort, enhances immersion, and elevates the overall experience for the user.


---
That'll be it for chapter 2 guys, I'll hand it back to mik to finish it off with chp 3.

[[1 - Introduction to VR|Previous]] | [[3 - Immersive Gameplay Testing|Next]]
<br>
[[index|Index]]

"I kinda knew that this is how it would end" -Balu Brigada
