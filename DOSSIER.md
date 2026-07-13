Athlete Training Dossier & Performance Roadmap

Dossier Version: v1.1.1
Protocol Compatibility: Section 11
Date: 2026-07-13
Primary Source System: Intervals.icu
Data Access: Connected GitHub training-data repository

1. Athlete Overview
Basic Information
Age: 40 years
Height: 158 cm
Current weight: 59 kg
Primary sport: Cycling
Current FTP: 156 W
Relative FTP: approximately 2.64 W/kg
Training Background
Approximately 10 years of cycling experience
Training volume was relatively low during the past 2–3 years
Regular riding resumed in April 2026
Current weekly training volume: approximately 5 hours
Weekly volume may be increased progressively as personal schedule permits
Health and Limitations
Current injuries: None reported
Current pain or physical limitations: None reported
Previous injuries affecting training: None reported
Known health-related training restrictions: None reported
2. Equipment and Data Sources
Outdoor Equipment
Power meter: Quarq
Heart-rate monitor: Garmin HRM 600
Indoor Equipment
Indoor trainer/bike: Wahoo KICKR BIKE
Preferred indoor training period: Weekday evenings
Outdoor Riding Preference
Outdoor riding is preferred on weekends when schedule and conditions permit
Data Platform
Training and wellness data: Intervals.icu
Training-data synchronization: GitHub Actions
AI data source: Connected GitHub repository
Training zones: Intervals.icu default zones
3. Training Schedule and Coaching Preferences
Typical Weekly Availability
Current target volume: approximately 5 hours per week
Weekdays: Indoor trainer sessions in the evening when available
Weekends: Outdoor rides when available
Fixed unavailable days: None
Fixed preferred high-intensity days: None
Coaching Preference
Flexible, adaptive guidance is preferred over a rigid fixed training plan
Recommendations should adjust to:
Personal schedule
Recent training load
Recovery status
Outdoor riding opportunities
Progress toward the October travel objective
Progression Preference
Increase weekly training duration gradually when personal schedule allows
Avoid abrupt increases in volume
Prioritize sustainable consistency over strict weekly compliance
4. Current Performance Metrics and Zones
Cycling Power
FTP: 156 W
Body weight: 59 kg
Relative FTP: approximately 2.64 W/kg
Separate indoor FTP: Not currently specified
Separate outdoor FTP: Not currently specified
Power zones: Use current Intervals.icu default cycling zones
Heart Rate
Resting heart rate: 60 bpm
Maximum heart rate: 207 bpm
Lactate threshold heart rate: 178 bpm
Heart-rate zones: Use current Intervals.icu default zones
Threshold Management

Use the FTP, LTHR, maximum heart rate, and zone settings stored in Intervals.icu as the operational source of truth.

Do not change threshold values based only on estimated performance. Update them after a validated test, reliable physiological evidence, or a clearly supported change in current fitness.

5. Nutrition and Fueling
Dietary Restrictions
No dietary or fueling restrictions reported
No specific food intolerance reported
Training Fueling Approach

Fueling recommendations should be adapted to session duration and intensity.

For longer rides and consecutive riding days, emphasize:

Beginning carbohydrate intake early rather than waiting for fatigue
Regular fluid intake
Adequate sodium intake according to conditions and sweat loss
Post-ride carbohydrate and protein intake
Replenishment between consecutive riding days

No specific preferred gels, drink mixes, bars, or solid foods have been defined.

6. Primary Goals
General Performance Goal

Improve overall cycling performance, including:

Aerobic capacity
Sustainable power
Muscular endurance
Long-ride durability
Fatigue resistance
Recovery between repeated rides
Ability to maintain performance across consecutive riding days
Main Target

Prepare for a cycling-focused trip to Vienna from October 16 through October 23, 2026.

Target Capabilities by October 2026

The athlete should be prepared to:

Complete rides of up to approximately 100 km in one day
Ride 3–4 times during a one-week period
Tolerate accumulated fatigue across repeated riding days
Recover sufficiently between rides
Maintain fueling, pacing, and hydration across longer sessions
Complete the trip without excessive fatigue compromising later rides

This is a travel-performance objective rather than a single-day peak race objective. Training should therefore prioritize durability, repeatability, and recovery in addition to FTP development.

7. Training Priorities
Immediate Phase

Rebuild consistent training after the recent low-volume period.

Priorities:

Establish regular weekly frequency
Develop aerobic base
Restore tolerance to structured intensity
Increase total duration progressively
Avoid excessive early fatigue
Development Phase

As consistency improves:

Gradually extend weekend outdoor rides
Add controlled tempo and sweet-spot work
Maintain some higher-intensity training for general performance
Develop fueling habits during longer rides
Monitor durability and cardiac drift
Introduce occasional two-day riding blocks
Trip-Specific Phase

Before the Vienna trip:

Complete several rides approaching the expected daily duration
Progress toward at least one ride close to the target 100 km distance when practical
Practice back-to-back riding days
Complete selected three-ride blocks within one week
Test travel-day fueling and recovery routines
Avoid a training plan focused only on a single peak performance day
8. Coaching Decision Framework

Recommendations should remain flexible and should consider:

Current readiness and recovery
Recent training load and training consistency
Available time that day
Indoor versus outdoor opportunity
Progress toward long-ride durability
Progress toward repeated riding-day tolerance
Proximity to the October 16–23, 2026 Vienna trip

When readiness is normal, prioritize consistency and completion of the planned training stimulus.

When fatigue indicators are meaningfully abnormal, modify duration or intensity rather than automatically cancelling all training.

Do not issue unnecessary recovery warnings based on TSB alone. Interpret load together with recovery, wellness, and recent performance data.

9. Planning Constraints
Personal schedule may vary from week to week
Weekly duration is expected to increase only when practical
Weekday sessions will usually need to be compatible with evening indoor training
Weekend sessions may be replaced or adjusted according to outdoor riding opportunities
The training plan should allow missed or moved sessions without treating them as failure
Important sessions should be prioritized, while lower-priority sessions may be shortened or omitted when time is limited
10. Coach Communication Preferences
Provide flexible recommendations rather than rigid instructions
Clearly identify the main purpose of each recommended session
Distinguish essential sessions from optional sessions
Offer shortened alternatives when time is limited
Use current Intervals.icu and synchronized JSON data for quantitative assessment
Keep recommendations concise when metrics are normal
Give additional explanation when thresholds are breached or when asked why
Emphasize actionable pacing, duration, intensity, recovery, and fueling guidance
11. Data Source

The AI coach should read the following files from the connected GitHub training-data repository:

latest.json
history.json
intervals.json when relevant
routes.json when relevant
ftp_history.json when available
SECTION_11.md
DOSSIER.md

The current JSON files and Intervals.icu settings take precedence over static values recorded in this dossier when the values differ.

Every current training metric used in coaching should come from a fresh data read during the current response.
