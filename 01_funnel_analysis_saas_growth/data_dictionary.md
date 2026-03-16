# Data dictionary

## leads.csv
- `user_id`: user identifier; includes one deliberate duplicate
- `lead_created_at`: creation timestamp with mixed formats
- `acquisition_channel`: marketing source with case/spacing inconsistencies
- `region`: user geography; some nulls
- `device_type`: first known device; inconsistent casing/spacing
- `lead_score`: CRM lead score; missing values included
- `company_size`: firmographic segment; inconsistent formatting included

## product_events.csv
- `user_id`: user identifier; includes some missing values
- `event_name`: product funnel stage event
- `event_timestamp`: event time with mixed formats and some out-of-order events
- `plan_selected`: pricing plan chosen during trial/subscription events
- `order_value_usd`: order value for paid conversion; includes impossible negative values
- `platform`: product platform; inconsistent values and blanks
