# Step by Step workshop guide

- make slide deck
- prepare small map app, working name "LoraTrack"
- required (for part 2): Azure account
- create accounts as back-up
- event organizing: Martin, talk: Tim & Winston, Martijn, support: Patrick, Hein


# Part 1

## Create accounts

- reservation of 5 minutes
- explain only the Freemium subscription

## Intro about KPN Things

- TODO IoT: embbed systems, remote monitoring, use cases!
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

## Connectivity

- SenML for Lora en ook voor M2M

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
  - secure by design

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
- hands-on

# Part 2

## Provision Streamline

- what, where, how many, which model (N1C2?) - 20 should be enough
- when can we have them, before 6 May? Pick up 5 May
- return after the demo? Do we have overstock? Put it on your bike
- what does it cost N1C2? Viloc is 55 at bol.com
- TODO test provisioning
- TODO Patrick? show Hardware use cases (locationtag, vulmeter)

## Demo reverse data: set Streamline in missing mode

- from Device view, tab Send data to Device
- TODO prepare SenML
- TODO test: blink LEDs!
- explain missing mode and battery use

## Set destination

- HTTPS endpoint to webhook.site to log data
- Explain SenML payload

## Locally run "LoraTrack"

- clone https://github.com/code-star/lora-track
- npm install
- TODO npm start?
- set up webhook.site XHR forwarding!
- maps in app should be updated

## Deploy "LoraTrack" to Azure Web App

- TODO azcli

## Set destination: Azure Web App

- Add as a second HTTPS endpoint, not as Azure
