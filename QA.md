# Front-end code challenge ![alt Batlogo](public/images/batlogo-small.png)

Batman needs your help! A supervillain was found.

Interface created for Batdevices have to show information about the possible attacks to Gotham, but it is looking bugged...

In this interface, Batman must be able to tell the Batcave's supercomputer the location (coordinate) of the recently found supervillain to identify which locations are most likely to be attacked.

You are requested to create acceptance tests scenarios to validate if coordinates sent by batmobile GPS are returning precise information about villains within the [Gotham boundaries](https://gist.githubusercontent.com/pitteri/d56780d610cb8e0a43bfa94fc54b71cd/raw/dcdd965c84cd05d856ae32646be69868d4a80afa/gotham_bbox.json), or in a specific location such as the GCPD, for example.

> Automated tests should be created by using using [Rest Assured](http://rest-assured.io/) or [Cucumber for Java](https://cucumber.io/)

> Some good tutorials to follow: [Java Cucumber Tutorial](https://www.youtube.com/watch?v=pD4B839qfos&list=PL_noPv5wmuO_t6yYbPfjwhJFOOcio89tI) and [Rest Assured](http://www.baeldung.com/rest-assured-tutorial)

> Remember, Batman is very demanding, even with the test scenarios you create. Bugs found are welcome. Surprise him!

### Batcave Supercomputer API

**Input**

Villain coordinate: http://code-challenge.maplink.com.br/coordinate?q={latitude},{longitude}

**Output**

[Sample](https://gist.githubusercontent.com/pitteri/578a6801d6f504eda6f6ce84cad59f89/raw)  
