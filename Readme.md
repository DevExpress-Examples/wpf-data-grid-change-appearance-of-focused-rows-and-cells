<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128648824/14.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1627)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/DXGrid_ChangeRowAppearance/Window1.xaml) (VB: [Window1.xaml](./VB/DXGrid_ChangeRowAppearance/Window1.xaml))
* [Window1.xaml.cs](./CS/DXGrid_ChangeRowAppearance/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/DXGrid_ChangeRowAppearance/Window1.xaml.vb))
<!-- default file list end -->
# How to change the appearance of a focused data row and a focused cell


<p>This example demonstrates how to use the View's RowStyle and CellStyle properties to apply custom styles to the focused row and cell. To identify whether the row and cell are focused, the attached IsFocusedRow and IsFocusedCell properties are used.</p>

<br/>

If you want to define a custom border around a focused cell or row, you can enable the [ShowFocusedRectangle](https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.ShowFocusedRectangle.property) property in your TableView and define custom [FocusedCellBorderTemplate](https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.FocusedCellBorderTemplate.property) or [FocusedRowBorderTemplate](https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.TableView.FocusedRowBorderTemplate.property). Please note that the focused rectangle is shown for cells or rows only when [NavigationStyle](https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.NavigationStyle.property) is set to **Cell** or **Row**, respectively.

