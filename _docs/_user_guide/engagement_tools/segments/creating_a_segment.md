---
nav_title: Creating a Segment
page_order: 1
---
# Creating a Segment

Your developers have integrated the SDK, and the data from your users has begun pouring in. Now what? It's time to start segmenting your users. Follow the guide below or check out [our LAB Segmentation course](https://lab.braze.com/segmentation-course)!

Segmentation allows you to target users based upon their demographic, behavioral, social, or technical characteristics and actions. Creative and intelligent use of segmentation and messaging automation enables you to seamlessly and easily move your users from install to your KPIs.

In order to build a house, you have to lay the first brick. Let's create your first segment.

## Step 1: Navigating to the Segments Section

On the left-hand side under Engagement click on Segments.

![Segment1][1]

## Step 2: Name Your Segment

Name your segment by describing the type of user you intend to filter for. This will ensure that this segment can easily and accurately be the target of multiple campaigns or Canvases to come. Vague segment titles can cause confusion down the line.

![Segment2][2]

## Step 3: Choose Your App or Platform

Choose which apps or platforms you'd like to target by either selecting "Include users from all apps" (default) or deselecting that checkbox. You will then have the opportunity to select which apps or platforms you want to include in your segment. For example, if you'd like to send an in-app message to only iOS devices, simply select your iOS app. This will ensure that users who might use both an iOS and an Android device will only receive the message on their iOS device.

![Segment App Selection][5]

## Step 4: Add Filters to Your Segment

Add at least one filter to your segment as depicted in the image below. You can combine as many filters as you want in order to make your segmentation more specific.

![segment_step4][3]

Choosing "OR" for your filters means that your segment will contain users satisfying any combination of one, some, or all of those filters, while "AND" means that users who do not pass that filter will not be included in your segment. This logic can be combined, so that you can segment users who pass one filter "AND" either one of two other filters.

Notice that the statistics on your segment are changing in real time as you add and subtract filters. Keep in mind that these statistics are estimates (+/- 1%) and that the exact segment membership is always calculated before a segment is affected by a message sent in a campaign or Canvas.

## Step 5: Save Your Segment

![Segment4][4]

Once you've clicked "Save" you're ready to start sending messages to your users!

## Archiving Segments

If you no longer need or wish to retire a specific segment, you can archive it by going to the __Segments__ page, clicking on the appropriate gear, then selecting "Archive" from the drop down that appears.

{% alert warning %}
When you archive a segment, any Campaigns or Canvases (even if the segment is only used in a single Canvas step) using it will __also be archived__. You will get a warning listing which Campaigns and Canvases are about to be archived by archiving the associated segment.
{% endalert %}

You can unarchive the segment by navigating to it within Segments, then selecting Unarchive from the top right corner of its page.

[1]: {% image_buster /assets/img_archive/Segment1.png %}
[2]: {% image_buster /assets/img_archive/Segment2.png %}
[3]: {% image_buster /assets/img_archive/segment_step4.png %}
[4]: {% image_buster /assets/img_archive/Segment4.png %}
[5]: {% image_buster /assets/img_archive/segment_app_selection.png %}
