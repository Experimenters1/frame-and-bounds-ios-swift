# frame-and-bounds-ios-swift
## frame and bounds ios swift
  if let customControl = Bundle.main.loadNibNamed("RightViewHeader", owner: self, options: nil)?.first as? RightViewHeader { <br>
           print("frame : -----> ",customControl.frame)  <br>
          customControl.frame = CGRect(origin: .zero, size: RightView.bounds.size)  <br>
           print("frame 1: -----> ",customControl.frame)  <br>
        customControl.frame = RightView.frame  <br>
        print("frame 2: -----> ",customControl.frame)  <br>
          customControl.frame = RightView.bounds  <br>
        print("frame 3: -----> ",customControl.frame)  <br>
 customSegmentedControl.autoresizingMask = [.flexibleWidth, .flexibleHeight]  <br>
   customControl.frame = CGRect(x: 0, y: 0, width: 100, height: 40)  <br>
