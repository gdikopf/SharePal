# SharePal
Yoyo Playground Hackathon Project, London, November 7-8 2015

SharePal is a project our team worked on for the Yoyo Wallet Playgrond Hackathon on 7-8 November, 2015. The Project is a group payments web application, designed to allow groups of friends/family to easily pay for anything together without requiring one person to rely on reimbursement after covering the cost individually.

It works by allowing a group admin to create an "event", an item to purchase with a target goal to reach. This notifies all included members via the Twilio API. Those members can then "pledge" their amount, which is basically a commit to pay without any money transfer actually happening. When the target goal is reached (tracked in real-time with the Pusher API), the group admin can complete the transaction on behalf of all member on the group, utilizing the yoyo transaction API (currently private).

Matt Alston's main contribution to this project was designing and building the database in MySQL, and writing the endpoints to query the database, using the Flask microframework of Python and JSON (the QueryDB file). In addition he played more minor roles in the implementation of Twilio, helped design the pitch, and co-pitched with Freddie Rawlins.


