**9/18/22**
	- made a [responsive navbar](https://codepen.io/evelyndale/pen/KKRmqNo?editors=0010) from a youtube tutorial
	- peeked at [emmet cheat sheet](https://docs.emmet.io/cheat-sheet/)
	- worked on coding train's data & api's course. [my project repo](https://github.com/evelyndale/Working-With-Data-and-APIs)
	- worked on [ShaiUI's tutorial](https://www.youtube.com/watch?v=xBQef0fs-_Q&t=784s) on making a live tone.js editor [my project repo](https://github.com/evelyndale/tonejs-live-editor)
**9/19/22**
	- **idea**:  website that creates a procedurally generated synthesizer interface each day. users submit music they created with each day's synth to a central repository for sharing.
	- 
**9/20/22**
	- **idea**: make a website for the Cats blender plugin. can use 3.js to show the models off
	- Worked on [tone.js synth ](https://codepen.io/evelyndale/pen/jOxwjQY)
**9/21/22**
	- Studied from Colt Steele Udemy Bootcamp
		- Element selection and style manipulation: 
			- `.querySelector()` and `.querySelectorAll()`
			-  `window.getComputedStyle()` 
			- `.getAttribute()` and `.setAttribute()`
			-  `.classList` to read and `.classList.add()` to write classes to elements
			- `.classList.toggle()` and `.classList.contains()`
		- Traversing parent/child/sibling
			- `.parentElement`
			-  `.children[]` returns child element at given index
				- note that `.children` will return an *HTML collection*, which looks like an array but isn't!
			- `.nextSibling` and `.previousSibling` return *nodes*, not elements, so generally don't use them. For example, if you use .nextSibling to select an img tag, it will actually return a text node, because there's a sneaky return character in there
			- `.nextElementSibling` and `.previousElementSibling` are what you want to use
		- Appending and removing
			- `document.createElement()`
			- `.appendChild()`
				- general workflow is something like:
					1. createElement (creates a new element but it has empty properties)
					2. add content, attributes, etc. to the element, e.g. newElement.innerText()
					3. append the element
			- `.append()` and `.prepend()`
			- `.insertAdjacentElement()` 
			- `.after()`
			- `.remove()` and `.removeChild()`
**9/22/22**
	- Colt Steele Udemy
		- `console.dir()`
		- Events! [MDN Link](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)
		- `.addEventListener()` is the **preferred** way to handle events
			- otherwise you can only have one callback function per event, since each new function overrides the previous 
			-syntax:  `myCoolElement.addEventListener("click", function(){ thing to happen });`
		- there are many events, such as `onmouseclick`,` onmouseenter`
		- Events can have options, such as `once` (see [MDN docs](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener))
		- `for of` loops
		- event object
	- Responsive Design at [web.dev](https://web.dev/learn/)
	- column.count
**9/23/22**
	- Web Developer Bootcamp
	- Event Object (e) or (evt)
	- e.key and e.code to read keyboard input
	- `switch(e.code){case 'ArrowUp'}`, for example, is a good way to check keys
	- Event Bubbling and e.stopPropagation()
	- Event Delegation
	- add an event listener to the parent element, then target the child element with the .target property, like ``(e).target.remove()
		- or `e.target.nodeName === 'LI' && e.target.remove()`
			- && in this case acts as an IF statement and only runs e.target.remove() if target.nodeName is LI (Short Circuit Operator, which stops evaluating if the condition on the left of the operator is false)
	- Understanding WAV with JavaScript [video link](https://www.youtube.com/watch?v=udbA7u1zYfc)
**9/24/22**
	- Frontend Mentor [Order Summary Component](https://www.frontendmentor.io/home/my-challenges)
	- https://csslayout.io/
**9/25/22**
	- [[React]] from the [Udemy course](https://www.udemy.com/course/react-the-complete-guide-incl-redux/learn/lecture/25595448#overview). Section 3, lessons 24-39
	- [[VSCode]] tip: Emmet Wrap in Tag, I've mapped to `shift + alt + w`
	toISOString to format `date` objects in js
**9/26/22**
	- [[React]], via [Udemy React Course](https://www.udemy.com/course/react-the-complete-guide-incl-redux/learn/lecture/25595454#content)
	- **Needs Review:**
	- {props.children}
	- default html elements automatically support className, but your custom components only support what you tell them, so you must explicitly declare that a className can be set on your component
	- both of the above are from From [lesson 40 of the React course](https://www.udemy.com/course/react-the-complete-guide-incl-redux/learn/lecture/25595454#content)
**9/27/22**
	- Spent much of the dang day trying to install Pop OS 22.04 with no luck.
		- Got black screen immediately after hitting the "try out pop" graphic which appears right after bios
		- did some extensive troubleshooting with guides such as these:
			- https://github.com/pop-os/pop/issues/1112
			- https://www.reddit.com/r/pop_os/comments/q09n7x/that_common_black_screen_on_boot_issue/
	- Eventually gave up and installed Ubuntu. Enjoying it for now.
**9/28/22**
	- [[Linux]]
	- Flatpak location: `/var/lib/flatpak/app`

