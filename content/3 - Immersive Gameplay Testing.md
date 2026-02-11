Hi! It's me again.

# 3.1. Risk of Motion Sickness in Virtual Reality

Remember what I said about me having motion sickness? This is my time to shine.

Motion sickness happens when there is a sensory conflict in the user's visual perception and vestibular system, responsible for balance and spatial orientation.
```
The vestibular system, in vertebrates, is a sensory system that creates the sense of balance and spatial orientation for the function of coordinating movement with balance.
- Wikipedia
```
Basically, when your brain gets opposite signals (e.g your eyes tell you you're moving, but you can still tell that you're standing still), that's when the motion sickens.

There are a few things that could contribute to motion sickness:
- **Artificial Locomotion**
	- Virtually moving while the user themselves stay still in the physical world can cause motion sickness, due do the perception of movement compared to their body actually staying still.
- **Smooth Camera Movement**
	- Smooth camera movement, like walking or continuous motion, can lead to the sicks. Moreso to people who are new to VR.
- **Low Frame Rates**
	- You can probably expect this stutter to get you sick. The lack of smoothness (counterintuitive from the last point) can cause discomfort. VR systems need to keep a high frame rate to reduce this risk.
	- Anything below 60 FPS will cause motion sickness. 120 FPS makes some great VR training, and anything above that is "just fantastic", according to the course notes.
- **Field of View (FOV)**
	- You should know what an FOV is from our previous modules. Narrower FOVs can lead to more motion sickness.

---

# 3.2. Light Modes, Lightmapping and Light Probes

This world has light. To make a virtual world realistic and immersive, we should add a lighting to it as well. This topic is about the lighting techniques we can use to make that lighting look extra nice.

## Light Modes
- Dynamic Lighting
	- Used for real-time, moving light sources such as moving flashlights, headlights really anything that needs to **dynamically interact with the environment**.
	- Provides a high level of realism and immersion in VR.
- Real-Time Shadows
	- They help objects **cast shadows on one-another and the environment**, enhancing perception of depth and spatial relationships.
	- Essential for creating depth and realism in VR
- Global Illumination
	- Simulates the way light bounces and affects the environment.
	- Includes diffuse lighting, indirect lighting and ambient occlusion.
	- Improves overall quality and realism.

## Lightmapping
- Baked Lighting
	- Lightmapping is often used for baked lighting.
	- The process involves using computer magic to calculate how light would interact with the environment and the objects in it, and then storing that data in lightmaps.
	- Lightmaps are then applied to surfaces, allowing for detailed and more realistic lighting that's easy on the computer.
	- It's good for static scenes and can improve performance a whole lot, since it's not continuously calculating light.

## Light Probes
- Real-Time Reflections
	- Light probes capture the environment's lighting and spits out accurate reflection info for stuff like mirrors.
	- Achieves dynamic and realistic reflections, enhances immersion.
- Ambient Lighting
	- Probes can also be used to capture information for ambient lighting in the environment.
	- Ensures objects and characters are appropriately lit and blends in seamlessly with the environment around it.

---

# 3.3. Distributing a VR Program

So, you've created your whole VR game. It's taken you months, maybe years of blood, sweat and tears, and it's almost all over.

Now, how do you publish it?

Unfortunately for you, that process is its own hill. What you'll have to go through is this...
## The Distribution Process
- Development and Testing
	- Develop and test your VR app to make sure it works on your target platform and hardware.
- Platform Selection
	- Decide which platforms your app will support (e.g Oculus Rift, Meta Quest, PS VR, etc.)
- Licensing and Distribution Agreements
	- If you're releasing it on commercial platforms like the Oculus Store or Steam, you might need to enter licensing agreements, just to make sure you comply.
- Packaging and Optimisation
	- Pack it up for distribution on whatever platforms you want, after optimising it for better performance and user experience.
	- Consider reducing file size for quicker downloads and installations.
- App Stores and Distribution Platforms
	- Create accounts for whatever store you're releasing your app on.
- Content Submission
	- Prepare your app for submission to these stores by creating a store listing with screenshots, videos, descriptions and other promotional materials.
- Quality Assurance and Review
	- And now, you send it off to the stores and pray. Your app will undergo review, so they can make sure it complies with their own guidelines, policies, whatever.
	- You might get some feedback and suggested modifications, so prepare for that.
- Pricing and Monetisation
	- Make up your mind on the money you're gonna make. You could make it paid, freemium (free version, premium version) or free with in-app purchases. This is really up to you and your needs.
- Marketing and Promotion
	- Come up with a marketing strategy, like with ads, social media marketing, etc.
- Launch and Release
	- Once your app has been approved for the store(s) you plan to distribute to, set a launch date. You should coordinate with the platforms to make sure it'll be a success, and not be in the shadows for another popular game, or maybe even the surprise announcement of a major video game console...
- Updates and Support
	- At this point, your app should be out. People should be using it and talking about it. Monitor it and fix any complaints or bugs that come up. Give your app regular updates for both user experience and compatibility with new hardware/software updates.
- Community Engagement
	- Engage with your app's community via forums, social media and support channels for feedback and reviews
- Cross-Platform Considerations
	- If your app was meant for more than one platform, make sure it works on all the platforms you targeted.
- User Support and Documentation
	- Make some clear FAQs, tutorials and troubleshooting guides. Helps your users make the most of your app.
- Legal and Copyright Compliance
	- Make sure your VR app complies with copyright laws, privacy regulations, all that other stuff, just so no Japanese video game company goliath that has been in the market since the 1970s.
	- Also make sure you can do that to anyone who copies you by protecting your intellectual property and trademarks as needed.
- Monitoring and Analytics
	- Use tools to track user engagement, performance and get insights to improve your application.

...And only then you can probably consider yourself done. Just like how you can consider yourself done with this module's theory!

---
Yep, that's all three chapters for Immersive Applications!

This also incidentally happens to be our penultimate skeleton book. The final one will be the one for BEV , coming hopefully not right before the test. See you then!

[[2 - Building Immersive Application Game Engines|Previous]]
<br>
[[index|Index]]
