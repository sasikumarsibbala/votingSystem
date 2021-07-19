Create a simple voting application, with a Html page, which has 'Answer Survey' button
----------------------------------------
This voting application has just one simple question
>The voting obj has an array of options from which people can choose, and an array with the number of replies for each option. This data is stored in the starter object below.
**your Tasks**
>Create a function called 'registerNewVote()' on the 'voting' object. 
This method does 2 things:
  1.1. Display a prompt window for the user to input the number of the selected option. The prompt should look like this:
        Which is the best indian car?
        0: Maruthi
        1: Hyundai
        2: KIA
        3: Ford
  1.2. Based on the input number, update the answers array. For example, if the option is 3, increase the value AT POSITION 3 of the array by 1.() Make sure to check if the input is a number and if the number is valid option )
2. Call this method whenever the user clicks the "Answer Survey" button.
3. Create a method 'displayVotingResults()' which displays the voting results. The method takes a string as an input (called 'type'), which can be either 'string' or 'array'. If type is 'array', simply display the results array as it is, using console.log(). This should be the default option. If type is 'string', display a string like "Poll results are 13, 2, 4, 1". 
4. Run the 'displayResults()' method at the end of each 'registerNewVote()' method call.
