# VESpinner

Spinner (or as apple named it UIActivityIndicator) which you can customize.

### Usage

    `CGFloat spinnerSize = 50.0;

    //setup frame and position
    _spinner = [[VESpinner alloc] initWithFrame:CGRectMake(0.0, 0.0, spinnerSize,spinnerSize)];
    [self.view addSubview:_spinner];
    [_spinner setCenter:self.view.center];

    //setup color
    [_spinner setBackgroundColor:[UIColor purpleColor]];
    //configure the amount of dots to spin.
    [_spinner setDotCount:10];
    //configure dot size
    [_spinner setDotSize:9.0];
    //start animating
    [_spinner startAnimating];`

### Screenshot
![alt tag](http://github.com/tdubik/VESpinner/screenshot.png)
