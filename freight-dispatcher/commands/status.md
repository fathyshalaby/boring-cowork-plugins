# Command: /freight:status

Generate a concise, professional load status update for a shipper or broker.

## Usage
When triggered, ask for:
1. Load/reference number
2. Current driver status (at pickup, in transit, at delivery, delivered)
3. Current location (city, state)
4. ETA to next stop
5. Any exceptions or delays

## Output Format
```
LOAD STATUS UPDATE
Load#: [number] | Ref#: [number]
Status: [IN TRANSIT / AT PICKUP / DELIVERED]
Location: [City, ST] as of [time] [timezone]
ETA: [date/time] to [destination]
Driver: [name] | Phone: [number]
Notes: [any exceptions, weather delays, or ETA changes]
```

Keep updates to 3-5 lines max. Shippers want facts, not narrative.
