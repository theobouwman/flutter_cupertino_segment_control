# cupertino_segment_control

A flutter package which adds the [Apple's iOS Segment Control UI element](https://developer.apple.com/ios/human-interface-guidelines/controls/segmented-controls/).

## Getting Started

- Add the package to your pubspec
- Add following code:
    ```dart
    new SegmentControl([
        new SegmentControlItem("test1", new Text("test1")),
        new SegmentControlItem("test2", new Text("test2")),
        new SegmentControlItem("test3", new Text("test3")),
    ]),
    ```
    
PS: minimum of 1 `SegmentControlItem` and maximum of 3 `SegmentControlItem` due to this bug: https://github.com/flutter/flutter/issues/12583

## Showcase

![](https://github.com/theobouwman/flutter_cupertino_segment_control/blob/master/screenshot.png)