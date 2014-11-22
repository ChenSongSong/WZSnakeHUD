WZSnakeHUD
==========


A clean and neat HUD is available NOW.

<p>
<img src="WZSnakeHudDemo/Gif/WZSnakeHUD.gif">
</p>

##Installation

First, drag the `WZSnakeHUD` file into your project.

Second, add `#import "WZSnakeHUD.h"` to the header of viewController.

Third, use
```` objc
[WZSnakeHUD showWithText:@"Loading"]
```` method to show.

###Custom

BackgroundColor:

```` objc
[WZSnakeHUD showWithBackgroundColor:[UIColor purpleColor]];
````

MaskColor:

```` objc
[WZSnakeHUD showWithMaskColor:[UIColor colorWithRed:0.0f green:0.0f blue:0.0f alpha:0.5f]];
````

LineWidth:

```` objc
[WZSnakeHUD showWithLineWidth:4.5f];
````

Dimiss:

```` objc
[WZSnakeHUD hide];
````
##TODO

 * More Customization and features
 * CocoaPods support
 * Uncoupled code

##Contribute

Pull request and contribution are welcomed.

##Contact

<wongzigii@outlook.com>

##License

MIT