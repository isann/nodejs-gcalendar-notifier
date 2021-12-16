# About
This is a cli application that runs only on Mac OSX.
It retrieves events from Google Calendar and displays them in a dialog.


# Prepare
`credentials.json` is google api credentials.
Generate it from Google Console.


# Getting started
Execute the following command.

```
node list.js 
```

# Note
## cron setting
```
* * * * * cd /path/to/gcalendar-notifier && /path/to/node /path/to/gcalendar-notifier/list.js
```


# Reference
[gcp-sample/calendar at main · Thirosue/gcp-sample](https://github.com/Thirosue/gcp-sample/tree/main/calendar)

[Google CalendarにAPI連携（スケジュール一覧取得 / スケジュール作成 / スケジュール削除）する（Node.js） - Qiita](https://qiita.com/takeshi_hirosue/items/f0cf49b3969a03ab6988)
