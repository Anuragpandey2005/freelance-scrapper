# Freelance Job Scraper  
**Scrapes RemoteOK, PeoplePerHour, and Wellfound daily.**  

## Features  
- Daily CSV outputs with timestamps.  
- Error handling and logging.  
- Headless Chrome for JavaScript sites.  

## Challenges Overcome  
1. **PeoplePerHour**: No location data without login.  
2. **Wellfound**: Dynamic React components required Selenium.  
3. **RemoteOK**: API metadata had to be filtered.  

## Setup  
1. Install packages:  
```bash
!pip install requests beautifulsoup4 pandas selenium webdriver-manager
