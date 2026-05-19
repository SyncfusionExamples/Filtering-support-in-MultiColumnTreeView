# Filtering support in MultiColumnTreeView

This session describes how to filter the nodes in **WinForms MultiColumnTreeView**.

In [WinForms MultiColumnTreeView](https://www.syncfusion.com/winforms-ui-controls/multicolumn-treeview), Filtering can be achieved by setting the [Filter](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.MultiColumnTreeView.MultiColumnTreeView.html#Syncfusion_Windows_Forms_Tools_MultiColumnTreeView_MultiColumnTreeView_Filter) delegate and calling the [RefreshFilter](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.MultiColumnTreeView.MultiColumnTreeView.html#Syncfusion_Windows_Forms_Tools_MultiColumnTreeView_MultiColumnTreeView_RefreshFilter) method.

You can clear the filters applied in nodes by setting the **Filter** delegate to null and calling the **RefreshFilter** method.

### C#

``` csharp
multiColumnTreeView1.Filter = null;

multiColumnTreeView1.RefreshFilter();
```

### VB

``` vb
multiColumnTreeView1.Filter = Nothing

multiColumnTreeView1.RefreshFilter()
```