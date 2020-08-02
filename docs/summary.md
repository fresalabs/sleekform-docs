---
id: summary
title: Summary
sidebar_label: Summary
---

Summary component to list items under a heading and show the summary of those items.

## Usage

```
const items: Array<SummaryItemType> = [
  { itemName: 'T-Shirt', itemValue: '20$' },
  { itemName: 'Size', itemValue: 'L' },
  { itemName: 'Quantity', itemValue: '2' },
  { itemName: 'Your Email', itemValue: 'snkreddy1@gmail.com' },
  { itemName: 'Shipping', itemValue: 'Flat 108 first floor, Anvotha Bee, 7th cross Alfa-Garden, KR-Puram, 500049' },
];

<Summary 
 header="Order Summary:"
 items={items}
 summary={{ itemName: 'Sum total', itemValue: '50$' }}
/>
```

## Types
```
export type SummaryItemType = { itemName: string; itemValue: string };
```

## Props
The SummaryField supports the following properties

Props                             | Description                             | Type                              | Default
----------------------------------|-----------------------------------------|-----------------------------------|-----------
header                            | Heading of list of item.                | string                            | None
items                             | List of items shown under heading.      | Array<SummaryItemType>            | None
summary                           | Net summary of items                    | SummaryItemType                   | None
----------------------------------------------------------------------------------------------------------------------------


## Demo
You can view a live demo of SummaryField in [our sandbox](https://codesandbox.io/s/v004-byyzz)

