
**Purpose**

Simple Typescript Definition for [gintersect by anvaka](https://github.com/anvaka/gintersect "gintersect github")

**Usage**

    import intersect from "gintersect";
    
	var intersection = intersect(
	  // first segment
	  -1, 1, // start
	  1, -1, // end
	  // second segment
	  -1, -1, // start
	  1, 1 // end
	);
	console.log(intersection);
	// prints {x: 0, y: 0} - intersection point of two segments or returns falsy (null)