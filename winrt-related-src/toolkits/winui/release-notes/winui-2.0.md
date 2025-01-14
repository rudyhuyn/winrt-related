---
title: WinUI 2.0 Release Notes
description: Release notes for WinUI 2.0.
author: jesbis
ms.author: mijacobs
ms.date: 03/14/2019
ms.topic: reference
---

# Windows UI Library 2.0

WinUI 2.0 is the first public release of the Windows UI Library. 

WinUI is the easiest way to build great Fluent Design experiences for Windows.

It includes two NuGet packages:

* [Microsoft.UI.Xaml](https://www.nuget.org/packages/Microsoft.UI.Xaml): Controls and Fluent Design for UWP apps. This is the main WinUI package.

* [Microsoft.UI.Xaml.Core.Direct](https://www.nuget.org/packages/Microsoft.UI.Xaml.Core.Direct): Low-level APIs for use in middleware components.

You can download and use WinUI packages in your app using the NuGet package manager: see [Getting Started with the Windows UI Library](https://docs.microsoft.com/en-us/uwp/toolkits/winui/getting-started) for more information.

WinUI is an open source project hosted on GitHub. We welcome bug reports, feature requests and community code contributions in the [Windows UI Library repo](https://aka.ms/winui).

## Microsoft.UI.Xaml 2.0.181011001

October 2018

This is the first release of the [Microsoft.UI.Xaml NuGet package](https://www.nuget.org/packages/Microsoft.UI.Xaml). It includes official native Fluent controls and features for Windows UWP apps.

### New Features

Controls and patterns in this release include:

| Feature | Description |
| --- | --- |
|[AcrylicBrush]( https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.media.acrylicbrush)| Paints an area with a semi-transparent material that uses multiple effects including blur and a noise texture.|
|[BitmapIconSource]( https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.bitmapiconsource)| Represents an icon source that uses a bitmap as its content.|
|[ColorPicker]( https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.colorpicker)| Represents a control that lets a user pick a color using a color spectrum, sliders, and text input.|
|[CommandBarFlyout](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.commandbarflyout)|Represents a specialized flyout that provides layout for AppBarButton and related command elements.|
|[DropDownButton](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.dropdownbutton)|Represents a button with a chevron intended to open a menu.|
|[FontIconSource ](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.fonticonsource)|Represents an icon source that uses a glyph from the specified font.|
|[MenuBar](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.menubar)|Represents a specialized container that presents a set of menus in a horizontal row, typically at the top of an app window.|
|[MenuBarItem](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.menubaritem)|Represents a top-level menu in a MenuBar control.|
|[NavigationView](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.navigationview)|Represents a container that enables navigation of app content. It has a header, a view for the main content, and a menu pane for navigation commands.|
|[ParallaxView](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.parallaxview)|Represents a container that ties the scroll position of a foreground element, such as a list, to a background element, such as an image. As you scroll through the foreground element, it animates the background element to create a parallax effect.|
|[PersonPicture](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.personpicture)|Represents a control that displays the avatar image for a person, if one is available; if not, it displays the person's initials or a generic glyph.|
|[RatingControl](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.ratingcontrol)|Represents a control that lets a user enter a star rating.|
|[RefreshContainer](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.refreshcontainer)|Represents a container control that provides a RefreshVisualizer and pull-to-refresh functionality for scrollable content.|
|[RefreshVisualizer](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.refreshvisualizer)|Represents a control that provides animated state indicators for content refresh.|
|[RevealBackgroundBrush](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.media.revealbackgroundbrush)|Paints a control background with a reveal effect using composition brush and light effects.|
|[RevealBorderBrush](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.media.revealborderbrush)|Paints a control border with a reveal effect using composition brush and light effects.|
|[RevealBrush](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.media.revealbrush)|Base class for brushes that use composition effects and lighting to implement the reveal visual design treatment.|
|[SplitButton](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.splitbutton)|Represents a button with two parts that can be invoked separately. One part behaves like a standard button and the other part invokes a flyout.|
|[SwipeControl](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.swipecontrol)|Represents a container that provides access to contextual commands through touch interactions.|
|[SymbolIconSource](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.symboliconsource)|Represents an icon source that uses a glyph from the Segoe MDL2 Assets font as its content.|
|[TextCommandBarFlyout](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.textcommandbarflyout)|Represents a specialized command bar flyout that contains commands for editing text.|
|[ToggleSplitButton](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.togglesplitbutton)|Represents a button with two parts that can be invoked separately. One part behaves like a toggle button and the other part invokes a flyout.|
|[TreeView](https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.treeview)|Represents a hierarchical list with expanding and collapsing nodes that contain nested items.|

