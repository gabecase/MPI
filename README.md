# MPI
*Model Page Interaction design pattern for selenium/web driver based test automation*

----------

**Model Page Interaction**

 - Model = Test Data Objects
   
 - Page = Object representation of visual elements in a page(titles, buttons,  
   input elements), views should not have much user interaction code in 
   them
   
   
 - Interaction = User interactions which act on page objects via their  
   selectors. Repetitive sequences of actions can be abstracted further into a interface to improve usability and maintenance


# TODO: 
Page object patterns? Factories to generate pages? Re-useable components that exist on multiple pages e.g. navigation bars, web form elements like date pickers, custom drop down lists?


----------


**Good test data model design:** ERD, identify if relational data and design objects accordingly, 
provide options in interface for model design


----------


Multiple Language Examples:
Selenium web driver examples, capybara examples, #{insert language heres popular UI framework abstraction library here},
python examples, .NET/Java examples


----------


Focus on design patterns, patterns established here and invididual language implementations should be there own 'fork' or implementations,
e.g. MVI-python, MVI-ruby, MVI-.NET

----------
S.O.L.I.D. theory and explanation for better object oriented code
Best practices for this kind of code and these kind of patterns?

---------
Mobile? MVC pattern is popular as well. How can this pattern be used in testing other software with visual interfaces.
