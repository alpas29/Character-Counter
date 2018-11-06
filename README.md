# Character Counter
Character Counter is a small jQuery plugin for inputs and textareas to count characters in it.

Demo: http://jsfiddle.net/alpas29/4h7p2ykq/2/

#Basic usage:

    $(".char-counter").charCounter();

#Options:

    backgroundColor: (string) Background of counter label.
    default: "#FFFFFF"

    position: (object) Label's position in element.
    default: {
	            right: 10,
	            top: 10
	         }
	font: (object) Label's font size and color.
	default: {
                size: 10,
                color: "#a59c8c"
             }
    limit: (integer) If you want to limit a textarea or an input, 
    you need to specify a limit. 
    If you don't want to limit your inputs set to 0.
    default: 255
    Also you can set the attribute "data-length" on input and set this size on this input.
    Example:
    
    	<input class="char-counter" type="text" data-length="200">
