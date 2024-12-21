# React Native FlatList Rendering Issue

This repository demonstrates a common issue in React Native: a FlatList component failing to render items even when the data array is populated. The problem is resolved by correctly implementing the `keyExtractor` prop.

## Bug Description
The `FlatList` component in React Native does not render any items, even though the data array contains elements. This often happens due to a missing or incorrectly implemented `keyExtractor` function.

## Bug Solution
The solution involves providing a unique key for each item in the `data` array using the `keyExtractor` prop.  This allows `FlatList` to correctly identify and render each item.