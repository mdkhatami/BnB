## Inspiration
Ensuring quick and sustainable mobility for all people, particularly in big cities, is a big concern for many public transport providers, citiy councils, employers, etc. Nowadays, car traffic is becoming more and more inefficient and strong solutions are needed to enable people to switch car traffic to other modes of transport.

We believe that a data-driven approach of transport behavior and related predictions for future transport concepts is best suited to make it easier for people to change their current mobility behaviour.

## What it does
We argue that the current scope of data is lacking in several regards. One, data access is often not feasible for many transport providers. They often do not have the resources to fully analyze their own user data. Further complicating the issue, even if you can analyze the public transport data, it becomes a heavily biased analysis if you do not include car traffic data. 

## How we built it
We collected car traffic data with an SDK set which delivers information (not only but mainly) car traffic in Berlin for about 60 K users. We developed an algorithm to analyze the main traffic paths between Berlin districts (think Origin-Destination-Matrices) and we visualized it for one day.
In the next step we have applied the same process to the provided BVG data (query data and geodata of stations) in order to see the patterns.

In conclusion we overlayed both traffic behaviour patterns and identified the next hotspots for JELBI based on the visualizations. We also argue for the establishment of a fastlane shuttle to further reduce travel time and thereby usage of cars on the same paths.

## Challenges we ran into
Lack of time to process all data
Difficulties to properly download and understand the labels of the data

## Accomplishments that we proud of
Finalized all the patterns
Analyzed traffic data and come up with strong suggestions for new JELBI stations

## What we learned
Understood more about Berlin traffic and the current struggles to plan, built and run JELBI stations in a city like Berlin. We were astounded by the complexity of all the involved players.

## What's next for BandB (Bonn meets Berlin)
Hopefully we go deeper and establish a channel to discuss further collaboration to analyze with more BVG and JELBI data combined with traffic data we can provide in a much bigger scale.
