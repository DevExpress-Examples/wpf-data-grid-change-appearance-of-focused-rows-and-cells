<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128648824/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1627)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# WPF Data Grid - Change the Appearance of Focused Rows and Cells

This example demonstrates how to use the View's [RowStyle](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.TableView.RowStyle) and [CellStyle](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.CellStyle) properties to apply custom styles to the focused row and cell. To identify whether the row and cell are focused, the attached [IsFocusedRow](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.IsFocusedRow) and [IsFocusedCell](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.IsFocusedCell) properties are used.

![image](https://user-images.githubusercontent.com/65009440/174086665-b5564ab8-2bd7-42b7-a9c9-277e263f5c26.png) 

If you want to define a custom border around a focused cell or row, you can enable the [ShowFocusedRectangle](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.ShowFocusedRectangle) property and define custom [FocusedCellBorderTemplate](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.FocusedCellBorderTemplate) or [FocusedRowBorderTemplate](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.TableView.FocusedRowBorderTemplate). Note that the focused rectangle is shown for cells or rows only when [NavigationStyle](http://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataViewBase.NavigationStyle) is set to **Cell** or **Row**, respectively.

<!-- default file list -->
## Files to look at

* [Window1.xaml](./CS/DXGrid_ChangeRowAppearance/Window1.xaml) (VB: [Window1.xaml](./VB/DXGrid_ChangeRowAppearance/Window1.xaml))

<!-- default file list end -->

## Documentation

* [Focus, Navigation, Selection](https://docs.devexpress.com/WPF/6118/controls-and-libraries/data-grid/focus-navigation-selection)
* [Appearance Customization](https://docs.devexpress.com/WPF/6152/controls-and-libraries/data-grid/appearance-customization)

## More Examples

* [WPF Data Grid - Focus a Cell with the Specified Value](https://github.com/DevExpress-Examples/how-to-focus-a-cell-with-the-specified-value-e1544)
* [WPF Data Grid - Change the Appearance of Focused and Selected Rows](https://github.com/DevExpress-Examples/how-to-change-the-appearance-of-a-focused-data-row-and-selected-rows-e2066)
* [WPF Data Grid - Change the Appearance of Focused and Selected Cells](https://github.com/DevExpress-Examples/how-to-change-selected-cells-appearance-when-gridcontrols-multi-cell-selection-is-enabled-e2568)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-data-grid-change-appearance-of-focused-rows-and-cells&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-data-grid-change-appearance-of-focused-rows-and-cells&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
