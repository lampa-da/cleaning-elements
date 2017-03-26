# cleaning-elements
Unfortunately, we sometimes mix large floating elements with non-floating ones, and elements do end up on top of each other.

See your footer (the blue bit between the two columns)? It's stuck back there because we haven't told it something very important: to clear the other elements on the page!

If you tell an element to clear: left, it will immediately move below any floating elements on the left side of the page; it can also clear elements on the right. If you tell it to clear: both, it will get out of the way of elements floating on the left and right!
