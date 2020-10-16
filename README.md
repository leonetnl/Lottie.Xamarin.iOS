# Lottie Xamarin iOS
## current version 3.1.8

## Code example
    var AnimationView = new CompatibleAnimationView();
	AnimationView.ContentMode = UIViewContentMode.ScaleAspectFit;
	AnimationView.LoopAnimationCount = 10;
	AnimationView.Frame = new CGRect(0, 0, 300, 300);
	var Animation = new CompatibleAnimation("CoolAnimation", NSBundle.MainBundle);

           
	AnimationView.CompatibleAnimation = Animation;
	this.View.AddSubview(AnimationView);
	AnimationView.PlayWithCompletion((completed) =>
	{
		Console.WriteLine("done!");
	});

## contribute
Feel free to integrate into https://github.com/Baseflow/LottieXamarin
