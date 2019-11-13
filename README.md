# pycon.org

This is the source code for [pycon.org](http://www.pycon.org/).

If you run a Python event or conference, you can add or edit your listing by
making a pull request to this repository.

## Ordering

National Conferences are listed in alphabetical location *by location*. 

Regional conferences are listed in alphabetical order *by name*. 

## Testing your change

PyCon.org is data-driven with [Jekyll templating](https://jekyllrb.com). 

This repo has been configured with [Netlify](netlify.com) [deployment previews](https://www.netlify.com/blog/2016/07/20/introducing-deploy-previews-in-netlify). When you submit your pull request, a render will be generated so you can preview your changes. 

## Adding your event

Each *national* conference card should be created as `_national/conferencename.yml`, with a: 

 * `name`
 * `flag` (2-letter ISO 3166 Alpha 2, e.g. [us](http://pycon.org/img/flags/4x3/us.svg), [nz](http://pycon.org/img/flags/4x3/nz.svg))
 * `location`
 * `website` URL

For Example:

```
---
name: PyCon Namibia
flag: na
location: Namibia
website: http://python-namibia.org/
---
```

*Special interest and regional* conferences should be created as `_regional/conferencename.yml`, with a:

 * `name`
 * `location`
 * `website` URL

For Example: 
```
---
name: Pycon Latam
location: Puerto Vallarta, México
website: https://www.pylatam.org/en/
---
```

*Be sure to include the `---` at the start and end of the file!*

### If in doubt

Copy an example from another conference. 

## Calendar

If you would like to submit your event to the event calendar please see
the [python.org wiki](https://wiki.python.org/moin/PythonEventsCalendar#Submitting_an_Event)
for instructions.

