# frame-and-bounds-ios-swift
## frame and bounds ios swift
  if let customControl = Bundle.main.loadNibNamed("RightViewHeader", owner: self, options: nil)?.first as? RightViewHeader {
           print("frame : -----> ",customControl.frame)
          customControl.frame = CGRect(origin: .zero, size: RightView.bounds.size)
           print("frame 1: -----> ",customControl.frame)
        customControl.frame = RightView.frame
        print("frame 2: -----> ",customControl.frame)
          customControl.frame = RightView.bounds
        print("frame 3: -----> ",customControl.frame)
 customSegmentedControl.autoresizingMask = [.flexibleWidth, .flexibleHeight]
   customControl.frame = CGRect(x: 0, y: 0, width: 100, height: 40)
