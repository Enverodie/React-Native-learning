# Meet 7 notes:

## I found these great resources if you want to know how to style various components.
* [Text](https://reactnative.dev/docs/text-style-props)
* [Layout (IT LITERALLY HAS AN INTERACTIVE LAYOUT)](https://reactnative.dev/docs/layout-props)
* [FlatList (Good for optimization because flatlists don't render what's not in view)](https://reactnative.dev/docs/flatlist)

**In order to scroll,** you need one of React Native's built in scroll components. This can either be [ScrollView](https://reactnative.dev/docs/scrollview), FlatList, or [SectionList](https://reactnative.dev/docs/sectionlist).
Additional note on FlatList: Unlike ScrollView components, one cannot simply call

```
 <Flatlist>
	<Component />
	<Component />
	<Component />
</Flatlist>
```

in order to scroll. Instead, you must itemize the component's props in an array, which the FlatList can then use to map to your <Component />. If you're unsure how to do this, read [the documentation](https://reactnative.dev/docs/flatlist) or ask Stephen during one of the meets.

# TODO for week 8:
