---
permalink: rough-draft
layout: base
---

## Why We Graph

![](https://plot.ly/~chriddyp/687.png)

## Mind Your Labels
It's **OK** not to have a title or axes labels



<div class="row">
    <div class="six columns">
        <div style="padding-right: 5px;">
            Don't

            <img style="width: 100%" src="https://plot.ly/~chriddyp/614.png">

            <i>"Current" is repeated 3 times</i>
        </div>
    </div>


    <div class="six columns">
        <div style="padding-left: 5px;">
            Do

            <img style="width: 100%" src="https://plot.ly/~chriddyp/619.png">
        </div>
    </div>
</div>


<div class="row" style="padding-top: 100px">
    <div class="six columns">
        <div style="padding-right: 5px;">
            Don't

            <img style="width: 100%" src="https://plot.ly/~chriddyp/674.png">

            <i>A date axis with an x-axis title <b>date</b> is redudant</i>
        </div>
    </div>


    <div class="six columns">
        <div style="padding-left: 5px;">
            Do

            <img style="width: 100%" src="https://plot.ly/~chriddyp/670.png">
        </div>
    </div>
</div>


## Dense Scatter Plots

<div class="row">
    <div class="six columns">
        <div>
            <img style="width: 100%" src="https://plot.ly/~chriddyp/636.png">
        </div>
    </div>

    <div class="six columns">
        <div>
            <img style="width: 100%" src="https://plot.ly/~chriddyp/633.png">
        </div>
    </div>
</div>

<div class="row">
    <div class="six columns">
        <div>
            <img style="width: 100%" src="https://plot.ly/~chriddyp/631.png">
        </div>
    </div>

    <div class="six columns">
        <div>
            <img style="width: 100%" src="https://plot.ly/~chriddyp/629.png">
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


<div class="row" style="height: ">
    <div class="six columns">
        <div>
            Don't
            <img style="width: 100%" src="https://plot.ly/~theengineear/3397/movies.png">
        </div>
    </div>

    <div class="six columns">
        <div>
            Do
            <iframe src="https://plot.ly/~theengineear/3398.embed" style="border: none; width: 100%; height: 100%"></iframe>
        </div>
    </div>
</div>


## Math Type

![LaTeX Example](https://plot.ly/~theengineear/3518.png)

[LaTeX Tutorial with Plotly](https://plot.ly/LaTeX-basics/)

[HTML Characters with Plotly](https://plot.ly/adding-HTML-and-links-to-charts/)

## Color Scales

Is your data **sequential** (you're interested in how much larger or smaller one value is from the other), **diverging** (about a midpoint), or **qualitative** (you're searching for features)?

Pick your colorscale!

**Sequential data**

- Depth or elevation
- Temperature

![](https://plot.ly/~chriddyp/664.png)


<img src="https://plot.ly/~chris/8522.png" style="width: 100%">


**Diverging data**

Examples
- Above sea level, below sea level
- Above freezing, below freezing
- Any sets of data with a clear midpoint


![](https://plot.ly/~chris/5496.png)


<img src="https://plot.ly/~chris/8523.png" style="width: 100%">


**Qualitative data**

- You're unsure of your data's model
- You're more interested in certain features in your dataset, like peaks or valleys that might be obscured in a sequential scale

![](https://plot.ly/~cfif/66.png)


<img src="https://plot.ly/~chris/8524.png" style="width: 100%">


## Histogram

<div class="row" style="height: ">
    <div class="six columns">
        <div>
            Bar chart
            <img style="width: 100%" src="https://plot.ly/~cparmer2/632.png">
        </div>
    </div>

    <div class="six columns">
        <div>
            Histogram
            <img style="width: 100%" src="https://plot.ly/~cparmer2/631.png">
        </div>
    </div>
</div>
