# Proyecto 
#Bienvenida
print("Bienvenidos a la taqueria virtual de Robin")
#Opciones de menú
print("Presione el número 1 si quiere ver el menu de refrescos")
print("Presione el número 2 si quiere ver el menú de tacos")


#Estabrecemos las funciones
def cuenta_refrescos(refresco):
    if refresco == 1 or refresco == 2 or refresco == 3:
        si_refresco = 25
        return si_refresco
    elif refresco == 4 or refresco == 5 or refresco == 6 or refresco == 7:
        si_refresco = 30
        return si_refresco
    
    
def cuenta_tacos(tacos):
    if tacos == 1:
        si_taco = 20
        return si_taco
    if tacos == 2:
        si_taco = 25
        return si_taco


#Selección de menú
menu=int(input("Selecciona un menú: "))


#Inicio del programa
if menu == 1:
        print("¿Qué desea ordenar? Favor de teclear el número correspondiente al producto")
        print("Coca-Cola = 1")
        print("Boing de mango = 2")
        print("Boing de güayaba = 3")
        print("Cerveza modelo especial = 4")
        print("Cerveza modelo obscura = 5")
        print("Cerveza victoria = 6")
        print("Cerveza corona = 7")
        refresco_o_cerveza=int(input())
        if refresco_o_cerveza == 1:
            print("Usted ordeno Cocacola")
            cocacola = 1
            cuenta_refrescos(cocacola)
            print("La cuenta total es: " + str(cuenta_refrescos(cocacola)))
        elif refresco_o_cerveza == 2:
            print("Usted ordeno Boing de mango")
            boingm = 2
            cuenta_refrescos(boingm)
            print("La cuenta total es: " + str(cuenta_refrescos(boingm)))
        elif refresco_o_cerveza == 3:
            print("Usted ordeno Boing de güayaba")
            boingg = 3
            cuenta_refrescos(boingg)
            print("La cuenta total es: " + str(cuenta_refrescos(boingg)))
        elif refresco_o_cerveza == 4:
            print("Usted ordeno Cerveza modelo especial")
            modeloe = 4
            cuenta_refrescos(modeloe)
            print("La cuenta total es: " + str(cuenta_refrescos(modeloe)))
        elif refresco_o_cerveza == 5:
            print("Usted ordeno Cerveza modelo obscura")
            modeloo = 5
            cuenta_refrescos(modeloo)
            print("La cuenta total es: " + str(cuenta_refrescos(modeloo)))
        elif refresco_o_cerveza == 6:
            print("Usted ordeno Cerveza victoria")
            victoria = 6
            cuenta_refrescos(victoria)
            print("La cuenta total es: " + str(cuenta_refrescos(victoria)))
        elif refresco_o_cerveza == 7:
            print("Usted ordeno Cerveza corona")
            corona = 7
            cuenta_refrescos(corona)
            print("La cuenta total es: " + str(cuenta_refrescos(corona)))
        else:
            print("Este producto no existe")
        
        
elif menu == 2:
        print("¿Qué desea ordenar? Favor de teclear el número correspondiente al producto")
        print("Tacos al pastor = 1")
        print("Tacos de asada = 2")
        tipo_de_taco=int(input())
        if tipo_de_taco == 1:
            print("Usted escogio un taco al pastor")
            tacop = 1
            cuenta_tacos(tacop)
            print("La cuenta total es: " + str(cuenta_tacos(tacop)))
        elif tipo_de_taco == 2:
            print("Usted escogio un taco de asada")
            tacoa = 2
            cuenta_tacos(tacoa)
            print("La cuenta total es: " + str(cuenta_tacos(tacoa)))
            
            
else:
    print("No es un menú valido")
    
print("Gracias por comprar en la Taqueria virtual de Robin")
