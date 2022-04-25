# Step by Step workshop guide

- make slide deck
- prepare small map app, working name "LoraTrack"
- required (for part 2): Azure account
- create accounts as back-up
- event organizing: Martin, talk: Tim & Winston, Martijn, support: Patrick


# Part 1

## Create accounts

- reservation of 5 minutes
- explain only the Freemium subscription

## Intro about KPN Things

- Explain that we want them to ask questions, keep it interactive
- Explain devices/connectivity/processing/data destination
- slide Martijn
- Martijn? of Winston/Tim

## Explain device types

- Marvin, Elsys SER, Own LoRa device, Streamline LoRa, Viloc, 1M2M ED1608
- own Arduino devices with HATs, there is an (unsupported?) example library

## Project

- A new account already has 1 project (and a flow)

## Provision simulated device

- live demo
- explain the App

## Explain M2M vs Lora

- slide!
- tell them about M2M promo for 2 free sims

## Connectivty

- TODO SenML only for Lora or also for M2M?

## SenML

- short intro

## Configure a flow

- flow is required
- just a way to group device settings

## Data Processing

- explain decoders/encoders

## Device twin

- live demo
- Show the updated data from the simulation App
- other tabs under device

## Destinations

- types: HTTPS, Azure Event/Iot Hub, Cumulocity, MQTT
- in Part 2 more details

## Cumulocity

- Patrick?
- Move this to Part 2?

## (All) Projects, (All) flows, Bulk reports

- prepare account to shows many flows etc, data on bulk reports to demo filtering/search/pagination

## Tenants/multi user accounts

- no live demo, only slides:
  - GRIP
  - tenants
  - resellers
  - also link to docs

## Explain subscription types

- slide
- Freemium, Explorer, Custom License
- upgrade button/promo
- News / Release Notes / release cycle

## docs.kpnthings

- https://docs.kpnthings.com/portal/
- https://docs.kpnthings.com/dm/

## Teaser Part 2

- show some hardware
- overview of Part 2: press a button, and show data. Show screenshot of the map.

# Part 2

## Provision Streamline

## Demo reverse data: set Streamline in missing mode

## Set destination: webhook.site to log data

- Explain SenML payload

## Locally run "LoraTrack"

- set up webhook.site XHR forwarding!

## Deploy "LoraTrack" to Azure Web App

## Set destination: Azure Web App
