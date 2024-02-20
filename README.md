# A demo of AWS Rekognition as a Practice to use AWS SDK

Used my profile photo in this repo, and got following result
![Jingshi's Profile Photo](./profile.png)

```
Detected faces for: jingshi-profile.png
The detected face is between: 12 and 18 years old
All other attributes:
  BoundingBox.Width:      0.34193360805511475
  BoundingBox.Height:     0.4063228666782379
  BoundingBox.Left:       0.2982037365436554
  BoundingBox.Top:        0.2891853153705597
  Age.Range.Low:          12
  Age.Range.High:         18
  Smile.Value:            false
  Smile.Confidence:       99.9986343383789
  Eyeglasses.Value:       true
  Eyeglasses.Confidence:  100
  Sunglasses.Value:       false
  Sunglasses.Confidence:  100
  Gender.Value:           Male
  Gender.Confidence:      99.99626159667969
  Beard.Value:            false
  Beard.Confidence:       99.94063568115234
  Mustache.Value:         false
  Mustache.Confidence:    99.99362182617188
  EyesOpen.Value:         true
  EyesOpen.Confidence:    98.76058197021484
  MouthOpen.Value:        false
  MouthOpen.Confidence:   87.65161895751953
  Emotions[0].Type:       CALM
  Emotions[0].Confidence: 98.046875
  Landmarks[0].Type:      eyeLeft
  Landmarks[0].X:         0.3550507724285126
  Landmarks[0].Y:         0.43427804112434387
  Pose.Roll:              -6.355159759521484
  Pose.Yaw:               -20.088279724121094
  Pose.Pitch:             -12.734016418457031
  Quality.Brightness:     75.28472900390625
  Quality.Sharpness:      7.589449882507324
  Confidence:             99.99383544921875
```