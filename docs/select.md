---
id: select
title: Select
sidebar_label: Select
---

Select component to select value from options.

## Usage

```
const options: Array<OptionType> = [
  {
    label: 'India',
    value: 'India',
  },
  {
    label: 'China',
    value: 'China',
  },
  {
    label: 'Cuba',
    value: 'Cuba',
  },
];

<SleekSelect
  options={options}
  placeholder="Select a Country"
  defaultValue={options[0]}
  onChange={(value: OptionType) => console.log(value.value)}
/>
```

## Types
```
export type OptionType = { label: string; value: string };
```

## Props
The SelectField supports the following properties

Props                             | Description                             | Type                              | Default
----------------------------------|-----------------------------------------|-----------------------------------|-----------
onChange?                         | onChange callback                       | (value: OptionType) => void;      | None
placeholder?                      | Placeholder of select.                  | string                            | None
value?                            | Current selected rating.                | OptionType                        | None
defaultValue?                     | Initial selected rating.                | OptionType                        | None
name?                             | Name of the HTML Input (optional - without this, no input will be rendered) | string | None
options                           | array of values of the scale            | Array<OptionType>                 | None
----------------------------------------------------------------------------------------------------------------------------


## Demo
You can view a live demo of SelectField in [our sandbox](https://github.com/)

