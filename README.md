# Time_Series_using_Plotly_Libraries

This code creates an interactive **time series chart** using Plotly. It visualizes values across consecutive dates and displays both a line and markers, making it easy to track trends and daily changes.

---

## What this plot shows
- A sequence of **daily values** over time
- Trend direction (increasing/decreasing)
- Day-to-day changes using visible markers

---

## Data Used
- Dates are generated using:
  - `pd.date_range(start="2023-01-01", periods=10, freq="D")`
- Values:
  - `[10, 12, 14, 11, 15, 18, 20, 17, 19, 22]`

---

## Visualization Details
- **Plot type:** Time series line chart
- **Trace used:** `go.Scatter`
- **Mode:** `lines+markers`
  - Line connects the values across dates
  - Markers highlight each day’s value
- Grid is enabled on both axes for readability.

---

## Libraries Used
- `plotly.graph_objects`  
  Used to build the interactive figure and add the line+marker trace.
- `pandas`  
  Used to generate the date sequence (`date_range`).

---

## Output
- An interactive plot titled **"Time Series Plot Using Plotly"**
- X-axis: Date  
- Y-axis: Value  
- Line + markers showing daily progression

---

## Developer
Grishma C.D

