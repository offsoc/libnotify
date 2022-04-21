# libnotify

## Description

libnotify is a library for sending desktop notifications to a notification
daemon, as defined in the [org.freedesktop.Notifications][fdo-spec] Desktop
Specification. These notifications can be used to inform the user about an event
or display some form of information without getting in the user's way.

## Notice

For GLib based applications the [GNotification][gnotif] API should be used
instead.

[fdo-spec]: https://specifications.freedesktop.org/notification-spec/notification-spec-latest.html
[gnotif]: https://docs.gtk.org/gio/class.Notification.html