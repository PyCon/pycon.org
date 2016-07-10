# pycon.org

This is the source code for [pycon.org](http://www.pycon.org/).

If you run a Python event or conference, you can add or edit your listing by
making a pull request to this repository.

Conferences/events are listed in alphabetical order, so please be sure to insert
yours in the correct position. As the conferences are presented in columns
you may need to move the column container to make two columns equal in length.

Each *national* conference card should follow this format:

```
<div class="conference">
  <div class="conference-header">
    <div class="flag">
      <span class="flag-icon flag-icon-country-code"></span>
    </div>
    <div class="conference-title">
      <h3>Conference Name</h3>
      <p class="location">Conference Country</p>
    </div>
  </div>
  <div class="conference-details">
    <p>A short introduction about the conference.</p>
    <p>Information about past conferences.</p>
    <p>Information about the next conference.</p>
    <p><a href="conference-url">Visit Website</a></p>
  </div>
</div>
```

For Example:

```
<div class="conference">
  <div class="conference-header">
    <div class="flag">
      <span class="flag-icon flag-icon-fr"></span>
    </div>
    <div class="conference-title">
      <h3>PyConFR</h3>
      <p class="location">France</p>
    </div>
  </div>
  <div class="conference-details">
    <p>PyConFR is the annual conference for the Francophone world, organized by the <a href="https://www.afpy.org/">AFPy</a>.</p>
    <p>Past conferences have been held in Pau(2015), AnotherLocation(2014), AnotherLocation(2013).</p>
    <p>The next PyConFR will be held in Rennes on the 13th-16th of October, 2016.</p>
    <p><a href="https://2016.pycon.fr/">Visit Website</a></p>
  </div>
</div>
```

*Special interest and regional* conferences should follow this format:

```
<div class="conference">
  <div class="conference-header">
    <div class="conference-title">
      <h3>Conference Name</h3>
      <p class="location">Location</p>
    </div>
  </div>
  <div class="conference-details">
    <p>A short introduction about the conference.</p>
    <p>Information about past conferences.</p>
    <p>Information about the next conference.</p>
    <p><a href="conference-url">Visit Website</a></p>
  </div>
</div>
```

If you would like to submit your event to the event calendar please see
the [python.org wiki](https://wiki.python.org/moin/PythonEventsCalendar#Submitting_an_Event)
for instructions.
