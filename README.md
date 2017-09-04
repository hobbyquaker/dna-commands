# List of DNA serial Commands

> A list of serial commands for Evolv DNA devices

## B

### B=GET 
Battery voltage

### B=GET CELL &lt;cell&gt;

Example: B=GET CELL 1

Cell Voltage

### B=GET CELLS
Get battery cell count


## C

### C=GET 

Battery Level Wh

### C=GET%
Battery Level Percent


## E

### E=GET MFR

### E=GET PRODUCT

### E=GET SERIAL

Board serial number

### E=GET VERSION

Get firmware version (eg. "201606050")

### E=GET FEATURE &lt;number&gt;

Example: E=GET FEATURE 1

Query numbers until receiving a question mark

#### Device capabilities:

* FG
* PC - Power control
* TC - Temperature control
* TC:M
* St - Long term statistics
* St:TP
* FG - Fuel gauging. Indicate the capacity can be queried with C=GET
* M - Profiles
* S
* Evolv_DNA

## F

### F=&lt;number&gt;S

Fire for specified seconds

Example: F=2.5S 


## I

Current

### I=GET

### I=GET OFFSET

### I=GET RAW

### I=GET SP

### I=GET SAMPLE 
 Sample



## M

### M=&lt;number&gt;

Set profile

### M=GET 

Get current profile


## P

Power

### P=&lt;number&gt;W

Set power

### P=GET
Get current power

### P=GET SP

Get power setpoint

### P=GET SAMPLE 
 Sample





## R

Resistance

### R=GET

Get cold resistance

### R=GET LIVE

Get current resistance

### R=GET STATIC

### R=GET RAW

### R=GET NOMINAL 

### R=GET NOMINAL TEMP 

### R=GET SAMPLE TIME 

### R=GET GROUND 
 
### R=GET TYPE 



## S

Statistics

### S=GET LASTENERGY

### S=GET LASTPOWER

### S=GET LASTTEMP

### S=GET LASTPOWER

### S=GET LASTPEAKTEMP

### S=GET PUFFS 

### S=GET DEVICE PUFFS

### S=GET TEMP PUFFS 

### S=GET DEVICE TEMP PUFFS 

### S=GET RESETS 

### S=GET ENERGY 

### S=GET MEAN ENERGY 

### S=GET SD ENERGY 

### S=GET DEVICE ENERGY 

### S=GET DEVICE MEAN ENERGY 

### S=GET DEVICE SD ENERGY 

### S=GET POWER 

### S=GET MEAN POWER 

### S=GET SD POWER 

### S=GET DEVICE POWER 

### S=GET DEVICE MEAN POWER 

### S=GET DEVICE SD POWER 

### S=GET TEMP 

### S=GET MEAN TEMP 

### S=GET SD TEMP 

### S=GET DEVICE TEMP 

### S=GET DEVICE MEAN TEMP 

### S=GET DEVICE SD TEMP 

### S=GET PEAK TEMP 

### S=GET MEAN PEAK TEMP 

### S=GET SD PEAK TEMP 

### S=GET DEVICE PEAK TEMP 

### S=GET DEVICE MEAN PEAK TEMP 

### S=GET DEVICE SD PEAK TEMP 

### S=GET TIME 

### S=GET MEAN TIME 

### S=GET SD TIME 

### S=GET DEVICE TIME 

### S=GET DEVICE MEAN TIME 

### S=GET DEVICE SD TIME 

### S=GET LAST TIME 

### S=RESET

Reset device statistics

## T

Temperature

### T=&lt;number&gt;C

### T=&lt;number&gt;F

### T=?

Turn temperature control off

### T=MONITOR

Monitoring mode - no temperature control but temperature is still measured and can be queried with T=GET

### T=GET

### T=GET COLD

### T=GET SP

### T=GET AIR 
Modeled

### T=GET BOARD 
Get board temperature

### T=GET ROOM 
Get room Temperature

### T=GET NOMINAL ROOM 
Sample


## U

USB Values

### U=GETP 

Get USB Power

### U=GETI 

Get USB current

### U=GETV 

Get USB voltage


## V

Voltage

### V=GET

### V=GET DEVICE

### V=GET OFFSET

### V=GET RAW

### V=GET SP

### V=GET SAMPLE 
Sample


## W

### W=GET


## X

### X=GET BANDGAP 
 Bandgap

### X=GET BUTTONS 
 Buttons

### X=GET METER 
 Meter

### X=GET MODE 
 Mode

### X=GET SCREEN 
 Screen

### X=GET SCRNDISC 
 Screen

### X=GET TIMER 
 Timer

