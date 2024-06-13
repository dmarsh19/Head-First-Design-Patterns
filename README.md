# Head First Design Patterns (2020 2nd Edition)

I have recently updated all the code for Head First Design Patterns for the 2nd edition of the book, released in December, 2020.

Download the code and compile and run from the command line, or load the code into project in Eclipse using Java 8 or higher.

Other links for the book are available on the book page at <a href="http://wickedlysmart.com/head-first-design-patterns/">wickedlysmart.com</a>.


## DMM 2024-05-29

1. Install [sdkman](https://sdkman.io/install) to manage Java installations.
2. Install a JDK via `sdk env install`

For the intro, you can compile and run the classes via:

```sh
javac @compile/compile-strategy
java -cp src headfirst.designpatterns.strategy.MiniDuckSimulator1
```

Ch. 2 - the observer pattern

```sh
javac @compile/compile-observer -Xlint:deprecation
java -cp src headfirst.designpatterns.observer.simple.Example
java -cp src headfirst.designpatterns.observer.simpleobservable.Example
java -cp src headfirst.designpatterns.observer.swing.SwingObserverExample
java -cp src headfirst.designpatterns.observer.weather.WeatherStation
java -cp src headfirst.designpatterns.observer.weather.WeatherStationHeatIndex
java -cp src headfirst.designpatterns.observer.weatherobservable.WeatherStation
java -cp src headfirst.designpatterns.observer.weatherobservable.WeatherStationHeatIndex
```

