# Notes for meet 2:

## Installing & Using React:
npx create-react-app "appname" - This will set up all of the React dependencies, the src folder, and everything else you need to get started. It's actually crazy simple to set up.
then, in the folder containing your react project, type `npm start`
You can also use `ctrl + C` to kill a running program in a terminal

If you don't have npm installed, you have to install it first!

Any JavaScript file you want to be rendered with React.js must be exported using export default NameOfMainClassorFunction.
It must then be imported into App.js or equivalent parent script using import NameOfMainClassorFunction from './NameOfScript'


According to Zach, REACT =/= REACT NATIVE. You CANNOT convert a react project to react native, as they are programmed entirely differently.
React is learned first because it helps users understand how to write HTML style script without it actually being HTML.
> It may be a good idea to get into React Native as soon as possible, as [multiple threads I've read](https://www.reddit.com/r/reactnative/comments/a9fqv7/should_i_learn_reactjs_before_learning_react/) indicate that React is not a mandatory prerequisite to React Native.

## Other notes:
npm is a package manager for javascript, just like pip is a package manager for Python.


#### If you find out the answers to any of these questions before the next meet, please commit a change to this document explaining in the notes! This will save us time.
Also, feel free to add more items to the todo list!

# TODO for next Wednesday (in order of priority):
* Ensure everyone has a working React project tree. Create a basic new UI from scratch, removing the non-essential React source code.
* Find out how React interacts with HTML. How is React executed? How does the client interact with it?
* Modify the notes_meet3.md file to reflect the collaborative findings of the group regarding:
  * React execution (see bullet #2)
  * Other general interesting/notable findings
* Begin looking into how to install React Native
  * If you get to this point, create a new section in the notes with corresponding instructions on how to do so (similarly to the instructions in this document (above) about how to install React).
