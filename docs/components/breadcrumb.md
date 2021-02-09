# Breadcrumb
A simple  **breadcrumb**  component to improve your navigation experience

The  **breadcrumb**  is a simple navigation component that only requires a  `breadcrumb`  container and a  `ul`  list. The dividers are automatically created in the content of the  `::before`(`:before` for support older browsers)  pseudo-element of  `li`  tags.

You can inform the current page using the  `current`  modifier in a  `li`  tag. It will disable the navigation of inner links.

## Example
```html
<ul class="breadcrumb">  
<li><a href="#">Home</a></li>  
<li><a href="#">Pictures</a></li>  
<li><a href="#">Summer 15</a></li>  
<li>Italy</li>  
</ul>
```
### Alternative separators

You can choose between  **4 additional separators**:  `arrow`  `bullet`  `dot`  and  `succeeds`.

### Develpment
- [ ] Implementation
  - [x] Basic
  - [ ] Alternative separators
- [ ] Tests
