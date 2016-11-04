# CircleProgressView

This is a Obj-C Binding Project based on https://github.com/Eclair/CircleProgressBar

### Usage

```
CircleProgressBar progressBar = new CircleProgressBar();
progressBar.Frame = new CGRect(50, 50, 60, 60);
progressBar.BackgroundColor = UIColor.Clear;
progressBar.ProgressBarWidth = 6f;
progressBar.HintTextColor = UIColor.Black;
progressBar.HintViewBackgroundColor = UIColor.Clear;
progressBar.HintTextFont = UIFont.PreferredBody;
this.View.AddSubview(progressBar);
progressBar.SetProgress(progressBar.Progress + 5f, true, 3f);
```

### Output

![](https://github.com/guntidheerajkumar/CircleProgressView/blob/master/output.gif)
