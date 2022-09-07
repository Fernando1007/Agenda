# Agenda
Aquí pueden ver mis apuntes 
apuntes de funciones para cadenas de caracteres 

´´´´

Sub actividad()
    
    For y = 2 To 21
        nom = nombres.Cells(y, 1)
        ult = Len(nom) - 1
        nombres.Cells(y, 2) = Mid(nom, ult, 2)
        
    Next y
    
End Sub

´´´´