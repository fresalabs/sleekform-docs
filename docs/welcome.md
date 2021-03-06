---
id: welcome
title: Welcome
sidebar_label: Welcome
---

Welcome is like a welcome screen.

## Usage

```
<Welcome
  header="Join Us"
  headerColor="White"
  description="We're looking for a Growth Hacker. Are you the right person for the job ?"
  buttonText="Lets Start"
  onButtonClick={() => console.log('welcome to sleek-form')}
/>
```

## Props
The WelcomeField supports the following properties

Props                             | Description                             | Type                              | Default
----------------------------------|-----------------------------------------|-----------------------------------|-----------
header?                           | Heading of welcome screen.              | string                            | None
headerColor?                      | Hex-code od header                      | string                            | None
description?                      | Description of welcome screen           | string                            | None
buttonText                        | Button text                             | string                            | None
onButtonClick                     | Button action                           | () => void;                       | None
----------------------------------------------------------------------------------------------------------------------------

## Preview
![alt](/img/welcome.png)

## Demo
You can view a live demo of WelcomeField in [our sandbox](https://codesandbox.io/s/v004-byyzz)

