---
id: radio
title: Radio
sidebar_label: Radio
---

- Used to select a single state from multiple options.
- The difference from Select is that Radio is visible to the user and can facilitate the comparison of choice, which means there shouldn't be too many of them.

## Usage

```
const options: Array<Option> = [
  { key: 'A', value: 'male' },
  { key: 'B', value: 'female' },
  { key: 'C', value: 'transgender' },
];

<Radio
 name="gender"
 options={options}
 value="male"
 onChange={(e, value) => console.log(value)}
/>
```

## Types
```
export type Option = { key: Char; value: string };
```

## Props
The RadioField supports the following properties

Props                             | Description                             | Type                                                | Default
----------------------------------|-----------------------------------------|-----------------------------------------------------|-----------
onChange?                         | onChange callback                       | (e: React.MouseEvent | null, value: string) => void;| None
value?                            | Current selected radio option.          | string                                              | None
defaultValue?                     | Initial selected radio option.          | string                                              | None
name?                             | Name of the HTML Input                  | string                                              | None
options                           | array of values of the radio            | Array<Option>                                       | None
----------------------------------------------------------------------------------------------------------------------------------------------

## Demo
You can view a live demo of RadioField in [our sandbox](https://github.com/)

