begin
    numeric nNum1, nNum2, nNum3
    display "ENTER THE FIRST NUMBER "
    accept nNum1
    display "ENTER THE SECOND NUMBER "
    accept nNum2
    display "ENTER THE THIRD NUMBER "
    accept nNum3
    if(nNum1<nNum2)
    begin
        if(nNum1<nNum3)
        begin
            display "SMALLEST ONE : " nNum1
        end
        else
        begin
            display "SMALLEST ONE : " nNum3
        end
    end
    else
    if(nNum2<nNum3)
    begin
        display "SMALLEST ONE : " nNum2
    end
    else
    begin
        display "SMALLEST ONE : " nNum3
    end
end
