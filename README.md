# YouTube Content Dashboard

This dashboard shows YouTube performance by content type: Shorts, Videos, Live streams, and Podcasts.

## Important links

- [Open the YouTube Content Dashboard](https://smevideodash.streamlit.app/)
- [SMEMedia repository](https://github.com/SMEMedia/VideoDash)

## Use the dashboard

1. Choose **Dashboard**.
2. Select a start date and end date.
3. Review the KPI cards, trend chart, summary table, and top videos.
4. Select **Refresh data** once when current YouTube information is needed.

Podcast videos are identified by the configured podcast playlist and are counted as Podcasts before other content types so they are not double-counted.

## Reconnect YouTube

Use this process when the dashboard says authorization expired or was revoked:

1. Choose **Reconnect YouTube**.
2. Select **Start YouTube sign-in**, then **Continue to Google**.
3. Sign in with an account that owns or manages the SME Media YouTube channel.
4. Approve the requested read-only access.
5. Follow the on-screen instructions to provide the renewed authorization to the Streamlit owner.
6. After it is saved, return to **Dashboard** and refresh once.

Never send authorization information through email, chat, GitHub, tickets, or screenshots.

## Troubleshooting

### No information appears for the selected dates

- Try a wider date range.
- Confirm the channel published content during the period.
- Allow YouTube time to process very recent analytics.
- Select **Refresh data** once.

### A video is in the wrong content type

- Confirm whether it is part of the configured podcast playlist.
- Confirm whether YouTube identifies it as a live stream.
- Record the video title, URL, expected type, and displayed type before escalating.

### Podcast videos are missing

- Confirm the videos are in the current podcast playlist.
- If the playlist changed, contact the Streamlit or technical owner to update the saved playlist setting.
- Refresh after the correction.

### Authorization expired

- Complete **Reconnect YouTube**.
- Use an account that manages the correct channel.
- If Google returns an access or redirect error, capture the message and contact the Google/YouTube and Streamlit owners.

### Results do not match YouTube Studio

- Confirm the same date range, timezone, channel, and metric.
- Allow for YouTube processing delays.
- Note whether Shorts, Videos, Live streams, and Podcasts are grouped differently in the two views.
- Record both values and filters before escalating.

### The dashboard will not open

- Use the live link above.
- Refresh the browser or try a private window.
- Check [Streamlit Community Cloud](https://share.streamlit.io/) for an app status message.
- Send the visible error and approximate time to the Streamlit owner.

## Ongoing maintenance

- Keep the channel-management account and Streamlit access assigned to current SME staff.
- Reconnect YouTube only when the dashboard reports an authorization problem.
- Review the podcast playlist setting whenever the official playlist changes.
- Escalate credential, playlist, deployment, and code changes to the assigned technical owner.
