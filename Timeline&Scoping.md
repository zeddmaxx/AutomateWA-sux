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

### Timeline
* 4th March - 30th April Research about web accessibility testing and testing tools/frameworks and prepare a scoping document.
* 1st May - 30th June  : After choosing the best possible solution (which can be one testing framework or a blend of more frameworks) code the test suite.
* 31st June - 20th July : Integrate the code suite with the Jenkins CI.
* 21st July - 30th August : Cleanup, write and update documentation.

In order to achieve the above tests I researched a few open source web accessibilty testing frameworks like axe cli, AATT and ppa11y. The best way of amalgamating features of these 3 testing frameworks is -











After combining the testing frameworks we'll have a test suite with about 0 false positives and very good efficiency in testing for web accessibility. We can then begin to code the tests and integrate them with our Jenkins CI.
A great step that we can take is by involving the community into this project so that they can suggest problems they face and we can try to code and incorporate those tests in our test suite. 





