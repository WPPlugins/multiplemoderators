multiple-moderators
===================

A Wordpress plugin which allows site administrators to nominate multiple blog users to moderate comments.

Adds a page to the Wordpress admin which enables the selection of blog users (either individually or by role) as comment moderators. Achieves moderation by plugging the wp_notify_moderator() function (in wp-includes/pluggable.php) and adding the extra moderators to the admin email.