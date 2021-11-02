<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/413372063/21.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1037053)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!--WARNING: This file has been automatically generated. Do not change it manually.-->
# Bind the WPF Data Grid to Data

This example shows how to bind the [WPF Data Grid](https://docs.devexpress.com/WPF/6084/controls-and-libraries/data-grid) to different data sources. Refer to the following topic for more information: [Bind to Data](https://docs.devexpress.com/WPF/7352/controls-and-libraries/data-grid/bind-to-data).

![Bind WPF Data Grid to Data](https://docs.devexpress.com/WPF/images/WPF_Grid_GSResult.png)


The example includes multiple solutions that demonstrate:

* How to bind the Data Grid to [Entity Framework](https://docs.microsoft.com/en-us/ef/ef6/), [EF Core](https://docs.microsoft.com/en-us/ef/), and [XPO](https://docs.devexpress.com/XPO/1998/express-persistent-objects).
* Different binding mechanisms: [virtual sources](https://docs.devexpress.com/WPF/10803/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources), [server mode sources](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback), and [local data](https://docs.devexpress.com/WPF/6090/controls-and-libraries/data-grid/bind-to-data/bind-to-local-data).
* MVVM and code-behind patterns.

See also: [Implement CRUD Operations in a Data-Bound Grid](https://github.com/DevExpress-Examples/how-to-implement-crud-operations)

# C#
## CodeBehind
||Entity Framework 6 [?](https://docs.microsoft.com/en-us/ef/ef6/)|Entity Framework Core [?](https://docs.microsoft.com/en-us/ef/)|DevExpress XPO [?](https://docs.devexpress.com/XPO/1998/express-persistent-objects)|
|:---|:---:|:---:|:---:|
|Local Data [?](https://docs.devexpress.com/WPF/6090/controls-and-libraries/data-grid/bind-to-data/bind-to-local-data)|[project](CS/CodeBehind/EntityFramework/LocalData), [code](CS/CodeBehind/EntityFramework/LocalData/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EntityFramework/LocalData/MainWindow.xaml)|[project](CS/CodeBehind/EFCore/LocalData), [code](CS/CodeBehind/EFCore/LocalData/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EFCore/LocalData/MainWindow.xaml)|[project](CS/CodeBehind/XPO/LocalData), [code](CS/CodeBehind/XPO/LocalData/MainWindow.xaml.cs), [xaml](CS/CodeBehind/XPO/LocalData/MainWindow.xaml)|
|Infinite Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#infinite-source)|[project](CS/CodeBehind/EntityFramework/InfiniteAsyncSource), [code](CS/CodeBehind/EntityFramework/InfiniteAsyncSource/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EntityFramework/InfiniteAsyncSource/MainWindow.xaml)|[project](CS/CodeBehind/EFCore/InfiniteAsyncSource), [code](CS/CodeBehind/EFCore/InfiniteAsyncSource/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EFCore/InfiniteAsyncSource/MainWindow.xaml)|[project](CS/CodeBehind/XPO/InfiniteAsyncSource), [code](CS/CodeBehind/XPO/InfiniteAsyncSource/MainWindow.xaml.cs), [xaml](CS/CodeBehind/XPO/InfiniteAsyncSource/MainWindow.xaml)|
|Paged Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#paged-source)|[project](CS/CodeBehind/EntityFramework/PagedAsyncSource), [code](CS/CodeBehind/EntityFramework/PagedAsyncSource/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EntityFramework/PagedAsyncSource/MainWindow.xaml)|[project](CS/CodeBehind/EFCore/PagedAsyncSource), [code](CS/CodeBehind/EFCore/PagedAsyncSource/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EFCore/PagedAsyncSource/MainWindow.xaml)|[project](CS/CodeBehind/XPO/PagedAsyncSource), [code](CS/CodeBehind/XPO/PagedAsyncSource/MainWindow.xaml.cs), [xaml](CS/CodeBehind/XPO/PagedAsyncSource/MainWindow.xaml)|
|Instant Feedback Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#instant-feedback-mode)|[project](CS/CodeBehind/EntityFramework/InstantFeedbackMode), [code](CS/CodeBehind/EntityFramework/InstantFeedbackMode/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EntityFramework/InstantFeedbackMode/MainWindow.xaml)|[project](CS/CodeBehind/EFCore/InstantFeedbackMode), [code](CS/CodeBehind/EFCore/InstantFeedbackMode/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EFCore/InstantFeedbackMode/MainWindow.xaml)|[project](CS/CodeBehind/XPO/InstantFeedbackMode), [code](CS/CodeBehind/XPO/InstantFeedbackMode/MainWindow.xaml.cs), [xaml](CS/CodeBehind/XPO/InstantFeedbackMode/MainWindow.xaml)|
|Server Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#server-mode)|[project](CS/CodeBehind/EntityFramework/ServerMode), [code](CS/CodeBehind/EntityFramework/ServerMode/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EntityFramework/ServerMode/MainWindow.xaml)|[project](CS/CodeBehind/EFCore/ServerMode), [code](CS/CodeBehind/EFCore/ServerMode/MainWindow.xaml.cs), [xaml](CS/CodeBehind/EFCore/ServerMode/MainWindow.xaml)|[project](CS/CodeBehind/XPO/ServerMode), [code](CS/CodeBehind/XPO/ServerMode/MainWindow.xaml.cs), [xaml](CS/CodeBehind/XPO/ServerMode/MainWindow.xaml)|
## ViewModel
||Entity Framework 6 [?](https://docs.microsoft.com/en-us/ef/ef6/)|Entity Framework Core [?](https://docs.microsoft.com/en-us/ef/)|DevExpress XPO [?](https://docs.devexpress.com/XPO/1998/express-persistent-objects)|
|:---|:---:|:---:|:---:|
|Local Data [?](https://docs.devexpress.com/WPF/6090/controls-and-libraries/data-grid/bind-to-data/bind-to-local-data)|[project](CS/ViewModel/EntityFramework/LocalData), [code](CS/ViewModel/EntityFramework/LocalData/MainViewModel.cs), [xaml](CS/ViewModel/EntityFramework/LocalData/MainWindow.xaml)|[project](CS/ViewModel/EFCore/LocalData), [code](CS/ViewModel/EFCore/LocalData/MainViewModel.cs), [xaml](CS/ViewModel/EFCore/LocalData/MainWindow.xaml)|[project](CS/ViewModel/XPO/LocalData), [code](CS/ViewModel/XPO/LocalData/MainViewModel.cs), [xaml](CS/ViewModel/XPO/LocalData/MainWindow.xaml)|
|Infinite Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#infinite-source)|[project](CS/ViewModel/EntityFramework/InfiniteAsyncSource), [code](CS/ViewModel/EntityFramework/InfiniteAsyncSource/MainViewModel.cs), [xaml](CS/ViewModel/EntityFramework/InfiniteAsyncSource/MainWindow.xaml)|[project](CS/ViewModel/EFCore/InfiniteAsyncSource), [code](CS/ViewModel/EFCore/InfiniteAsyncSource/MainViewModel.cs), [xaml](CS/ViewModel/EFCore/InfiniteAsyncSource/MainWindow.xaml)|[project](CS/ViewModel/XPO/InfiniteAsyncSource), [code](CS/ViewModel/XPO/InfiniteAsyncSource/MainViewModel.cs), [xaml](CS/ViewModel/XPO/InfiniteAsyncSource/MainWindow.xaml)|
|Paged Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#paged-source)|[project](CS/ViewModel/EntityFramework/PagedAsyncSource), [code](CS/ViewModel/EntityFramework/PagedAsyncSource/MainViewModel.cs), [xaml](CS/ViewModel/EntityFramework/PagedAsyncSource/MainWindow.xaml)|[project](CS/ViewModel/EFCore/PagedAsyncSource), [code](CS/ViewModel/EFCore/PagedAsyncSource/MainViewModel.cs), [xaml](CS/ViewModel/EFCore/PagedAsyncSource/MainWindow.xaml)|[project](CS/ViewModel/XPO/PagedAsyncSource), [code](CS/ViewModel/XPO/PagedAsyncSource/MainViewModel.cs), [xaml](CS/ViewModel/XPO/PagedAsyncSource/MainWindow.xaml)|
|Instant Feedback Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#instant-feedback-mode)|[project](CS/ViewModel/EntityFramework/InstantFeedbackMode), [code](CS/ViewModel/EntityFramework/InstantFeedbackMode/MainViewModel.cs), [xaml](CS/ViewModel/EntityFramework/InstantFeedbackMode/MainWindow.xaml)|[project](CS/ViewModel/EFCore/InstantFeedbackMode), [code](CS/ViewModel/EFCore/InstantFeedbackMode/MainViewModel.cs), [xaml](CS/ViewModel/EFCore/InstantFeedbackMode/MainWindow.xaml)|[project](CS/ViewModel/XPO/InstantFeedbackMode), [code](CS/ViewModel/XPO/InstantFeedbackMode/MainViewModel.cs), [xaml](CS/ViewModel/XPO/InstantFeedbackMode/MainWindow.xaml)|
|Server Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#server-mode)|[project](CS/ViewModel/EntityFramework/ServerMode), [code](CS/ViewModel/EntityFramework/ServerMode/MainViewModel.cs), [xaml](CS/ViewModel/EntityFramework/ServerMode/MainWindow.xaml)|[project](CS/ViewModel/EFCore/ServerMode), [code](CS/ViewModel/EFCore/ServerMode/MainViewModel.cs), [xaml](CS/ViewModel/EFCore/ServerMode/MainWindow.xaml)|[project](CS/ViewModel/XPO/ServerMode), [code](CS/ViewModel/XPO/ServerMode/MainViewModel.cs), [xaml](CS/ViewModel/XPO/ServerMode/MainWindow.xaml)|
# Visual Basic
## CodeBehind
||Entity Framework 6 [?](https://docs.microsoft.com/en-us/ef/ef6/)|Entity Framework Core [?](https://docs.microsoft.com/en-us/ef/)|DevExpress XPO [?](https://docs.devexpress.com/XPO/1998/express-persistent-objects)|
|:---|:---:|:---:|:---:|
|Local Data [?](https://docs.devexpress.com/WPF/6090/controls-and-libraries/data-grid/bind-to-data/bind-to-local-data)|[project](VB/CodeBehind/EntityFramework/LocalData), [code](VB/CodeBehind/EntityFramework/LocalData/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EntityFramework/LocalData/MainWindow.xaml)|[project](VB/CodeBehind/EFCore/LocalData), [code](VB/CodeBehind/EFCore/LocalData/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EFCore/LocalData/MainWindow.xaml)|[project](VB/CodeBehind/XPO/LocalData), [code](VB/CodeBehind/XPO/LocalData/MainWindow.xaml.vb), [xaml](VB/CodeBehind/XPO/LocalData/MainWindow.xaml)|
|Infinite Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#infinite-source)|[project](VB/CodeBehind/EntityFramework/InfiniteAsyncSource), [code](VB/CodeBehind/EntityFramework/InfiniteAsyncSource/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EntityFramework/InfiniteAsyncSource/MainWindow.xaml)|[project](VB/CodeBehind/EFCore/InfiniteAsyncSource), [code](VB/CodeBehind/EFCore/InfiniteAsyncSource/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EFCore/InfiniteAsyncSource/MainWindow.xaml)|[project](VB/CodeBehind/XPO/InfiniteAsyncSource), [code](VB/CodeBehind/XPO/InfiniteAsyncSource/MainWindow.xaml.vb), [xaml](VB/CodeBehind/XPO/InfiniteAsyncSource/MainWindow.xaml)|
|Paged Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#paged-source)|[project](VB/CodeBehind/EntityFramework/PagedAsyncSource), [code](VB/CodeBehind/EntityFramework/PagedAsyncSource/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EntityFramework/PagedAsyncSource/MainWindow.xaml)|[project](VB/CodeBehind/EFCore/PagedAsyncSource), [code](VB/CodeBehind/EFCore/PagedAsyncSource/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EFCore/PagedAsyncSource/MainWindow.xaml)|[project](VB/CodeBehind/XPO/PagedAsyncSource), [code](VB/CodeBehind/XPO/PagedAsyncSource/MainWindow.xaml.vb), [xaml](VB/CodeBehind/XPO/PagedAsyncSource/MainWindow.xaml)|
|Instant Feedback Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#instant-feedback-mode)|[project](VB/CodeBehind/EntityFramework/InstantFeedbackMode), [code](VB/CodeBehind/EntityFramework/InstantFeedbackMode/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EntityFramework/InstantFeedbackMode/MainWindow.xaml)|[project](VB/CodeBehind/EFCore/InstantFeedbackMode), [code](VB/CodeBehind/EFCore/InstantFeedbackMode/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EFCore/InstantFeedbackMode/MainWindow.xaml)|[project](VB/CodeBehind/XPO/InstantFeedbackMode), [code](VB/CodeBehind/XPO/InstantFeedbackMode/MainWindow.xaml.vb), [xaml](VB/CodeBehind/XPO/InstantFeedbackMode/MainWindow.xaml)|
|Server Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#server-mode)|[project](VB/CodeBehind/EntityFramework/ServerMode), [code](VB/CodeBehind/EntityFramework/ServerMode/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EntityFramework/ServerMode/MainWindow.xaml)|[project](VB/CodeBehind/EFCore/ServerMode), [code](VB/CodeBehind/EFCore/ServerMode/MainWindow.xaml.vb), [xaml](VB/CodeBehind/EFCore/ServerMode/MainWindow.xaml)|[project](VB/CodeBehind/XPO/ServerMode), [code](VB/CodeBehind/XPO/ServerMode/MainWindow.xaml.vb), [xaml](VB/CodeBehind/XPO/ServerMode/MainWindow.xaml)|
## ViewModel
||Entity Framework 6 [?](https://docs.microsoft.com/en-us/ef/ef6/)|Entity Framework Core [?](https://docs.microsoft.com/en-us/ef/)|DevExpress XPO [?](https://docs.devexpress.com/XPO/1998/express-persistent-objects)|
|:---|:---:|:---:|:---:|
|Local Data [?](https://docs.devexpress.com/WPF/6090/controls-and-libraries/data-grid/bind-to-data/bind-to-local-data)|[project](VB/ViewModel/EntityFramework/LocalData), [code](VB/ViewModel/EntityFramework/LocalData/MainViewModel.vb), [xaml](VB/ViewModel/EntityFramework/LocalData/MainWindow.xaml)|[project](VB/ViewModel/EFCore/LocalData), [code](VB/ViewModel/EFCore/LocalData/MainViewModel.vb), [xaml](VB/ViewModel/EFCore/LocalData/MainWindow.xaml)|[project](VB/ViewModel/XPO/LocalData), [code](VB/ViewModel/XPO/LocalData/MainViewModel.vb), [xaml](VB/ViewModel/XPO/LocalData/MainWindow.xaml)|
|Infinite Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#infinite-source)|[project](VB/ViewModel/EntityFramework/InfiniteAsyncSource), [code](VB/ViewModel/EntityFramework/InfiniteAsyncSource/MainViewModel.vb), [xaml](VB/ViewModel/EntityFramework/InfiniteAsyncSource/MainWindow.xaml)|[project](VB/ViewModel/EFCore/InfiniteAsyncSource), [code](VB/ViewModel/EFCore/InfiniteAsyncSource/MainViewModel.vb), [xaml](VB/ViewModel/EFCore/InfiniteAsyncSource/MainWindow.xaml)|[project](VB/ViewModel/XPO/InfiniteAsyncSource), [code](VB/ViewModel/XPO/InfiniteAsyncSource/MainViewModel.vb), [xaml](VB/ViewModel/XPO/InfiniteAsyncSource/MainWindow.xaml)|
|Paged Async Source [?](https://docs.devexpress.com/WPF/120193/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources/virtual-sources-overview#paged-source)|[project](VB/ViewModel/EntityFramework/PagedAsyncSource), [code](VB/ViewModel/EntityFramework/PagedAsyncSource/MainViewModel.vb), [xaml](VB/ViewModel/EntityFramework/PagedAsyncSource/MainWindow.xaml)|[project](VB/ViewModel/EFCore/PagedAsyncSource), [code](VB/ViewModel/EFCore/PagedAsyncSource/MainViewModel.vb), [xaml](VB/ViewModel/EFCore/PagedAsyncSource/MainWindow.xaml)|[project](VB/ViewModel/XPO/PagedAsyncSource), [code](VB/ViewModel/XPO/PagedAsyncSource/MainViewModel.vb), [xaml](VB/ViewModel/XPO/PagedAsyncSource/MainWindow.xaml)|
|Instant Feedback Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#instant-feedback-mode)|[project](VB/ViewModel/EntityFramework/InstantFeedbackMode), [code](VB/ViewModel/EntityFramework/InstantFeedbackMode/MainViewModel.vb), [xaml](VB/ViewModel/EntityFramework/InstantFeedbackMode/MainWindow.xaml)|[project](VB/ViewModel/EFCore/InstantFeedbackMode), [code](VB/ViewModel/EFCore/InstantFeedbackMode/MainViewModel.vb), [xaml](VB/ViewModel/EFCore/InstantFeedbackMode/MainWindow.xaml)|[project](VB/ViewModel/XPO/InstantFeedbackMode), [code](VB/ViewModel/XPO/InstantFeedbackMode/MainViewModel.vb), [xaml](VB/ViewModel/XPO/InstantFeedbackMode/MainWindow.xaml)|
|Server Mode [?](https://docs.devexpress.com/WPF/6279/controls-and-libraries/data-grid/bind-to-data/server-mode-and-instant-feedback#server-mode)|[project](VB/ViewModel/EntityFramework/ServerMode), [code](VB/ViewModel/EntityFramework/ServerMode/MainViewModel.vb), [xaml](VB/ViewModel/EntityFramework/ServerMode/MainWindow.xaml)|[project](VB/ViewModel/EFCore/ServerMode), [code](VB/ViewModel/EFCore/ServerMode/MainViewModel.vb), [xaml](VB/ViewModel/EFCore/ServerMode/MainWindow.xaml)|[project](VB/ViewModel/XPO/ServerMode), [code](VB/ViewModel/XPO/ServerMode/MainViewModel.vb), [xaml](VB/ViewModel/XPO/ServerMode/MainWindow.xaml)|


