---
layout: widget
title: LinkedIn Profile

---

# LinkedIn Profile

Add a LinkedIn personal profile widget to your template.

## Overview

You can add a LinkedIn personal profile widget to your template. This profile URL can be changed later in the BaseKit Editor.

To include a LinkedIn profile widget in your template you will need to add the following line:

{% highlight ruby %}
{% raw %}

	{{widget('linkedinprofile', 'thisunqiuewidgetname', {'linkedin': 'http://www.linkedin.com/in/johndoe'})|raw}}

{% endraw %}
{% endhighlight %}

## Widget Options

You can change the following options for the widget:

* ```linkedin```: The linkedin profile public URL. For example: ```http://www.linkedin.com/in/johndoe```
