# Aviation Accident Analysis
# Aviation Accident Analysis

## Business Understanding

This project analyzes aviation accident data to identify aircraft manufacturers and airplane types associated with safer accident outcomes. The client is interested in understanding which airplanes demonstrate:

- Lower serious/fatal passenger injury rates
- Lower aircraft destruction rates
- Better overall survivability during accidents

The analysis focuses on professionally built airplanes from 1983 onwards to ensure that evaluated aircraft types could still reasonably be active today.

Separate analyses were conducted for:
- Small airplanes
- Large airplanes

The project also investigates how operational factors such as weather conditions and engine count influence accident severity.

---

## Data Understanding

The dataset contains aviation accident records from 1948–2023, including information about:

- Aircraft make and model
- Injury outcomes
- Aircraft damage
- Weather conditions
- Flight purpose
- Engine type
- Number of engines
- Phase of flight

The dataset was cleaned and filtered to focus only on relevant airplane records.

---

## Data Cleaning

The following cleaning tasks were performed:

- Converted date columns into datetime format
- Filtered accidents from 1983 onwards
- Retained only airplanes
- Removed amateur-built aircraft
- Removed rows with missing make/model values
- Standardized categorical text columns
- Created derived safety metrics:
  - Fatal injury rate
  - Serious injury rate
  - Combined serious/fatal injury rate
  - Aircraft destruction indicator
- Removed columns with excessive missing values

---

## Exploratory Data Analysis

The analysis explored:

- Safety performance across airplane manufacturers
- Safety performance across specific airplane types
- Differences between small and large airplanes
- Passenger injury severity distributions
- Aircraft destruction rates
- Relationships between operational variables and accident outcomes

Visualizations included:
- Bar plots
- Violin plots
- Strip plots

---

## Key Findings

### Small Airplanes

Several small airplane manufacturers and plane types demonstrated:
- Lower serious/fatal injury fractions
- Lower aircraft destruction rates
- More stable injury distributions

These airplane types appear to provide more favorable passenger safety outcomes during accidents.

### Large Airplanes

Several large airplane manufacturers similarly showed:
- Lower passenger injury severity
- Lower aircraft destruction rates
- More consistent safety outcomes

### Weather Conditions

Adverse weather conditions were associated with:
- Higher serious/fatal injury rates
- Higher aircraft destruction rates

### Number of Engines

Aircraft with more engines generally demonstrated:
- Lower passenger injury severity
- Lower destruction rates

This may suggest improved operational redundancy and survivability.

---

## Recommendations

The client should prioritize airplane manufacturers and models that consistently demonstrated:

- Low serious/fatal injury fractions
- Low aircraft destruction rates
- Stable injury distributions across accidents

Both small and large airplane recommendations were made using statistically robust comparisons with sufficient accident sample sizes.

---

## Conclusion

This project used aviation accident data to evaluate aircraft safety outcomes and identify airplane manufacturers and models associated with safer operational performance.

The findings suggest that both aircraft design characteristics and operational conditions influence accident severity outcomes.

The analysis provides evidence-based insights that may support aviation risk assessment and insurance decision-making.
