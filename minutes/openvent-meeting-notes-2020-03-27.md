# Meeting Minutes
## Meeting Information
**Meeting Date/Time:** 2020/03/27, 1600 UTC  
**Meeting Purpose:** Discussion of project
**Meeting Location:** Remote (Hangouts Meet)
**Host:** Tancred Yip
**Note Taker:** Kirill

## Attendees
- Tancred Yip
- Kirill
- Sean Erickson
- David Wilkinson
- Noah Wood

## Discussion Items 

### PAPR
- Sean has access to respirator and could be open to modifying for testing the idea 

### MQTT and HIPAA compliance
- Potential for remote UI
- Tancred mentioned that AWS MQ is HIPAA eligible.
- Described messaging protocol design


## Interface design
- Need to study existing ventilator systems
- Tancred posted ventilator simulator to Slack

- Sean volunteered to study use cases in greater detail
- Discussed potential use of dome buttons (e.g. such as microwave) for interface

## Build
- Local development vs central manufacturing
- Simple ventilator using a tube
- David suggests doing
- Parts should be standardized

- PCB/circuits can take a few days for delivery (7-10 days)
- Injection molding could take a few weeks 
- Testing and packaging would be a few days
- If everything goes smoothly, maybe 3 weeks
- Flow sensor needs its own tests
- If all goes smoothly, around a month turnaround time

## Quarantine
- Mentioned stats and the current growth rate in NY and the US

## MVP Status Update
- Blower
- Sensors
    - Pressure sensor
    - Flow sensor
- Control board
- Pressure regulation system
- UI
    - Sean, Kirill, and Isaac will discuss use cases
- Trello overview
    - Henry completed test workbench setup
- Reviewed project leads/coordinators

- Blower design review
    - Started with design by Mark
    - Necro modified to use drone motor
    - Henry waiting on components and iterating on blower design

- Need to review blower suppliers and confirm availability
- Potentially supply chain challenges

- Sean, Isaac, and Kirill will put together design doc for UI/UX and interface.
- Noah and Kirill to flesh out firmware design

- Pressure regulation system
    - Oxygen system
    - Humidifier
        - Isaac will research requirements

## Action Items
| Done? | Item | Responsible | Due Date |
| ---- | ---- | ---- | ---- |
| | UI/UX requirements gathering and design overview | Sean, Isaac, and Kirill | 03/28 |
| | Firmware requirements gathering and design overview | Noah | 03/28 |
| | Research requirements for humidity sensor/control | Isaac | 03/28 |

## Other Notes & Information
- [Recording of video meeting]( https://drive.google.com/file/d/1tNGBm5K5iky4gUO5z3Dq4mZC5O8OgnNA/view?usp=sharing)