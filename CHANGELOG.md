# AutoMate Changelog
 
 Changelog for AutoMate. This should be update for every build and version of the app. 
 
 # Version 1

## Build 8

Release date: 

- `bug fix` Replaced `id` with `identifier` in the Car entity of the core data model. This may require an erase and reinstall of the app.
- `bug fix` Fixes the issue of either the app crashing or the view not dismissing when you delete a car. 
- `enhancements` Changed the way the car detail view appears. It now comes in from the right on the navigation stack. 

## Build 7
 
Release date: 10/05/2020
 
- `bug fix` Resolves an issue with the app crashing on iOS 14.2 betas 
- `bug fix` When saving a vehicle the view correctly dismisses and updates the root view.
- `enhancements` Adds a button that links to the change log of the public bug tracker in the settings view.
- `enhancements` Adds the ability to delete a vehicle from the vehicle details view.
- `enhancements` Adds an alert to confirm that you want to delete the vehicle that is currently selected.
- `enhancements` Adds the ability to see a service record's details by tapping on a service record's cell.
- `known bugs` In iOS 14 there's a bug that cases the horizontal list of cars to not update until the app is relaunched. This is resolved in iOS 14.2 beta 2.

## Build 6

Release date: 09/24/2020

- `enhancements` Adds the ability to save service logs and to start building your service history
- `enhancements` Adds a "Thanks to" section in the Settings with links to people who have helped me thus far in building AutoMate. This list will continue to grow.

## Build 5

Release date: 09/20/2020

- `enhancements` Adds the Tip Jar view. Buttons do not invoke in app purchase.
- `bug` Changed the X button to "Done" for accessibility reasons in the Car Details view.
- `bug` Replaced the navigation bar items with a toolbar and tool bar items. This affects the Settings and Add Car buttons.
- `beta tools` Adds a button in Settings to add 3 pre-defined cars. The add car form still works.
 
## Build 4
 
Release date: 09/18/2020
 
- Moves the add service button down in the main view to the right of “Service history:”. Also changes the button from a wrench to a +. 
- Fixes a bug that had the nitpick details appear twice.
- Changed the style of the section headers in the car details view.
- Adds a text field to include additional details about the service. 
- Changes the image that navigates to the car details view.
 
 ## Build 3
 
Release date: N/A
 
- Adds support options in Settings
- You can now add extra details about your car. Currently called “Nitpicky details”. These details are optional. This part of the form is hidden behind a toggle switch in the add car form.
- Adds some basic form validation when adding a car. Year, Make, and Model are required fields.
- Adds two navigation bar buttons for Add Car(depicted by a car) and Add Service(depicted by a wrench). 
 
## Build 2
 
Release date: N/A
 
Not documented 😕
 
## Build 1
 
Release date: N/A
 
Not documented 😕
