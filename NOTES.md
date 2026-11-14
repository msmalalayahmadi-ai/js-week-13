# Observing HTTP Requests in DevTools

## Website
YouTube – https://www.youtube.com

I used Google Chrome DevTools and the Network tab to observe HTTP requests while browsing YouTube and playing a video.

## Request 1: Log Event

- **Method:** POST
- **URL:** https://www.youtube.com/youtubei/v1/log_event?alt=json
- **Status Code:** 200 OK
- **Purpose:** This request is likely used to send user interaction events and activity information to YouTube's server for logging and analytics.

## Request 2: Watch Time

- **Method:** POST
- **URL:** https://www.youtube.com/api/stats/watchtime
- **Status Code:** 204 No Content
- **Purpose:** This request is used to send video watch-time information and playback status to YouTube's server. It helps YouTube track video playback activity.

## Request 3: Quality of Experience (QoE)

- **Method:** POST
- **URL:** https://www.youtube.com/api/stats/qoe
- **Status Code:** 204 No Content
- **Purpose:** This request is likely used to send video streaming quality and playback performance information to YouTube's server.

## What I Learned

By completing this exercise, I learned how to use Chrome DevTools to inspect HTTP requests in the Network tab. I observed how YouTube communicates with its servers using HTTP POST requests.

I also learned that HTTP status code 200 means the request was successful, while 204 means the request was successfully processed but the server returned no response content.

This exercise helped me better understand the HTTP request and response cycle through real website activity.