# How to Localize the GridDateTimeColumn Button Text in WPF DataGrid?

This example illustrates how to localize the [GridDateTimeColumn](https://help.syncfusion.com/cr/wpf/Syncfusion.UI.Xaml.Grid.GridDateTimeColumn.html) button text in [WPF DataGrid](https://www.syncfusion.com/wpf-controls/datagrid) (SfDataGrid).

The [DateTimeEdit](https://help.syncfusion.com/cr/wpf/Syncfusion.Windows.Shared.DateTimeEdit.html) control as an edit element for GridDateTimeColumn in `DataGrid`. The `DateTimeEdit` control referred by **Syncfusion.Shared.Wpf** assembly. You can localize the `GridDateTimeColumn` button text by adding the resource file as **Syncfusion.Shared.Wpf.\<culture name>.resx**.  

```C#
public MainWindow()
{
     System.Threading.Thread.CurrentThread.CurrentUICulture = new System.Globalization.CultureInfo("de");
     InitializeComponent();
}
```

![Shows the resource file adding steps in SfDataGrid](AddingResourceFile.gif)

The following screenshot shows the localized GridDateTimeColumn button text,

![Shows localized text for Today and None button text in GridDateTimeColumn](Localized.png)