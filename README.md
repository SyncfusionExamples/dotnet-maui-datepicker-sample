# Getting started with .NET MAUI Date Picker
This section explains how to add the [.NET MAUI Date Picker](https://www.syncfusion.com/maui-controls/maui-datepicker) control. It covers only the basic features needed to get started with Syncfusion<sup>&reg;</sup> Date Picker.

## Register Syncfusion handler

Make sure to add the namespace.

{% highlight MauiProgram.cs %}
using Syncfusion.Maui.Core.Hosting;
{% endhighlight %} 

Register the Syncfusion core handler in your `CreateMauiApp` method of `MauiProgram.cs` file to use Syncfusion controls.

{% highlight MauiProgram.cs %}
builder.ConfigureSyncfusionCore();
{% endhighlight %}

## Import the Date picker namespace

Add the following namespace in your XAML or C#.

{% tabs %}
{% highlight xaml tabtitle="xaml" %}
xmlns:picker="clr-namespace:Syncfusion.Maui.Picker;assembly=Syncfusion.Maui.Picker"
{% endhighlight %}
{% highlight c# tabtitle="C#" %}
using Syncfusion.Maui.Picker;
{% endhighlight %}
{% endtabs %}

## Add the Date picker component

Create an instance of Date Picker and add it to your page.

{% tabs %}
{% highlight xaml tabtitle="XAML" %}
    <picker:SfDatePicker />
{% endhighlight %}
{% highlight c# tabtitle="C#" %}
    SfDatePicker picker = new SfDatePicker();
    this.Content = picker;
{% endhighlight %}
{% endtabs %}

The following screenshot illustrates the result of the above code.

![Set Height and width in .NET MAUI Date picker.](images/getting-started/maui-date-picker-set-height-and-width.png)

You can download the Picker Getting Started sample from [GitHub](https://github.com/syncfusion/maui-demos/tree/master/MAUI/Picker/SampleBrowser.Maui.Picker/Samples/DatePicker)
