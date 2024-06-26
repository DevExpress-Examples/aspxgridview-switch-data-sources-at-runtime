<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128537797/13.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2965)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# Grid View for ASP.NET Web Forms - How to bind the control created in design mode to different data sources at runtime

This example demonstrates how to bind an [ASPxGridView](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxGridView) with autogenerated columns to different data sources at runtime. The grid is created in design mode.

![Switch Data Source at Runtime](switch-data-source-at-runtime.png)

The project contains an [ASPxRadioButtonList](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxRadioButtonList) control that allows users to switch between three data sources (SqlDataSource). 

Note that the grid's [`EnableViewState`](https://docs.microsoft.com/en-us/dotnet/api/system.web.ui.control.enableviewstate#System_Web_UI_Control_EnableViewState) property is set to `false` to avoid exceptions when binding the grid to another data source.

## Files to Look At

- [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
- [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))

## Documentation

- [Bind Grid View to Data at Runtime](https://docs.devexpress.com/AspNet/403612/components/grid-view/concepts/bind-to-data/bind-to-data-at-runtime)

## More Examples

- [Grid View for ASP.NET Web Forms - How to dynamically switch the Grid's data source and recreate columns at runtime](https://github.com/DevExpress-Examples/aspxgridview-switch-grid-data-source-and-recreate-columns-at-runtime)
- [How to bind ASPxGridView with manually created columns to different data sources](https://github.com/DevExpress-Examples/how-to-bind-aspxgridview-with-manually-created-columns-to-different-data-sources-e2967)
- [How to bind ASPxGridView created at runtime to different data sources](https://github.com/DevExpress-Examples/how-to-bind-aspxgridview-created-at-runtime-to-different-data-sources-e2968)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=asp-net-web-forms-grid-switch-data-sources-at-runtime&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=asp-net-web-forms-grid-switch-data-sources-at-runtime&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
