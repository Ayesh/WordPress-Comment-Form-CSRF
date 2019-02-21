=== Comment Form CSRF Protection ===
Contributors: ayeshrajans
Tags: comments, spam, security, csrf
Requires at least: 4.2
Tested up to: 5.1
Stable tag: 1.0
Requires PHP: 7.1
License: GPLv2 or later

Prevent Cross-Site Request Forgery attacks on your comments form.

== Description ==
WordPress has an 9 year old unfixed security vulnerability that it does not properly validate incoming comments.

An attacker can trick both anonymous and logged in users to post comments on a victim site without them realizing, while using their own credentials.

See this issue for more information: https://core.trac.wordpress.org/ticket/10931

This is a tiny (fewer than 40 effect lines of code) module that adds a secure token to the comment form and validate it before accepting any comment, thus making your comment forms secure as they should\'ve been for all these years!

It provides no UI - just install it and you are all set!