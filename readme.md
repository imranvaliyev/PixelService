# PIXEL Tracker

Website visitor tracker.

## Brief notes

Implemented with:
- gRPC 

## How to run

1. Run `docker compose build` and `docker compose up -d`
2. Visit the page http://localhost:5200/track
3. Revise log file at `./tmp/visits.log` on projects root directory.

## Consume

In order to leverage, just put the snippet into your webpage.

```html
<img src="http://localhost:5200/track" alt="Pixel Tracker" />
```
