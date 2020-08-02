---
id: question
title: Question
sidebar_label: Question
---

Question is styled text component with `number` prop as serial number and `required` prop tell the question need to be answered. 

## Usage
```
<Question
 number={1}
 required={true}   
>
 We're looking for a Growth Hacker. Are you the right person for the job ?
</Question>
```

## Props
The QuestionField also supports the following properties

Props                             | Description                                 | Type                                  | Default
----------------------------------|---------------------------------------------|---------------------------------------|-----------
number?                           | The question number                         | number                                | None
required?                         | When the question required is true gets `*` at the question end | string            | None
--------------------------------------------------------------------------------------------------------------------------------

## Demo
You can view a live demo of QuestionField in [our sandbox](https://codesandbox.io/s/v004-byyzz)

