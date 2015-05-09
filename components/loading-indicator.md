---
layout: default
title: Loading Indicator
---

### Container Loading Indicator

#### Loading Indicator
A loading indicator used in a container.

<div class="ui-example">
    <div class="loading-indicator-container">
        <div class="loading-indicator">
            <span></span>
        </div>
        <p>This is some content inside the container</p>
        <p>The loading indicator must be prepended to it</p>
    </div>
</div>

    <div class="loading-indicator-container">
        <div class="loading-indicator">
            <span></span>
            <p>This is some content inside the container</p>
            <p>The loading indicator must be prepended to it</p>
        </div>
    </div>

#### Text Loading Indicator
A loading indicator can have text by adding a `<div>` element inside.

<div class="ui-example">
    <div class="loading-indicator-container">
        <div class="loading-indicator">
            <span></span>
            <div>Loading...</div>
        </div>
    </div>
</div>

    <div class="loading-indicator-container">
        <div class="loading-indicator">
            <span></span>
            <div>Loading...</div>
        </div>
    </div>

#### Loading Indicator Sizes

A loading indicator can have a size by adding `size-X` to the container. These sizes are available: **size-small**.

<div class="ui-example">
    <div class="loading-indicator-container">
        <div class="loading-indicator size-small">
            <span></span>
            <div>Loading (size-small)</div>
        </div>
    </div>
</div>

    <div class="loading-indicator-container">
        <div class="loading-indicator size-small">
            <span></span>
            <div>Loading (size-small)</div>
        </div>
    </div>

#### Loading Indicator Alignment

A loading indicator can be aligned to the center by adding `indicator-center` to the container and/or indicator.

<div class="ui-example">
    <div class="loading-indicator-container">
        <div class="loading-indicator indicator-center">
            <span></span>
        </div>
    </div>
</div>

    <div class="loading-indicator-container">
        <div class="loading-indicator indicator-center">
            <span></span>
        </div>
    </div>