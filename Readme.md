<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128640878/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1537)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/WpfApplication2/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication2/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/WpfApplication2/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfApplication2/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Create Bars in One Common Container Using BarManager


<p>This example shows how to create three bars (File, Edit and StatusBar) using the BarManager component. Actions for bar elements are defined by commands implemented in the MyViewModel class.</p>
<p> </p>
<p>The window's DataContext is set to a MyViewModel class descendant, which is automatically generated by the DevExpress.Mvvm.POCO.ViewModelSource object. This descendant automatically generates commands for all public methods in the MyViewModel class (the OpenFileCommand, NewFileCommand and SetAlignmentCommand are generated).</p>

<br/>


