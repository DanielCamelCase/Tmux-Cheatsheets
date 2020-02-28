# Tmux-Cheatsheets
Atajos de teclado para usar la consola de tmux en linux 

INSTALL TMUX - SEGUIR LOS 4 PASOS 
https://github.com/gpakosz/.tmux

; = Interpretar como "despues" 

USAR TMUX :

CONTROL + B ; m                  = MODO MOUSE ACTIVADO/DESCATIVADO

CONTROL + D                        = ELIMINAR PANEL
CONTROL + B ; X                   = ELIMINAR PANEL PIDE CONFIRMACION 

CONTROL + B + SHIFT + 2  = CREAMOS UN PANEL ABAJO
CONTROL + B + SHIFT + 5  = CREAMOS UN PANEL LATERAL 
CONTROL + B + ,                  = RENOMBRAMOS PANEL
CONTROL + B + FLECHAS    = AJUSTA TAMAÑO DEL PANEL 
CONTROL +B ; Z                    = ZOOM DE UN PANEL LO MISMO PARA VOLVER A COMO ESTABA




CONTROL + B ; FLECHAS     = CAMBIAMOS EL PANEL EN USO (NOS MOVEMOS ENTRE PANELES)
CONTROL + B ;  ESPACIO     = INVERTIR PANELES ABAJO HACIA ARRIBA Y VICEVERSA
CONTROL + B ;  ALT + }      = INTERCAMBIA EL PANEL DE AL LADO POR EL ACTUAL 



CONTROL + B ; CONTROL + O = ROTA PANELES SENTIDO CONTRARIO AL RELOJ
CONTROL + B ;  O                      = ROTA PANELES SENTIDO AGUJAS DEL RELOJ

CONTROL + B + ,  (coma)         = RENOMBRAMOS PANEL


PODEMOS ABRIR VENTANAS Y DENTRO DIFERENTES PESTAÑAS 

$ tmux new -s nombre                = Crea una nueva sesion con X nombre
$ tmux kill-session -t nombre     = Cierra la sesion con X nombre 

CONTROL + B ; S                       = VEMOS LAS SESIONES ABIERTAS
CONTROL + B ; CONTROL + C = ABRIR UNA NUEVA PESTAÑA 
CONTROL + B ; 1 o 2 o 3           = NOS MUEVE A LA PESTAÑA CORRESPONDIENTE 
