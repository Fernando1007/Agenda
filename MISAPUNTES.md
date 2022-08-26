# apuntes
hoy aprendimos mas usar github desktop 
"a como subir desde un clone el proyecto

Sub sumar()
    a = Int(InputBox("su ingreso es de"))
   If a > 0 And a < 1000 Then
      MsgBox " no pagar impuesto"
   Else
     If a > 1.001 And a < 100000 Then
        vp = a * 0.05
        MsgBox " el valor a pagar es: " & vp
     Else
      If a > 10.001 And a < 100000 Then
        vp = a * 0.1
        
        MsgBox " el valor a pagar es: " & vp
      Else
       If a > 100.001 And a < 1000000 Then
        vp = a * 0.15
        
        MsgBox " el valor a pagar es: " & vp
       Else
         If a > 1000001 And a < 10000000 Then
            vp = a * 0.2
            MsgBox " el valor a pagar es: " & vp
         Else
            If a > 10000001 Then
                vp = a * 0.25
                MsgBox " el valor a pagar es: " & vp
            Else
               MsgBox " no se puede"
               
            End If
         End If
       End If
      End If
     End If
   End If
   
     

      
     
     
      


End Sub