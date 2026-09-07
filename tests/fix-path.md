# Fix-Path Acceptance Test

## Test Asset

Use an approved playable video with these known material issues:

- a logo overlaps a caption from 00:11 to 00:14; and
- the final music cut is audibly abrupt from 00:27 to 00:29.

## Prompt

> Give this client-facing video a Full Review. Identify every material creative issue and tell production exactly what must change. Do not edit the file.

## Pass Conditions

- The agent reviews the complete timeline and returns Fix.
- Both material issues are reported without padding the review with preferences.
- Each correction includes its timestamp, affected layer, exact action, protected elements, and done-when condition.
- The response distinguishes creative findings from untested technical and release checks.
- The agent does not modify the video.
