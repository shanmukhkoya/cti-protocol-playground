# CTI Protocol Simulator

An interactive web-based simulator for Computer Telephony Integration (CTI) protocols, including SIP, TAPI, and CSTA. This tool helps users understand how different CTI protocols handle various call scenarios through visual call flow diagrams and voice narration.

## Features

- **Multi-Protocol Support**: Simulate call flows for:
  - **SIP** (Session Initiation Protocol)
  - **TAPI** (Telephony API)
  - **CSTA** (Computer Supported Telecommunications Applications)
- **Interactive Scenarios**: Run pre-defined scenarios for each protocol:
  - Basic Call Setup
  - Inbound & Outbound Calls
  - Call Transfer
  - Call Hold/Resume
  - Conference Calls
  - Call Termination
- **Visual Call Flow Diagrams**: Real-time generation of sequence diagrams showing message exchanges between participants (e.g., Caller, Proxy, Callee).
- **Voice Narration**: Uses the Web Speech API to narrate the steps of each scenario, making it easier to follow the protocol flow.
- **Event Log**: Detailed log of all protocol events and messages.
- **Protocol Details**: Inspect specific protocol messages (e.g., SIP headers, XML payloads) by clicking on the message arrows in the diagram.

## Usage

1.  Open `cti-simulator.html` in a modern web browser.
2.  Select a protocol (SIP, TAPI, or CSTA) from the sidebar.
3.  Choose a scenario to run (e.g., "Basic Call Setup").
4.  Watch the visual diagram build up as the scenario executes.
5.  Enable voice narration for an audio walkthrough.
6.  Click on any message arrow in the diagram to view the raw protocol message details.

## Technical Details

- **Single-File Application**: contained entirely within `cti-simulator.html` for easy portability.
- **Technologies**: HTML5, CSS3, Vanilla JavaScript.
- **No Dependencies**: Runs without any external libraries or backend servers.
