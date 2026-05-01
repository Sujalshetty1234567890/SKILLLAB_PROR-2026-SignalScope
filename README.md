# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 16 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-TeamName`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name

`SignalScope`

## 1.2 Team Members

| Name                  | Primary Role                    | Secondary Role   | Strengths Brought to the Project |
| --------------        | ------------------------------- | --------------   | -------------------------------- |
| `Aryan Bharti`        | `[Electronics / Coding / App ]` | `Documentation`  | `Documentation, Gift of Gab `    |
| `Aaditi Chougule`     | `[Electronics / Fabrication]`   | `[Coding]`       | `Material Handling, Hardware`    |
| `Akshata Sarawadekar` | ``|``|``|
|`Sujal Shetty`         |``|``|``|

## 1.3 Project Title

`"DSO Signal Analyzer"`

`(because Logic Analyzer)`

<img width="1600" height="1131" alt="image" src="https://github.com/user-attachments/assets/c64bfbd4-b3b7-43d9-83ad-c203a5aa11bc" />

## 1.4 One-Line Pitch

`Educating Early Teens and Collegites on DSO, Analyzing Logical Signals without making it confusing but rather Easy and Fun`

## 1.5 Expanded Project Idea

In 1–2 paragraphs, explain:

- what your project is,
- what kind of experience it creates,
- what technologies are involved.

**Response:**  
`Creating a Digital Oscilloscope for our topic Logic Analyzer using an FPGA (Artix-7,Basys-3), Arduino UNO and ESP 32 Boards. The ESP 32 is used as a function generator to generate signals of different frequencies, then the signals are sent to the FPGA which works as the brain of the system and segregates the signals into different frequency bands, these segregated signals are then sent to the Arduino which Plots the Signals based on the channel selected by the user. This Project helps in teaching early learners About the working of DSO without much confusion as compared to the traditional methods.`

---

# 2. Inspiration

## 2.1 References

List what inspired the project.

| Source Type | Title / Link                                                        | What Inspired You                                                                         |
| ----------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `[Video]`   | `https://youtube.com/shorts/fqcnga908rw?si=p3kwRwn5LOU0oAG_`        | `How Signals Analyzing can be made Easy and Fun for Early Interest induction in Early Teens` |
|             |                                                                     |                                                                                           |
|             |                                                                     |                                                                                           |

## 2.2 Original Twist

What makes your project original?

**Response:**
`The Tradtional methods are really Complex, amking it hard, hence we created thuis project to deliver an Easy and Interesting, using ESP32, Arduino, and FPGA Boolean board`


---

# 3. Project Intent

## 3.1 User Journey 

Describe exactly how a user will use the project.Make it a story
**Response:**  
`To begin, A user in his teen years curious about Electronic components, loves dwelling into such things and making projects, comes across DSO, which he needs for his Project, he finds it really complex which makes him less interested to go forward with it, instead he gets to know about our version of the DSO, which helps him to understand its working in easier ways, making him more involved in it, the user just uses the switch and sees the signals generated, he understands the signals generated at different fequency bands, through this the user understands how the ESP 32 generates input signal (Works as function generator giving signals of different frequencies), he gets a glimpse of the working of FPGA board, and how it helps in segregating the signals based on different frequency bands, he also gets to know more abt Arduino Board, through such ways the user not only learns about Digital Oscilloscope but also abt ESP 32, FPGA and Arduino, and Signal Generation and Segregation of Signals for different Frequency Bands`

                                                  |



---

# 4. Definition of Success

## 4.1 Definition of “Usable”
` For us in the Project, Segregation of Signals of different Frequency Bands and displaying them on different channels in the form of square waves is the definition of usable.`


## 4.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

**Response:**  

`The input signal gets generated by ESP 32, FPGA Board performs Logical Analysis on the obtained input,FPGA sends out the frequency band of the signals and Arduino plots the signal on channel 1 accordingly.`
## 4.3 Stretch Features

What features are nice to have but not essential?
`Some Features are the Display of Square waveforms on the Graphic LCD, making it interesting for the User to use, and it showcased waveforms on many channels (3-4), creating an extensive experience for the user and to understand more about the waveforms, frequency bands and Signal Generation` 

---

# 5. System Overview

## 5.1 Project Type

Check all that apply.

- [x] Electronics-based

- [x] Mechanical

- [ ] Sensor-based

- [ ] App-connected

- [ ] Motorized

- [ ] Sound-based

- [ ] Light-based

- [x] Screen/UI-based

- [ ] Fabricated structure

- [ ] Game logic based

- [x] Installation

- [ ] Other:

## 5.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
- Input: Input signals are generated by ESP32
- processing: Logic is analyzed using FPGA (Finite State Machine)
- output: Output signals are displayed by Arduino and can be observed on the serial plotter
- physical structure: ESP 32, FOGA, Arduino are connected through PMODS of FPGA via wires
- app interaction if any: NA
## 5.3 Input / Output Map

| System Part                              | Type            | What It Does|                                                              |
|`ESP 32`                                  | `Input`         |`It works as a function generator and produces signals of different frequencies`|
|`FPGA Board`                              | `Processor`     |`It works as the brain, Analysing the Signals and segregating the signals based on Frequency bands and Duty cycles`|
|`Arduino UNO`                             | `Output`        |`It gets the Segregated Signals and Displays the Signals based on the channel selected by the user`|

---

# 6. System Design, Sketches and Visual Planning 

## 6.1 Concept Architecture/sketch/schematic

Add an early sketch of the full idea.

**Insert image below:**  
`<img width="1200" height="1600" alt="WhatsApp Image 2026-05-01 at 23 04 19" src="https://github.com/user-attachments/assets/65eca119-ed13-4edb-924d-04b7c0c2c8b3" />
`

Example:

```md

```



## 6.2 Labeled Build Sketch/architecture/flow diagram/algorithm

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`<img width="1042" height="1338" alt="Flowchart1 drawio" src="https://github.com/user-attachments/assets/12b383c2-e199-40b4-bbba-d1a2d62e316e" />
`
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/95637f31-b4e7-4427-a9e1-4b63fbeb0ac5" />

## 6.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `16 cm` |
| Width            | `16 cm` |
| Height           | `8 cm`  |
| Estimated weight | `400 g` |

---

# 7. Electronics Planning

## 7.1 Electronics Used

| Component                 | Quantity | Purpose                               |
| ------------------------- | --------:| ------------------------------------- |
| `[FPGA Artix-7 Basys-3]`  | `1`      | `[Main controller]`                   |
| `[ESP 32]`                | `1`      | `[Input Signal Generator]`            |
| `[Arduino UNO]`           | `1`      | `[Output signal Displayer]`           |
 

## 7.2 Wiring Plan

Describe the main electrical connections.

**Response:**  
`Pin connections from fpga (pmod JA) to arduino uno
1) J1 to D10
2) L2 to D11
3) J2 to D12
4) gnd to gnd

Pin connections from fpga (pmod JB) to esp 32
1) A14 to P4
2) A16 to P5
3) B15 to P18
4) B16 to P19
5) gnd to gnd

Switches to control channel selection (manual selection)
1) V17 - channel 1 (high frequency band)
2) V16 - channel 2 (medium frequency band)
3) W16 - channel 3 (low frequency band)
4) W15 - channel 4 (ideal frequency band)`

## 7.3 Circuit Diagram/architecture diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="867" height="1156" alt="" src="" />


# 7.4. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Voltage required | `3.3V for ESP32, Arduino and FPGA`                                                                                                                |
 

---

# 8. Software Planning/

## 8.1 Software Tools

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
| `[Vivado]`                     | `Control FPGA`                                 |
| `[Arduino IDE]`                | `to control both the ESP32 and the Arduino. ` |
 

## 8.2 Software Logic/Algorithm

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`

-Startup behavior: The ESP32 boots and immediately begins running high-speed micros() timers to generate waves. The FPGA initializes the 100ms stopwatch to zero. The Arduino opens the 115200 baud serial connection. 
-Input handling: The user flips switches (SW0, SW1, SW2) on the Basys 3 board to select which hardware channel to analyze. 
-Board Reading: The FPGA reads the incoming voltage on the selected Pmod pin. It passes this raw signal through a 1,000-clock-cycle debounce filter to eliminate physical wire ringing and crosstalk. 
-Decision logic: A rising edge detector counts the clean pulses over exactly 100ms. The classifier uses mathematically isolated "buckets" (e.g., <=3 for Slow, <=15 for Mid, <=45 for Fast) to assign a state to the wave. 
-Output behavior: The FPGA forces a 3-bit binary combination (000, 001, 010, 011) onto the output pins. The Arduino reads this and translates it into massive, medium, or tiny square waves on the screen for extreme visual contrast. 
-Reset behavior: Every 100ms, the FPGA resets its internal stopwatch and edge counter to zero to evaluate the next window. If no switches are active, it defaults to State 0 (Idle flatline). `

## 8.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
<img width="1600" height="1200" alt="image" src="" />
<img width="1600" height="1200" alt="image" src="" />




# 9. Bill of Materials

## 9.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `[FPGA]`                         | `[1]`    | `[Yes]` | `[No]`       | `14000[lab]`   | `[Artix-7 Basys-3 FPGA]`      | `[100MHz hardware sampling without overhead.]` |
| `[ESP 32]`                       | `[1]`    | `[No]`  | `[Yes]`      | `[400]`        | `[LN296]`                     | `[To drive both motors]`  |
| `[Arduino UNO ]`                 | `[1]`    | `[No]`  | `[Yes]`      | `[500 ]`       | `[BO Motors and 6 cm wheels]` | `[high torque motors]`    |
 

## 9.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`A standard microcontroller cannot effectively sample, debounce, classify, and output high-speed data simultaneously without blocking delays. An FPGA was chosen to build a dedicated hardware pipeline. The ESP32 was selected as the generator because its clock speed allows for microsecond-level signal generation.`


## 9.3 Items You chose

| Item                 | Why Needed               | Purchase Link | Latest Safe Date to Procure | Status       |
| -------------------- | ------------------------ | ------------- | --------------------------- | ------------ |
| `FPGA Board`         | `Analyze the input signals and segregate them`| `robu.in`| `29th April`| `[Received]` |
| `ESP 32`             | `To generate input signals` | `local store`| `before testing`| `[Received]` |
| `Arduino`            | `To display Signals based on Channel selection`| `local store`| `before testing`  `[Recieved]` |

## 9.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[900]`                     |
| Mechanical parts      | `[0]`                     |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[300]`                     |
| **Total**             | `[1200]`                     |

## 9.5 Budget Reflection

NA

**Response:**  

---

# 10. Planning the Work

## 10.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
Tasks were divided based on the strengths of each student and it was seen to it that it would work smoothly and help is provided if needed by anyone, Each Part of the Project was given to a student, with tasks like Code, Implementation, Debugging, Documentation, Material Acquisition, Each student took decision for his/her department and would ask others for their opinion and approval, Progress was checked at every 2 hours with outputs, If a task was taking long all the members would look into it and try to solve it as fast as possible to reduce the delay and speed up the provcess, Documentation was done every 2 hours to keep proper records of the project without any misses iin the timeline.

## 10.2 Task Breakdown

| Task ID | Task                    | Owner    | Estimated Hours | Deadline     | Dependency | Status |
| ------- | ----------------------- | -------- | ---------------:| ------------ | ---------- | ------ |
| T1      | `[Finalize concept]`    | `[All]`  | `16`            | `30th April`  | `None`     | `Done` |


## 10.3 Responsibility Split

| Area                 | Main Owner     | Support Owner |
| -------------------- | ----------     | ------------- |
| Concept              | `[]`           | `[]`     |
| Electronics          | `[Aditi]`           | `[]`          |
| Coding               | `[Aditi]`           | `[]`          |
| Mechanical build     | `[]`           | `[]`          |
| Testing              | `[Akshata]`           | `[]`          |
| Documentation        | `[Sujal]`           | `[]`          |

---

# 11 hour Milestones

## 11.1 8-hour Plan(tentetively you may set)

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [ ] Purchase needs identified
- [ ] Key uncertainty identified
- [ ] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [x] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [x] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready

## 12.2  Update Log

| Days   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Day 1  | `[A basic simple version of the project to be built]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 2  | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |

---

# 13. Risks and Unknowns

## 13.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                        
| --------------------------------------------------------------- | ------------ | ---------- | -------- | -------------------------------------------------------------------------------------  
|Crosstalk / Wire Ringing                                     | `Hardware `  | `High `   | `High`   | Implemented a 1,000-clock-cycle digital low-pass debounce filter inside the Verilog code.| 
|Ground Loops                                                 | `Electrical `  | `High `   | `Fatal `   | Ensure strict, physical M-M wires connecting all three board GND pins together.  

## 13.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  
How to best visually present the invisible edge-counting math happening inside the FPGA fabric to the judges during a live, high-pressure demo. 

---

# 14. Testing 

## 14.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------|
| `[ESP32 Generation ]`  | `[Run the custom "Self-Reporting Logic Analyzer" code on the ESP32 to plot its own pins. ]` | `[Four distinct, stacked waveforms appear on the serial plotter. ]`|
| `[FPGA Classification ]`| `[Flip SW0, SW1, SW2 independently and monitor Arduino output.]`| `[The Arduino perfectly draws tight, medium, and massive square waves with no visual overlap.]`|
                
## 14.2 Testing and Debugging Log

| Date          | Problem Found                         | Type         | What You Tried                                | Result               | Next Action                                    |
| ------------- | ------------------------------------- | ------------ | --------------------------------------------- | -------------------- | ---------------------------------------------- |
| `18th April`  | `Car not balancing properly`          | `Mechanical` | `Add low-friction caster support to one side` | `Worked`             | `improve caster structure`                     |


## 14.3 Playtesting Notes

| Tester      | What They Did                        | What Confused Them                    | What They Enjoyed                         | What You Will Change                          |
| ----------- | ------------------------------------ | ------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| `Gopal` | `Tried navigating through obstacles` | `Some obstacles ewren't clear enough` | `Liked projection + real car interaction` | `Add a slight red highlight around obstacles` |


---

# 15. Build Documentation

## 15.1 Fabrication Process(if any)

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
` NA.`

## 16 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/user-attachments/assets/74baa570-5770-483e-be6d-d2f03386e37c" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  
The final build is a 3-channel, Digital Storage Oscilloscope and Logic Analyzer. It utilizes an ESP32 to generate continuous, multiplexed hardware signals. These are fed into a Basys 3 FPGA, which uses custom Verilog to digitally filter out electromagnetic interference, count rising edges in 100ms windows, and mathematically classify the frequency bands. The classification is sent over a parallel bus to an Arduino, which renders distinct waveform visuals in real-time. 

## 17.2 What Works Well
The input signals generated pur being analyzed accurately and being plotted in 3 channels, an upgrade from the version we made in the beginning, their is no much time delay in signal generation and Signal display, with everything working with very low Latency


## 17.3 What Still Needs Improvement
We wanna connect a Graphic LCD for the display of the output signals to give it a traditional DSO feel and some finishing touch.

## 17.4 What Changed From the Original Plan
 
How did the project change from the initial idea?

**Response:**  
We initially planned for a 4-channel system including a pure "EMI Noise" channel. However, the physical reality of breadboard wire capacitance caused the high-frequency noise signals to flatline. To ensure a flawless, presentation-ready demo, we triaged the system down to 3 highly distinct frequency channels, drastically improving system stability and visual clarity. And created a 4th channel having idle output signals 

---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  

Our team worked well together and every department went hand-in-hand without much issues, everyone was very co-operative and understood each others weaknesses and strengths deeply, they helped out each other for a smoother and faster process without much delays, The integration between all the 3 components, Arduino, ESP 32 and FPGA Board slowed down the process and delayed our progress, the connection of the graphic LCD also posed a great challenge which was thewn dropped and replaced by Serial plotter, Eacg task was given appropriate time, without anuything lagging behind, tasks and responsibilities were divided to the strengths of the members and everyone worked in unison without any member being un co-operative and lazy.
## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  

We learned that software logic doesn't always map 1:1 to hardware reality. In software, a pin toggling is instant. In hardware, wires act as capacitors, fast loops trigger Watchdog OS panics, and unconnected pins act as floating radio antennas picking up ambient room noise. Learning to build a digital debounce filter in Verilog was a major breakthrough in understanding true EXTC engineering. 
## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  


## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

`We would try to add a Graphic LCD for the display of output signals `

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
<img width="1131" height="1600" alt="image" src="" />

---


---


