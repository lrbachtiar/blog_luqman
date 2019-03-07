---
layout: post
title: "Airplane Accident - Data Scraping and Wrangling"
date: 2019-03-07 23:00:00 +1200
comments: false
categories: [projects]
---

### Overview

Data source: [http://www.planecrashinfo.com/database.htm](http://www.planecrashinfo.com/database.htm)

The aviation accident database includes: 

* All civil and commercial aviation accidents of scheduled and non-scheduled passenger airliners worldwide, which resulted in a fatality (including all U.S. Part 121 and Part 135 fatal accidents)
* All cargo, positioning, ferry and test flight fatal accidents. 
* All military transport accidents with 10 or more fatalities.
* All commercial and military helicopter accidents with greater than 10 fatalities.
* All civil and military airship accidents involving fatalities.
* Aviation accidents involving the death of famous people. 
* Aviation accidents or incidents of noteworthy interest.

### Data Format

* Date:	 Date of accident,  in the format - January 01, 2001
* Time:	 Local time, in 24 hr. format unless otherwise specified
* Airline/Op:	 Airline or operator of the aircraft
* Flight #:	 Flight number assigned by the aircraft operator
* Route:	 Complete or partial route flown prior to the accident
* AC Type:	 Aircraft type
* Reg:	 ICAO registration of the aircraft
* cn / ln:	 Construction or serial number / Line or fuselage number
* Aboard:	 Total aboard (passengers / crew)
* Fatalities:	 Total fatalities aboard (passengers / crew)
* Ground:	 Total killed on the ground
* Summary:	 Brief description of the accident and cause if known

### Data Scraping

Data has been scraped to a csv.