---
id: scale
title: Scale Field
sidebar_label: Scale Field
---

Scale fields let users to choose a scale.

## Scale Field

The ScaleField component is a complete form control.

## Usage

```
<Scale
  values={[
    { label: 'dark', value: 'dark' },
    { label: 'wheatish', value: 'wheatish', number: 3 },
    { value: 'wheatish brown', number: 7 },
    { value: 'bright', number: 11 },
    { label: 'very fair', value: 'very fair', number: 15 },
  ]}
  defaultValue={{ value: 'bright', number: 11 }}
  onChange={(value) => console.log(value)}
/>
```

## Types
```
type ScaleValueType = { label?: string; value: string; number?: number };
```

## Props
The ScaleField supports the following properties

Props                             | Description                             | Type                              | Default
----------------------------------|-----------------------------------------|-----------------------------------|-----------
onChange?                         | onChange callback                       | (value: ScaleValueType) => void;  | None
value?                            | Current selected rating.                | ScaleValueType                    | None
defaultValue?                     | Initial selected rating.                | ScaleValueType                    | None
values                            | array of values of the scale            | Array<ScaleValueType>             | None
----------------------------------------------------------------------------------------------------------------------------


## Demo
You can view a live demo of ScaleField in [our sandbox](https://github.com/)

