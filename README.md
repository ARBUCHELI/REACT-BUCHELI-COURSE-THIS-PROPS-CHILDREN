# REACT-LESSONS-INSTRUCTOR-ANDRES-R.-BUCHELI

## Take a look to the live example at:
https://bucheli-web-development-react-course-this-props-children.netlify.app/

## Usage:
* Rendering all the page from an App component.
* Creating an index entry point for all the application.
* Import the main component into the index file.
* Import components into the App component.
* Passing props from the parent component to the child component.
* The child component access the data via this.props.(name of the prop).
* Rendering child components.

## Important consideration:
* If a component has more than one child between its JSX tags, then this.props.children will return those children in an array. However, if a component has only one child, then this.props.children will return the single child, not wrapped in an array.
