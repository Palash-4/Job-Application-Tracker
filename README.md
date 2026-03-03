
# Main Requirements

## Design Part

## Dashboard
- Website name and Create a dashboard like figma 
- The section should be responsive for mobile devices. It is totally up to you. 

## Available Jobs Section
- A title on the left side, jobs count on the right side 
- 3 different tab  below the section title 
- Minimum 8 cards with:
	- companyName
	- position
	- location
	- type
	- salary
	- description
	- 2 buttons: Interview, Rejected
- By default all the jobs data will show on All tab, and the Interview, Rejected tab will show “No jobs Available” message with a subtitle below and an icon/image on the above

- The section should be responsive for mobile devices. It is totally up to you.

--- 

## Functionalities Part
- Clicking on Interview button on the card 
    - will add the data on Interview tab 
    - add the status as Interview.
    - Will increase the the count of interview in Dashboard 

- Clicking on Rejected button on the card 
    - will add the data on Rejected tab 
    - add the status as Rejected.
    - Will increase the the count of Rejected in Dashboard

- Enable toggle between Interview and rejected button(you can select Rejected button after clicking on Interview, and Interview button after clicking on Rejected button). It will change the tab and dashboard count also. It will show tab wise jobs count on the right.

---

# Challenges Requirements
- Clicking on the delete button will remove that card from the UI, and the count will be deducted from the dashboard card and the main section.
- No lorem ipsum text on your website. At least 8 meaningful commits in your project.  

- Create a readme file and answer this question on your own. Don’t copy-paste from Google or any AI chatbot. 


## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans:
getElementById():
This method selects only one element using its unique id.
Since id is always unique, it returns a single element.
It is fast and very specific.

getElementsByClassName():
This method selects all elements that have the same class name.
It returns a live HTMLCollection.
If elements are added or removed, the collection updates automatically.

querySelector():
This method selects the first element that matches a CSS selector.
We can use id,class,tag name more complex selectors.

querySelectorAll():
This method selects all elements that match a CSS selector.
It returns a static NodeList.
It does not update automatically when elements change.

### 2. How do you create and insert a new element into the DOM?
Ans:
First, we create a new element using document.createElement().
Then we add text,attributes,classes to it.
After that we insert it into the page using methods like appendChild() or append().
So the basic step are:
1.Create the element
2.Add content
3.Insert it into the DOM

### 3. What is Event Bubbling? And how does it work?
Ans:
Event Bubbling is a process in JavaScript where an event starts from the target element and then moves up to its parent elements.
For example if we click a button inside a div:
First, the button click event runs.
Then the event moves to the parent div.
Then it continues to body and other parent elements.
### 4. What is Event Delegation in JavaScript? Why is it useful?
Ans:
Event Delegation is a technique where we add one event listener to a parent element instead of adding many listeners to child elements.
Because of event bubbling, when we click a child element, the event goes up to the parent. So the parent can detect which child was clicked.
It is useful because:
It improves performance,reduces memory usage,dynamically added elements,keeps code cleaner and more maintainable.


### 5. What is the difference between preventDefault() and stopPropagation() methods?
Ans:
preventDefault():
This method stops the default action of the browser.
For example, it can stop a form from submitting or stop a link from opening a new page.
stopPropagation():
This method stops the event from moving up to parent elements.
It prevents event bubbling.

