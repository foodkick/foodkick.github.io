---
layout: styleguide
title: Grids
lead:  This 16-column, responsive grid provides structure for website content. 
---
<p>The grid is based on the following measurements:</p>
<ul>
  <li><em class="em-yellow-bg">1200px page width</em></li>
  <li><em class="em-yellow-bg">30px gutter width</em></li>
  <li><em class="em-yellow-bg">15px side margin</em></li>
</ul>
<div class="preview preview-no_border">

  <h2 class="usa-heading">Grid</h2>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-whole">1/1</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-half">1/2</div>
    <div class="usa-width-one-half">1/2</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-third">1/3</div>
    <div class="usa-width-one-third">1/3</div>
    <div class="usa-width-one-third">1/3</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-fourth">1/4</div>
    <div class="usa-width-one-fourth">1/4</div>
    <div class="usa-width-one-fourth">1/4</div>
    <div class="usa-width-one-fourth">1/4</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-fifth">1/5</div>
    <div class="usa-width-one-fifth">1/5</div>
    <div class="usa-width-one-fifth">1/5</div>
    <div class="usa-width-one-fifth">1/5</div>
    <div class="usa-width-one-fifth">1/5</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-sixth">1/6</div>
    <div class="usa-width-one-sixth">1/6</div>
    <div class="usa-width-one-sixth">1/6</div>
    <div class="usa-width-one-sixth">1/6</div>
    <div class="usa-width-one-sixth">1/6</div>
    <div class="usa-width-one-sixth">1/6</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
    <div class="usa-width-one-eight">1/8</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
    <div class="usa-width-one-tenth">1/10</div>
  </div>
  <div class="usa-grid usa-grid-example usa-grid-example-blank">
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
    <div class="usa-width-one-twelfth">1/12</div>
  </div>

  <!-- <h2 class="usa-heading">Grid Examples</h2> -->

</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Implementation</h4>
    <p>To use the grid, wrap each grid row in a <code>&lt;div&gt;</code> with the <code>usa-grid</code> class. To use a grid without padding on the right and left, use the <code>usa-grid-full</code> class instead.</p>
    <p>Each grid item is written semantically by its width. For example: <code>usa-width-one-half</code> = 1/2 grid item, <code>usa-width-two-thirds</code> = 2/3 grid item.</p>
    <p>Medium breakpoints are used for 1/6 and 1/12 grid items, which both transform into a 1/3 grid item at medium screen sizes.</p> 
    <p>All grid items are full-width at small screen sizes.</p>
    <h4 class="usa-heading">Accessibility</h3>
    <ul class="usa-content-list">
      <li>Low-vision users should be able to increase the size of the text by up to 200 percent without breaking the layout.</li>
    </ul>
    
    <h4 class="usa-heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="usa-content-list">
      <li>Almost always use a grid layout — visitors can read more quickly on pages that use grids. Choose a single grid system for your entire site.</li>
    </ul>
    <h5>When to consider something else</h5>
    <ul class="usa-content-list">
      <li>Avoid mixing this grid and other grid systems.</li>
    </ul>
    <h5>Guidance</h5>
    <ul class="usa-content-list">
      <li>Choose a 16-column grid with flexible column widths and fixed gutters. The width of the padding on the left and right edge of the grid depends on device size.</li>
      <li>Avoid text lines longer than 75 characters. Place text in narrower grid boxes to keep text lines from becoming too wide.</li>
    </ul>
  </div>
</div>
