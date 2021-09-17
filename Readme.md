Hello and welcome to your bitvavo assignment!

In the assignment today we will be asking you to create an app using the github api (Specifically: https://docs.github.com/en/rest/reference/search) that allows users to search for repositories using text and specifying a programming language and subsequently view information about the result of their search.

For this assigment we require you to use the following technologies:

- React Native (0.63+)
- Typescript
- Redux

Extra credit is given to projects that also implement the following technologies:

- Redux Saga's
- Styled Components / Styled System / Theme management

Other than the technologies listed above also feel free to use other open source libraries that make the app simpler to implement. Please approach this as if you were making the app as part of a business and make choices based on the libraries maturity and community support.

The specification:

The app should feature two screens with the requirements listed below, the requirements don't specify how the screens should look, and the decision to style them in any way is left down to the developer.

Screen 1:

On screen one you are required to add a search box that takes string input which will be used as the input for the repository name.
On screen one you are required to add five select boxes with the following options: C, C#, Javascript, Rust and GO. (When no select box is specified you should show all options returned from the api)
On screen one you are required to show the first 100 results returned from the api.
On screen one you are required to add the functionality that when a user clicks on an entry they are navigated to screen two. 

To clarify: 

When a user types text into the input after a short delay we should make an api request that returns a list of found repositories, this should then be displayed to the user. After which they can select an option and be navigated to screen two which displays information about the repository.
 
Optional:

- Make the list paginated and show more results.
- Add further styling

Screen 2:

On screen two you are required to show information about the repository that you've selected (Only name and description are required).
On screen two you should provide a way for the user to go back to screen one.

Optional:

- Add more textual information
- Display the last commit

If at any point in your assignment you are unsure about the context or want to ask questions please mail liam@bitvavo.com and we'll do our best to point you in the right direction. The project in total shouldn't take longer than three hours to complete, but you can take longer if it's required.

Once you've finished your assignment, and you are ready to submit your project please send a link to your repository to liam@bitvavo.com. Please note that you should ensure that the project is installable and runs on both Android and IOS simulators. If you can only run your project on android please specify when you submit, so the marker knows to run the project in android.