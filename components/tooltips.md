---
layout: default
title: Tooltips
---
Tooltips are an alternative to the standard browser title tooltip.

## Tooltip markup
A standard tooltip

<div class="ui-example" style="height: 60px">
    <div class="tooltip fade top in">
        <div class="tooltip-arrow"></div>
        <div class="tooltip-inner">Create a new blog post based on this</div>
    </div>
</div>

{% highlight html %}
<div class="tooltip fade top in">
    <div class="tooltip-arrow"></div>
    <div class="tooltip-inner">Create a new blog post based on this</div>
</div>
{% endhighlight %}

## Spawning tooltips
Tooltips can be automatically created when the mouse enters an element using the `data-toggle="tooltip"` tag.

{% highlight html %}
<a
    href="javascript:;"
    data-toggle="tooltip"
    data-placement="left"
    data-delay="500"
    title="Tooltip content">
    Some link
</a>
{% endhighlight %}