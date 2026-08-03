For Day 17 of the #60DayClaudeChallenge, I built an AI Vehicle Cost & Fuel Analysis Dashboard—taking unstructured CSV logs and converting them into a dynamic, interactive visualization.

Raw spreadsheet logs (mileage, fuel volume, maintenance costs, charging metrics) are hard to scan and draw insights from. By combining Claude's data parsing abilities with interactive UI rendering (HTML/JS/React or Artifacts), you can turn flat rows of data into a functional data product in minutes.

Here is how I structured the data-to-dashboard workflow:

📥 1. Raw CSV Data Ingestion & Cleaning

Fed unstructured vehicle telemetry and maintenance logs into Claude, instructing it to clean missing values, normalize units, and aggregate cost-per-mile metrics.

📊 2. Interactive KPI & Trend Visualization

Prompted Claude to render visual charts for fuel efficiency trends over time, total cost-per-kilometer, and predictive maintenance schedules based on driving patterns.

🎛️ 3. Real-Time Parameter Controls

Integrated interactive sliders and filters directly into the dashboard—allowing users to adjust projected fuel prices, driving distance, or maintenance intervals to see instant cost forecasts.

The Key Takeaway:
Data visualization isn't just about static charts; it’s about making data explorable. With Generative AI, you can bridge the gap from raw CSV files to interactive web applications in a single prompt iteration.
