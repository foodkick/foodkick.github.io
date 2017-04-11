---
layout: styleguide
type: element
title: Text Links
lead: Text Links are used to trigger actions or lead users through the site. They can also be used as a tooltip to reveal details about our services. 
---

<div class="preview">

  <h3>Text Link</h3>

  <h6 class="zero-margin-bottom">Primary (Purple)</h6>
  <div class="link_wrapper"><a class="fk-link-purple" href="http://foodkick.com" target="_blank">This text link takes you to a world full of flavor</a></div>

  <h6 class="zero-margin-bottom">Secondary (Teal)</h6>
  <div class="link_wrapper"><a class="fk-link-blue-dark" href="http://foodkick.com" target="_blank">This text link takes you to a world full of flavor</a></div>

  <div class="link_wrapper dark"><a class="fk-link-blue-light" href="http://foodkick.com" target="_blank">This text link takes you to a world full of flavor</a></div>
  
  <h3>Text Link in a Paragraph</h3>
  <p class="example">Text Links in a paragraph <a class="fd-link" href="#">look like this</a>. With pretty stories for which there's little good evidence quasar. Stirred by starlight cosmic ocean, with <a class="fd-link" href="#">pretty stories for which there's little good evidence</a> rogue extraordinary claims require extraordinary evidence lorem ipsum dolor sit amet!</p>
  <!-- <p class="example"><a class="fd-link-visited" href="#">This is a visited link</a> inside a paragraph.</p> -->

  <h3>Information Link</h3>
  <p class="example"><strong>Super Salmon</strong> <a class="tooltip-small" href="#" info="This is some information about freshness. Bread, cheese, red pepper, olives, lox, thyme, and more.">q</a><br />Use a question tooltip for terminology that may need further explanation.</p>
  <p class="example"><strong>Sales Tax</strong> <a class="tooltip-small info" href="#" info="This is some information about freshness. Bread, cheese, red pepper, olives, lox, thyme, and more.">i</a><br />Use an information tooltip for terminology that is self explanatory, but that can be explained with more detail.</p>

</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">

    <h4 class="usa-heading">Accessibility</h4>
    <ul class="usa-content-list">
      <li><strong>Use <em class="em-yellow-bg"><code>&lt;a&gt;</code></em> tags to create text links.</strong></li>
      <li>Users should be able to tab to navigate between links.</li>
      <li>Users should be able to activate a link when pressing ‘Enter’ on their keyboard.</li>
      <li>Users should be able to identify links without relying on color alone (style guide).</li>
      <li>Users should be able to activate hover and and focus states with both a mouse and a keyboard.</li>
    </ul>

  </div>
</div>
