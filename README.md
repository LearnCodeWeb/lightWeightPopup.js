# lightWeightPopup.js
How to create a custom POPUP form with PHP &amp; Ajax

<h1>Add Files</h1>

```
<link rel="stylesheet" href="lightweightpopup.css" type="text/css">
```

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script src="lightWeightPopup.js"></script>
```

<h1>Initialization</h1>

```javascript
$(document).ready(function(e) {
	$("#popup").lightWeightPopup({href:"contact-us.html", overlay:true, width:"90%", maxWidth:"600px", title:"Ajax Model"});
	$("#inline").lightWeightPopup({title:"Inline Model"});
	$("#ancher").lightWeightPopup({width:"95%", maxWidth:"320px", title:"Ajax Model"});
	$("#iframe").lightWeightPopup({href:"https://www.youtube.com/embed/N59KnLf2pbY", maxWidth:"600px", height:"400px", title:"Iframe Model"});
	$(".iframe").lightWeightPopup({width:"100%", height:"100%", title:"Iframe Model"});
});
```

<h1>Complete Detail</h1>

For complete documentation <a href="https://learncodeweb.com/web-development/how-to-create-a-custom-popup-form-with-php-and-ajax/" target="_blank">click here</a>


For demo <a href="https://learncodeweb.com/demo/web-development/how-to-create-a-custom-popup-form-with-php-and-ajax/" target="_blank">click here</a>
