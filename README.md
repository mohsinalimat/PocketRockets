# PocketRockets
This is a fun code challenge that shows a list of up comming SpaceX rocket launches as well as counting down to the next launch.

## Thoughts
1. I used SnapKit to create a custom view, LaunchHeaderView. SnapKit was pretty easy and fun to use! I personally find Storyboard to be easier to use and maintain thanks to improvements Apple had made to Interface Builder over the years. Ultimately SwiftUI canvas is the future though, so I am looking forward to say goodbye to Autolayout. 

2. Please view WWDCC Session 233 on the topic of "Layout Driven UI." This is a really great technique to manage complex view hierarchies. The idea is pretty simple: In a reactive data driven design pattern, do not update views directly. Instead dirty the layout by calling setNeedsLayout(), then update your views in layoutSubviews(). This allows UIKit to determin where in the drawing cycle to update everything at once. I feel obligated to pass this along.

![gif](https://raw.githubusercontent.com/LunarFlash/PocketRockets/master/Media/demo.gif "gif")
