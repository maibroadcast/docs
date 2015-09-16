---
title: Media Capture and Streams
readiness: 'Ready to Use'
standardization_status: 'W3C Working Draft'
summary: 'Enables access to local devices (video cameras, microphones, Web cams) that can generate multimedia stream data (video, audio, or both).'
tags:
  0: API
  1: Listings
  3: Media
  4: Capture
  5: and
  6: Streams
  7: WebRTC
todo_broken_links:
  note: 'During import MediaWiki could not find the following links, please fix and adjust this list.'
  links:
    - dom/methods/getUserMedia
uri: 'apis/media capture and streams'

---
## Summary

Enables access to local devices (video cameras, microphones, Web cams) that can generate multimedia stream data (video, audio, or both).

## Usage

     The MediaStream interface is used to represent streams of media data, typically (but not necessarily) of audio and/or video content, e.g. from a local camera. Each MediaStream object can contain zero or more tracks, in particular audio and video tracks. And each track in a MediaStream object has a corresponding MediaStreamTrack object.

A [MediaStreamTrack](/apis/media_capture_and_streams/MediaStreamTrack) represents content comprising one or more channels, where the channels have a defined well known relationship to each other (such as a stereo or 5.1 audio signal).

A new [MediaStream](/apis/media_capture_and_streams/MediaStream) object can be created from accessible media sources using the MediaStream() constructor, or generated by a [getUserMedia()](/w/index.php?title=dom/methods/getUserMedia&action=edit&redlink=1) call. After calling navigator.getUserMedia the user is asked for permission to let the browser access the camera or the microphone.

## See also

### Related articles

#### Mobile

-   [Battery Status API](/apis/battery_status)

-   [Mediastream Image Capture](/apis/image_capture)

-   **Media Capture and Streams**

-   [Network Information API](/apis/network_information)

-   [Vibration API](/apis/vibration)

-   [capture](/html/attributes/capture)

#### WebRTC

-   [Track ended](/apis/MediaStream/ended)

-   **Media Capture and Streams**

-   [WebRTC API](/apis/webrtc)

-   [WebRTC](/concepts/Internet_and_Web/webrtc)

-   [WebRTC Resources](/tutorials/webrtc_resources)

### External resources

-   [Media Capture and Streams API](http://www.w3.org/TR/mediacapture-streams/)
-   [Media Capture and Streams API - W3C Working Draft 16 May 2013](http://www.w3.org/TR/2013/WD-mediacapture-streams-20130516/)
-   [Device APIs working group](http://www.w3.org/2009/dap/)
-   [WebRTC working group](http://www.w3.org/2011/04/webrtc/)
-   [Media Capture Wiki](http://www.w3.org/wiki/Media_Capture)