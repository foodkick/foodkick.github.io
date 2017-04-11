---
layout: styleguide
type: element
title: Buttons
lead: Use buttons to signal actions. 
---

<div class="preview buttons">
  <h2>Primary Button</h2>
  <h6>Main Styling</h6>
  <div class="button_wrapper">
    <button>Default</button>
    <button class="button-active">Active</button>
    <button class="button-hover">Hover</button>
    <button class="button-focus">Focus</button>
  </div>
  <h6>Ghost Styling (Light Background)</h6>
  <div class="button_wrapper">
    <button class="button-primary-alt">Default</button>
    <button class="button-primary-alt button-active">Active</button>
    <button class="button-primary-alt button-hover">Hover</button>
    <button class="button-primary-alt button-focus">Focus</button>
  </div>
  <h6>Ghost Styling (Dark Background)</h6>
  <div class="button_wrapper dark">
    <button class="button-primary-alt-dark">Default</button>
    <button class="button-primary-alt-dark button-active">Active</button>
    <button class="button-primary-alt-dark button-hover">Hover</button>
    <button class="button-primary-alt-dark button-focus">Focus</button>
  </div>

  <h2>Secondary Button</h2>
  <h6>Main Styling</h6>
  <div class="button_wrapper">
    <button class="button-secondary">Default</button>
    <button class="button-secondary button-secondary-active">Active</button>
    <button class="button-secondary button-secondary-hover">Hover</button>
    <button class="button-secondary button-secondary-focus">Focus</button>
  </div>
  <h6>Ghost Styling</h6>
  <div class="button_wrapper">
    <button class="button-secondary-alt">Default</button>
    <button class="button-secondary-alt button-secondary-active">Active</button>
    <button class="button-secondary-alt button-secondary-hover">Hover</button>
    <button class="button-secondary-alt button-secondary-focus">Focus</button>
  </div>

  <h2>Button Variations</h2>
  <h6>Button Sizes</h6>
  <div class="button_wrapper">  
    <button class="small">Small</button>
    <button>Medium</button>
    <button class="large">Large</button>
  </div>
  <h6>Wide Buttons</h6>
  <div class="button_wrapper">  
    <button class="small wide">Small</button>
    <button class="wide">Medium</button>
    <button class="large wide">Large</button>
  </div>

  <h2>Other Buttons</h2>
  <h6>Disabled Button</h6>
  <div class="button_wrapper">
    <button disabled>Default</button>
  </div>


</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <!-- <h4 class="usa-heading">Implementation</h4>
    <p>The examples demonstrate how to use button elements. To use a button style on an anchor link, add the <code>usa-button</code> class to your anchor link. 
    <p>To use a different style button on your anchor link, add the special button class in addition to <code>usa-button</code>:</p>
    <ul>
      <li><code>usa-button-primary-alt</code></li>
      <li><code>usa-button-secondary</code></li>
      <li><code>usa-button-gray</code></li>
      <li><code>usa-button-outline</code></li>
      <li><code>usa-button-outline-inverse</code></li>
      <li><code>usa-button-disabled</code></li>
      <li><code>usa-button-big</code></li>
    </ul>
    <p>For example, a secondary button style would use the following code:
    <code>&lt;a class="usa-button usa-button-secondary" href="/my-link"&gt;My button&lt;/a&gt;</code></p> -->
    <h4 class="usa-heading">Accessibility</h4>
    <ul class="usa-content-list">
      <li>Buttons should display a visible focus state when users tab to them.</li>
      <li>Avoid using <code>&lt;div&gt;</code> or <code>&lt;img&gt;</code> tags to create buttons. Screen readers don't automatically know either is a usable button.</li>
      <li>When styling links to look like buttons, remember that screen readers handle links slightly differently than they do buttons. Pressing the Space key triggers a button, but pressing the Enter key triggers a link.</li>
    </ul>
    <h4 class="usa-heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="usa-content-list">
      <li>Use buttons for the most important actions you want users to take on your site, such as "download," "create account," or "sign out".</li>
    </ul>
    <h5>When to consider something else</h5>
    <ul class="usa-content-list">
      <li>If you want to lead users between pages of a website. Use links instead.</li>
      <li>Less popular or less important actions may be visually styled as links.</li>
    </ul>
    <h5>Guidance</h5>
    <ul class="usa-content-list">
      <li>Generally, use primary buttons for actions that go to the next step and use secondary buttons for actions that happen on the current page.</li>
      <li>Style the button most users should click in a way that distinguishes from other buttons on the page. Try using the  “large button” or the most visually distinct fill color.</li>
      <li>Make sure buttons should look clickable—use color variations to distinguish static, hover and active states.</li>
      <li>Avoid using too many buttons on a page.</li>
      <li>Use sentence case for button labels. </li>
      <li>Button labels should be as short as possible with “trigger words” that your users will recognize to clearly explain what will happen when the button is clicked (for example, “download,” “view” or “sign up”).</li>
      <li>Make the first word of the button’s label a verb. For example, instead of “Complaint Filing” label the button “File a complaint.”</li>
      <li>At times, consider adding an icon to signal specific actions (“download”, “open in a new window”, etc). </li>
    </ul>
  </div>
</div>
