# React Native Dimensions API Returns Incorrect Values

This repository demonstrates a bug and its solution related to the `Dimensions` API in React Native.  The bug involves getting incorrect or undefined dimensions, impacting layout and rendering.  The solution involves using useEffect and ensuring dimensions are accessed after they've been properly populated.

## Bug Description

The `Dimensions` API sometimes returns incorrect or undefined values when accessed too early in the component lifecycle. This results in layout issues where elements are improperly sized or positioned. 

## Solution

This repository provides a fix using `useEffect` to access the dimensions only after the component has mounted and the dimensions are available.