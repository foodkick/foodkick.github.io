---
layout: styleguide
title: Colors
order: 02
---

<p>A flexible, yet distinctly American palette designed to communicate warmth and trustworthiness while meeting the highest standards of 508 color contrast requirements.</p><!-- <a class="usa-button usa-button-primary-alt" href="{{ site.baseurl }}/assets/releases/wds-design-v0.8.1.zip">Download the design files</a>
<p class="usa-text-small">Download a zip file with font files and color swatches.</p> -->

<h3 class="usa-heading" id="palette">Palette</h3>

<p>This palette is designed to support a range of distinct visual styles that continue to feel connected. The intent of the palette is to convey a warm and open American spirit, with bright saturated tints of blue and red, grounded in sophisticated deeper shades of cool blues and grays. These colors — combined with clear hierarchy, good information design, and ample white space — should leave users feeling welcomed and in good hands.</p>

<p>This is a simple, minimalist color palette. Shades of blue dominate, providing a neutral backdrop on which brighter shades, clean type treatment, and bright white content areas "pop" on the page.</p>

<h4 class="usa-heading">Primary colors</h4>

<p>These are accent colors to provide additional lightness and style to pages looking for a more modern flair. These colors should be used to highlight important features on a page, such as buttons, or for visual style elements, such as illustrations. They should be used sparingly and never draw the eye to more than one piece of information at a time.</p>

<div class="usa-grid-full usa-color-row">
  <div class="color-big">
    <div class="usa-color-short color-primary">
    </div>
      <p class="usa-color-hex">#732282</p>
      <p class="usa-color-name">primary</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-primary-darker">
    </div>
      <p class="usa-color-hex">#4f175a</p>
      <p class="usa-color-name">primary-darker</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-primary-lighter">
    </div>
      <p class="usa-color-hex">#852796</p>
      <p class="usa-color-name">primary-lighter</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-primary-lightest">
    </div>
      <p class="usa-color-hex">#972daa</p>
      <p class="usa-color-name">primary-lightest</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-primary-fade">
    </div>
      <p class="usa-color-hex">#fbf4fc</p>
      <p class="usa-color-name">primary-fade</p>
  </div> 
</div>

<h4 class="usa-heading">Secondary colors</h4>

<p>These are accent colors to provide additional lightness and style to pages looking for a more modern flair. These colors should be used to highlight important features on a page, such as buttons, or for visual style elements, such as illustrations. They should be used sparingly and never draw the eye to more than one piece of information at a time.</p>

<div class="usa-grid-full usa-color-row">
  <div class="color-big">
    <div class="usa-color-short color-secondary">
    </div>
      <p class="usa-color-hex">#0099b2</p>
      <p class="usa-color-name">secondary</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-secondary-darker">
    </div>
      <p class="usa-color-hex">#006d7f</p>
      <p class="usa-color-name">secondary-darker</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-secondary-lighter">
    </div>
      <p class="usa-color-hex">#00afcc</p>
      <p class="usa-color-name">secondary-lighter</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-secondary-lightest">
    </div>
      <p class="usa-color-hex">#00bcdb</p>
      <p class="usa-color-name">secondary-lightest</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-secondary-fade">
    </div>
      <p class="usa-color-hex">#effdff</p>
      <p class="usa-color-name">secondary-fade</p>
  </div>
</div>

<h4 class="usa-heading">Background colors</h4>

<p>These colors are used largely for background blocks and large content areas. When alternating between tones, be sure to use enough contrast between adjacent colors.</p>

<div class="usa-grid-full usa-color-row">
  <div class="color-big">
    <div class="usa-color-short color-gray-dark">
    </div>
      <p class="usa-color-hex">#575860</p>
      <p class="usa-color-name">gray-dark</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-gray">
    </div>
      <p class="usa-color-hex">#a6a8b1</p>
      <p class="usa-color-name">gray</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-gray-light">
    </div>
      <p class="usa-color-hex">#e1e1e1</p>
      <p class="usa-color-name">gray-light</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-gray-lighter">
    </div>
      <p class="usa-color-hex">#f4f4f3</p>
      <p class="usa-color-name">gray-lighter</p>
  </div>
  <div class="color-small">
    <div class="usa-color-short color-white">
    </div>
      <p class="usa-color-hex">#ffffff</p>
      <p class="usa-color-name">white</p>
  </div>
</div>

<!-- Links section begin -->

<h3 class="usa-heading" id="links">Links</h3>

<p class="usa-font-lead">Links lead users to a different page or further information.
</p>

<div class="preview">

  <a href="#">This is a link without surrounding text.</a>
  <p><a href="#">This</a> is a text link on a light background.</p>

  <div class="usa-background-dark">
    <p><a href="#">This</a> is a text link on a dark background.</p>
  </div>
</div>

<!-- Links section end -->

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Accessibility</h4>
    <ul class="usa-content-list">
      <li>Users should be able to tab to navigate between links.
      <li>Users should be able to activate a link when pressing ‘Enter’ on their keyboard.</li>
      <li>Users should be able to identify links without relying on color alone.</li>
      <li>Users should be able to activate hover and and focus states with both a mouse and a keyboard.</li>
    </ul>
  </div>
</div>


<!-- <p>The options below offer color palette combinations that fall within the range of Section 508 compliant foreground/background color contrast ratios. To ensure that text remains accessible, use only these permitted color combinations.</p>
<p>If you choose to customize beyond this palette, this <a href="http://webaim.org/resources/contrastchecker/">color contrast tool</a> is a useful resource for testing the compliance of any color combination.</p>
<h4 class="usa-heading">Fully accessible combinations</h4>

<h5>Colors on a white background</h5>

<div class="usa-grid-full usa-color-outline">
  <div class="usa-width-one-half">
    <div class="usa-color-text usa-color-text-primary-darkest">
      primary-darkest on white
    </div>
    <div class="usa-color-text usa-color-text-primary-darker">
      primary-darker on white
    </div>
    <div class="usa-color-text usa-color-text-primary">
      primary on white
    </div>
    <div class="usa-color-text usa-color-text-cool-blue-light">
      cool-blue-light on white
    </div>
    <div class="usa-color-text usa-color-text-primary-alt-darkest">
      primary-alt-darkest on white
    </div>
    <div class="usa-color-text usa-color-text-green">
      green on white
    </div>
    <div class="usa-color-text usa-color-text-visited">
      visited on white
    </div>
  </div>
  <div class="usa-width-one-half usa-end-row">
    <div class="usa-color-text usa-color-text-gray-dark">
      base on white
    </div>
    <div class="usa-color-text usa-color-text-gray-dark">
      gray-dark on white
    </div>
    <div class="usa-color-text usa-color-text-gray">
      gray on white
    </div>
    <div class="usa-color-text usa-color-text-gray-warm-dark">
      gray-warm-dark on white
    </div>
    <div class="usa-color-text usa-color-text-secondary-darkest">
      secondary-darkest on white
    </div>
    <div class="usa-color-text usa-color-text-secondary-dark">
      secondary-dark on white
    </div>
    <div class="usa-color-text usa-color-text-secondary">
      secondary on white
    </div>
  </div>
</div>

<h5>Neutrals on a colored background</h5>

<div class="usa-grid-full">
  <div class="usa-width-one-half">
    <div class="usa-color-text usa-color-base usa-color-text-white">
      white on base
    </div>
    <div class="usa-color-text usa-color-gray-warm-dark usa-color-text-white">
      white on gray-warm-dark
    </div>
    <div class="usa-color-text usa-color-gray-dark usa-color-text-white">
      white on gray-dark
    </div>
    <div class="usa-color-text usa-color-gray usa-color-text-white">
      white on gray
    </div>
    <div class="usa-color-text usa-color-primary-darkest usa-color-text-white">
      white on primary-darkest
    </div>
    <div class="usa-color-text usa-color-primary-darker usa-color-text-white">
      white on primary-darker
    </div>
    <div class="usa-color-text usa-color-primary usa-color-text-white">
      white on primary
    </div>
    <div class="usa-color-text usa-color-cool-blue-light usa-color-text-white">
      white on cool-blue-light
    </div>
    <div class="usa-color-text usa-color-primary-alt-darkest usa-color-text-white">
      white on primary-alt-darkest
    </div>
    <div class="usa-color-text usa-color-primary-alt-dark">
      base on primary-alt-dark
    </div>
    <div class="usa-color-text usa-color-primary-alt">
      base on primary-alt
    </div>
    <div class="usa-color-text usa-color-green usa-color-text-white">
      white on green
    </div>
    <div class="usa-color-text usa-color-green-light">
      base on green-light
    </div>
    <div class="usa-color-text usa-color-gold">
      base on gold
    </div>
    <div class="usa-color-text usa-color-gold-light">
      base on gold-light
    </div>
    <div class="usa-color-text usa-color-secondary-darkest usa-color-text-white">
      white on secondary-darkest
    </div>
    <div class="usa-color-text usa-color-secondary-dark usa-color-text-white">
      white on secondary-dark
    </div>
    <div class="usa-color-text usa-color-secondary usa-color-text-white">
      white on secondary
    </div>
  </div>
  <div class="usa-width-one-half usa-end-row">
    <div class="usa-color-text usa-color-gray-light">
      base on gray-light
    </div>
    <div class="usa-color-text usa-color-gray-lighter">
      base on gray-lighter
    </div>
    <div class="usa-color-text usa-color-gray-warm-light">
      base on gray-warm-light
    </div>
    <div class="usa-color-text usa-color-cool-blue-lighter">
      base on cool-blue-lighter
    </div>
    <div class="usa-color-text usa-color-cool-blue-lightest">
      base on cool-blue-lightest
    </div>
    <div class="usa-color-text usa-color-primary-alt-lightest">
      base on primary-alt-lightest
    </div>
    <div class="usa-color-text usa-color-green-lighter">
      base on green-lighter
    </div>
    <div class="usa-color-text usa-color-green-lightest">
      base on green-lightest
    </div>
    <div class="usa-color-text usa-color-gold-lighter">
      base on gold-lighter
    </div>
    <div class="usa-color-text usa-color-gold-lightest">
      base on gold-lightest
    </div>
    <div class="usa-color-text usa-color-secondary-lightest">
      base on secondary-lightest
    </div>
  </div>
</div>
 -->