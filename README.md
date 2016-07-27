
<img src="http://i.imgur.com/nG93ITp.jpg" width="320">

A Bill Splitting Hybrid Phone App that converts a photo of a bill into a digital list of items. The list can be sent to different emails to request payment via Paypal. <a style="text-decoration:none" href="https://vimeo.com/knowerlittle/billsplitter">Watch App Video</a>.
## App Frontend
**Technologies used:**
<br>
`IONIC, AngularJS, JavaScript, ngCordova`
<br>
**Testing Frameworks:**
<br>
`Karma, Protractor`


##Installation

1. Clone this repository
2. Run `npm install`
3. Run `bower install`
4. Run `ionic serve` to run app in Web Browser
<br> or `ionic serve --lab` for both iOS and Andriod emulators
5. Backend is currently hosted on `http://splitterbackend.herokuapp.com`
   <br> Since this is a free dyno it may be asleep! 

####Tests 

Open each element in a **seperate** terminal tab

1. Run `npm run start`
2. Run `npm start webdriver-manager start`
3. Run `Ionic serve` make sure it is running on `localhost:8100`
4. **UNIT TESTS** &nbsp; Run `karma start test/karma.conf.js`
5. **FEATURE TESTS** &nbsp; run  `protractor test/protractor.conf.js`

For more info on setting test environments for Karma and Protractor click [HERE](https://github.com/knowerlittle/setting_up_angular_notes)

## How it works
- To use on the phone you must use with `Adobe PhoneGap` or `Ionic View` 
- Users sign up for an account so they can keep track of their bills
- Users take a photo of a bill with their phone camera through the app
- Image gets processed by the [BACK END](http://github.com/knowerlittle/splitter-backend)
- The app then presents a list of items for the user to add or edit
- User then selects which items they want to group and bill to different e-mail addresses until all items have been cleared from the list
- Recipent receives the email with list of items and total with a Paypal link for payment

## Known Issues
- Tesseract Gem needs to be tweaked for better results
- Logging out is sometimes an issue (bug)


## Authors
- [Jack Hardy](https://github.com/jackhardy1)
- [Wayne Rumble](https://github.com/wrumble)
- [Matt Ward](https://github.com/iammatthewward)
- [Noah Pollock](https://github.com/knowerlittle)

License
-------
:hatching_chick: Free as a bird - 2016 :hatched_chick:
