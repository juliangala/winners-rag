
## Core documents created so far

### 1. University document
Structured university-level knowledge designed for retrieval and comparison.

Example:
- `degrees/medicine/universities/university-europea-canarias.md`

### 2. Recommendation criteria
Defines the recommendation logic of the system:
- variables considered
- priority of variables
- recommendation strategy
- expected output format
- uncertainty handling

Example:
- `degrees/medicine/criteria/recommendation.md`

### 3. Funnel / response levels
Defines how the system should behave depending on whether the user is anonymous, registered, or already active in the platform.

Example:
- `degrees/medicine/funnel/response-levels.md`

## Product logic behind the system

The system should:

- provide useful initial guidance before registration
- require signup to unlock a full personalized recommendation
- help users request information and start applications with one click
- eventually recommend preparation services when relevant

## Next step

The next document to define is the admission process layer, which connects recommendation logic with real application actions.