# What is dom
dom describes our html page as hierarchitectural tree of nodes
and each elements of the dom is a node
dom provides us api by which we can manipulate our html elements
inside the elements content are also node
this is called text node

1. always use document.querySelector() and querySelector.all() to grab the elements.
    query selector returns nodelist and document.getElementsbyTagName or classname
    return htmlcollection which should be converted to array by using
    Array.from(elements)


2. to cycel through the elements we need foreach function like
    node.foreach ((ele)=> console.log (ele))