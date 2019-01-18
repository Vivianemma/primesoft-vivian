<body>
<h2>quadaratic equation</h2>
  <h4>steps</h4>
<p>step 1: Start
  <br>
Step 2: Declare variables a, b, c, D, x1, x2, rp and ip;<br>
Step 3: Calculate discriminant<br>
         D←b2-4ac<br>
Step 4: If D≥0<br>
              r1←(-b+√D)/2a<br>
              r2←(-b-√D)/2a <br>
              Display r1 and r2 as roots.<br>
        Else     <br>
              Calculate real part and imaginary part<br>
              rp←b/2a<br>
              ip←√(-D)/2a
              Display rp+j(ip) and rp-j(ip) as roots<br>
  Step 5: Stop </p>     
  </body>

<hr>
<hr>
<hr>
<body>
<h2>ATM/h2> <br>
  <h4>steps</h4><br>
<P>WHILE TRUE<br>
   DISPLAY "Welcome to Python Bank ATM - Cash Withdrawal"<br>
   amount = INPUT "How much would you like to withdraw today?"<br>
   IF (amount MOD 10) != 0 THEN<br>
      DISPLAY "You can only withdraw a multiple of ten!"<br>
   ELSE<br>
      IF amount<10 OR amount>200 THEN<br>
         DISPLAY "You can only withdraw between £10 and £200"<br>
      ELSE<br>
         notes20 = amount DIV 20<br>
         notes10 = (amount MOD 20) / 10<br>
         DISPLAY "Collect your money: "
         DISPLAY "    >> £20 Banknotes: " + notes20<br>
         DISPLAY "    >> £10 Banknotes: " + notes10<br>
         DISPLAY "Thank you for using this Python Bank ATM."<br>
         DISPLAY "Good Bye."<br>
      END IF<br>
   END IF<br>
  END WHILE</P><br>
  </body>
