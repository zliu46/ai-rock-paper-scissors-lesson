# Teacher Guide

## Project
AI Rock Paper Scissors Lesson

## GitHub Repository
https://github.com/zliu46/ai-rock-paper-scissors-lesson.git

## Overview
This lesson introduces students to AI-assisted game design by combining a simple Rock Paper Scissors project with Teachable Machine and beginner-friendly coding. Students explore how a machine learning model can recognize hand gestures and then use that model in a classroom coding project.

The main goal is not only to complete the project, but also to help students understand how to:
- train a basic image model
- test whether the model works reliably
- connect the model to a simple interactive program
- reflect on the strengths and limits of AI tools in creative work

## Recommended Grade Level
Upper elementary, middle school, or early high school, depending on how much coding support students need.

## Suggested Lesson Length
45 to 60 minutes

A possible breakdown:
- 5–10 min: introduction and project preview
- 10–15 min: create and train the Teachable Machine model
- 15–20 min: connect the model to the project
- 10–15 min: testing, debugging, and reflection

## Learning Goals
By the end of the lesson, students should be able to:
- explain what the project does
- create three image classes: Rock, Paper, and Scissors
- collect image samples for each class
- train and test a simple model in Teachable Machine
- export the model link for use in the coding project
- describe one thing AI does well and one limitation it has

## Student Prerequisites
Students do not need prior machine learning experience.

Helpful prior experience:
- basic computer navigation
- typing and copying/pasting text or links
- simple familiarity with classroom coding platforms or browser-based projects

## Materials and Setup
Teachers should prepare:
- laptops or desktop computers with internet access
- webcams enabled on student devices, or a set of saved hand-pose images
- access to the coding project starter files
- access to the Teachable Machine website
- projector or screen for modeling the steps live

Before class, check that:
- webcams work in the browser
- the school network allows access to Teachable Machine and GitHub
- students can open the starter project
- at least one complete example works from beginning to end

## Teacher Preparation
Before teaching the lesson, it helps to:
1. Build the project once yourself.
2. Train a sample model with Rock, Paper, and Scissors.
3. Test whether the exported model link works inside the coding project.
4. Decide whether students will use live webcam images or uploaded images.
5. Review the troubleshooting section below.

## Teaching Notes
### What to emphasize
- Students are not “teaching the computer perfectly”; they are giving it examples.
- A model works better when the examples are clear, varied, and balanced.
- Testing matters. Students should expect to revise and retrain.
- AI output should be checked, not assumed to be correct.

### What students often misunderstand
- They may think more pictures always means better results, even if the images are low quality.
- They may accidentally collect very similar images for every class.
- They may think the model is broken when the lighting or hand position changes.
- They may confuse the exported model link with the project URL.

## Suggested Teaching Flow
### 1. Introduce the project
Show students the finished result first. Explain that they will train a computer to recognize hand signs for Rock, Paper, and Scissors, then connect that model to a game.

### 2. Create classes
Students create three classes in Teachable Machine:
- Rock
- Paper
- Scissors

Explain that each class should represent one clear hand gesture.

### 3. Collect samples
Students collect several example images for each class using the webcam or uploaded images.

Teacher reminders:
- Keep the background reasonably consistent.
- Make the hand gesture clear.
- Use enough variety in angle and distance.
- Try to collect a similar number of images for each class.

### 4. Train the model
Students click **Train Model** and wait for the training process to complete.

During this step, ask students to predict:
- Which class will be easiest to recognize?
- Which class might get confused with another?

### 5. Test the preview
Students test the preview with live gestures.

Encourage them to notice:
- whether the correct class gets the highest score
- whether some gestures are confused
- whether retraining is needed

### 6. Export the model
Students click **Export Model**, then copy the shareable link or relevant model output needed for the coding project.

Make sure students save the correct link.

### 7. Connect to the coding project
Students paste the model information into the project and test whether the game responds correctly to Rock, Paper, and Scissors.

### 8. Reflect
Close with a short reflection:
- What helped the model work well?
- What made it less reliable?
- How is this different from regular coding?

## Checks for Understanding
Use quick questions throughout the lesson:
- What is each class supposed to represent?
- Why do we need multiple samples for each class?
- What do you do if the preview prediction is inconsistent?
- Why should the number of samples be similar across classes?
- What exactly are you copying from the export step?

## Common Student Problems and Fixes
### Problem: The model confuses Rock and Scissors
Possible fixes:
- add more distinct examples
- change the hand angle
- improve lighting
- remove unclear samples
- retrain the model

### Problem: One class has far fewer images
Possible fix:
- collect more samples until the classes are more balanced

### Problem: Webcam does not work
Possible fixes:
- refresh the browser
- allow camera permissions
- switch browsers
- use uploaded images instead

### Problem: The coding project does not respond
Possible fixes:
- confirm the correct model link was copied
- check that the model was fully trained
- verify the link was pasted in the correct place
- test the project with the teacher’s working example

### Problem: Students rush through sample collection
Possible fix:
- require a quick teacher check before training

## Differentiation
### For students who need more support
- provide a partially prepared starter project
- give a fixed minimum image target for each class
- use a whole-class model first before independent work
- pair students for sample collection and testing

### For students ready for extension
- add a fourth custom gesture
- compare two differently trained models
- test how background or lighting affects results
- ask students to redesign the game or scoring system

## Assessment Ideas
You can assess students based on:
- completion of the three classes
- successful model training
- ability to test and improve the model
- correct connection of the model to the project
- reflection on model performance

Simple evidence of learning could include:
- a working demo
- a screenshot of the trained model preview
- a copied export link placed in the project
- a short written reflection

## Reflection Questions
Use one or two at the end:
- What made your model more accurate?
- What mistakes did your model make?
- What would you improve if you had more time?
- How is training a model different from writing step-by-step code?

## Optional Extension
Have students compare their models with classmates and discuss:
- which model performs more consistently
- how sample quality changed the outcome
- whether fairness and balance matter in training data

## Related Files in This Repository
- `lesson-plan/` — lesson documents
- `screenshots/` — visual setup guide
- `project-example/` — project example files


## Final Teacher Tip
Keep the pace focused on understanding and testing, not just finishing. Students learn the most when they notice why a model succeeds, why it fails, and how better examples improve the result.
