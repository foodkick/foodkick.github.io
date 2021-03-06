---
layout: styleguide
type: component
title: Form controls
lead: Form controls allow users to enter information into a page.
---

<h3 class="usa-heading">Accessibility</h3>

<p>As you customize form controls from this library, be sure they continue to meet the following accessibility requirements:</p>

<ul class="usa-content-list">
  <li>All form control tags should have an associated label. The labels for attribute value should match the related input <em class="em-yellow-bg"><code>id</code></em> attribute and should also be unique to the entire page. For example, the input with <em class="em-yellow-bg"><code>id=<wbr>"delicious-ramen"</code></em> will always have a label with <em class="em-yellow-bg"><code>for=<wbr>"delicious-ramen"</code></em>. This way screen readers are able to perceive the relevant content.</li>
  <li>Any additional information — such as required, optional, or example text — should be wrapped within the label tags. For example: <em class="em-yellow-bg"><code>&lt;label for=<wbr>"name"&gt;Favorite Pie &lt;span&gt;Optional&lt;/span&gt;&lt;/label&gt;</code></em>. This way screen readers know what additional information is related to each field.</li>
  <li>Do not replace <em class="em-yellow-bg"><code>&lt;input&gt;</code></em> tag-based form controls with styled <em class="em-yellow-bg"><code>&lt;div&gt;</code></em> tags, or use JavaScript to create 'fake' form controls. Screen readers have a difficult time reading form controls that are not written in semantic HTML.</li>
  <li>If you adjust the color scheme of the buttons, ensure a minimum contrast ratio of 4.5:1 (for small text, 3:1 for large) for all states of the button. This includes default, hover, selected, and disabled.</li>
  <li>Do not use JavaScript to auto advance the focus from one field to the next. This makes it difficult for keyboard-only users to navigate and correct mistakes.</li>
  <li>Display form controls in the same order in HTML as they do on screen. Do not use CSS to rearrange the form controls. Screen readers narrate forms in the order they appear in the HTML.</li>
  <li>Group each set of thematically related controls in a fieldset element. Use the legend element to offer a label within each one. The fieldset and legend elements make it easier for screen reader users to navigate the form.</li>
  <li>A single legend is always required for fieldset. A common use of fieldset and legend is a question with radio button options for answers. The question text and radio buttons are wrapped in a fieldset, with the question itself being inside the legend tag.</li>
  <li>You can embed multiple fieldsets and legends for more complex forms.</li>
</ul>
<h4>Error Handling</h4>
<ul class="usa-content-list">
  <li>Only show error validation messages or stylings after a user has interacted with a particular field.</li>
  <li>When a validation error is detected, <em class="em-yellow-bg">aria-invalid="true"</em> should be set to each invalid form element. This attribute causes screen readers to identify the control as being "invalid" or in need of attention.</li>
  <li>All required fields should have the <em class="em-yellow-bg">aria-required</em> attribute.</li>
</ul>

<h2 class="usa-heading" id="text-inputs">Text input</h2>
<p class="usa-font-lead">Text inputs allow people to enter any combination of letters, numbers, or symbols of their choosing (unless otherwise restricted). Text input boxes can span single or multiple lines.</p>
<div class="preview">

  <h4>Text Input</h4>
  <div class="box label"><h6>Default</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Nickname</label>
    <input name="input-type-text" type="text" placeholder="i.e.: Superman, Little Randy">
  </div>
  <div class="box label"><h6>Focused</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Nickname</label>
    <input class="focus" name="input-type-text" type="text" placeholder="i.e.: Superman, Little Randy">
  </div>
  <div class="box label"><h6>Filled</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Nickname</label>
    <input name="input-type-text" type="text" placeholder="i.e.: Superman, Little Randy" value="Wonder Woman">
  </div>
  <div class="box label"><h6>Disabled</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Nickname</label>
    <input name="input-type-text" type="text" placeholder="i.e.: Superman, Little Randy" disabled>
  </div>
  <div class="box label"><h6>Error Handling</h6></div>
  <div class="box">
    <label for="input-type-text">First Name</label>
    <input class="error" name="input-type-text" type="text" >
    <span class="error-msg">Required</span>
  </div>

  <h4>Text Input w/ Float Labels</h4>
  <p class="full uneven-margin">This example uses <a target="_blank" href="http://clubdesign.github.io/floatlabels.js/">Floatlabels.js</a> JQuery plugin.</p>
  <div class="box label"><h6>Default</h6></div>
  <div class="box">
    <input class="floatlabel" name="input-type-text" type="text" data-label="Street Address" placeholder="Street Address (optional)">
  </div>
  <div class="box label"><h6>Focused</h6></div>
  <div class="box">
    <input class="floatlabel focus" name="input-type-text" type="text" data-label="Street Address" placeholder="Street Address (optional)">
  </div>
  <div class="box label"><h6>Filled</h6></div>
  <div class="box">
    <input class="floatlabel" name="input-type-text" type="text" data-label="Street Address" placeholder="Street Address (optional)" value="30-10 Bergen St.">
  </div>
  <div class="box label"><h6>Disabled</h6></div>
  <div class="box">
    <input class="floatlabel" name="input-type-text" type="text" placeholder="Street Address (optional)" disabled>
  </div>
  <div class="box label"><h6>Error Handling</h6></div>
  <div class="box">
    <input class="error floatlabel" name="input-type-text" type="text" placeholder="First Name" >
    <span class="error-msg">Required</span>
  </div>

  <h4>Text Area</h4>  
  <div class="box label"><h6>Default</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Label</label>
    <textarea name="input-type-text" type="text" placeholder="Something helpful about what to enter in this text area"></textarea>
  </div>
  <div class="box label"><h6>Focused</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Label</label>
    <textarea class="focus" name="input-type-text" type="text" placeholder="Something helpful about what to enter in this text area"></textarea>
  </div>
  <div class="box label"><h6>Disabled</h6></div>
  <div class="box">
    <label class="optional" for="input-type-text">Label</label>
    <textarea name="input-type-text" type="text" placeholder="Something helpful about what to enter in this text area" disabled></textarea>
  </div>
</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Accessibility</h4>
    <p>If you customize the text inputs, ensure they continue to meet the the <a href="{{ site.baseurl }}/form-controls/"> accessibility requirements that apply to all form controls.</a></p>
    <ul class="usa-content-list">
      <li>Avoid placeholder text for accessibility reasons. Most browsers’ default rendering of placeholder text does not provide a high enough contrast ratio.</li>
      <li>Avoid breaking numbers with distinct sections (such as phone numbers, Social Security Numbers, or credit card numbers) into separate input fields. For example, use one input for phone number, not three (one for area code, one for local code, and one for number). Each field needs to be labeled for a screen reader and the labels for fields broken into segments are often not meaningful.</li>
    </ul>
    <h4 class="usa-heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="usa-content-list">
      <li>If you can’t reasonably predict a user’s answer to a prompt and there might be wide variability in users’ answers.</li>
      <li>When using another type of input will make answering more difficult. For example, birthdays and other known dates are easier to type in than they are to select from a calendar picker.</li>
      <li>When users want to be able to paste in a response.</li>
    </ul>
    <h5>When to consider something else</h5>
    <ul class="usa-content-list">
      <li>When users are choosing from a specific set of options.</li>
    </ul>
    <h5>Guidance</h5>
    <ul class="usa-content-list">
      <li>The length of the text input provides a hint to users as to how much text to write. Do not require users to write paragraphs of text into a single-line input box; use a text area instead.</li>
      <li>Text inputs are among the easiest type of input for desktop users but are more difficult for mobile users.</li>
      <li>Only show error validation messages or stylings after a user has interacted with a particular field.</li>
      <li>Avoid using placeholder text that appears within a text field before a user starts typing. If placeholder text is no longer visible after a user clicks into the field, users will no longer have that text available when they need to review their entries. (People who have cognitive or visual disabilities have additional problems with placeholder text.)</li>
    </ul>
  </div>
</div>

<h2 class="usa-heading" id="dropdown">Dropdown</h2>
<p class="usa-font-lead">A dropdown allows users to select one option from a list.</p>

<div class="preview extra-padding">
  
  <div class="box label"><h6>Default</h6></div>
  <div class="box">
    <label for="default">Label</label>
    <select id="default">
      <option value="1">Option 1</option>
      <option value="2">Option 2</option>
      <option value="3">Option 3</option>
    </select>
  </div>

  <div class="box label"><h6>Focused</h6></div>
  <div class="box">
    <label for="focused">Label</label>
    <select id="focused" class="focus">
      <option value="1">Option 1</option>
      <option value="2">Option 2</option>
      <option value="3">Option 3</option>
    </select>
  </div>

  <div class="box label"><h6>Disabled</h6></div>
  <div class="box">
    <label for="disabled">Label</label>
    <select id="disabled" disabled>
      <option value="1">Option 1</option>
      <option value="2">Option 2</option>
      <option value="3">Option 3</option>
    </select>
  </div>

  <div class="box label"><h6>Error Handling</h6></div>
  <div class="box">
    <label for="error">Label</label>
    <select id="error" class="error">
      <option value="1">Option 1</option>
      <option value="2">Option 2</option>
      <option value="3">Option 3</option>
    </select>
    <span class="error-msg" role="alert" >Required</span>
  </div>

</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Accessibility</h4>
    <p>If you customize the dropdown, ensure it continues to meet the the <a href="{{ site.baseurl }}/form-controls/"> accessibility requirements that apply to all form controls.</a></p>
    <ul class="usa-content-list">
      <li>Make sure your dropdown has a label. Don’t replace it with the default menu option (for example, removing the “State” label and just having the dropdown read “Select a state” by default).</li>
      <li>Don’t use JavaScript to automatically submit the form (or do anything else) when an option is selected. Auto-submission disrupts screen readers because they select each option as they read them.</li>
    </ul>

    <h4 class="usa-heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="usa-content-list">
      <li>Use sparingly — only when a user needs to choose from about seven to 15 possible options and you have limited space to display the options.</li>
    </ul>
    <h5>When to consider something else</h5>
    <ul class="usa-content-list">
      <li>If the list of options is very short. Use radio buttons instead.</li>
      <li>If the list of options is very long. Let users type the same information into a text input that suggests possible options instead.</li>
      <li>If you need to allow users to select more than one option at once. Users often don’t understand how to select multiple items from dropdowns. Use checkboxes instead.</li>
      <li>For site navigation (use the navigation components instead).</li>
    </ul>
    <h5>Guidance</h5>
    <ul class="usa-content-list">
      <li>Test dropdowns thoroughly with members of your target audience. Several usability experts suggest they should be the “UI of last resort.” Many users find them confusing and difficult to use.</li>
      <li>Avoid making options in one dropdown menu change based on the input to another. Users often don’t understand how selecting an item in one impacts another.</li>
      <li>When most users will (or should) pick a particular option, make it the default: <code>&lt;option selected=<wbr>"selected"&gt;Default<wbr>&lt;/option&gt;</code></li>
      <li>Don’t use JavaScript to automatically submit the form (or do anything else) when an option is selected. Offer a “submit” button at the end of the form instead. Users often change their choices multiple times. Auto-submission is also less accessible.</li>
    </ul>
  </div>
</div>

<h2 class="usa-heading" id="checkboxes">Checkboxes</h2>
<p class="usa-font-lead">Checkboxes allow users to select one or more options from a visible list.</p>

<div class="preview">

  <fieldset class="usa-fieldset-inputs usa-sans">

    <legend class="usa-sr-only">Historical figures 1</legend>

    <ul class="usa-unstyled-list">
      <li>
        <input id="apple-pie" type="checkbox" name="pies" value="apple-pie" checked />
        <label for="apple-pie">Sojourner Truth</label>
      </li>
      <li>
        <input id="key-lime-pie" type="checkbox" name="pies" value="key-lime-pie">
        <label for="key-lime-pie">Frederick Douglass</label>
      </li>
      <li>
        <input id="peach-pie" type="checkbox" name="pies" value="peach-pie">
        <label for="peach-pie">Booker T. Washington</label>
      </li>
      <li>
        <input id="disabled" type="checkbox" name="pies" disabled />
        <label for="disabled">George Washington Carver</label>
      </li>
    </ul>

  </fieldset>

</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Accessibility</h4>
    <p>If you customize the text inputs, ensure they continue to meet the the <a href="{{ site.baseurl }}/form-controls/"> accessibility requirements that apply to all form controls.</a></p>
    <ul class="usa-content-list">
      <li>Surround a related set of checkboxes with a <code>&lt;fieldset&gt;</code>. The <code>&lt;legend&gt;</code> provides context for the grouping. Do not use fieldset and legend for a single check.</li>
      <li>The custom checkboxes here are accessible to screen readers because the default checkboxes are moved off-screen with <code>position: absolute; left: -999em</code>.</li>
      <li>Each input should have a semantic <code>id</code> attribute, and its corresponding label should have the same value in it’s <code>for</code> attribute.</li>
      <li>The <code>title</code> attribute can replace <code>&lt;label&gt;</code>.</li>
    </ul>

    <h4 class="usa-heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="usa-content-list">
      <li>When a user can select any number of choices from a set list.</li>
      <li>When a user needs to choose “yes” or “no” on only one option (use a stand-alone checkbox). For example, to toggle a setting on or off.</li>
      <li>When users need to see all the available options at a glance.</li>
    </ul>
    <h5>When to consider something different</h5>
    <ul class="usa-content-list">
      <li>If there are too many options to display on a mobile screen.</li>
      <li>If a user can only select one option from a list (use radio buttons instead).</li>
    </ul>
    <h5>Guidelines</h5>
    <ul class="usa-content-list">
      <li>Users should be able to tap on or click on either the text label or the checkbox to select or deselect an option.</li>
      <li>List options vertically if possible; horizontal listings can make it difficult to tell which label pertains to which checkbox.</li>
      <li>Avoid using negative language in labels as they can be counterintuitive. For example, “I want to receive a promotional email” instead of “I don’t want to receive promotional email.”</li>
      <li>If you customize, make sure selections are adequately spaced for touch screens.</li>
    </ul>
  </div>
</div>

<h2 class="usa-heading" id="radiobuttons">Radio buttons</h2>
<p class="usa-font-lead">Radio buttons allow users to see all available choices at once and select exactly one option.</p>

<div class="preview">

  <fieldset class="usa-fieldset-inputs usa-sans">

    <h6>Small</h6>

    <legend class="usa-sr-only">Historical figures 2</legend>

    <ul class="usa-unstyled-list">
      <li>
        <input id="pea-soup" type="radio" checked name="soup" value="pea">
        <label for="pea-soup">Elizabeth Cady Stanton</label>
      </li>
      <li>
        <input id="chicken-noodle" type="radio" name="soup" value="chicken-noodle">
        <label for="chicken-noodle">Susan B. Anthony</label>
      </li>
      <li>
        <input id="tomato" type="radio" name="soup" value="tomato">
        <label for="tomato">Harriet Tubman</label>
      </li>
    </ul>

  </fieldset>
  <fieldset class="usa-fieldset-inputs usa-sans">

    <h6>Large</h6>

    <legend class="usa-sr-only">Foods I like</legend>

    <ul class="usa-unstyled-list soup-list">
      <li>
        <input id="orange-soup" class="large" type="radio" checked name="ing" value="orange-pea">
        <label for="orange-soup"><p>Split Pea is great<br>on rainy days</p></label>
      </li>
      <li>
        <input id="blue-noodle" class="large" type="radio" name="ing" value="blue-noodle">
        <label for="blue-noodle"><p>Melting cheddar cheese on<br>toasted sour dough is best</p></label>
      </li>
      <li>
        <input id="red-tomato" class="large" type="radio" name="ing" value="red-tomato">
        <label for="red-tomato"><p>My favorite dish is<br>a big bowl of ramen</p></label>
      </li>
    </ul>

  </fieldset>

</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Accessibility</h4>
    <p>If you customize the radio buttons, ensure they continue to meet the the <a href="{{ site.baseurl }}/form-controls/"> accessibility requirements that apply to all form controls.</a></p>
    <ul class="usa-content-list">
      <li>Group related radio buttons together with <code>&lt;fieldset></code> and describe the group with <code>&lt;legend&gt;</code>.</li>
      <li>Each radio button should have a <code>&lt;label&gt;</code>. Associate the two by matching the <code>&lt;label&gt;</code>’s for attribute to the <code>&lt;input&gt;</code>’s <code>id</code> attribute.</li>
      <li>The <code>title</code> attribute can replace <code>&lt;label&gt;</code>.</li>
    </ul>

    <h4 class="usa-heading">Usability</h4>
    <h5>When to use</h5>
    <ul class="usa-content-list">
      <li>When users need to select only one option out of a set of mutually exclusive choices.</li>
      <li>When the number of available options can fit onto a mobile screen.</li>
    </ul>
    <h5>When to consider something else</h5>
    <ul class="usa-content-list">
      <li>Consider checkboxes if  users need to select more than one option or if there is only one item to select.</li>
      <li>Consider a  dropdown if you don’t have enough space to list out all available options.</li>
      <li>If users should be able to select zero of the options.</li>
    </ul>
    <h5>Guidance</h5>
    <ul class="usa-content-list">
      <li>Users should be able to tap on or click on either the text "label" or the radio button to select or deselect an option.</li>
      <li>Options that are listed vertically are easier to read than those that are listed horizontally. Horizontal listings can make it difficult to tell which label pertains to which radio button.</li>
      <li>If you customize, make sure selections are adequately spaced for touch screens.</li>
      <li>Use caution if you decide to set a default value. Setting a default value can discourage users from making conscious decisions, seem pushy, or alienate users who don’t fit into your assumptions. If you are unsure, leave nothing selected by default.</li>
    </ul>
  </div>
</div>
