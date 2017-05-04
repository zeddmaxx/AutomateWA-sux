## Web Accessibilty testing
The aim of this project is to automate web accessibility testing, so that the web is accessible, approachable and navigable to all users and not just to some. So that even people with disabilities are able to make the best possible use of the web.

### Scope of the project
Our tests will ensure these checks are in place:

* Visual Impairment
  * Text alternatives for non-textual content should be present.
  * Captions should be present to supplement videos.
  * The webpage should be magnifiable and customisable i.e you should be able to change the color and other attributes of the text.
  
* Auditory Impairment
  * Text alternatives for non-textual content should be present.
  * Options to stop, pause and adjust volume.
  * Captions should be present to supplement audio and videos.
  
* Cognitive/Neurological Impairment
  * Well structured content
  * Well labelled content
  * Options to supress blinking and fashing content
  
* Physical Impairment
  * The keyboard has full functionality to access all parts of the webpage.
  * more time to type, click or fill a form.
  
* Speech Impairment
  * text based chat alternatives to interact.
  * feedback forms and emails are present instead of phone number.
  
* Miscellaneous
  * If translations to other languages are available.

### Timeline
* <b>4th March - 30th April </b> Research about web accessibility testing and testing tools/frameworks and prepare a scoping document.
* <b>1st May - 30th June</b>  : After choosing the best possible solution (which can be one testing framework or a blend of more frameworks) code the test suite.
* <b>1st July - 25th July</b> : Integrate the code suite with the Jenkins CI.
* <b>26th July - 30th August </b>: Cleanup, write and update documentation.

In order to achieve the above tests I researched a few open source web accessibilty testing frameworks like axe cli, Pa11y and AATT. The best way of amalgamating features of these testing frameworks-
AATT has a really great felexible API available through which we can set the errors, output, engine and the level of checking that we want to do(e.g: WCAG2A, WCAG2AA etc), It can be used for checking the accessibility of pages that require Login and Sign Up. On the other hand Axe cli and Pa11y are great tools which have immense potential via the command line. 

After combining the testing frameworks we'll have a test suite with about 0 false positives and very good efficiency in testing for web accessibility. We can then begin to code the tests and integrate them with our Jenkins CI.
A great step that we can take is by involving the community into this project so that they can suggest problems they face and we can try to code and incorporate those tests in our test suite. 

