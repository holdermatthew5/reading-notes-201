- `<form>` - surrounds actual input boxes/submit buttons. action attribute is mandatory and describes url of server that will communicate with the input. method attribute describes how it will be communicated ('get' retrieves info and is good for search boxes; 'post' sends values to server in http headers and should be used for file upload, sensitive data, adds removes info from a database, or lengthy input boxes). get is used if method attribute is not used
- `<input>` - creates different form controls. type describes what info the control will transmit and text makes a text box. name is a mandatory attribute and assignes a name to the input for reference. maxlength attribute is NOT mandatory and limits the number of characters the input box will take. size is old and shouldn't be used anymore (use css instead), but it was used to describe a specific input box length in characters but does not limit input length.
- password as a type acts like a normal text input box, but blocks out the actual characters used. name, size and maxlength apply. This does not secure data. An SSL should be used to secure data, but that's a whole other course.
- any text put in opening and closing `<textarea>` tags by the developer is put inside the text box.
- col and row attributes measure box size by character and should not be used anymore (use css instead).
- radio as a type creates circle check box where you only choose one. names will be the same for the same question. checked attribute auto checks a circle when page loads.
- checkbox as a type makes checklist type checkboxes name value is same for same question. value attribute describes what will be sent to the server if the box is checked. name applies.
- `<select>` - drop down box. `<option>` - surrounds drop down box choices. ^value applies^. selected attribute auto selects a choice when page loads (first option shown if not used). Only one can be chosen. works better for long lists of choices. size atribute allows more than one option to show at a time, but doesn't work well with some browsers. multiple attribute with value attribute allows multiple choices in drop down box. name applies
- file as a type lets you upload a file and shows as a text box and browse/choose file button.
- submit as a type makes a submit button. value shows what the button says. name applies.
- image as a type allows you to use an image as a submit button with src attribute. mind original size.
- `<button>` allows other elements to appear inside a submit button with no input tags like img and p
- hidden as an input type hides the control for use by developer and not by user. can be seen in sources, but not on page.
- surround input in label tags to tell the user what to type (username:, age:, password:...). can also be used not surrounding input by putting id value in for attribute. place top or bottom of referenced tag for left or right positioning espectively.
- fieldset tags surround all inputs desired to create surrounding box. legend tags put a name onscreen on the fieldset border line.
- `required="required"` makes sure the user puts readable info in before doing anything else.
- date as type creates date box.
- email as type creates email input box (some browsers put related characters in modified keyboard for user ease).
- url as a type makes sure the user types something in a proper url format.
- use search as type for search boxes (creates single line search box some browsers add functionality to this).
- placeholder attribute puts temp text in text box until user clicks/starts typing.
- bullet appearance controlled by `list-style-type:` rule.
- `list-style-image: url();` replaces bullet with image.
- `list-style-position:` with inside/outside value determines whether the text will wrap arround its bullet.
- `list-style:` acts as a shorthand like `border: 1px solid black;`.
- text transform topo make table headers uppercase
- letter spacing
- `empty-cells: show;` adds styling to empty boxes (they're not normsally affected by styling). hide hides it and inherit uses styling from parent graph.
- border-spacing/collapse seperate i collapse adds space between graph boxes. px in spacing.
- :focus changes input box background color when in use
- background-image can apply to text boxes for small icon as descriptor
- text-shadow gives 3d appearance
- class reference add float to align boxes despite descriptor length
- web dev tool kits available as browser extension to aid in writing
