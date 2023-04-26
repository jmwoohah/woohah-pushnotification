

# Event Push Notification Control Panel

This is a ReactJS-based control panel that uses the JotForm API to receive push notifications and broadcast them to all users watching a live stream. This Readme provides a guide to the control panel's functionality and features.

## Table of Contents

- [Manage Live Notifications](#manage-live-notifications)
- [API Testing](#api-testing)
- [API Usage Log](#api-usage-log)
- [Push Notification Window](#push-notification-window)

## Manage Live Notifications

In this window, you can manage your live notifications. Here you can find the "Send Message" and "Delete Notifications" buttons. The "Send Message" button opens a pop-up window where you can send messages. The "Delete Notifications" button deletes all previous push notifications, so late attendees won't be bombarded with a bunch of notifications from earlier in the morning.

## API Testing

In this window, you will find a string for the last push notification you sent. The current API status is also displayed, so if you've deleted messages, it will reflect that here, and if you've just received a notification, that will also be reflected here. 

There are two buttons here: "Start Searching" and "Stop Searching." The "Start Searching" button allows you to start searching for new messages and emulates the experience of the user/client. The "Stop Searching" button stops this functionality. The main use here is so you don't have it constantly searching and saving API calls.

## API Usage Log

In this window, you can view a log of the current API status call quota. [See what each response means under the sample response example here:](https://api.jotform.com/docs/#user-usage). There is a refresh button so you can refresh the current data limit.

## Push Notification Window

In this window, you will see the push notification. This is basically where your emulated experience of the user will reside. Although it has added functionality where you can edit the text upon click, for testing purposes (if you wish to see what the message looks like longer, etc.). This does not affect the user whatsoever.

## Conclusion

That's all for the Event Push Notification Control Panel! We hope you find it useful and easy to use. If you have any feedback or suggestions, please let us know!
