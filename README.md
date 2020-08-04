# helium-gtw-diy-multi-container-balenaos

This project deploys a Helium LoRa gateway with [balena.io](https://balena.io). It runs on a Raspberry Pi or balenaFin with a RAK2245 Pi Hat. 


## Introduction

Deploy a DIY Helium LoRa gateway running the miner inside the board. We are using balena.io and RAK to reduce fricition for the LoRa gateway fleet owners.


## Getting started

### LoRa has been configured for EU region !

### Hardware

* Raspberry Pi 4 or [balenaFin](https://www.balena.io/fin/)
* [RAK 2245 pi hat](https://store.rakwireless.com/products/rak2245-pi-hat)
* SD card in case of the RPi 4

### Software

* A Helium account ([sign up here](console.helium.com/))
* A balenaCloud account ([sign up here](https://dashboard.balena-cloud.com/))
* [balenaEtcher](https://balena.io/etcher)

Once all of this is ready, you are able to deploy this repository following instructions below.

## Deploy the code

### Via [Balena Deploy](https://www.balena.io/docs/learn/deploy/deploy-with-balena-button/)

Running this project is as simple as deploying it to a balenaCloud application. You can do it in just one click by using the button below:

[![](https://www.balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/PastaGringo/helium-gtw-diy-multi-container-balenaos)

Follow instructions, click Add a Device and flash an SD card with that OS image dowloaded from balenaCloud. Enjoy the magic 🌟Over-The-Air🌟!
