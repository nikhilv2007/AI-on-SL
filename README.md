# AI-on-SL
Paper for extending AI on Selenium Webdriver

##Problem-

Regular selenium webdriver provides functions to recognize & act on native HTML elements such as links(<a>..</a>), Select (<select>..</select>)etc. 

With the popularity and increasing usage of css frameworks the HTML code is different than what appears visually on the webpage. Like a <div> can be used to depict a link. And more element blocks appearing on the UI like carousal, tabs etc not finding explicit mention in the selenium webdriver framework. Always this has to be handled genrically which involves lot of code.


##Solution -

When a page is loaded completely, take a screenshot of page and run computer vision libs to detect elements. Also another process needs to anlayse the HTML code to corelate with the visual elements.

Later on use custom elements to drive the automated tests.