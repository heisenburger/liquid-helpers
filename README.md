# liquid-helpers
A collection of small liquid snippets that I've found helpful over time.

## Using these in Jekyll sites
These can be used in your [Jekyll](https://jekyllrb.com/) builds by importing the relevant helpers into your `_includes` folder, and instantiating with

  {% include helper-filename.html argument=value %}
  
Each helper has the expected inputs and outputs documented in a comment at the beginning of the file.

### Are you trying to make functions in liquid?

Yes, sometimes you don't want to bundle extraneous javascript and do everything client side, don't @ me
