SEND 'Please type the temperature ' TO DISPLAY
RECEIVE temperature FROM KEYBOARD
IF temperature < 18 THEN
  IF temperature > 21 THEN
   SEND'perfect'TO DISPLAY
  ELSE:
    'No! the temperature that good for sleeping is 18-21 degree'
  END IF
ELSE:
 'COLD! the temperature that good for sleeping is 18-21 degree'
END IF
