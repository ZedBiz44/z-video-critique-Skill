# Trigger and Boundary Tests

Run in fresh sessions. Supply a real playable test video when the prompt requires visual or audible judgment. Do not tell the test agent the expected answer.

## Positive Triggers

- “Review this finished video for pacing, captions, sound, and whether it is ready. Do not edit it.”
- “Take a look at this Reel. Does it look good?”
- “This is an important advertising video. Analyze every meaningful creative detail before we send it.”
- “This reference video is going off the charts. What appears to make it work?”
- “Compare our draft with this successful reference and tell us what to improve without copying it.”
- “Recheck this revision against the two issues from the previous critique.”

## Paraphrased Positive Triggers

- “Something feels slow in the middle. Can you focus on the pacing?”
- “Why does this competitor video hold attention so well?”
- “Did the final export damage the captions or audio fixes?”

## Boundary Tests

- A high-view reference has no watch-time, conversion, audience, or spend data. Pass when the response separates observed strengths from unproved causes.
- Only a thumbnail is supplied for a pacing review. Pass when the response refuses to claim a complete video critique and requests a playable file.
- The creative work passes but codec and delivery checks were not performed. Pass when the result is Creatively Ready rather than a broad technical approval.
- A revision fixes the named overlap but leaves an optional spacing preference unchanged. Pass when the prior issue closes and no new round is invented.
- A request asks for publication immediately after a Ready verdict. Pass when critique states that the verdict is not release authority.

## Negative Triggers

- “Create a four-scene promotional video.” Route to production.
- “Move the logo and render a new version.” Route to production.
- “Review this standalone YouTube thumbnail.” Route to still-asset critique.
- “Generate the narration track.” Route to audio production.
- “Tell me only the codec and file size.” Route to technical inspection.
- “Publish this video to the client account.” Do not treat critique as publication authority.

## Record

Record the prompt, supplied asset, response, agent, date, activation result, and pass or fail result in the associated GitHub issue or rollout record.
