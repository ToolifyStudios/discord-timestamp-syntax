# Discord Timestamps
Discord timestamps are useful items for specifying a date/time across multiple users time zones. They work with the Unix Timestamp format and can be posted by any type of user.
[The Epoch Unix Time Stamp Converter](https://www.unixtimestamp.com/) is a good way to quickly generate a timestamp. For the examples in the table I will be using the Time Stamp of `1677312000`, which represents `February 25th, 2023` at `00:00:00` hours for my local time zone (GMT-0800).

## Formatting

|Style|Input|Output (12-hour clock)|Output (24-hour clock)
|--|--|--|--
|Default|`<t:1677312000>`|Febreuary 25, 2023 12:00 AM|28 November 2018 00:00
|Short Time|`<t:1677312000:t>`|12:00 AM|00:00
|Long Time|`<t:1677312000:T>`|00:00:00 AM|12:00:00
|Short Date|`<t:1677312000:d>`|02/25/2023|02/25/2023
|Long Date|`<t:1677312000:D>`|February 25, 2023|February 2023
|Short Date/Time|`<t:1677312000:f>`|February 25, 2023 12:00 AM|25 February 2023 00:00
|Long Date/Time|`<t:1677312000:F>`|Saturday, February 25, 2023 12:00 AM|Saturday, 25 February 2023 12:00
|Relative Time|`<t:1543392060:R>`|0 days ago|0 days ago

If you have your language set to `English US`, then it will use the 12-hour format. If your language is `English UK` or any other one, then it will use the 24-hour format.
