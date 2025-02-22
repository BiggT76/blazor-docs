#event-callback-can-be-async
>tip The event is an `EventCallback` and it can be synchronous (return `void`), or it can also be asynchronous and return `async Task`.
#end

#ensure-nuget-packge-for-upgrade
Make sure that you have a NuGet feed source with the version you want to upgrade to. This is usually the [Telerik NuGet Feed]({%slug installation/nuget%}), but you can also use a local feed from [our MSI installer]({%slug installation/msi%}) or [ZIP archive]({%slug installation/zip%}).
#end

#date-format-per-culture
the `Format` is culture-specific and the same format may produce different results depending on the culture. You can find more information and examples in the [Supported Date Formats]({%slug components/dateinput/supported-formats%}) article.
#end

#cdn
You can reference the built-in Telerik assets from a cloud CDN instead of a local resource on your server.

>caption Reference the Telerik assets from the cloud CDN

````CSHTML
<!DOCTYPE html>
<html>
<head>
    . . .
    <!-- Choose only one of the themes -->
    
    <link rel="stylesheet" href="https://blazor.cdn.telerik.com/blazor/{{site.uiForBlazorLatestVersion}}/kendo-theme-default/all.css" />
    
    <!-- 
        <link href="https://blazor.cdn.telerik.com/blazor/{{site.uiForBlazorLatestVersion}}/kendo-theme-bootstrap/all.css" rel="stylesheet" />
        <link href="https://blazor.cdn.telerik.com/blazor/{{site.uiForBlazorLatestVersion}}/kendo-theme-material/all.css" rel="stylesheet" />
    -->
    
    <script src="https://blazor.cdn.telerik.com/blazor/{{site.uiForBlazorLatestVersion}}/telerik-blazor.min.js" defer></script>
</head>

 . . .
 
</html>
````


>important Make sure that the version in the URLs matches the version of the Telerik UI for Blazor package.

>tip If you decide to use a CDN over static assets, you may want to implement a [fallback]({%slug common-kb-cdn-fallback%}) in case it is unavailable to your users.


#end



#vsx-download
You can get them from the:

* [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=TelerikInc.TelerikBlazorVSExtensions) (for Windows)
* [Telerik UI for Blazor automated installer]({%slug installation/msi%}) (for Windows and Mac)
* Your [Telerik.com account](https://www.telerik.com/account/product-download?product=BLAZOR) - the `.mpack` file for VS for Mac

#end



#valuebind-vs-databind-link
For details on Value Binding and Data Binding, and the differences between them, see the [Value Binding vs Data Binding]({%slug get-started-value-vs-data-binding%}) article.
#end