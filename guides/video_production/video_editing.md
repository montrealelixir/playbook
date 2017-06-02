# Video Production Guide

This guide documents the recording and video editing of the Montreal Elixir meetups.


## Equipment

- Video camera
- Tripod
- Wireless microphone (lavalier mic, transmitter & receiver units)
- HDMI splitter
- HDMI capturing device
- HDMI adapters for computers
- AA batteries for the wireless units
- Batteries for the video camera (and charger)
- HDMI cables
- USB splitter and AC block to provide power to HDMI splitter and HDMI capturing device
- SD card for video camera
- SD card for HDMI capturing device
- Presentation remote
- Headphones


## Overall process

1. Pre-meetup checks
2. Set-up and audio/video checks
3. Record each presentation
4. Pack equipment
5. Video editing
6. Upload to YouTube
7. Make public each recording


## Pre-meetup checks

The day before, make sure all the batteries are fully charged. Check the battery level on the wireless mic units (turn them on and look at the level on the screen). Erase old files on the SD cards.

With each presenter, make sure her/his computer has notifications disabled and nightshift off. See playbook for instructions. Then do a quick HDMI capturing test, to make sure it works with her/his computer.


## Set-up and audio/video checks

On location, you should plan about 30 minutes to set-up the equipment and check the video and audio.

Refer to this diagram for connections.

[diagram](...)

For the video camera, you want a little portion of the screen to be in the frame. This will help syncing the video with the HDMI capture during the video editing process. Here's an example of a good framing:

[video-frame](...)


## Record each presentation

- Help presenter set-up
- Install mic on presenter
- Tell presenter to wait for the OK before starting his presentation (thumbs up by the cameraman)
- Turn on HDMI capturing
- Go to the camera and check the audio using the headphones
- Wait for the presenter to be introduced by the MC
- Start video recording
- Give "thumps up" to presenter
- Stop video recording when no more questions
- Turn off HDMI capturing

Note: we do record the questions, but at the moment, we are not using including them in the final video edit. But we never know.

## Pack equipment

Make sure to not forget any cables on location.

## Video Editing

We use Screenflow for video editing. If you do not have a license, please contact the meetup organizer.

First, create a working folder on your computer. Then copy the files from the SD cards to the working folder. Video editing will be faster if the files are on your computer instead of the SD card.

Now let's start video editing the presentation.

IMPORTANT: save often your work in Screenflow!!! If can crash, and it will crash.

### Template

First, download the template to use. The templates (zipped) can be found in the Montreal Elixir Playbook.

- If the presenter was to the left of the screen, use _template-left_,
- otherwise use _template-right_.

Then, open up the file in screenflow. Get familiar with the assets in the template. Watch it to see how the transactions are implemented.

![Test](video_production/images/logo.png)

### Title

In the timeline, drag the "pointer" the title _slide_ and click on the title clip in the timeline (first row, first clip). You should see the presentation title in the preview pane. In the preview pane, double-click on the title and update it. Do the same with the presenter name and the date.

### Sponsors

If required, add/remove sponsors. One sponsor per "slide".

### Media Clips

Notice where the presentation clips are located in the timeline (second and third rows). We will remove them later. For now, let's keep them in the timeline.

In the toolbar panel at the right, click on the last icon. That should bring up the Media Library. At the bottom of the library, click on "Add Media..." and select the presenter's video clip in your working folder.  Do the same with the HDMI video capture.

### Presenter clip

Now locate the presenter's clip in the media libray and drag it on the second row, at the end (after the dummy one we have there).  It's around the 28s mark.

Preview the video and locate where the presentation should start.  Right-click on the clip and select "Split Clip" (or T on the keyboard). The first part should automatically be selected.  Hit "Delete" on the keyboard to delete it.  Go at the end of the clip and locate where the presentation should stop.  It should stop just before the questions, and after the audience stopped applauding.  Split the clip at that location and delete the last part.

Now drag the preview pointer to approx. 5s into the presenter's clip.  In the toolbar, click on the first icon.  You should now see the Video pane.  Click on the presenter's clip and then on the "+ Action" button in the Video pane.  We are adding a video action to change the dimension and position of the video.  Change the scale to 29%.

Leave the clip at this temporary location in the timeline.  It will be useful for syncing the screen capture.

### HDMI clip

Locate the HDMI clip in the media library and drag it on the third row at around 30s. Move the preview to a location where you can see both the presenter's clip and the HDMI clip. Click on the clip in the timeline.  

In the preview pane, locate the vertical handles (small circle in the middle).  Click on it and drag to resize the video.  Make the border snap with the presenter's clip.

The next step is to drag the presenter's video on the timeline so that both clips are synced.  This can be a bit tedious. The frame should include a small portion of the projection screen at the right (or left).  The presentation most likely has a change in the background color.  Locate that moment in the first few seconds of the presenter's clip.  In the Video page, click on "+ Action" just to create a visual indicator on the clip in the timeline. Now click on the HDMI clip, and locate that same moment in the timeline. When you find it, drag the presenter's video left or right to have the video action aligned.  Tweak the position of each clip.

Then you can split the HDMI clip and remove the "overflow".

At this point, you should have to clips synced and of the same length.

### Layout & transitions

Move the preview pointer to where we added the first video action to shrink the presenter's clip.  Click on the presenter's clip and set the proper cropping values in the Video pane:

- Cropping - left: 200
- Cropping - right: 200

Then in the preview pane, drag the video rectangle in the bottom corner.  It will snap to the borders.

Click on the HDMI clip in the timeline. In the preview pane, locate the vertical handles (small circle in the middle).  Click on it and drag to resize the video.  Make the border snap with the presenter's clip.

Next, move the preview marker to the beginning of the presentation and click on the presenter's clip.  The video in the preview pane should be fullscreen.  We need to resize it.  Click on the clip in the Preview pane, locate the resize handle on the side and drag towards the center until it snaps to the HDMI clip underneath.

Preview the clips.  If the clips shrinks at the wrong moment, you can drag left or right the video action on the clip (small blue square).

For each clip, right-click and select "Add Starting & Ending Transaction".

Now we can delete the dummy clips.  Select them and select "Edit > Delete" (or Delete key).

For the next steps, it is useful to see the entire timeline.  Use the zoom slider at the bottom so you can all the clips.

Select both the presenter's clip and HDMI clip (shift click on the second one).  Then drag them to left until they touch the last sponsor slide.

Double-click the logo clip on the fourth row.  Change the duration to the one you see in the footer + 2 seconds.

Do the same with the background clip on the fifth row.

Zoom the timeline and go at the end of the video and make sure the clips are aligned.  Visually, it is nice to have the background and logo fade out after the presenter's clip.  Adjust accordingly.

### Export

First, review to make sure everything plays well.

Save your work.

Then in the File menu, select "Export..." and use these settings:

- Web - High
- Scale by 100%

### Publish

Upload the video to YouTube but don't make it public yet. Send a secret private link to the meetup organizer for approval.  Don't add anything else to the YouTube entry because if the video editing has to be updated, you cannot update a new version of the video and you will loose that data.

Upload a corrected to YouTube if necessary.  Add meta-data to the entry (refer to a previous meetup video as a guide).

Let the organizer know that the video is ready for publishing.

### Archiving

Send your files to the video organizer for archiving purposes.
