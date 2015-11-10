---
layout: post
title: "Building an Android app for Odoo"
description: ""
category: 
tags: ["Odoo","Android","OpenERP"]
---
{% include JB/setup %}

We have a requirement to create a simple Android application to enable truck drivers to capture Proof of Delivery information at the time of delivery.

The posts attached to this aren't so much a tutorial, rather just documenting my thinking as we attempt to build this application. It is important to note that at this point I have zero Java, Android, SQLite or JSON-RPC experience.  Along the way I'll include all the links that have helped me out.  I'm sure this list will change as we go along.

In rough terms the requirements can be broken down as follows:

1. Investigate options
2. Install Android Studio
3. Learn enough to get started
4. Make some design decisions
5. Establish connection with OpenERP
6. Create internal SQLite database
7. Create a preferences screen for needed settings
8. Enable app to take pictures
9. Store pictures against delivery order
11. Optionally email to client when delivered

At this point, the app is done in terms of the actual requirement, but lets extend it a little.

10. Enable sync option when connected to wireless only
11. Capture other information like GPS coordinates, timestamps
12. Enable to capture a signature
13. Add QR code to pickings to enable drivers to scan deliveries onto and off their device.

