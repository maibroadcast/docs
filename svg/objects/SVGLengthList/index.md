---
title: SVGLengthList
attributions:
  - 'Microsoft Developer Network: [[Windows Internet Explorer API reference](http://msdn.microsoft.com/en-us/library/ie/hh828809%28v=vs.85%29.aspx) Article]'
notes:
  - 'Unreviewed MSDN import'
readiness: 'Not Ready'
relationships:
  subclass_of:
    predicate: 'Inherits from '
    value: SVGElement
    href: /svg/objects/SVGElement
standardization_status: Unknown
tags:
  - API
  - Objects
  - DOM
uri: svg/objects/SVGLengthList

---
Inherits from [SVGElement](/svg/objects/SVGElement)[SVGElement](/svg/objects/SVGElement)

## Properties

*No properties.*

## Methods

*No methods.*

## Events

*No events.*

## Inherited from SVGElement

### Properties

*No properties.*

### Methods

*No methods.*

### Events

*No events.*

## Examples

The following code example declares the **SVGLengthList** object as read-only and identifies the appropriate exceptions to raise.

``` html
interface SVGLengthList {
  readonly attribute unsigned long numberOfItems;
  void clear() raises(DOMException);
  SVGLength initialize(in SVGLength newItem) raises(DOMException);
  SVGLength getItem(in unsigned long index) raises(DOMException);
  SVGLength insertItemBefore(in SVGLength newItem, in unsigned long index) raises(DOMException);
  SVGLength replaceItem(in SVGLength newItem, in unsigned long index) raises(DOMException);
  SVGLength removeItem(in unsigned long index) raises(DOMException);
  SVGLength appendItem(in SVGLength newItem) raises(DOMException);
};
```

## Notes

### Remarks

**Note:** In addition to the attributes, properties, events, methods, and styles listed above, SVG elements also inherent core HTML attributes, properties, events, methods, and styles.

You can designate an **SVGLengthList** object as read-only, so that any attempts to modify the object cause a **NoModificationAllowedError** exception that is defined during initialization.

### Standards information

-   [Scalable Vector Graphics: Basic Data Types and Interfaces](http://go.microsoft.com/fwlink/p/?linkid=204732), Section 4.5.13

### Members

The **SVGLengthList** object has these methods:

-   [**appendItem**](/svg/methods/appendItem): Inserts a new item at the end of the list.
-   [**clear**](/svg/methods/clear): Clears all existing items from the list, which creates an empty list.
-   [**getItem**](/svg/methods/getItem): Returns the specified item from a list.
-   [**initialize**](/svg/methods/initialize): Clears current items from the list and re-initializes the list to contain the specified item.
-   [**insertItemBefore**](/svg/methods/insertItemBefore): Inserts a new item into a list at a specified position.
-   [**removeItem**](/svg/methods/removeItem): Removes an existing item from the list.
-   [**replaceItem**](/svg/methods/replaceItem): Replaces a specified existing item in the list with a specified new item.

The **SVGLengthList** object has these properties:

-   [**numberOfItems**](/svg/properties/numberOfItems): Gets or sets the number of items in a list.