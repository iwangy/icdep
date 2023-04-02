# Extension
### How can we add additional features to the protocol without breaking previous functionality?

**Proposed Solution:** We can add additional features to the protocol without breaking previous functionality by using header information to specific additional metadata. For the ICDEP protocol we can write additional information separate from the body/content of the card. 
- Send to any individual on the whole UW campus
  - To send the card to any individual we can add an unique 'address' to the header information of the card. Each node would do a calculation to determine the best path to get closer to the destination.
- Specific whether contents are ASCII text, Unicode text, or binary values
  - Similar to POST/GET requests, there can be a content-type field written on the index card. That way the contents of the card are known.
- Keep a record of what nodes the card has passed through
  - As the index card is passed, each node writes the date, time, and their name onto the card. As the card arrives at the destintation, the full history of where the card has passed through is recorded.