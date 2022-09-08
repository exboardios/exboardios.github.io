# FAQs

### How to install keyboard app in IOS

1. Open Settings Page

2. Tap on the Keyboard Section

3. Tap on Keyboard

4. Tap on 'Add new keyboard'

5. Tap on 'ExBoard' to add

6. Tap on 'ExBoard' to enter settings page

7. Tap on 'Allow full control'

### How to restore purchase on another device?

N/A

### Why do I have to enable Full Access?

ExBoard uses Full Keyboard Access to allow the Main App to communicate with the Keyboard Extension. This way, the Snippets that are created in the Main App can be seen in the Keyboard itself.

### What is a snippet variable?

Snippet variable is a placeholder which will be replaced when the snippet is inserted. A snippet variable is usually in the form of `${VARIBLE_TYPE|ADDITIONAL_INFO}`, for exmple, the variable `${DATE|YYYY-MM-DD}` will be replaced as today's date with the format specified.

### What are do the characters mean in the date-format varible?

| Format according to ISO 8601 | Value ranges                                 |
| ---------------------------- | -------------------------------------------- |
| Year (Y)                     | YYYY, four-digit, abbreviated to two-digit   |
| Month (M)                    | MM, 01 to 12                                 |
| Week (W)                     | WW, 01 to 53                                 |
| Day (D)                      | D, day of the week, 1 to 7                   |
| Hour (h)                     | hh, 00 to 23, 24:00:00 as the end time       |
| Minute (m)                   | mm, 00 to 59                                 |
| Second (s)                   | ss, 00 to 59                                 |
| Decimal fraction (f)         | Fractions of seconds, any degree of accuracy |

The [ISO 8601 Wiki](https://en.wikipedia.org/wiki/ISO_8601) explains in detail what symbols are allowed in a `${DATE|format}` variable.

### Additional Questions

If you have additional questions, you can send an e-mail to ex.board.ios+support@gmail.com
