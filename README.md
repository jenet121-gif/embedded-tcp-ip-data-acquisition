# embedded-tcp-ip-data-acquisition
# Embedded TCP/IP Data Acquisition System

## Overview

This project implements a TCP/IP-based client-server architecture for real-time data acquisition between a Raspberry Pi (embedded server) and a Linux/Windows host system (client).

The Raspberry Pi operates as an embedded telemetry node, generating structured sensor data and transmitting it over a reliable TCP connection. The host client establishes a socket connection, receives JSON-formatted data packets, and reconstructs the transmitted telemetry information.

---

## System Architecture

Raspberry Pi (TCP Server)  --->  TCP/IP Network  --->  Host PC (TCP Client)

---

## Project Structure
