# Short Answer Questions

Ingrid(Xinyue) Zeng
A00937032
Midterm for 1620 October 2020
BCIT

## Q1 . 
Git is a version control system that lets users manage and keep track of their source code history.It makes the project works easier and allows for team collaboration. Github is a cloud-based hosting service used to manage Git repositories. Git and Github are difference in many ways: Git is a software, while Github is a hosting service. Git is installed locally on the system, while GitHub is hosted on web. Git is a tool to manage different copies of source code, while GitHub is a space to upload the copy.

## Q2 .
Branch is different lines of development. It has a unique set of code changes with a unique name. Branching is useful when working on new features or bug fixes because it isolates the work from other team members. A branch can be created using the git command:
    1. git branch new_branch, then use git checkout new_branch to switch to it.
    2. or just git checkout -b

## Q3 .
When a requested resource is not found, HTTP 404 will show up instead. HTTP 404 is in the category of 4xx codes which indicate a client error. HTTP 404 is not permanent, which means the requested resource may be available in the future. The clients are also permitted to submit subsequent requests.

## Q4 . 
For the h2 in this html document, CSS is added in 2 ways, both with inline and internal. Internal CSS styles h2 green, while inline CSS styles h2 red. The h2 will be in red due to the cascading order of CSS: inline syles override internal CSS.

## Q5 .
URL is an address given to a gien unique source on the web. It has the follwing parts:
    1. Protocol: is a set of method for exchanging or transferring data around a computer network.
    2. Domain Name: is the name that browser uses to check with the server if website exists.
    3. Path: is the path to the resource(webpage) on the website.

## Q6 .
The HTTP header is a human readable name value pair serperated by a colon, added to the HTTP request or response, which can be used to pass standard or custom information back and forth between the user and the server.
    1. Server: contains information about the software used by the origin server to handle the request.
    2. Accept: is used to specify certain media types which are acceptable for the response.
    3. Date: is used to represent the date and time at which the message was originated.

## Q7 .
In the CSS Box Model, all HTML elements can be considered as boxes. The term 'box model' is used for describing design and layout. From the inside to the outside, different parts are:
    1. Content: is where text and images appear.
    2. Padding: is the area around the content.
    3. Border: is around the padding and content.
    4. Margin: is an area outside the border.

## Q8 .
    1. Descendant Combinator: matches all elements that are descendants of a specified element.
        ```
        div p {
          background-color: yellow;
        }
        ```
    2. Child Combinator: selects all elements that are the children of a specified element.
        ```
        div > p {
          background-color: yellow;
        }
        ```
    3. General Sibling Combinator: selects all elements that are siblings of a specified element.
        ```
        div ~ p {
          background-color: yellow;
        }
        ```
    4. Adjacent Sibling Combinator: selects all elements that are the adjacent siblings of a specified element.
        ```
        div + p {
          background-color: yellow;
        }
        ```

## Q9 .
Yes. In HTML, the `<p>` elements defines a paragraph, and it always starts on a new line.

## Q10 .
For the `<img>` tag, it is missing the required attribute 'alt'. 'alt' is the descriptive text that shows up when the image doesn't load.
For the `<a>` tag, the order of attribute is wrong. The title attribute should be right after the url and before the text that is visible to the user. The properly formatted version:
`<a href="https://bcit.ca" title="bcit">bcit site</a>`
