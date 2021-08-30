# Quick HTML references

- **!DOCTYPE html** tag (self closing) - Specifies the document type is html

- **html** tag - Everything goes inside html tags  
	>< html >  
	>  . . .  
	>< /html >

- **meta charset="UTF-8"** - Specifies the charachter set we will be using

- **head** tag - Site info that doesn't show in the webpage itself goes here, ideally. e.g. title
	>< head >  
	>. . .  
	>< /head >

	- **title** tag - This tag is used to display website info in the top tab space.
		>< tag >some text< /title >

- **body** tag - Everything that shows up on the webpage is inside of the body tag
	>< body >  
	>every freakin' thing  
	>< /body >
	
	- **h1 to h6** tags - These are for different sizes of texts biggest is h1 and smallest is h6.
		>< h1 >text< /h1 >

	- **p** tag - Paragraph tags for, well, paragraphs or small text. Their text size is similar to h4.
		>< p >Lorem ipsum< / p>

	- **a** tag - Anchor tag is used to create links to external/internal webpages.
		>< a href="somewebsite/#some_id" target="_blank">some text< /a >

		- **href** attribute - Hypertext reference or href attribute contains the link to the webpage.

			*It either contains an external link or link to the same page id using # symbol, e.g.*
				
			>*linking to external site*  
			>
			>< a href="https://www.duckduckgo.com" >some text< /a >  

			>*linking to internal element the current page*  
			>
			>< a href="#footer">some text< /a >  
			>
			>*paired with an id attribute in a different element*  
			>
			>< p id="footer">footer< /p >

			*href can be used to make dead links as well when the # is used alone. This is useful as placeholder for future links*

			>< a href="#">dead link< /a >

		- **target** attribute - This attribute is used to specify where the new link will be opened.
			>< a href="https://www.duckduckgo.com" target = "_blank">some text< /a >
			>
			>*This opens the webpage in a new tab*
	- **img** tag (self closing) - The image tag is used to display images on a webpage.
		- **src** attribute - The source attribute is used to specify location of said image, whether it be on local storage or as an external link.
			>< img src="image path/URL" >

		- **alt** attribute - The alternate atrribute is used to specify alternate text for the image file in case the image fails to load for any reaason.
			>< img src="image path/URL" alt="info about the image" >
		- **width** attribute - The width attribute sets the image width to specified pixels.  
		***The height attibute does the same thing, vertically.***

			>< img src="image path/URL" alt="info about the image" width=150 >

	- **div** tag - The division tags are **important** in a sense that they divide up the html into sections which can then be worked on by CSS or Javascript individually. The **id** attribute can be used to identify them for easier manipulation. (further study required)
		>< div >  
		>. . .  
		>< /div >

	- **input** tag (self closing) - The input tag is used to take data input from users.

		- **type** attribute - The type attribute is used to specify which kind of data is to be expected from user.
			>< input type="text" >
			- **radio** type - Radio is a type of input type. Basically MCQs.
				>< input type="radio" >
		
		- **placeholder** attribute - The placeholder attribute is used to display some text in the input field before any data is fed by the user.
			>< input type="text" placeholder="Name" >

		- **required** attribute - The required attribute is used when a form fill is required.
			>< nput type="text" required >

	- **form** tag - The form tag is used to create web forms. This is useful in storing data from the user.  
		*It is used in conjunction with the **input** and the **action** attributes which specify the data from user and the URL of where said data is to be sent/stored.*

		>< form action="URL of database" >< input type="text" >< /form >

	- **button** tag - The button tag adds buttons.  
	*Uses the **type** attribute.*
		>< button type="Submit">Submit< /button >
			