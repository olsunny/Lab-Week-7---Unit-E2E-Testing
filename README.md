Olivia Sun

1) Where would you fit your automated tests in your Recipe project development pipeline? 

I would have automated tests within a Github action that runs whenever code is pushed so that tests can be streamlined and ran to make sure that new code does not interfere with previous functionalities and that improvements to the code are made in small chunks to ensure quality and effectiveness.

2) Would you use an end to end test to check if a function is returning the correct output?

No, because that would only require a unit test since we are not trying to emulate the experience of a user from start to finish.

3) What is the difference between navigation and snapshot mode?
Navigation mode analyzes a full page load, while Snapshot mode analyzes the page in a specific static state without measuring loading performance. Snapshot mode does not provide performance score and can't analyze anything outside the current DOM (while these things can be measured by Navigation). Navigation is good for inital page load performance and immediate accessibility while snapshot is good for checking accessibility of hidden elements, SPAs after ineraction, and complex forms.

1) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
Three things we can do to improve the shop site is do add a meta discription to the document to improve search results, add a [lang] attribute to the <html> element so text can be interpreted correctly, and reduce unused js to improve performance impact since there is an estimated saving of 124 KiB. 


 






