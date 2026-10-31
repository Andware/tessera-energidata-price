# Changelog

## 0.6.0

- New options **Cheapest hours** (0 to 6) and **Cheapest hours as**: the graph marks the cheapest hours to come with
  a dark stroke over their bars, each on its own or as the cheapest stretch in a row. The card names them in its day
  row ("Cheapest 02:00–05:00"). Only known prices count, not the forecast. Off (0) until you set it.

## 0.5.0

- **Next 24 hours** and **Next 48 hours** now fill the hours after the known prices with Carnot's forecast from
  Energi Data Service, in fainter bars, so the graph always reaches 24 or 48 hours ahead. Turn on the forecast
  (Carnot) in the integration's options to get it; without it the graph ends where the prices end, as before.
- The card's low and high still come from the known prices only.

## 0.4.0

- **Period** can now show only the hours to come: the next 24 or the next 48 hours from the hour of now, without the
  hours that have passed. The next 48 go as far as the prices do (midnight tomorrow). On the card, the low and high
  are those of the hours the graph shows.

## 0.3.0

- New option **Period**: today and tomorrow (48 hours, as before) or today only (24 hours). Nothing to do: tiles
  keep showing both days until you change it.

## 0.2.0

- New option **Price per**: every quarter of an hour, or each hour as the average of its quarters. The price now,
  the low, high, average and the graph follow it. Nothing to do: tiles keep showing quarters until you change it.

## 0.1.0

- First version: the electricity price now from an Energi Data Service sensor, in kr/kWh or øre/kWh, with a graph of
  today and tomorrow on bigger tiles, a card and the price in the top bar.
- Built on the Electricity price plugin by Heronimonimo (MIT).
