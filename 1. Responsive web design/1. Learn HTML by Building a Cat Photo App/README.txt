nesting
	Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.\

<img>: elements have an opening tag without a closing tag
	Attributes
	src=""
	alt

<a href='...'>...</a>
	target=_blank

section: element to separate the cat photos content from the future content

ul: unordered list

figure: element represents self-contained content and will allow you to associate an image with a caption
	figcaption

<em></em>: chữ nghiêng
<strong></strong>: chữ đậm

<form>
	action="link" : the data should be sent to the link (attribute)
	<input>: self closing
		type="..." : text, password, radio
		name="..."
		placeholder
		required
		id="..."
		value="..." : value as id
	<button>
		type="...": submit

fieldset:used to group related inputs and labels together in a web form.fieldset elements are block-level elements, meaning that they appear on a new line.
	<legend> : act as a caption for the content in the fieldset
	
	<label>: used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers)

Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.

There's another way to associate an input element's text with the element itself. You can nest the text within a label element and add a for attribute with the same value as the input element's id attribute.