# 目录

* [简介](README.md)
* [典型例子](compelling-example/index.md)
* [成功故事](https://github.com/reactiveui/ReactiveUI/issues/979)
* [基础](fundamentals/index.md)
  * [历史背景](fundamentals/history.md)
  * [函数响应编程](fundamentals/functional-reactive-programming.md)
  * [Model-View-ViewModel](fundamentals/model-view-viewmodel.md)
  * [Reactive Extensions](fundamentals/reactive-extensions.md)
  * [Our Philosophy](fundamentals/philosophy.md)
* [开始](getting-started/index.md)
  * [解决方案设计](getting-started/solution-layout.md)
  * [Visual Studio 设置](getting-started/visual-studio-settings.md)
  * [Xamarin Studio 设置](getting-started/xamarin-studio-settings.md)
  * [调试符号](getting-started/debugging-symbols.md)
  * [Example](getting-started/example.md)
* [例子](https://github.com/reactiveui/samples)
* [用户指导](user-guide/index.md)
  * [WhenAny](user-guide/when-any/index.md)
  * [视图模型](user-guide/view-models/index.md)
    * [数据封存](user-guide/data-suspension/index.md)
    * [AutoSuspendHelper](user-guide/data-suspension/autosuspendhelper.md)
  * [视图](user-guide/views/index.md)
    * [视图定位](user-guide/views/view-location.md)
    * [设计时](user-guide/design-time/index.md)
  * [绑定](user-guide/binding/index.md)
    * [类型转换器](user-guide/binding/type-converters.md)
    * [平台](user-guide/binding/platforms.md)
      * [Xamarin Android](user-guide/binding/xamarin-android.md)
      * [Xamarin Forms](user-guide/binding/xamarin-forms.md)
      * [Xamarin iOS](user-guide/binding/xamarin-ios.md)
      * [Windows Forms](user-guide/binding/windows-forms.md)
      * [Windows Presentation Framework](user-guide/binding/windows-presentation-framework.md)
      * [Windows Universal](user-guide/binding/windows-universal.md)
  * [命令](user-guide/commands/index.md)
    * [Reactive Commands](user-guide/commands/reactive-commands.md)
    * [例子](user-guide/commands/an-example.md)
    * [异步与同步](user-guide/commands/asynchronous-synchronous.md)
    * [参数](user-guide/commands/command-parameters.md)
    * [返回值](user-guide/commands/command-values.md)
    * [Controlling Scheduling](user-guide/commands/controlling-scheduling.md)
    * [错误处理](user-guide/commands/command-errors.md)
    * [可执行性](user-guide/commands/controlling-executability.md)
    * [绑定](user-guide/commands/binding-commands.md)
    * [调用](user-guide/commands/invoking-commands.md)
    * [组合](user-guide/commands/combining-commands.md)
    * [取消](user-guide/commands/canceling.md)
    * [杂项](user-guide/commands/misc.md)
      * [Automatic Execution](user-guide/commands/automatic-execution.md)
      * [Thrown Exceptions](user-guide/commands/thrown-exceptions.md)
      * [Asynchronous operations](user-guide/commands/asynchronous-operations.md)
      * [Common Patterns](user-guide/commands/common-patterns.md)
      * [Unit Testing](user-guide/commands/unit-testing.md)
  * [Interactions](user-guide/interactions/index.md)
  * [ObservableAsPropertyHelper](user-guide/observableaspropertyhelper/index.md)
  * [Lists](user-guide/lists/index.md)
    * [Derived Lists](user-guide/lists/derived-lists.md)
  * [WhenActivated](user-guide/when-activated/index.md)
  * [Dependency Injection](user-guide/dependency-injection/index.md)
  * [Events](user-guide/events/index.md)
    * [Windows Forms](user-guide/events/windows-forms.md)
  * [Routing](user-guide/routing/index.md)
    * [Xamarin Forms](user-guide/routing/xamarin_forms.md)
  * [Caching](user-guide/caching/index.md)
    * [Common Patterns](user-guide/caching/common-patterns.md)
  * [MessageBus](user-guide/message-bus/index.md)
  * [Logging](user-guide/logging/index.md)
    * [Visual Studio IntelliTrace](user-guide/logging/visual-studio-intellitrace.md)
    * [Debugging Observables](user-guide/logging/debugging-observables.md)
  * [Troubleshooting](user-guide/troubleshooting/index.md)
* [模式](patterns/index.md)
  * [Validation](patterns/validation.md)
* [平台相关](platform-considerations/index.md)
  * [Xamarin Android](platform-considerations/xamarin-android.md)
  * [Xamarin Forms](platform-considerations/xamarin-forms.md)
  * [Xamarin iOS](platform-considerations/xamarin-ios.md)
  * [Xamarin Mac](platform-considerations/xamarin-mac.md)
  * [Windows Forms](platform-considerations/windows-forms.md)
  * [Windows Presentation Framework](platform-considerations/windows-presentation-framework.md)
  * [Windows Universal](platform-considerations/windows-universal.md)
* [设计指南](design-guidelines/index.md)
  * [命令](design-guidelines/commands.md)
  * [命令名称](design-guidelines/command-names.md)
  * [命令执行](design-guidelines/command-execution.md)
  * [销毁订阅](design-guidelines/dispose-your-subscriptions.md)
  * [UI 线程和调度器](design-guidelines/ui-thread-and-schedulers.md)
  * [Prefer OAPH over Properties](design-guidelines/prefer-opah-over-properties.md)
  * [Use this on Left of WhenAny](design-guidelines/use-this-on-left-of-whenany.md)
  * [Use descriptive variables with WhenAny](design-guidelines/use-descriptive-variables-with-whenany.md)
* [异步命令](design-guidelines/asynchronous-commands.md)
* [构建](contributing/index.md)
  * [Documentation](contributing/documentation.md)
    * [Authors](https://github.com/reactiveui/documentation/graphs/contributors)
    * [Copyright Assignment](https://github.com/reactiveui/documentation/blob/master/COPYRIGHT.md)
    * [License](https://github.com/reactiveui/documentation/blob/master/LICENSE.md)
  * [Framework](contributing/framework/index.md)
    * [Pre-release Builds](contributing/framework/pre-release-builds.md)
    * [Approval Tests](contributing/framework/approval-tests.md)
    * [Commit Message Convention](contributing/framework/commit-message-convention.md)
    * [Submitting A Pull Request](contributing/framework/submitting-a-pull-request.md)
    * [Reviewing Pull Requests](contributing/framework/reviewing-pull-requests.md)
    * [Merging Pull Requests](contributing/framework/merging-pull-requests.md)
    * [Semantic Versioning](contributing/framework/semantic-versioning.md)
    * [Release Workflow](contributing/framework/release-workflow.md)
    * [Troubleshooting AppVeyor](contributing/framework/troubleshooting-appveyor.md)
    * [Code of Conduct](https://github.com/reactiveui/ReactiveUI/blob/develop/CODE_OF_CONDUCT.md)
    * [License](https://github.com/reactiveui/ReactiveUI/blob/develop/LICENSE)
  * [Plugins](contributing/plugins/index.md)
* [支持](support/index.md)
* [发布日志](https://github.com/reactiveui/reactiveui/releases)
