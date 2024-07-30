# cper1-gnss-debug-tools
GNSS Failure Debug Tools

## GNSS Failure Context Tools - Alpha Prototype

### Business Need  (WHY)

As a designer, question often arises about why GPS location via standard modem AT commands is not provided by the modem SOC. Arguments ensue quite often led by human intuition of various project stakeholders instead of technical data-driven analysis. 

Validation of statement: Nothing public.  Based on modem driver debug between 2017-2024 on various mobile cellular platforms (cell phones, COTS, Quectel SOCs, Qualcomm QMI debug).




### Project Objective (WHAT)

TO: 
Create an independent piece of software which can read GNSS serial feeds.  This information can be forwarded to (or read by) other programs for GPS network failure context.


IN A WAY THAT:
- GNSS failures are human readable
- GNSS failures are timestamped and formatted in a manner for easy external correlation 
