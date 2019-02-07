---
title: "Calgary Cycletrack"
slug: cycletrack
modified: 2018-12-08
date: 2016-07-28
js: cycletrack.js
---

# Looking at the cycle track pilot numbers

<div id='pilot'>

## Budget

The budget of the Cycle Track was set at $7,100,000<a
href="#citation_final_project"><sup>1</sup></a>. The spending according to the
City of Calgary at the end of the pilot was {{< adjustable_number
variable="cost_of_cycletrack" format="dollars" min="5e6" max="1e9" step="5e4"
>}}, which is <span data-var="percentage_of_pilot_budget"
data-format="percent"></span>&nbsp;of the cycle track budget

If you look at the {{< adjustable_number variable="trips"
format="pretty_numbers" min="1e6" max="1e9" step="1e4">}}&nbsp;trips done over
the lifespan of the cycle track pilot project, you can see that this comes to
<span data-var="cost_per_trip" data-format="dollars_cents"></span>&nbsp;spent per
trip.

## Safety

When the pilot started, the average collisions per year was {{<
adjustable_number variable="y2014_benchmark_collisions_per_year" min="0"
max="800" >}}. Since the track has been put in place, there is now {{<
adjustable_number variable="y2016_collisions_per_year" min="0" max="800" >}}<a
href="#citation_final_project"><sup>1</sup></a>. Assuming a cost to the city of
{{< adjustable_number format="dollars" variable="cost_per_collision" min="1e4"
max="1e6" step="1e4" >}}<a href="#cost_per_collision"><sup>2</sup></a>, this
comes to a savings of <span data-var="total_cost_of_collisions" data-format="dollars"></span>&nbsp;per
year.

## Comparisons

Assuming airport tunnel construction costs came to {{< adjustable_number
variable="cost_of_airport_tunnel" format="dollars" min="25e7" max="1e9"
step="5e5" >}}<a href="#exact_numbers"><sup>2</sup></a>.  Assuming the same
dollar-per-trip construction value,<a
href="#apples_to_oranges"><sup>3</sup></a> you would see <span
data-var="num_airport_tunnel_trips"
data-format="pretty_numbers"></span>&nbsp;trips, or roughly <span
data-var="airport_tunnel_trips_per_day"
data-format="pretty_numbers"></span>&nbsp;trips/day.<a
href="#no_numbers_available"><sup>4</sup></a>

## Citations/Footnotes

1. [ ](#citation_final_project) [Centre City Cycle Track Network Pilot Project Final Report](49246212072016100730178.PDF)
2. [ ](#cost_per_collision) I was unable to find the report that had exact numbers. If you know where I can get the exact numbers, {{< please_contact_me >}} with a link to the report.
3. [ ](#exact_numbers) This is an apples-to-oranges comparison. Different projects have different strategic value to the city.
4. [ ](#no_numbers_available) To my knowledge no exact numbers exist. If you know where these can be retrieved, {{< please_contact_me>}}!
