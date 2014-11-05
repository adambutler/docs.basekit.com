---
layout: widget
title: Content Widget
---

# Content Widget

Add a Content widget to your template

## Overview

You can add a content widget to your template to display a paragraph text. The widget can be later customised within the BaseKit Editor. 

To include a content widget in your template you will need to add the following line:

{% highlight ruby %}
{% raw %}

	{{widget('content', 'thisunqiuewidgetname', {content: 'This is a content widget.', lines: 'all'})|raw}}

{% endraw %}
{% endhighlight %}

## Widget Options

You can change the following options for the widget:

* ```content```: The content on the widget.

* ```lines```: Set the text truncation.

  * ```one```
  * ```two```
  * ```all```