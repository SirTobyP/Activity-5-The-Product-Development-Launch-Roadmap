# Risk Mitigation & Technical Constraints

## Core Technical Risks

*   **Highest Risk Feature:** Collision Detection & Satellite Data Processing

*   **The Hazard:** LEON relies on accurate and up-to-date satellite tracking data to identify potential collision risks. Missing, delayed, or inaccurate data could lead to unreliable predictions and reduce confidence in the platform's recommendations.

## User Experience Consideration

  * Even if collision detection functions correctly, complex data visualization and navigation may make collision information difficult for users to interpret, reducing the effectiveness of the system.

## The Pivot Strategy

If real-time collision detection cannot be fully implemented due to data availability or technical constraints, our backup plan is to:

   * Notify users when satellite data is unavailable or outdated.
   * Display the latest verified data timestamp.
   * Use historical or simplified datasets when live data is unavailable.
   * Simplify collision visualizations and workflows to ensure users can still access essential tracking information.
