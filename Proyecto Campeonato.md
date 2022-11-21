import random
Equipos=['Brasil','Argentina','Colombia','Chile','Ecuador','Peru']
Brasil={1:'Gomez', 10:'Triana', 15:'Fernandez', 2:'Palacio', 8: 'Miranda',7: 'Montero',9: 'Benito',3: 'Pinzon',4:'Rueda', 11: 'Hernandez', 5:'Vasco', 12:'Alfonso', 19:'Alvarez', 17:'Batanero', 16: 'Montaño', 23:'Rodriguez', 18:'Vargas'}
Argentina={1:'Ramirez',10: 'Messi',29: 'Gutierrez',24: 'Rodriguez',4: 'Matiz',5: 'Bernal', 12:'Escobar', 25:'Valderrama',45:'Velez', 11:'Lozano',21:'Atehortua',90: 'Torres',16: 'Lopez',9: 'Pedraza', 14:'Bonilla', 56:'Triviño',44:'Sacristan' }
Colombia={1:'Rodriguez',23: 'Ospina',11: 'Diaz',9: 'Sanchez',7: 'Cuadrado',10:'Uribe',16: 'Mina', 21:'Triana',19:'Fernandez', 22:'Ramirez', 34:'Matiz',4: 'Miranda', 3:'Escobar', 17:'Valderrama', 2:'cubidez',6:'Ortega', 56:'Olaya'}
Chile={1:'Iniesta', 33:'Hernandez',7: 'Busquest', 9:'Ramos',11: 'Ronaldo',10: 'Alexis',21: 'Vidal', 19:'Vargas',22:'Bravo',66:'Valdivia', 101:'Jarrasco', 49:'Alvarez', 2:'Estupiñan',5: 'Cardona', 17:'Musleda', 77:'Garrincha',18:'Khan'}
Ecuador={ 1:'Llanos',15: 'Lloris',6: 'Kante',7: 'Pogba',9: 'Mbappe',11: 'Kounde', 10:'Pique', 33:'Torres',19: 'Acosta',43:'Carrion',15: 'Bernal', 88:'Di Maria', 23:'Haland', 54:'Cortes', 8:'Carpintero', 3:'Rengifo',41:'Virguez'}
Peru={1:'Miranda',7: 'Uribe',9: 'Quijano',11: 'Valencia',10: 'Zarama',19: 'Acero',21: 'Bonilla',8: 'Olaya',66:'Ramos',22:'Rosales',33: 'Sanchez', 17:'Gonzalez',18: 'Dybala',5: 'Ferrar',2: 'Matiz', 4:'Triana', 77:'Montero'}
Posiciones=['Portero', 'Defensa', 'Defensa', 'Defensa', 'Defensa', 'Delantero', 'Delantero','Delantero', 'Mediocampista', 'Mediocampista', 'Mediocampista', 'Suplentes','Suplentes', 'Suplentes','Suplentes', 'Suplentes', 'Suplentes']
print (Equipos)
print('----------------------------------------------------------')
#Jugadores de Brasil
for Numeros in Brasil:
  print(f'Jugador de Brasil:', Numeros,':',Brasil[Numeros])
print()
#Jugadores de Argentina
for Numeros in Argentina:
  print(f'Jugador de Argentina:',Numeros,':',Argentina[Numeros])
print()
#Jugadores de Colombia
for Numeros in Colombia:
  print(f'Jugador de Colombia:',Numeros,':',Colombia[Numeros])
print()
#Jugadores de Chile
for Numeros in Chile:
  print(f'Jugador de Chile:',Numeros,':',Chile[Numeros])
print()
#Jugadores de Ecuador
for Numeros in Ecuador:
  print(f'Jugador de Ecuador:',Numeros,':',Ecuador[Numeros])
print()
#Jugadores de Peru
for Numeros in Peru:
  print(f'Jugadores de Peru:',Numeros,':',Peru[Numeros])
print()
print('----------------------------------------------------------')
#Posiciones de Jugadores de Brasil
for Numeros,Posicion in enumerate (Brasil):
  print(f'Posición de jugador de Brasil:',Posicion,':',Posiciones[Numeros])
print()
#Posiciones de Jugadores de Argentina
for Numeros,Posicion in enumerate (Argentina):
  print(f'Posición de jugador de Argentina:',Posicion,':',Posiciones[Numeros])
print()
#Posiciones de Jugadores de Colombia
for Numeros,Posicion in enumerate (Colombia):
  print(f'Posición de jugador de Colombia:',Posicion,':',Posiciones[Numeros])
print()
#Posiciones de Jugadores de Chile
for Numeros,Posicion in enumerate (Chile):
  print(f'Posición de jugador de Chile:',Posicion,':',Posiciones[Numeros])
print()
#Posiciones de Jugadores de Ecuador
for Numeros,Posicion in enumerate (Ecuador):
  print(f'Posición de jugador de Ecuador:',Posicion,':',Posiciones[Numeros])
print()
#Posiciones de Jugadores de Peru
for Numeros,Posicion in enumerate (Peru):
  print(f'Posición de jugador de Peru:',Posicion,':',Posiciones[Numeros])
print()
print('----------------------------------------------------------')
#Añadir un jugador de Brasil
Cambio={27:'Gonzalez'}
Brasil.update(Cambio)
Brasil.pop(3)
for Numeros,Jugador in Brasil.items():
  print(f'Jugador Nueva convocatoria de Brasil',Numeros,':',Jugador)
print()
#Añadir un jugador de Argentina
Cambio1={90:'Palacio'}
Argentina.update(Cambio1)
#Argentina.pop(3)
for Numeros,Jugador in Argentina.items():
  print(f'Jugador Nueva convocatoria de Argentina',Numeros,':',Jugador)
print()
#Añadir un jugador de Colombia
Cambio2={105:'Jones'}
Colombia.update(Cambio2)
Colombia.pop(11)
for Numeros,Jugador in Colombia.items():
  print(f'Jugador Nueva convocatoria de Colombia',Numeros,':',Jugador)
print()
#Añadir un jugador de Chile
Cambio3={96:'Miranda'}
Chile.update(Cambio3)
#Chile.pop(8)
for Numeros,Jugador in Chile.items():
  print(f'Jugador Nueva convocatoria de Chile',Numeros,':',Jugador)
print()
#Añadir un jugador de Ecuador
Cambio4={89:'Serrato'}
Ecuador.update(Cambio4)
#Ecuador.pop(5)
for Numeros,Jugador in Ecuador.items():
  print(f'Jugador Nueva convocatoria de Ecuador',Numeros,':',Jugador)
print()
#Añadir un jugador de Peru
Cambio5={48:'Perez'}
Peru.update(Cambio5)
Peru.pop(11)
for Numeros,Jugador in Peru.items():
  print(f'Jugador Nueva convocatoria de Peru',Numeros,':',Jugador)
print()
print('----------------------------------------------------------')
#Capitanes de cada equipo
print('Capitan de Brasil es:')
print (Brasil[1])
print('Capitan de Argentina es:')
print (Argentina[10])
print('Capitan de Colombia es:')
print (Colombia[10])
print('Capitan de Chile es:')
print (Chile[7])
print('Capitan de Ecuador es:')
print (Ecuador[10])
print('Capitan de Peru es:')
print (Peru[10])
print('----------------------------------------------------------')
#Lista de partidos y resultados
def realizar_partido():
    goles1 = random.choice(range(0,5))
    goles2 = random.choice(range(0,5))
    if goles1 > goles2:
        puntos1 = 3
        puntos2 = 0
    elif goles1 < goles2:
        puntos1 = 0
        puntos2 = 3
    else:
        puntos1 = 1
        puntos2 = 1
     
    return [(puntos1, goles1, goles2), (puntos2, goles2, goles1)]

def jugar_calendario(partidos):
    resultados = {}
    for ronda, matches in partidos.items():
        print("========== {} ==========".format(ronda))
        for match in matches:
            grupo = match[0]
            pais1 = match[1]
            pais2 = match[2]
            r = realizar_partido()
            print("{} -> {} {} - {} {}".format(grupo, pais1, r[0][1], r[1][1], pais2))
            if pais1 not in resultados:
                resultados[pais1] = [r[0]]
                resultados[pais2] = [r[1]]
            else:
                resultados[pais1].append(r[0])
                resultados[pais2].append(r[1])
        print()
    return resultados

def crear_calendario(equipos):
    todos_partidos = {}
    for grupo, paises in equipos.items():
        
        ronda1 = [(grupo, paises[0], paises[1]), (grupo, paises[2], paises[3])]
        ronda2 = [(grupo, paises[1], paises[2]), (grupo, paises[3], paises[0])]
        ronda3 = [(grupo, paises[0], paises[2]), (grupo, paises[3], paises[1])]
        
        if 'Ronda 1' not in todos_partidos:
            
            todos_partidos['Ronda 1'] = [ronda1[0], ronda1[1]]
            todos_partidos['Ronda 2'] = [ronda2[0], ronda2[1]]
            todos_partidos['Ronda 3'] = [ronda3[0], ronda3[1]]
        else:
            
            todos_partidos['Ronda 1'].extend([ronda1[0], ronda1[1]])
            todos_partidos['Ronda 2'].extend([ronda2[0], ronda2[1]])
            todos_partidos['Ronda 3'].extend([ronda3[0], ronda3[1]])
    return todos_partidos

#Tabulación de los resultados de cada equipo
equipos = {\
'GRUPO A':['Argentina', 'Chile', 'Colombia', 'Equipo invitado'], \
'GRUPO B':['Brasil', 'Peru', 'Ecuador', 'Equipo inivitado']}

calendario = crear_calendario(equipos)
tabla_resultados = jugar_calendario(calendario)
#imprimir los resultados de goles por pais
print("========== RESULTADOS ==========")

for pais, resultados in tabla_resultados.items():
    pais = pais.ljust(12, ' ') 
    puntos = 0
    GF = 0
    GC = 0
    for values in resultados:
        puntos += values[0]
        GF += values[1]
        GC += values[2]
    print("{} -> PTS: {} | GF: {} | GC: {}".format(pais, puntos, GF, GC))
