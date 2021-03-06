<!-- default file list -->
*Files to look at*:

* [ConnectionHelper.cs](./CS/XpoTutorial2/MyDataModelCode/ConnectionHelper.cs) (VB: [ConnectionHelper.vb](./VB/XpoTutorial2/MyDataModelCode/ConnectionHelper.vb))
* [Customer.cs](./CS/XpoTutorial2/MyDataModelCode/Customer.cs) (VB: [Customer.Designer.vb](./VB/XpoTutorial2/MyDataModelCode/Customer.Designer.vb))
* [Customer.Designer.cs](./CS/XpoTutorial2/MyDataModelCode/Customer.Designer.cs) (VB: [Customer.Designer.vb](./VB/XpoTutorial2/MyDataModelCode/Customer.Designer.vb))
* [Order.cs](./CS/XpoTutorial2/MyDataModelCode/Order.cs) (VB: [Order.vb](./VB/XpoTutorial2/MyDataModelCode/Order.vb))
* [Order.Designer.cs](./CS/XpoTutorial2/MyDataModelCode/Order.Designer.cs) (VB: [Order.Designer.vb](./VB/XpoTutorial2/MyDataModelCode/Order.Designer.vb))
* [Program.cs](./CS/XpoTutorial2/Program.cs) (VB: [Program.vb](./VB/XpoTutorial2/Program.vb))
* [XtraForm1.cs](./CS/XpoTutorial2/XtraForm1.cs) (VB: [XtraForm1.vb](./VB/XpoTutorial2/XtraForm1.vb))
<!-- default file list end -->
# Tutorial 2 - Relations (One to Many)


<p>In this lesson, you will create a Customers-Orders data-aware application that stores and modifies Customers and Orders in a database. Each Order belongs to a specific Customer. A Customer can have a number of associated Orders.<br />
<img src="https://raw.githubusercontent.com/DevExpress-Examples/tutorial-2-relations-one-to-many-e4557/12.2.6+/media/52c6dd78-2b76-49fe-a596-9075de003913.png"><br />
     <img src="https://raw.githubusercontent.com/DevExpress-Examples/tutorial-2-relations-one-to-many-e4557/12.2.6+/media/4b663488-3cd3-4488-82e7-d27a51c5533f.png"><br />
</p>

<br/>


# See also:

## Tutorials for .NET Core and .NET Framework UI Platforms

The following .NET Core and .NET Framework examples create a typical data model in line-of-business apps. These examples also illustrate how to bind XPO models to UI controls and implement CRUD operations.


### Using XPO in Web Applications

* A Blazor CRUD Application:
    * [Server-Side](https://github.com/DevExpress/XPO/tree/master/Tutorials/ASP.NET/Blazor.ServerSide/CS)
    * [WebAssembly ](https://github.com/DevExpress/XPO/tree/master/Tutorials/ASP.NET/Blazor.WebAssembly)
* [How To: Connect XPO to a Database Server (ASP.NET WebForms)](https://docs.devexpress.com/XPO/3185/examples/how-to-connect-xpo-to-a-database-server-aspnet)
* [An ASP.NET WebForms CRUD Application](https://github.com/DevExpress/XPO/tree/master/Tutorials/ASP.NET/WebForms).
* An ASP.NET MVC CRUD Application: 
    - [ASP.NET MVC 5](https://github.com/DevExpress/XPO/tree/master/Tutorials/ASP.NET/MVC5)
    - [ASP.NET Core MVC](https://github.com/DevExpress/XPO/tree/master/Tutorials/ASP.NET/MVC.Core/CS)
    - [An ASP.NET Core MVC (Razor)](https://github.com/DevExpress/XPO/tree/master/Tutorials/ASP.NET/MVC.RazorPages/CS)
* An ASP.NET Web API OData v4 Service: 
    - [ASP.NET](https://github.com/DevExpress-Examples/XPO_how-to-implement-odata4-service-with-xpo)
    - [ASP.NET Core](https://github.com/DevExpress-Examples/XPO_how-to-implement-odata4-service-with-xpo-netcore)
    - [ASP.NET Core with XAF Security System](https://github.com/DevExpress-Examples/XAF_how-to-use-the-integrated-mode-of-the-security-system-in-non-xaf-applications-e4908/tree/19.2.6%2B/ASP.NetCore/DevExtreme.OData?utm_source=DevExpress&utm_medium=Website&utm_campaign=XAF&utm_content=XAF_Security_NonXAF_Series_2)
* [How to Create API Controllers for an ASP.NET Core MVC Application](https://docs.devexpress.com/AspNetCore/401035/devextreme-based-controls/concepts/scaffolding#xpo-data-model)



### Using XPO in Desktop Applications

* A WinForms CRUD Application: [.NET Framework](https://github.com/DevExpress/XPO/tree/master/Tutorials/WinForms/Classic), [.NET Framework (MVVM)](https://github.com/DevExpress/XPO/tree/master/Tutorials/WinForms/DevExpress.MVVM), [.NET Core](https://github.com/DevExpress/XPO/tree/master/Tutorials/WinForms/Classic.Core).
* A WPF CRUD Application: [.NET Framework](https://github.com/DevExpress/XPO/tree/master/Tutorials/WPF/Classic), [.NET Framework (MVVM)](https://github.com/DevExpress/XPO/tree/master/Tutorials/WPF/DevExpress.MVVM).
* [XPO Best Practices in WPF applications](https://supportcenter.devexpress.com/ticket/details/t838546/xpo-best-practices-in-wpf-applications)


- How To articles:

    * [How to Bind Data to WinForms Controls Using XPO and XPBindingSource](https://github.com/DevExpress-Examples/XPO_how-to-bind-data-to-winforms-controls-using-xpbindingsource).
    * [How to Bind Data to WinForms Data Grid Using XPO and XPServerModeView or XPInstantFeedbackView](https://github.com/DevExpress-Examples/XPO_how-to-bind-data-to-winforms-controls-using-xpservermodeview-or-xpinstantfeedbackview).
    * [How to Bind Data to WPF Data Grid Using XPO and XPServerModeView or XPInstantFeedbackView](https://github.com/DevExpress-Examples/XPO_how-to-bind-data-to-wpf-controls-using-xpservermodeview-or-xpinstantfeedbackview).


### Using XPO in Mobile Applications

* [A Xamarin CRUD Application (Android, iOS)](https://github.com/DevExpress/XPO/tree/master/Tutorials/Xamarin.Forms)

  This tutorial demonstrates how to create a Xamarin mobile application for iOS and Android.





