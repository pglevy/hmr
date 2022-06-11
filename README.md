# Low-code prototyping demo

Issues:
- Unnecessary availability and identity checks since the service now requires log in
- Unnecessary instructional text ("Select the first and last days of your USPS Hold Mail request" for clearly labeled fields First Day of Service and Last Day of Service)
- Labeling of required fields could be better
- Date selection uses overbearing pop-up with lots of instructions and hidden buttons to complete the task
    - You can tab into fields and type directly but clicking on them opens pop-up
    - Clicking the X button does not close the pop-up
    - Clicking outside of the pop-up and pressing <kbd>ESC</kbd> don't close the pop-up either
    - The reason I couldn't close the pop-up was because the error message to "select an end date" was not visible because of scrolling within the pop-up element (on a 16" laptop)
    - The pop-up has to go
- Use of dropdown for two-option field
- Legal text that implies acknowledgement but doesn't require any user action
- Inconsistent styling of field labels could cause hesitation
- Inconsistent text size and presentation in fields
    - Additional instructions is unnecessarily large for the text size and allowed number of characters
