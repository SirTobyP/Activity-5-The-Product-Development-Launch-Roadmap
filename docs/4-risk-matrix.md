# Risk Mitigation & Technical Constraints

## Core Technical Risks

*   **Highest Risk Feature:** Collision Detection & Satellite Data Processing

*   **The Hazard:** The application depends on accurate, current satellite data to identify potential collision risks. If satellite data is missing, delayed, incomplete, or outdated, the system may generate incorrect collision assessments or fail to detect potential hazards altogether.

## The Pivot Strategy

If our primary implementation for this feature fails or takes too long, our backup plan is to:

   * Display the most recent validated satellite data along with a timestamp indicating when it was last updated.
   * Notify users when data is unavailable, incomplete, or outdated and temporarily suspend risk calculations that rely on that data.
   *  Use simplified collision assessment models or historical datasets until live data services are restored.
   *  Prioritize core tracking and monitoring features while advanced collision prediction capabilities are being refined.
