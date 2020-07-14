---
id: rating
title: Rating
sidebar_label: Rating
---

Rating fields let users to rate things.

## Rating Field

The RatingField component is a complete form control including customized rating symbols, rating step size.

## Usage

```
<Rating 
  step={1} 
  start={0} 
  stop={5} 
  emptySymbol={empty1}
  fullSymbol={full1}
/>
```

## Props
The RatingField supports the following properties

Props                             | Description                             | Type                      | Default
----------------------------------|-----------------------------------------|---------------------------|-----------
onChange?                         | onChange callback                       | (value: number) => void   | None
value?                            | Current selected rating.                | number                    | None
defaultValue?                     | Initial selected rating.                | number                    | None
start                             | Range starting value (exclusive).       | number                    | None
stop                              | Range stop value (inclusive).           | number                    | None
step                              | Describes how many values each Symbol represents. For example, for a start value of 0, a stop value of 10 and a step of 2, we will end up with 5 Symbols, with each Symbol representing value increments of 2.| number | None
emptySymbol                       | element or object or string or array	| React.ReactElement        | None
fullSymbol                        | element or object or string or array	| React.ReactElement        | None
----------------------------------------------------------------------------------------------------------


## Demo
You can view a live demo of RatingField in [our sandbox](https://github.com/)

