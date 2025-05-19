# financer-docs
This is just a centralized repo to show all the microservices involved in my "financer" app

## Overview
Some services are still in the same repo. I started this just with 3 and I was keeping them in the same repo so it was easier to deploy, but now I'm expanding it even more, so I'm splitting them all completely. 
Some services are not done yet, there's still a LOT todo. 

## Financer architecture
- `category`, `transaction` and `bff` services are all here: https://github.com/ArthurWerle/financer-services
- Logs service can be found here: https://github.com/ArthurWerle/logging
- Microservice to send monthly reports with my personal finances data: https://github.com/ArthurWerle/financer-reports
- The client-side: https://github.com/ArthurWerle/financer
- Analytics server to get insights of my own home server database and expose it to all my home server applications: https://github.com/ArthurWerle/analytics
- Lite version https://github.com/ArthurWerle/financer-lite

## FAQ
### What's financer?
Financer is my personal finances self-hosted app. 

### Couldn't it be just a simple vanilla JS app?
Yes, and what could not be just a vanilla JS app? JK. I intentionally over-engineered this for one purpose: studying.


