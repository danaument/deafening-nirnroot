# deafening-nirnroot

Design goals
1. Distributed IO controllers 
  a. standardized nomenclature for inputs and outputs
    - location, series, function
  b. modular/interchangeable/expandable
    - must be able to replace, reassign, copy and paste settings
  c. individual and group control
    - e.g. able to edit variables for individual or multiple units
  d. controller health reporting
    - connection status, activity log
2. remotely accessible web server
  a. secure access
  b. active notification via email
  c. control over parameters
  d. meta data and reporting
    - graphs, floating averages of activity, logs
3. local touch screen control via RPI
  a. UI navigation by directory
    - view and control components in individual systems
  b. view/edit scheduling
    - read/write variables
  c. realtime control for some controllers as needed
    - on/off/step
    
    
Component examples
1. Plant care
  a. Light control 
    - Output: 12v switch (LED)
    - scheduling
    - pause/resume schedule
  b. Moisture sensor/irrigation feedback loop 
    - Output: 12v switch (pump)
    - Input: 3.3-5v moisture sensor
    - key variable: moisture
  c. water reservoir fill status
    - Input: 5v float switch
2. Window blind position
  a. Light feedback loop
    - Input: photoresistor
    - Output: servomotor
    - local control on demand
    - optional control - close blinds when tv is turned on
3. 
