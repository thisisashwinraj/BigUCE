
# Big UCE: Google Action
Big UCE is a Google Action built by incorporating text-based interactions, developed to help guide students at campus. The currently deployed action is version 8.0. Latest update included bug fixes and addition of newer actions. The action is powered with Dialogflow and supports more than half a dozen actions.

The repository and the deployed google action are maintained by [Ashwin Raj](https://github.com/ashwinraj-in/) and distributed under the MIT License.

# Usage and Supported Actions
Try saying to your Google Assistant `Talk to Big UCE` or `Speak to Big UCE` to Google Assistant to invoke the action. The action is included in the category of Education & Reference and is available for users in all 215 countries. The action is set to match the user's language settings.

The action does not require any account linking or login information

### Supported Actions
- Faculty Details
- Holiday Schedule
- Mid/End Semester Exam schedule
- Club Details
- Upcoming institute events
- Library Details
- College Contacts

# Development and Dependencies
actions.intent.MAIN is invoked when the user requests action by invocation names. It integrates actions from Dialogflow and is of the conversational fullfillment type. The image corner style is set as angled and primary texts in action cards such as card titles uses default typography settings.

At no point does the action leaves the mic open without prompting the user to respond. The privacy policy for the action can be found in the action directory. The action also does not require the users to sign up for new accounts via voice. No cloud functions provided by firebase are used for developing the action.

### Supported Devices
- Android 6.0+ watches
- Android 6.0+ TVs
- Google Home
- Android 5.0+ phones
- iOS 10.0+ devices
- Headphones
- Smart Displays
- Android 6.0+ tablets

# Contributing
Download the existing code to your local system
```
git clone https://github.com/ashwinraj-in/ucekguide
```
Go to action Console and select Custom intent. Import the code into DialogFlow. Make the necessary changes, test the action on the simulator, download the ZIP file and make a pull request on this repository.

## License and Project Status
The action package and other resources for developing this assistant action are distributed under MIT license. The project is completed and all the files are available in this repository. Further improvements can be made by increasing the number of training phases to facilitate the NLU process and adding cloud functions and/or enabling webhook.
