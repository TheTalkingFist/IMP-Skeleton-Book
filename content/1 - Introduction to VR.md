# Augmented/Virtual/Mixed Reality

Weird how the introduction chapter is technically a third of the module, huh?

First thing we're gonna cover is the differences between Augmented, Virtual and Mixed reality. Finding out the differences between these three can be a bit tricky.

These technologies appear in pop-culture, and many people can be familiar with them.


## Augmented Reality (AR)

AR involves **superimposing digital information onto a user's real-world environment**.
```
superimpose
/ˌsuːp(ə)rɪmˈpəʊz/
_verb_

1. place or lay (one thing) over another, typically so that both are still evident.

    "the number will appear on the screen, **superimposed on** a flashing button"
```

Basically, it'll place or overlay digital images onto our real world. If you've ever watched Iron Man (or any of the other Marvel films he's in, really), you can see that his HUD is an example of AR.
![[Pasted image 20260209201707.png]]

In context of entertainment though, a good and classic example is Pokemon Go. You should know that that is.

In manufacturing, though, AR headsets can **present information**, such as the machine's model, serial number, instruction manual and repair procedures. It could also seamlessly connect to some external device for a superior to observe an employee's perspective and give some guidance or pointers when they're using equipment or making repairs.

Restaurants can also offer AR tech to browse menu items when dining or ordering, which enhances customer's understanding of food items by providing additional details. It can also cut costs by eliminating the need to print menus.

In warehouse logistics, AR can be used to identify the most efficient route within the warehouse for obtaining a specific item for a customer and prompting a worker once they have reached the destination. Good for if a warehouse happens to be a labyrinth.


## Virtual Reality (VR)

This is a **computer-simulated environment** in **three dimensions** where the user can engage **with digital objects** through **input methods** like **mouse clicks**, or wearable devices like **headsets and gloves**. We have quite a few consumer headsets available as you probably know, like the Meta's Oculus Rift and Sony's PS VR 2. Google had one called Google Cardboard... apparently.

You might've seen VR in films like The Matrix or Ready Player One, where they have all human senses carried over into a virtual environment. Unfortunately, in this world, you can't smell, feel or taste the virtual chicken you use your virtual hand to put in your virtual mouth. Instead, what you'd probably be doing is using your real hand to bring a very plastic controller to your teeth. But what we have right now is still pretty cool, I think.

So, what can it be used for?

Manufacturers can use VR headsets for **equipment analysis, production process assessments and worker training**. Employees can also enter a **recreated manufacturing process**, letting them **examine it** and **point out possible improvements in the operation**, all with a VR set.

It can also be used in healthcare, where it can be used as a medium for **exposure therapy** for help with **PTSD patients**, or those with **neurological diseases**.

## Differences between AR and VR

- **Smartphones are used for AR**, while **VR is only usable with headsets**.
- **AR** allows a user to **connect the virtual world to a real world**, while **VR** users inhabit a **fictional world**.
- The slightly obvious, **AR mixes the the virtual and real world** to coexist, while **VR sets are strictly virtual**.

## Mixed Reality

This is an advancement of AR that offers users the capability to **manipulate and engage with virtual elements and data**. It gives information that aligns with specific locations **within their real-world surroundings**, letting them **interact with digital elements**.

MR headsets are pretty darn expensive, going for at least US$1000.

The difference between AR and MR is in the user's capability to actively engage with the digital content. That is to say, someone with an AR set can view holographic images of an engine, but can't virtually disassemble it manipulate it.

I guess a good example of this would be if you've watched, like, Spider-Man: Far From Home? Where he's saved from the Netherlands and is building his next suit, you can see him picking up holograms of his webshooters and putting them on his arm? Something like that?<sub>{citation needed}</sub>


MR can be used by **technicians** who can look at **holographic images of pieces of equipment**, taking them apart virtually to **examine its inner workings**, **saving time and eliminating the need for tools** needed for inspecting the physical thing itself.

**Retail merchandisers** can also use MR to **visualise a store layout** before carrying out in the real world. Similar to technicians, they can use holographic displays to, for example, **display a promotional display** at the front of the store **before committing to it**.

Students can use MR as a **learning enhancement**, reinforcing educational concepts **without the risks of real-life learning**. An archaeology student could practice cleaning an ancient artifact without damaging it, for exapmle.


## Extended Reality (XR)
...is a computer-generated that unites aspects of real and virtual worlds, combining some parts of AR, VR and MR. It's seen as an umbrella term for the three types of realities.

---
# 1.1. Differences Between Engines

If you've been at this course for... like, 2 terms, you'd know that there are different engines you can use to make a game. You should also know that there is no best engine, except for The One That Works For You And/Or Your Current Project<sup>©</sup>

So, despite probably only using Unity for this module's practical, let's go through some of them!

## Unity
- Widely used for VR development and supports multiple platforms.
- User-friendly interface and large community of developers, meaning accessibility for both beginner and experienced developers.
- The Asset Store gives some VR-specific assets and plugins which can speed up development
- It has support for the well-known C#, known for simplicity and versatility

## Unreal Engine
- Well-known for high-quality graphics and realistic rendering capabilities
- Has a visual scripting system (kinda like Scratch) called Blueprints, making it accessible for developers without coding experience
- Also supports a lot of VR platforms
- Often favoured for its ability to make visually stunning VR environments, making it a top choice for architectural visualisation and high-end gaming projects
- Alongside Blueprint, it also supports C++, known for performance

## Godot
- It's open-source, meaning that it can be cost-effective for VR development
- May have fewer features that Unity and Unreal for VR dev

## CryEngine
- Known for powerful rendering capabilities, offering photorealistic graphics in VR
- Supports multiple VR platforms and integration with popular VR headsets
- CryEngine is suited for projects that need exceptional visual fidelity

## Lumberyard
- Being owned by Amazon, it has integration with Amazon Web Services (AWS), that definitely have had no problems and crashes whatsoever recently
- Good for VR games with cloud services and networking features
(Fun Fact that isn't important: Apparently Amazon partnered with The Linux Foundation and has since rebranded Lumberyard to O3DE.)

Of course, these are only a few of the game engines. But, say it with me: There is no best engine, except for The One That Works For You And/Or Your Current Project<sup>©</sup>

---
# 1.2. Transform Tools In An Editor

Transform tools let you manipulate and transform objects within the virtual environment.

- **Grab Tool** is just as it sounds, you can reach for and grab objects within the virtual world.
- **Scale Tool** is also just as it sounds, users can stretch and resize objects by manipulating them with their hands.
- **Rotate Tool** lets you rotate objects. Surprise!

- **Physics Based Tools**
Some editors also incorporate physics-based interactions where objects respond realistically to forces and collisions.

- **Holographic Tools**
Users may have access to holographic interfaces that can be manipulated using controllers that allow precise control over transformations

- **Gesture-Based Controls**
Some editors use hand gestures and motions for bigger transformations. For example, using motion tracking to detect a wave of the hand might trigger scaling while rotating a hand could do rotation.
- As well, Leap Motion Controller, a small USB-connected device that uses infrared cameras and sensors to track movements of a user's hands with precision.
	- Real-time tracking of hand and finger movements to create natural and
	immersive interactions within VR and AR environments.
	- Enables users to interact with virtual objects, manipulate 3D models, and
	control interfaces using their hands and gestures in fields such as gaming,
	design, education, and healthcare.
	- Emits infrared light, which is reflected off the user's hands, and the device's
	cameras capture the reflections to track hand and finger movements.

- **Multi-Hand Controls**
These enable users to perform transformations with both hands simultaneously, useful for complex operations.

- **Telekinesis or Mind-Controlled Tools**
Some experimental VR apps explore Brain-Computer Interfaces (BCIs) to control transformations, essentially allowing users to move or manipulate objects with their thoughts.

- **Voice Commands**
Some VR environments can use voice commands to trigger transformations

The availability depends on the program, platform, hardware and design. That is to say, not all programs will have all of these features.

---
# 1.3. Locomotion

This basically deals with how you move around in a virtual/augmented environment. There's a specific balance we need to strike here, and that is the balance between the effectiveness of our movement and minimising motion sickness.

As someone who is VERY susceptible to motion sickness, I'd like to emphasise the motion sickness part. Please.

## Teleportation
- Users point to a specific area and instantly teleport themselves.
- Reduces motion sickness since it avoids continuous movement.

## Room-Scale VR
- Some environments are room-scale, meaning they are as big as the room you're in.
- As you can predict, this would be really immersive since your movement in the real world would be 1-to-1 with the VR environment
- However this is limited by the space available, or how big your room is.

## Walk-In-Place
- This has you simulate walking by lifting your feet or making small steps. Basically, marching on the spot. These motions are translated into movement in game.
- Allows you to explore the environment without walking around.

## Joystick-Thumbstick Locomotion
- If you've tested your labsheet projects in any capacity in the class, you'd know that most controllers have joysticks with little thumbsticks on 'em.
- You can use these as movement in the same way you'd turn a joystick on a normal game controller.
- The functionality of each button can be mapped via XR input mappings.

## Physical Treadmills
- You could use specialised treadmills, equipped with sensors and trackers that can allow the user to physically walk or run in place, without actually moving.
- Of course, this feels a lot more natural.

## Gesture-Based Locomotion
- Some users can use hand or body gestures for movement. For example, an arm pointing forward may trigger forward movement.
- These needed specialised devices, such as the aforementioned Leap Motion Controller, as well as the Kinect for Microsoft's Xbox (Remember that??? Good times).

## Sitting or Seated Locomotion
- Suitable for users who prefer to sit. They can use a controller for navigation while they do.

## Climbing And Flying
- Some experiences use climbing or flying mechanics, where users can interact with objects that are meant for them to do, well, just that.

## Natural Walking
- For as simple as this is, this apparently needs some more advanced VR systems.
- Uses advanced tracking systems to let users naturally traverse through a large world.

## Path-Based Navigation
- Gets you to follow a predefined path or rail system, like a guided tour.

Just like before, there is no best way of locomotion, all of these are applicable to different contexts. However, obviously, it's important to consider who's gonna use your product. You're probably gonna wanna try meet all of their needs, making it as comfortable as possible or maybe even offering different locomotion systems in your game.

---

And that should be the whole of Chapter 1! Jabriel will be writing the next one, so I'll see you guys back in Chapter 3.

[[2 - Building Immersive Application Game Engines|Next]]
<br>
[[index|Index]]

Though, while I was writing it, I saw the Kinect mention and had to look it up. I had one of those as a younger kid with an Xbox and absolutely loved it.

I found out they were discontinued, which was a bit disappointing, but also not surprising. I don't see anyone talk about these anymore.

What I did find surprising was that how much use they had for use cases that had nothing to do with Xbox. Apparently, even past discontinuation, they were used in research labs and some even used them for studying the human posture. Isn't that something?
