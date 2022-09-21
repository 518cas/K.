SEND "Enter height" TO DISPLAY
RECEIVE Height FROM KEYBOARD
SEND "Enter weight" TO DISPLAY
RECEIVE Weight FROM KEYBOARD
SET BMI TO (Weight/Height^2)
IF BMI <18.5
  SEND "Underweight" TO DISPLAY
ELSE
  IF BMI <=24.9
    SEND "Normal weight" TO DISPLAY
  ELSE
    IF BMI >=25 
      SEND "Overweight" TO DISPLAY
    END IF
  END IF
END IF
