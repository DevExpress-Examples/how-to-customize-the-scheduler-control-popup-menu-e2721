<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/PopupMenuCustomization/MainWindow.xaml) (VB: [MainWindow.xaml.vb](./VB/PopupMenuCustomization/MainWindow.xaml.vb))
* [MainWindow.xaml.cs](./CS/PopupMenuCustomization/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/PopupMenuCustomization/MainWindow.xaml.vb))
<!-- default file list end -->
# How to customize the Scheduler control popup menu


<p>The following example illustrates how to customize the Scheduler control popup menus by removing existing menu items and adding new items to the <strong>Default Popup Menu</strong> and <strong>Appointment Popup Menu</strong>.<br>In XAML, add new <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfBarsBarItemtopic">BarItem elements</a> and <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfBarsRemoveBarItemAndLinkActiontopic">RemoveBarItemAndLinkAction</a> actions to the <a href="http://help.devexpress.com/#WPF/DevExpressXpfSchedulerSchedulerControl_DefaultMenuCustomizationstopic">DefaultMenuCustomizations</a> and <a href="http://help.devexpress.com/#WPF/DevExpressXpfSchedulerSchedulerControl_AppointmentMenuCustomizationstopic">AppointmentMenuCustomizations</a> collections.<br>At runtime, handle the <a href="http://help.devexpress.com/#WPF/DevExpressXpfSchedulerSchedulerControl_PopupMenuShowingtopic">PopupMenuShowing</a> event and add new <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfBarsBarItemtopic">BarItem elements</a> and <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfBarsRemoveBarItemAndLinkActiontopic">RemoveBarItemAndLinkAction</a> actions to the <a href="http://help.devexpress.com/#WPF/DevExpressXpfSchedulerSchedulerMenuEventArgs_Customizationstopic">e.Customizations</a> collection.<br><br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-customize-the-scheduler-control-popup-menu-e2721/16.2.3+/media/f4c1eff8-7c68-4895-9d5e-1b508f8e578c.png"><br><br></p>

<br/>


