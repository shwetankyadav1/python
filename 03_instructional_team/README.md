# Technical Facilitator Playbook

## How do you interact with the repo?
The Technical Facilitator will deliver the content in the `/01_materials/slides` directory. You are encouraged to live code with participants during live sessions. Please ensure that live coding files are uploaded to a new directory called `/live_code` under `/04_cohort_three` in this repository using a new branch. Please open a pull request for it to be merged.

## How does the module flow?
The module is organized into 3 main directories:
1. Slides
2. Assignments
3. Homework

The `/01_materials/slides` directory contains the live learning session slides.

The `/02_activities/assignments` contains assignments participants should submit for evaluation as  `complete` or `incomplete`. The assignments measure a participant's achievement of the learning outcomes, and help technical facilitators determine if a participant has successfully completed the learning module. 

The `/02_activities/homework` directory contains homework participants can complete to further develop and practice the skills covered in a learning module. Homework is optional, but participants are encouraged to complete as much as they can.

### Week 1

#### Live Learning Session 1
The focus of this session is to deliver the `data_types` and `control_flow` content first, and let the cohort play around with it via `homework` or `assignment`. For `control_flow`, focus on `conditionals` and `for loops`. The cohort can go through the rest of the Python notebook and learn interactively.

#### Live Learning Session 2
The focus of this session is to deliver the `comments_and_errors`, `inputs`, `strings`, and `converting_types` content next. For `converting_types`, you can allow the cohort to go through the `converting_types` asynchronously, rather than synchronously.

#### Live Learning Session 3
TBD

#### Assignment 1
The assignment guides participants through programming an anagram checker. There are three parts to this assignment, where each part builds upon each other. Examples are given and it is up to the participants how they build the program.

### Week 2

#### Live Learning Session 4
Introduce the cohort to `functions` and `testing`. Spend more time on `functions` and emphasize how it allows anyone to create reusable blocks of code.

#### Live Learning Session 5
Introduce the cohort to `object_oriented_programming` and `numPy`. The emphasis will be on `numPy` as it is needed for their second assignment.

#### Assignment 2
The assignment in the second week of this module is to analyze a fictional clinical trial where 60 patients were administered a new drug for arthritis. Participants must evaluate the effectiveness of a fictional medication designed to reduce inflammation caused by arthritis flare-ups.

## How do you assign assignments?
Technical Facilitators are encouraged to introduce assignments as early as possible in the learning module. The Technical Facilitator should describe the assignment to participants and explain how the topics covered in the module will equip them with the knowledge and skills to complete the assignment.

## How an assignment is expected to be completed and delivered?
Participants are expected to complete the assignment by the end of the first week. They will deliver the assignment by opening a pull request on their copied repo. The participants will also add a Learning Support Staff as a reviewer indicating they delivered a completed assignment, and it is ready to be evaluated as `complete` or `incomplete`.

## What is the criteria for `complete` or `incomplete`?
The criteria for a `complete` or `incomplete` is if all parts of the program are working, and nothing in the code is broken. For some assignments, a rubric is provided outlining the criteria needed to assess an assignment as incomplete.

## How to evaluate?
If the participant's solution works, then their assignment should be assessed as `complete`! Technical Facilitators and the Learning Support Staff should focus on providing constructive feedback to participants who need to improve their code. If the solution does not work, then the assignment is `incomplete`. Facilitators should provide constructive feedback on their existing code, and guide them to get their solution working.

## How will feedback be given?
Feedback should be given through the pull request a participant has made. Technical Facilitators are encouraged to allow participants to make revisions if needed. In order to maximize learning, feedback should be constructive, and specific.

<hr>

## Definitions
**Live Learning Sessions**: A Live Learning Session is a synchronous period of time, lasting up to 2.5 hours, where the Technical Facilitator will facilitate and deliver the content and learning outcomes online through Zoom. Participants are encouraged to participate and ask questions as they learn. 10 minute breaks are encouraged once per hour.

**Work Period**: A Work Period is an asynchronous period of time, lasting up to 3 hours. Participants will work on assignments and/or homework during this block of time. Learning Support Staff are to be present online through Zoom to assist participants and answer any questions they may have. As work periods are asynchronous and flexible, participants can choose to work on their own time. However, it is encouraged that they work during the block of time when a Learning Support Staff is present.

**Assignments**: An Assignment is work assigned as part of the learning modules. They provide an opportunity for participants to integrate and synthesize what they have learned throughout the week to meet the set learning outcomes.

## generate_slides.sh

This script is designed to convert Markdown files located in a specified folder into slide presentations using Marp CLI, allowing for the generation of either HTML or PDF formats based on user input. It includes an option to apply a custom CSS theme to the slides by specifying a theme path. The script also provides a help function detailing its usage, options, and examples for convenience. It ensures the necessary directories exist, validates the presence of Marp CLI on the system, processes each Markdown file found in the specified directory, and outputs the generated slides into a designated output folder, displaying the status of each operation and a completion message. The only configuration needed is to set where the md files are and where you would like the pdf/html files to be placed.
