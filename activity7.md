SET number TO 3
SEND 'Enter the number between 1-10' TO DISPLAY
RECIEVE number FROM KEYBOARD
   IF number >10 THEN 
     SEND 'Error' TO DISPLAY
   ELSE 
     IF number < 1 THEN
       SEND 'Error' TO DISPLAY
     ELSE
       IF number > number THEN
         SEND 'Number too high' TO DISPLAY
       ELSE
         IF number < number THEN
           SEND 'Number too low' TO DISPLAY
         ELSE
           IF number = number THEN
             SEND 'Correct answer' TO DISPLAY
           END IF
          END IF
        END IF
     END IF
   END IF
