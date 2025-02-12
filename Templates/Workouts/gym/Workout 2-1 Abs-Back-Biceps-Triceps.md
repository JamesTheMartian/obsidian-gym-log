---
date: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
workout_title: Workout 2:1 Mage-Rygg-Biceps-Triceps
exercises: [293271, 291088]
workout_order: [293271, 291088]
workout: 2-1
type: 2
sub_type: 1
tags:
 - workout
---

```dataviewjs

const {workout} = customJS;
const note = {dv: dv, container: this.container, window: window};

workout.renderHeader(note);

```

## Remaining Exercises
```dataviewjs

const {workout} = customJS;
const note = {dv: dv, container: this.container, window: window};

workout.renderRemaining(note);

```

## Performed Exercises
```meta-bind-button
style: primary
label: Log
action:
  type: command
  command: quickadd:choice:d5df32b0-6a04-481d-9a8d-b9bd1b2f0ea7
```
^button-2vzj
```dataviewjs

const {workout} = customJS;
const note = {dv: dv, container: this.container, window: window};

workout.renderPerformed(note);
workout.renderEffortChart(note);

```