SEND 'Please enter the temperature' TO DISPLAY
RECEIVE temp FROM KEYBOARD
IF temp < 18°c THEN
  SEND 'Cold, the perfect temperature for sleep is 18-21 degrees.' TO DISPLAY
ELSE
  IF temp > 21°c THEN
    SEND 'Perfect!' TO DISPLAY
  ELSE
    SEND 'No!, the perfect temperature for sleep is 18-21 degrees.' TO DISPLAY
  END IF
END IF
