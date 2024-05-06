# Attribution Queries
CoolTShirts sells shirts of all kinds, as long as they are T-shaped and cool. Recently, CTS started a few marketing campaigns to increase website visits and purchases. Using touch attribution, they’d like to map their customers’ journey: from initial visit to purchase. They can use that information to optimize their marketing campaigns. This project will guide you through some of that process.

### Schema: page_visits
A table describing each time a user visits the CoolTShirts website

| Column | Description    |
| :---:   | :---: |
| user_id | A unique identifier for each visitor to a page   |
| timestamp | The time at which the visitor came to the page   |
| page_name | The title of the section of the page that was visited   |
| utm_source | Identifies which site sent the traffic (i.e., google, newsletter, or facebook_ad)   |
| utm_campaign | Identifies the specific ad or email blast (i.e., june-21-newsletter or memorial-day-sale)   |


