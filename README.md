# sonify_climate_stripes
code getting the data of the climate 'stripes' (temperature data series) in the appropriate format, plus sonic pi code to make it sound

Inspired by https://showyourstripes.info/, I gather the temperature data for Switzerland https://opendata.swiss/de/dataset/schweizer-temperaturmittel/resource/8721bd6e-3c34-486a-b1d9-7aad77fc8ba2 (Source: MeteoSchweiz), which can also be explored visually here https://meteostats.ch/?parameter=Temperature&period=Year&display=Relative&reference-period=1961-1990&code=SWISS

In a jupyter notebook, I prepare the data appropriately (difference relative to the reference period of 1961 to 1990, shift range so that it makes sense for sonic pi). Manual copying into sonic pi follows. The sonic pi code is also present in the repo.
