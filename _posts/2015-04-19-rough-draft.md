---
permalink: rough-draft
layout: base
---

## Why We Graph


<a href="https://plot.ly/~chriddyp/687">
    <img style="width: 100%" src="https://plot.ly/~chriddyp/687.png">
</a>


## Mind Your Labels
It's **OK** not to have a title or axes labels


Don't
<a href="https://plot.ly/~chriddyp/614">
    <img src="https://plot.ly/~chriddyp/614.png">
</a>

<i>"Current" is repeated 3 times</i>



Do
<a href="https://plot.ly/~chriddyp/619">
    <img src="https://plot.ly/~chriddyp/619.png">
</a>


Don't

<a href="https://plot.ly/~chriddyp/674">
    <img src="https://plot.ly/~chriddyp/674.png">
</a>
<i>A date axis with an x-axis title <b>date</b> is redudant</i>

Do

<a href="https://plot.ly/~chriddyp/670">
    <img src="https://plot.ly/~chriddyp/670.png">
</a>


## Lighten it up
Remove unncessary gridlines, ticks, borders.


Don't


<a href="https://plot.ly/~chriddyp/614">
    <img src="https://plot.ly/~chriddyp/755.png">
</a>

Do


<a href="https://plot.ly/~chriddyp/619">
    <img src="https://plot.ly/~chriddyp/619.png">
</a>


## Dense Scatter Plots

<iframe src="https://plot.ly/~chriddyp/636.embed" style="width: 100%; height: 550px; border: none;"></iframe>


<div class="row">
    <div class="six columns">
        <div>
            <a href="https://plot.ly/~chriddyp/636">
                <img style="width: 100%" src="https://plot.ly/~chriddyp/636.png">
            </a>
        </div>
    </div>

    <div class="six columns">
        <div>
            <a href="https://plot.ly/~chriddyp/633">
                <img style="width: 100%" src="https://plot.ly/~chriddyp/633.png">
            </a>
        </div>
    </div>
</div>

<div class="row">
    <div class="six columns">
        <div>
            <a href="https://plot.ly/~chriddyp/631">
                <img style="width: 100%" src="https://plot.ly/~chriddyp/631.png">
            </a>
        </div>
    </div>

    <div class="six columns">
        <div>
            <a href="https://plot.ly/~chriddyp/629">
                <img style="width: 100%" src="https://plot.ly/~chriddyp/629.png">
            </a>
        </div>
    </div>
</div>


<iframe src="https://plot.ly/~chriddyp/629.embed" style="width: 100%; height: 700px; border:none;"></iframe>


### Use opacity when your data is dense

<b>Without opacity</b>

![](https://plot.ly/~chriddyp/651.png)

<b>Opaque markers</b>

![](https://plot.ly/~chriddyp/649.png)

<b>Opaque markers with thin marker borders</b>

![](https://plot.ly/~chriddyp/653.png)

![](https://plot.ly/~alex/455.png)

## Cases for Interactivity

#### Reduce noise and allow exploration

**Comparing Values**


<iframe src="https://plot.ly/~theengineear/3510.embed?autosize=false&height=600&width=800"
        style="border: none; width: 100%; height: 850px;"></iframe>


<iframe src="https://plot.ly/~chriddyp/598.embed?autosize=false&height=600&width=800"
        style="border: none; width: 100%; height: 850px;"></iframe>


<iframe src="https://plot.ly/~chris/7365.embed?autosize=false&height=600&width=800"
        style="border: none; width: 100%; height: 850px;"></iframe>

<iframe src="https://plot.ly/~chriddyp/708.embed?autosize=false&height=600&width=800"
        style="border: none; width: 100%; height: 850px;"></iframe>

**Text**

Don't

<img style="width: 100%" src="https://plot.ly/~theengineear/3397/movies.png">

Do

<iframe src="https://plot.ly/~theengineear/3398.embed" style="border: none; width: 100%; height: 500px;"></iframe>


## Math Type


<div class="row" style="height: ">
    <div class="six columns">
        <div>
            Don't
            <img style="width: 100%" src="https://plot.ly/~chriddyp/764.png">
        </div>
    </div>

    <div class="six columns">
        <div>
            Do
            <img style="width: 100%"  src="https://plot.ly/~chriddyp/764.png">
        </div>
    </div>
</div>



[LaTeX Tutorial with Plotly](https://plot.ly/LaTeX-basics/)

[HTML Characters with Plotly](https://plot.ly/adding-HTML-and-links-to-charts/)

## Color Scales

Is your data **sequential** (you're interested in how much larger or smaller one value is from the other), **diverging** (about a midpoint), or **qualitative** (you're searching for features)?

Pick your colorscale!

**Sequential data**

- Depth or elevation
- Temperature

![](https://plot.ly/~chriddyp/664.png)


<a href="https://plot.ly/~chris/8523.png">
    <img src="https://plot.ly/~chris/8523.png" style="width: 100%">
</a>


**Diverging data**

Examples
- Above sea level, below sea level
- Above freezing, below freezing
- Any sets of data with a clear midpoint


![](https://plot.ly/~chris/5496.png)


<a href="https://plot.ly/~chris/8523.png">
    <img src="https://plot.ly/~chris/8523.png" style="width: 100%">
</a>


**Qualitative data**

- You're unsure of your data's model
- You're more interested in certain features in your dataset, like peaks or valleys that might be obscured in a sequential scale

![](https://plot.ly/~cfif/66.png)


<a href="https://plot.ly/~chris/8524.png">
    <img src="https://plot.ly/~chris/8524.png" style="width: 100%">
</a>

**Exploring Contour Plots and Heatmaps**

[![](http://i.imgur.com/11rI5jt.png)](http://chriddyp.github.io/interactive-heatmaps/)

