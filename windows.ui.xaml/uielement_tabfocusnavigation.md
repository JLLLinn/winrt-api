---
-api-id: P:Windows.UI.Xaml.UIElement.TabFocusNavigation
-api-type: winrt property
---

<!-- Property syntax.
public KeyboardNavigationMode TabFocusNavigation { get;  set; }
-->

# Windows.UI.Xaml.UIElement.TabFocusNavigation

## -description
Gets or sets a value that modifies how tabbing and [TabIndex](../windows.ui.xaml.controls/control_tabindex.md) work for this control.

> [!NOTE]
> For Windows 10 Creators Update (build 10.0.15063) and newer, use this property of the [UIElement]() base class instead of the [TabNavigation](../windows.ui.xaml.controls/control_tabnavigation.md) property of a [Control](../windows.ui.xaml.controls/control.md) object.

## -xaml-syntax
```xaml
<uiElement TabFocusNavigation="keyboardNavigationModeMemberName"/>
```

## -xaml-values
<dl><dt>keyboardNavigationModeMemberName</dt><dd>keyboardNavigationModeMemberNameA named constant of the [KeyboardNavigationMode](../windows.ui.xaml.input/keyboardnavigationmode.md) enumeration, for example, **Cycle**.</dd>
</dl>

## -property-value
A value of the enumeration. The default is **Local**.

## -remarks

Use this property instead of the [Control.TabNavigation](../windows.ui.xaml.controls/control_tabnavigation.md) property for objects that do not use a [ControlTemplate](../windows.ui.xaml.controls/controltemplate.md) to define their appearance.

## -examples

## -see-also
[Keyboard interactions](http://msdn.microsoft.com/library/ff819bac-67c0-4ec9-8921-f087be188138), [Keyboard accessibility](http://msdn.microsoft.com/library/ddae8c4b-7907-49fe-9645-f105f8dfad8b)

