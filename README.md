# SwiftUI-Weather
SwiftUI-Weather is a weather app UI prototype built with SwiftUI. Users may check the current weather in their city, and choose between bright and dark settings. The project showcases the developer's proficiency in utilizing SwiftUI for a visually stunning UI.

based on this [youtube video](https://www.youtube.com/watch?v=HXoVSbwWUIk) by Sean Allen ([@SAllen0400](https://www.github.com/SAllen0400))

note: for those who watch the video, I didn't follow Sean's recommendation about adding `@Binding` annotation for `isNight` variable inside `BackgroundView` because in my opinion:
- the preferable way to change `isNight` value is using `WeatherButton`
- `BackgroundView` should only receive value from it's parent, `ContentView`
- therefore, it shouldn't be able to change the `isNight` value right from itself

![swiftui-weather-seanallen](https://user-images.githubusercontent.com/129122862/230707297-fac27ba4-5094-4608-8307-b82b83f10bc8.png)
