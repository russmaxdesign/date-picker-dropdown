# Accessible date picker

Demo version: https://russmaxdesign.github.io/date-picker-dropdown/

## Initial field requirements

- User can can enter a date via keystrokes without using date picket via an input element
- Label text is explicitly associated with date field
- Hint text explaining required date format is explicitly associated with date field
- If date format is incorrect entered by the user, an explicitly associated error message is presented
- The error message should clearly explain the error and how to fix it

## Pop-up date picker requirements

- Pop-up date picker widget trigger mechanism is presented as a button, separate to the input field
- Pop-up date picker can be triggered via ENTER or SPACEBAR keystrokes
- When button triggered, focus should shift to the Pop-up date picker widget
- Pop-up date picker widget should include:
    - Previous month navigation mechanism as a button
    - Next month navigation mechanism as a button
    - Current month and year, presented as text
    - Table containing all dates in current month
    - An optional "Close" button to close the date picker

## Date picker table requirements

- table header elements for all days
- table header content should include full days, but can be visually shortened (see HTML example)
- each date should be presented as button
- each button should have appropriate aria-label
- Date buttons should be triggered via ENTER or SPACEBAR keystrokes

## Choosing a date requirements

- When a date button is triggered, focus should return to the input, with the chosen date presented

## Closing the datepicker requirements

- Regardless of whether a "Close" button is presented, users can close the datepicker widget using the ESC key

## Example datepickers:

Datepicker:
https://dequeuniversity.com/library/aria/date-pickers/sf-date-picker

Date Range Picker:
http://airbnb.io/react-dates/?selectedKind=DateRangePicker%20%28DRP%29&selectedStory=default&full=0&addons=1&stories=1&panelRight=0&addonPanel=storybook%2Factions%2Factions-panel

ReactJS Datepicker:
https://reactdatepicker.com/

Accessible Bootstrap Date Picker:
http://eureka2.github.io/ab-datepicker/

ca11y:
http://code.viget.com/ca11y/
