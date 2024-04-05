# Communication Trailer Design

## Objective

Update existing "race trailer" for use as a communication trailer

## Priorities

1. Function "off grid" as a communication center for a period of at least 24 hours
1. Provide storage for radio related gear
1. Provide comfortable environment in which to conduct radio operations. 2 people should be able to work very comfortably with up 4 people able to work less comfortably.
1. When practical, avoid exterior characteristics that could advertise the presence of expensive equipment

## Exclusions/Constraints

- Design *shall not* include plumbing elements which introduce a need for winterization

## Power systems

- Primary 12v
  - *SEPARATE* from 12v system used for towing operation
  - Covers *all* components considered essential for operation
  - When practical, non-essential components should also be 12v
  - Large capacity house battery (preferably 200ah)
  - Disconnect at battery for ease of avoiding parasitic discharge
  - System *must* support AGM battery chemistry
  - System *should* support LiFePo4 battery chemistry if practical
  - Primary connection method Anderson Power Pole
  - Available automotive style accessory outlet
  - Anderson SB50 connectors for higher current
  - Inlet from outside Anderson SB50 near driver side front of trailer
  - Charging station at inside front of trailer
  - 6 circuits terminated in Anderson SB50 connectors distributed throughout trailer interior
    - 2 on front bulkhead
    - 2 on side bulkheads to the front of the axle
  - 3 circuits terminated in Anderson SB50 connectors distributed throughout trailer exterior
    - 1 in front
    - 1 on each side near center
- 120v ancillary
  - 30A inlet near driver side front of trailer (adapters for 50A, 20A, and 15A)
  - 12v power supply to drive primary systems when AC is available
  - House battery charges when AC is present
  - 6 dual outlet receptacles distributed throughout trailer interior
    - 2 on front bulkhead
    - 2 on side bulkheads to the front of the axle
    - 2 on side bulkheads to the read of the axle
- Solar
  - Used only for charging house battery (no direct powering of components)
  - Inlet near driver side front of trailer for external panel (not permanently mounted)
  - Long term consider roof mounted panel
- 20v/60v tools
  - Use Dewalt cordless tool ecosystem for interoperability
  - Multi-battery charger connected to AC circuit and located with other battery charging
  - Step-down transformer with Anderson Power Pole connectors on load side to allow batteries to be used for critical components if necessary
