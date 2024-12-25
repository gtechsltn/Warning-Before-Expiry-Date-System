# Show warning before expiry date system

Theo dõi | quản lý ngày hết hạn của hàng hóa | sản phẩm

https://viindoo.com/documentation/17.0/vi/applications/supply-chain/inventory/warehouse-management/lots-serial-numbers/product-expiration-dates.html

Task Scheduler is the standard mechanism for dealing with repetitive tasks in Windows 

https://stackoverflow.com/questions/15925403/expiration-notification

https://stackoverflow.com/questions/48287225/alert-30-days-before-expiry-date-in-c-sharp-windows-forms-application-using-sql

```
CREATE TABLE [dbo].[Medicine]
(
    [Item_Id] INT PRIMARY KEY INT IDENTITY(1, 1) NOT NULL,
    [Item_Code] [nvarchar](50) NULL,
    [Item_Manufacture_Date] [date] NULL,
    [Item_Expiry_Date] [date] NULL,
    [Price] [nvarchar](50) NULL
)

SELECT Item_Code, Item_Expiry_Date, Price FROM [dbo].[Medicine] WHERE Item_Expiry_Date BETWEEN DATEADD(DAY, -30, GETDATE()) and GETDATE()

SELECT Item_Code, Item_Expiry_Date, Price FROM [dbo].[Medicine] WHERE Item_Expiry_Date < DATEADD(month, 2, GETDATE());
```

https://asp-blogs.azurewebsites.net/stevewellens/ah-ah-ah-ah-staying-alive-staying-alive

https://www.codeproject.com/KB/scripting/Session_Timeout.aspx

https://stackoverflow.com/questions/10522482/session-timeout-warning-in-asp-net

https://stackoverflow.com/questions/7029168/asp-net-javascript-timeout-warning-based-on-sessionstate-timeout-in-web-config

https://www.aspsnippets.com/questions/260062/Display-Expiry-reminder-message-after-Login-in-ASPNet-MVC/

https://learn.microsoft.com/en-us/answers/questions/1529382/session-timeout-notification-in-asp-net-web-apps

https://community.devexpress.com/blogs/aspnet/archive/2011/06/15/asp-net-how-to-show-a-popup-warning-before-session-timeout.aspx

https://supportcenter.devexpress.com/ticket/details/e3302/popup-control-for-asp-net-web-forms-how-to-control-state-when-the-session-is-being

https://www.youtube.com/watch?v=DyFgB878pOI

https://www.youtube.com/watch?v=w67WctTPQFc

https://www.youtube.com/watch?v=U0zYxZ6OzDM

### Add sorting, filtering, paging in ASP.NET Core MVC

https://github.com/alihaider11/Sort-Filter-Paging-Asp-.Net-Core-MVC-/

https://github.com/gtechsltn/Sort-Filter-Paging-Asp-.Net-Core-MVC-/

### Custom User Message Extension Methods in C# and ASP.NET Core MVC

https://exceptionnotfound.net/custom-user-message-extension-methods-in-csharp-and-dotnet-5-mvc/

https://github.com/exceptionnotfound/FlashMessageCoreDemo

https://github.com/gtechsltn/FlashMessageCoreDemo

### Implement Search using DataTables
+ https://www.youtube.com/watch?v=Ra38OYYk_-U
+ https://www.youtube.com/watch?v=sXNs_UPnl70
+ https://www.youtube.com/watch?v=EpuTN5ezcFc
+ https://drive.google.com/file/d/1MHv2ySJofYSIMFURh9WfZoaJCrBrylNg/
