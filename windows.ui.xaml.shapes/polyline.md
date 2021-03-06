---
-api-id: T:Windows.UI.Xaml.Shapes.Polyline
-api-type: winrt class
---

<!-- Class syntax.
public class Polyline : Windows.UI.Xaml.Shapes.Shape, Windows.UI.Xaml.Shapes.IPolyline
-->

# Windows.UI.Xaml.Shapes.Polyline

## -description
Draws a series of connected straight lines.

## -xaml-syntax
```xaml
<Polyline .../>
```


## -remarks

## -examples
This example shows how to use a Polyline to create a closed triangle.

```xaml
<Canvas>  
  <Polyline Points="50,25 0,100 100,100 50,25"
    Stroke="Blue" StrokeThickness="10"
    Canvas.Left="75" Canvas.Top="50" />
</Canvas>
```



## -see-also
[Shape](shape.md), [XAML vector-based drawing sample](https://go.microsoft.com/fwlink/p/?linkid=226866), [Draw shapes](https://docs.microsoft.com/windows/uwp/graphics/drawing-shapes)
