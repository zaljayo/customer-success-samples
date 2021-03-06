Blur Factory & UIImageView Extension
=====
This sample creates a blur factory class and UIImageView extension class for the UIBlurEffect.

## How it works

```
var imageView = new UIImageView {
	Frame = View.Frame,
	ContentMode = UIViewContentMode.ScaleAspectFill
};

imageView.AddBlur (UIBlurEffectStyle.Light);

View.AddSubview (imageView);
```

## Screenshots
![screenshot](https://github.com/xamarin/customer-success/blob/master/samples/Xamarin.iOS/Blur.iOS/Screenshot/2.png "Before")
![screenshot](https://github.com/xamarin/customer-success/blob/master/samples/Xamarin.iOS/Blur.iOS/Screenshot/1.png "After")

Xamarin.iOS Version
---------------------
This sample was written with [Xamarin.iOS 8.0](http://xamarin.com/platform)

Authors
-------
- Jon Davis: [GitHub](https://github.com/jon-davis-xamarin)
- Photo by Glenn Wester: [GitHub](https://github.com/glennwester)