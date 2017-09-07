# react-native-notifications-example
Example of using react-native-notifications plugin

TO send push:


POST https://fcm.googleapis.com/fcm/send

    {
     "notification": {
                "priority" : "high",
                "sound" : "default",
                "tag": "example",
                "icon" : "icon",
                "title" : "Notification Title",
                "body" : "Notification Body"
        },
        "data": {
                "priority" : "high",
                "sound" : "default",
                "tag": "example",
                "icon" : "icon",
                "title" : "Notification Title",
                "body" : "Notification Body",
                "custom_field" : {}
        },
      "to" : "DEVICE_TOKEN"
    }
