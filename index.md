# COVID-19 data for India

This is a place for experiments.

After providing almost real-time updates for COVID-19 data in India
since March 2021, [covid19india.org]<https://covid19india.org> wound
down their crowdsourced data collection operation on 31 October, 2021.
This data, meticulously collected from various sources and made
available in a standardized format, as well as the frontend that
presents this data, have been invaluable to both the general public
and those who used the data for further analysis.

Fortunately, several other groups are attempting to continue this
effort by building on their work, including

- [incovid19.org](https://incovid19.org) - data and frontend

- [covid19tracker.in](https://covid19tracker.in) - data and frontend

- [datakind](https://data.covid19bharat.org/) - data

Disclaimer: I am involved with the first effort.

This page hopes to supplement these efforts by serving as a place to
develop and provide additional resources and tools. These may include
visualization frontends, data consistency checking, further analyses,
etc.


## Visualization frontend

The covid19india visualization frontend is written using
[react](https://en.wikipedia.org/wiki/React_(JavaScript_library)), and
is available at <https://github.com/covid19india/covid19india-react>
under the MIT license. 

Our first experiment is to port this frontend, with minimal changes,
to work with data from other sources. So far we have

- <https://c19in.github.io/covid19india/> - using data upto 31 October
  from <https://data.covid19india.org>

- <https://c19in.github.io/incovid19/> - using data from
  <https://data.incovid19.org>

- <https://c19in.github.io/datakind/> - using data from
  <https://data.covid19bharat.org/>


## Contributing

So far this is just [my](https://deepayan.github.io) personal
project. But contributors are more than welcome.

