Bibcam - Burnt-in barcode metadata camera
=========================================

**Bibcam** is a proof-of-concept project where I tried the idea of "burnt-in
barcode metadata" carrying camera tracking data within a single video stream.

By using this format, you can record/edit/playback AR-ready video clips without
worrying about desynchronization with external tracking data.

System Requirements
-------------------

This project uses a LiDAR enabled iOS device as a camera. I'd recommend iPhone
13 Pro/Pro Max for better quality.

You can playback recorded video clips on any Unity-supported platform.

I created this project on Unity 2021.2.

How To Try
----------

Build and play the `Encoder` scene on a LiDAR enabled iOS device. You can
record Bibcam video clips by just pressing the "Record" button. It stores
recorded clips in the camera roll.

Transfer a video clip to your computer. Copy it into the `StreamingAssets`
directory, and rename it to `Test.mp4`. Then you can play it back in the
`Decoder` scene.

For more advanced usage, see the [BibcamVfx] repository.

[BibcamVfx]: https://github.com/keijiro/BibcamVfx
