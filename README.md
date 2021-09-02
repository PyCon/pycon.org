# pycon.org

This is the source code for [pycon.org](http://www.pycon.org/).

## Starting a new PyCon

To start a new PyCon you must:
- Email the Python Software Foundation [trademark workgroup](https://www.python.org/psf/committees/#trademarks-work-group) seeking permission
- Confirm you have a Code of Conduct for your PyCon
- Confirm there is no other regional PyCon (e.g. in your country)
- Confirm that your conference is a community conference and not for commercial profit

## Adding your PyCon to the website

If you run a Python event or conference, you can add or edit your listing by
making a pull request to this repository.

### Ordering

National Conferences are listed in alphabetical location *by location*. 

Regional conferences are listed in alphabetical order *by name*. 

### Testing your change

PyCon.org is data-driven with [Jekyll templating](https://jekyllrb.com) served via [GitHub Pages](https://docs.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll). 

This repo has been configured with [Netlify](netlify.com) [deployment previews](https://www.netlify.com/blog/2016/07/20/introducing-deploy-previews-in-netlify). When you submit your pull request, a render will be generated so you can preview your changes. Click the 'Details' link on the deploy-preview check to see your preview.  

### Adding your event

Each *national* conference card should be created as `_national/conferencename.yml`, with a: 

 * `name`
 * `flag` (2-letter ISO 3166 Alpha 2, e.g. [us](http://pycon.org/img/flags/4x3/us.svg), [nz](http://pycon.org/img/flags/4x3/nz.svg))
 * `location`
 * `website` URL
 * `twitter` Twitter Handle

For Example:

```
---
name: PyCon Namibia
flag: na
location: Namibia
website: http://python-namibia.org/
twitter: PyConNA
---
```

*Special interest and regional* conferences should be created as `_regional/conferencename.yml`, with a:

 * `name`
 * `location`
 * `website` URL
 * `twitter` Twitter Handle

For Example: 
```
---
name: Pycon Latam
location: Puerto Vallarta, México
website: https://www.pylatam.org/en/
twitter: pylatam
---
```

*Be sure to include the `---` at the start and end of the file!*

#### If in doubt

Copy an example from another conference. 

## Calendar

If you would like to submit your event to the event calendar please see
the [python.org wiki](https://wiki.python.org/moin/PythonEventsCalendar#Submitting_an_Event)
for instructions.

