---
id: text
title: Text
sidebar_label: Text
---

A basic widget for getting the user input is a text field. Keyboard and mouse can be used for providing or changing data.
It also supports errorMessage showcasing!

## Usage
```
<Text
  placeholder="https://"
  errorMessage="hmm.. that we address doesn't exist"
  onChange={(v) => console.log(v)}
/>
```

## Props
The TextField also supports the following  properties

Props                             | Description                             | Type                                  | Default
----------------------------------|-----------------------------------------|---------------------------------------|-----------
onChange?                         | onChange callback                       | (value?: string) => void;             | None
value?                            | Current selected text.                  | string                                | None
defaultValue?                     | Initial selected text.                  | string                                | None
name?                             | Name of the HTML Input.                 | string                                | None
placeholder?                      | Placeholder of select.                  | string                                | None
errorMessage?                     | The error message to be shown.          | string                                | None
--------------------------------------------------------------------------------------------------------------------------------

## Validation
You can pass validation errors to the TextField, which changes the color of field

## Demo
You can view a live demo of TextField in [our sandbox](https://github.com/)

