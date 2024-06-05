# OCPP 1.6 Charge Point Simulator
A simple charge point simulator, working with OCPP 1.6

This repo is forked from [OCPP-1.6-Chargebox-Simulator](https://github.com/victormunoz/OCPP-1.6-Chargebox-Simulator)

Functionalities:
- Define the central station to connect with
- Specify the tag id that will activate the charge point
- Send charge point message events:
  - Connect
  - Authorize
  - Start/Stop transaction
  - Heartbeat
  - Meter values
  - Status Notification
  - Data Transfer

Added functionalities in this fork:
- Stop meter values sending loop
- Clear console

Fixed errors:
- WebSocket tries to reconnect after client initiated connection close
   