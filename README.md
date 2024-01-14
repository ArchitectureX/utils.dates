# @architecturex/utils.dates

This JavaScript utility library provides a set of functions for handling date-related operations. It's designed to facilitate common date manipulations, such as formatting dates, calculating rates based on months, determining if a date is reserved, and more. This library can be particularly useful in applications dealing with reservations, event planning, or any scenario where date manipulation is essential.

### Installation

`npm install @architecturex/utils.dates`

### Usage

```javascript
import dates from '@architecturex/utils.dates'
```

Then, you can use the various functions provided:

```javascript
// Example: Get a formatted date
const formattedDate = dates.getDashedDate(new Date())
console.log(formattedDate)

// Example: Check if a date is reserved
const isReserved = dates.isDateReserved(new Date(), reservationsArray)
console.log(isReserved)
```

### Features

The `cx` function can accept multiple arguments of various types:

- **Dashed Date Formatting:** Convert Date objects into 'YYYY-MM-DD' format.
- **Date Creation Without Timezone:** Create a Date object from a string without timezone issues.
- **Date Reservation Checking:** Check if a given date falls within a range of reserved dates.
- **Date Formatting:** Format dates into human-readable strings, supporting different locales.
- **Monthly Rate Calculation:** Determine rates based on the month of the year.
- **Days Until a Date:** Calculate the number of days until a specific date.
- **Year-based Reservation Filtering:** Filter reservations based on the year.
- **Date Addition:** Add a specified number of days to a date.
- **Long Date Formatting:** Convert a date into a long, descriptive format.
- **Month and Day Extraction:** Extract and format the month and day from a date string.
- **Date Validation:** Validate if a given string is a proper date.
- **Weekend Checking:** Determine if a date is a weekend.
- **Day of the Week Calculation:** Find the day of the week for a given date.
- **Date Difference Calculation:** Calculate the difference in days between two dates.
- **Two-Digit Day and Month Formatting:** Format days and months into two digits.
- **Today Checking:** Check if a given date is today.
- **Event Existence Checking:** Check if events exist within a given date range.
- **Available Date Calculation:** Calculate available dates based on reservations and other factors.

### Functions

- **getDashedDate(date: Date):** Returns a string in 'YYYY-MM-DD' format.
- **createDateWithoutTimezone(dateStr: string):** Creates a Date object from a string.
- **isDateReserved(date: Date, reservations: Array, forceValidation: boolean):** Checks if a date is within reserved dates.

### Contribution

Feel free to suggest improvements, report issues, or contribute to enhancing these utilities. Your feedback and contributions are welcome!
