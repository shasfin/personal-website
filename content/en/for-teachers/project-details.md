---
title: "📋 Robotics Project: Detailed Info"
description: "Detailed information about the project."
date: 2025-02-13T17:09:09+01:00
draft: false
---

{{< section title="What is this about?" open=true >}}

⚠️ **Please note:** This project is currently only available for German-speaking schools. All teaching materials and activities are in German.

Do you want to introduce your **7th and 8th grade students** to **Python programming** in a playful way?  
In our project, you will receive ready-made teaching materials and support to try out two exciting approaches:

* Track 1: Programming a **mobile robot**
* Track 2: Controlling a **24-LED ring**

Together, we aim to find out which approach best fosters students’ interest and understanding. Your experience and feedback help us develop the best teaching methods – and you benefit from tested, practical materials for your class.

{{< /section >}}

{{< section title="Who can participate?" >}}

This project is aimed at **computer science and robotics teachers** at secondary schools teaching **7th or 8th grade classes without programming experience**.

{{< /section >}}

{{< section title="Duration and Process" >}}

The project consists of **10 double lessons**, structured as follows:

* **8 double lessons**: teaching based on our materials.
* **2 double lessons**: tests and questionnaires for evaluation.

The process can be summarized as:

1. **Preparation**: You receive all teaching materials. On request, we offer an introduction to the WebTigerPython programming environment.
2. **Introduction for students**: A research team member visits your school, presents the project, and distributes **consent forms** to parents/guardians. Duration: approx. **15 minutes**.
3. **Pre-tests**: Students complete computer-based questionnaires about their **prior knowledge in robotics and programming** and their **attitudes toward computer science**. Duration: approx. **1 double lesson**.
4. **Teaching**: You teach your class **8 double lessons** using our materials.
5. **Post-tests**: Students complete questionnaires again to assess **learning progress** and **changes in attitudes**. Duration: approx. **1 double lesson**.
6. **Feedback**: You share your **experience** with the materials and project. Feedback can be given anytime during or after the sequence.

**Note**: You can independently design and conduct your own **tests** regardless of the research team.

{{< /section >}}

{{< section title="What is your role?" >}}
* **Organization**: Collect the **consent forms** and forward them to our research team.
* **Teaching**: Teach **8 double lessons** based on our materials.
* **Online Questionnaires**: Students complete online questionnaires at the beginning and end of the project.
* **Your feedback matters!** Share your experiences with us.

We support you throughout the project and are available for any questions.

{{< /section >}}

{{< section title="What will you receive?" >}}

* Teaching materials (including code examples and solutions) that you can continue to use after the study.
* An engaging introduction to programming for your students.
* A valuable contribution to educational research.
* Our experience and support for questions or technical issues.

{{< /section >}}

{{< section title="What will be taught?" >}}
This section lists the learning objectives for each track and week.

{{< collapse title="Track 1: Mobile Robot" track="robot">}}

{{< subcollapse "Week 1 – Drive, Turn, Repeat" >}}
* Students understand that programming means giving a machine precise instructions.
* Students learn how to handle the robot and transfer programs from WebTigerPython via USB.
* Students learn what the driving commands `forward`, `backward`, `left`, `right` do.
* Students learn how to combine driving commands with `sleep` and `stop` to execute driving sequences.
* Students understand the advantages of `repeat`-loops over copy-paste.
* Students use `repeat`-loops purposefully to repeat code sequences.
  {{< /subcollapse >}}

{{< subcollapse "Week 2 – Precise Driving with Custom Commands" >}}
* Students control left and right motors separately.
* Students notice deviations when driving straight and consider possible causes.
* Students experiment to determine parameters for straight driving or rotating in place.
* Students explain with example code why functions reduce redundancy.
* Students define syntactically correct Python functions to encapsulate driving maneuvers.
* Students call their own functions in their code.
  {{< /subcollapse >}}

{{< subcollapse "Week 3 – Sensors and Conditionals" >}}
* Students explain why conditions are necessary to respond to user input.
* Students name the sensors on the robot and describe their functions.
* Students explain how the ultrasonic sensor works.
* Students correctly apply comparison operators (`<`, `<=`, `==`, `>=`, `>`, `!=`) in Python to compare sensor values with reference values.
* Students evaluate logical statements (e.g., `getDistance() < 50`) and predict when they are true or false.
* Students explain how the infrared sensor works.
* Students experiment to find out what values the infrared sensor returns on different surfaces.
  {{< /subcollapse >}}

{{< subcollapse "Week 4 – Providing Alternatives and Following Lines" >}}
* Students explain why an `else`-block is necessary for alternative actions when a condition is not met.
* Students analyze the difference between code with and without `else` and describe the impact on program behavior.
* Students explain why the order of conditions in `if`-`elif`-`else` statements is important.
* Students compare programs with different elif orders and predict behavior in different scenarios.
* Students use `if`-`elif`-`else` constructs to follow a line using infrared sensors.
  {{< /subcollapse >}}

{{< subcollapse "Week 5 – Storing Values with Variables" >}}
* Students explain why variables are needed to reuse sensor values.
* Students identify errors caused by missing variables, e.g., duplicate calls to `random.randint`.
* Students use variables to store sensor measurements (e.g., distance) to decide robot direction.
* Students perform calculations using sensor data.
  {{< /subcollapse >}}

{{< subcollapse "Week 6 – Counting with Variables" >}}
* Students use variables to track whether the robot has crossed a black stripe.
* Students recognize that counting stripes without variables is inefficient or impossible.
* Students purposefully use variables as counters (e.g., crossed stripes, rotations in a direction).
  {{< /subcollapse >}}

{{< /collapse >}}

{{< collapse title="Track 2: LED Ring" track="led">}}

{{< subcollapse "Week 1 – Music and Repetition" >}}
* Students understand that programming means giving a machine precise instructions.
* Students learn how to connect the micro:bit and transfer programs via USB from WebTigerPython.
* Students understand the parameters of `pitch` (tone and duration).
* Students use `repeat`-loops to repeat code sequences.
* Students identify which code blocks are repeated based on indentation.
* Students recognize repeating patterns in songs and implement them using `repeat`-loops.
  {{< /subcollapse >}}

{{< subcollapse "Week 2 – Rainbow Music" >}}
* Students describe how additive color mixing works.
* Students use `fill(r, g, b)` to display a color on the LED ring.
* Students explain why functions are useful to reuse code blocks.
* Students define syntactically correct Python functions.
* Students call their own functions in code.
* Students recognize recurring patterns in songs and implement them as functions.
  {{< /subcollapse >}}

{{< subcollapse "Week 3 – Buttons and Conditionals" >}}
* Students explain why conditions are necessary to respond to user input.
* Students name micro:bit sensors and describe their functions.
* Students use infinite loops to respond continuously to input.
* Students apply comparison operators (`<`, `<=`, `==`, `>=`, `>`, `!=`) to compare sensor values with reference values.
* Students evaluate logical statements (e.g., `display.read_light_level() < 50`) and predict truth values.
  {{< /subcollapse >}}

{{< subcollapse "Week 4 – Providing Alternatives" >}}
* Students explain why an `else`-block is necessary for alternative actions when a condition is not met.
* Students analyze the difference between code with and without else and describe the impact on program behavior.
* Students explain why the order of conditions in `if`-`elif`-`else` statements is important.
* Students compare programs with different `elif` orders and predict behavior in different scenarios.
  {{< /subcollapse >}}

{{< subcollapse "Week 5 – Storing Values with Variables" >}}
* Students explain why variables are needed to reuse sensor values.
* Students identify errors caused by missing variables (e.g., duplicate calls to `get_presses` or `random.randint`).
* Students use variables to store sensor measurements.
* Students use variables and `randint` to program a digital dice.
* Students perform calculations using sensor data.
  {{< /subcollapse >}}

{{< subcollapse "Week 6 – Changing Variables" >}}
* Students identify LED indices (0–23) on the LED ring.
* Students control individual LEDs with `set_led(index, r, g, b)` and predict which lights up.
* Students recognize that repetitive commands without variables are inefficient.
* Students purposefully use variables as counters for running lights and color gradients.
  {{< /subcollapse >}}

{{< /collapse >}}

{{< /section >}}

{{< section title="Technical Requirements" >}}

For this project, you need:

* **Hardware** (per student):

{{< track-cards >}}

{{< track-card img="/images/robots/maqueen_plusV3_flat_layout.png" title="Track 1: Mobile Robot" track="robot">}}
1. micro:bit
2. Maqueen Plus V3 robot
3. Micro-USB cable
4. Laptop or Android tablet (**no iPads**, WebUSB not supported)
5. Suitable batteries
   {{< /track-card >}}

{{< track-card img="/images/robots/led_ring_flat_layout.png" title="Track 2: LED Ring" track="led">}}
1. micro:bit
2. LED ring
3. Micro-USB cable
4. Laptop or Android tablet (**no iPads**, WebUSB not supported)
5. 3 AAA batteries
6. Battery holder for 3 AAA batteries
   {{< /track-card >}}

{{< /track-cards >}}

* **Software**:
    * Browser: Google Chrome
    * Programming environment: [WebTigerPython](https://webtigerpython.ethz.ch/)
* **Missing equipment?** No problem — we’ll find a solution together.

{{< /section >}}

{{< section title="Track Comparison" >}}

| Aspect | Track 1: Mobile Robot                                                        | Track 2: LED Ring                                             |
|--------|------------------------------------------------------------------------------|---------------------------------------------------------------|
| **Hardware** | ![Maqueen Lite](/images/robots/maqueen_plusV3.png) micro:bit + Maqueen robot | ![LED-Ring](/images/robots/LED-ring.png) micro:bit + LED ring |
| **Programming concepts** | Loops, functions, conditionals, variables                                    | Loops, functions, conditionals, variables                     |
| **Practical application** | Controlling a robot (e.g., avoiding obstacles)                               | Creating music, light patterns, animations, simple games      |
{.robot-led-table}

{{< /section >}}

{{< section title="Ethics and Data Protection" >}}

The study has been approved by the ETH Ethics Committee. All data is anonymized and treated confidentially. Participation is voluntary and can be withdrawn at any time.

{{< /section >}}

{{< section title="How to register?" >}}

Interested? Register via [email](mailto:alexandra.maximova%40inf.ethz.ch?subject=Robotikprojekt%20Anmeldung). We are happy to answer any questions.
{{< /section >}}
