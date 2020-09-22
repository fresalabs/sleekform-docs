---
id: sleekFormThemProvider
title: SleekFormThemProvider
sidebar_label: SleekFormThemProvider
---

`SleekFormThemeProvider` provides a way to pass custom styles to sleekform components. These styles are passed to all children.

## Usage

```

const theme = {
  heights: {
    tiny: heights.TINY,
    small: heights.SMALL,
    medium: heights.MEDIUM,
    large: heights.LARGE,
    extraLarge: heights.EXTRA_LARGE,
  },
  paddings: {
    tiny: paddings.TINY,
    small: paddings.SMALL,
    medium: paddings.MEDIUM,
    large: paddings.LARGE,
    extraLarge: paddings.EXTRA_LARGE,
  },
  margins: {
    tiny: margins.TINY,
    small: margins.SMALL,
    medium: margins.MEDIUM,
    large: margins.LARGE,
    largeInt: margins.LARGE_INT,
    extraLarge: margins.EXTRA_LARGE,
  },
  letterSpacings: {
    tiny: letterSpacings.TINY,
    small: letterSpacings.SMALL,
  },
  fontWeights: {
    thin: fontWeights.THIN,
    normal: fontWeights.NORMAL,
    medium: fontWeights.MEDIUM,
    thick: fontWeights.THICK,
    bold: fontWeights.BOLD,
  },
  fontFamily: '"Graphik Web", Lato, "Helvetica Neue", Helvetica, sans-serif',
  fontSizes: {
    extraTiny: fontSizes.EXTRA_TINY,
    tiny: fontSizes.TINY,
    small: fontSizes.SMALL,
    medium: fontSizes.MEDIUM,
    large: fontSizes.LARGE,
    xlLarge: fontSizes.XL_LARGE,
    extraLarge: fontSizes.EXTRA_LARGE,
  },
  lineHeights: {
    extraTiny: lineHeights.EXTRA_TINY,
    tiny: lineHeights.TINY,
    small: lineHeights.SMALL,
    medium: lineHeights.MEDIUM,
    large: lineHeights.LARGE,
    extraLarge: lineHeights.EXTRA_LARGE,
  },
  iconSizes: {
    small: sizes.ICON_SMALL,
    medium: sizes.ICON_MEDIUM,
    large: sizes.ICON_LARGE,
  },
  sizes: {
    tiny: sizes.TINY,
    small: sizes.SMALL,
    medium: sizes.MEDIUM,
    large: sizes.LARGE,
    extraLarge: sizes.EXTRA_LARGE,
  },
  backgroundImage: "url('https://images.typeform.com/images/YuBdD6m3incD/background/large')",
  componentsBackGroundColor: 'rgba(26, 145, 162, 0.1)',
  buttonBackgroundColor: 'white',
  questionColor: 'rgb(83, 83, 83)',
  answerColor: 'rgb(26, 145, 162)',
  selectOptionsColor: 'rgba(83, 83, 83, 0.1)',
  selectOptionsHoverColor: 'rgba(83, 83, 83, 0.2)',
  selectOptionsSelectedColor: 'rgba(83, 83, 83, 0.6)',
  selectOptionsFocusedColor: 'rgba(83, 83, 83, 0.4)',
  selectOptionsBorderColor: 'rgba(83, 83, 83)',
  errorContainerBackgroundColor: 'rgba(153, 0, 0, 0.6)',
  errorMessageColor: 'white',
  buttonTextColor: linkBlue,
  numberColor: 'red',
  pressEnterColor: 'red',
  toastBackgroundColor: 'red',
  toastTextColor: 'red',
  footerBackgroundColor: 'red',
  footerTextColor: 'red',
  progressColor: 'red',
  progressTextColor: 'red',
};

<SleekFormThemeProvider>
    <Question
     number={1}
     required={true}   
    >
     We're looking for a Growth Hacker. Are you the right person for the job ?
    </Question>
</SleekFormThemeProvider>

```

## Props
The SleekFormThemeProvider supports the following properties

Props                             | Description                                   | Type                              | Default
----------------------------------|-----------------------------------------------|-----------------------------------|-----------
sleekFormTheme?                   | The customised theme for sleekform components | Similar to above theme object     | theme 
---------------------------------------------------------------------------------------------------------------------------------

## Preview
![alt](/img/sleekformthemeprovider.png)

## Demo
You can view a live demo of SleekFormThemeProvider in [our sandbox](https://codesandbox.io/s/v004-byyzz)

