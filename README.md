# LNG Data

Analysis of LNG shipment logistics showing how route choice, vessel type, seasonality, and risk management affect profit margins. Includes data processing, visualization, and actionable recommendations for margin optimization.

This dataset simulates LNG shipments from Sabine Pass, LA to key European ports. It is generated synthetically with realistic relationships between distance, vessel type, season, and transport costs. Minor random noise is added to emulate natural variability while keeping the data consistent for analysis.

## Column descriptions

- `id` — Unique shipment identifier
- `origin_port` — Port of departure (all Sabine Pass, LA)
- `destination_port` — European destination port
- `vessel_type` — Type of vessel: Q-Max, Q-Flex, Standard
- `distance_km` — Approximate distance from origin to destination in kilometers
- `vessel_capacity_m3` — Tanker cargo volume in cubic meters
- `season` — Shipping season derived from month
- `month` — Month of shipment
- `total_transport_cost_usd_per_m3` — Total transport cost per cubic meter
- `route_category` — Categorized cost efficiency of the route (`excellent`, `good`, `satisfactory`)
- `risk_level` — Risk level based on distance and operational factors (`low`, `medium`, `high`)
- `freight_rate_usd_per_m3` — Portion of cost attributed to freight
- `fuel_cost_usd_per_m3` — Portion of cost attributed to fuel
- `port_fees_usd_per_m3` — Portion of cost attributed to port fees
- `insurance_cost_usd_per_m3` — Portion of cost attributed to insurance
