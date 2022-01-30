
# Big UCE: Google Action
Big UCE is a Google Action built by incorporating text-based interactions, developed to help guide students at the campus. The currently deployed action is version 8.0. Latest update included bug fixes and addition of newer actions. The action is powered with Dialogflow and supports more than half a dozen actions.

The repository and the deployed assistant action are maintained by [Ashwin Raj](https://github.com/ashwinraj-in/) and distributed under MIT License.

# Usage and Privacy Policy
Try saying  `Talk to Big UCE` or `Speak to Big UCE` to Google Assistant to invoke the action. The action is included in the category of Education & Reference and is available for users in all 215 countries. The action is set to match the user's language settings. As per the privacy policy, the user data is totally secure and no maintainer has any access over the messages the user may send to the action or the responses that it sends back. The action also does not require the user to provide any account linking or login information.

### Supported Actions
- Faculty Details
- Holiday Schedule
- Mid/End Semester Exam schedule
- Club Details
- Upcoming institute events
- Library Details
- Contact Details

Usage data such as information regarding how many users are using the app, which geographical regions they are located in, and basic data including users’ language, device type, and length and frequency of use can be accessed and used to make the action better and add features. When you use the Big UCE, you are also using the Google Assistant, and the Google Privacy Policy describes how Google collects and uses data about your use of the app. You may wish to consult Google’s documentation regarding what information is shared with your Google Assistant and how to delete your Google Assistant activity. 

# Development and Dependencies
actions.intent.MAIN is invoked when the user requests action by invocation names. It integrates actions from Dialogflow of the conversational fullfillment type. The image corner style is set as angled and primary texts in action cards such as card titles uses default typography settings.

### Supported Devices
Google actions can be invoked on a wide array of platforms. Based on the capibilities that are specified, the action will trigger for users on the following surfaces:
- Android 6.0+ watches
- Android 6.0+ TVs
- Google Home
- Android 5.0+ phones
- iOS 10.0+ devices
- Headphones
- Smart Displays
- Android 6.0+ tablets

At no point does the action leaves the mic open without prompting the user to respond. The privacy policy for the action can be found in the action directory. The action also does not require the users to sign up for new accounts via voice. No cloud functions provided by firebase are used for developing the action.

# Contributing
New contributors of all experience levels are welcomed to contribute to this repository. Basic information about the project has been included in this README file. For major changes, it is recommended that you open an issue first to discuss what you would like to change. To contribute to this project, download the existing code to your local system
```
git clone https://github.com/ashwinraj-in/BigUCE
```
Go to Action Console and select Custom intent. Import the code into DialogFlow. Make the necessary changes, test the action on the simulator, download the ZIP file and make a pull request on this repository.

## License and Project Status
The action package and other resources for developing this assistant action are distributed under [MIT license](https://github.com/ashwinraj-in/BigUCE/blob/master/LICENSE). The project is completed and all the files are available in this repository. Further improvements can be made by increasing the number of training phases to facilitate the NLU process and adding cloud functions and/or enabling webhook.
