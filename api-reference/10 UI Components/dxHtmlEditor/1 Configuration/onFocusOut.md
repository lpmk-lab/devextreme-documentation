---
id: dxHtmlEditor.Options.onFocusOut
type: function(e)
default: null
---
---
##### shortDescription
A function that is executed when the UI component loses focus.

##### param(e): ui/html_editor:FocusOutEvent
Information about the event that caused the function execution.

##### field(e.component): {WidgetName}
The UI component's instance.

##### field(e.element): DxElement
#include common-ref-elementparam with { element: "UI component" }

##### field(e.event): event
#include common-ref-eventparam

##### field(e.model): any
Model data. Available only if you use Knockout.

---
#####See Also#####
- [onFocusIn](/api-reference/10%20UI%20Components/dxHtmlEditor/1%20Configuration/onFocusIn.md '/Documentation/ApiReference/UI_Components/dxHtmlEditor/Configuration/#onFocusIn')