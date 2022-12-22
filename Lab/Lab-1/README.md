# Lab 1: HTML Elements
Make a webpage with the following html elements:
   Nested order and unorder list
   Semantics tags for the layout
   Text formatting tags
   Image, video and audio
   Iframe


# HTML Lists:
    An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
    The list items will be marked with bullets (small black circles) by default:

    An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
    The list items will be marked with numbers by default:

# Semantics Tags:
    A semantic element clearly describes its meaning to both the browser and the developer.

    Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

    Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

# Text formatting tags:
    Formatting elements were designed to display special types of text:

    <b> - Bold text
    <strong> - Important text
    <i> - Italic text
    <em> - Emphasized text
    <mark> - Marked text
    <small> - Smaller text
    <del> - Deleted text
    <ins> - Inserted text
    <sub> - Subscript text
    <sup> - Superscript text

#  Image, video and audio:
    -Image:
        The HTML <img> tag is used to embed an image in a web page.

        Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.
        The <img> tag is empty, it contains attributes only, and does not have a closing tag.
        The <img> tag has two required attributes:

        src - Specifies the path to the image
        alt - Specifies an alternate text for the image 

    -Video:
        To show a video in HTML, use the <video> element:
        The controls attribute adds video controls, like play, pause, and volume.

        It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

        The <source> element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

        The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.
    
    -Audio:
        The HTML <audio> element is used to play an audio file on a web page.
        The controls attribute adds audio controls, like play, pause, and volume.

        The <source> element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.

        The text between the <audio> and </audio> tags will only be displayed in browsers that do not support the <audio> element. 

#   Iframe
    An HTML iframe is used to display a web page within a web page.
    The HTML iframe tag specifies an inline frame.
    An inline frame is used to embed another document within the current HTML document.
    Syntax: 
    <iframe src="url" title="description"></iframe>