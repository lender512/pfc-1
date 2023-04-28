# Trabajo de Proyecto Final de Carrera I
Luis Berrospi
## Introducción
<!-- ### Contexto -->
Desde inicios de la era digital, la seguridad a sido un tema de gran importancia, en especial la autenticación de usuarios. Distintos métodos han sido utilizados a lo largo de los años, desde el uso de contraseñas, hasta el uso de huellas dactilares[[7]](#7). Sin embargo, la mayoria de estos métodos buscan garántizar la identificación del usuario solo al comienzo de la sesión, y no durante la misma. Esto es un problema, ya que si un usuario deja su sesión abierta, cualquier persona puede acceder a su información. Por ello, se ha propuesto el uso de la biometría conductual, la cual permite identificar al usuario durante toda la sesión, y no solo al comienzo de la misma[[8]](#8). Una de las aplicaciones de biometría conductual es la llamada *Keystroke Dynamics*, la cual consiste en identificar a un usuario constantemente a lo largo de uan sesion mediante los patrones y ritmo que presenta al escribir utilizando un teclado.
<!-- ### Problema -->
El pricipal problema que tiene la tecnica de Keystroke Dynamics son los algoritmos de clasificación que se utilizan para identificar a los usuarios. Se han utilizado distintas tecnicas de comparación, metricas de distancia [[1]](#1), multiples tecnicas de machine learning[[2]](#2) y *Probabilistic Neural Networks*[[3]](#3). Todas estas implementaciones dan resultados muy distintos, algunos de los mejores logran un *average false rate* de 2% mientras que otros se encuentran entre 8 y 27% [[4]](#4). Además, se a desmotrado que la preseicion puede variar segun lo que se esté escribiendo. Se ha logrado observar como la precision pasa de 79% con texto que se trasncribe a 21% con texto que se escribe libremente [[5]](#5) o como se logra identificar personas escribinendo codigo con una presicion de 98.6% [[6]](#6).
<!-- ### Objetivo -->
Este trabajo tiene como objetivo principal el de implementar dos algoritmos ya planteados de clasificación para la identificación de usuarios mediante Keystroke Dynamics. Se busca comparar los resultados obtenidos por cada uno de los algoritmos, y determinar cual de ellos es el más adecuado para este tipo de identificación. Además, se busca determinar el comportamiento de cada uno de los algoritmos con respecto al tipo de data que se le ingresa, es decir, si el algoritmo es más preciso con texto libre o con texto que se transcribe.


## Referencias
<a id="1">[1]</a> 
Zhong, Y., Deng, Y., & Jain, A. K. (2012, June). Keystroke dynamics for user authentication. In 2012 IEEE computer society conference on computer vision and pattern recognition workshops (pp. 117-123). IEEE.

<a id="1">[2]</a> 
Alsultan, A., Warwick, K., & Wei, H. (2017). Non-conventional keystroke dynamics for user authentication. Pattern Recognition Letters, 89, 53-59.


<a id="3">[3]</a>
Revett, K., Gorunescu, F., Gorunescu, M., Ene, M., Magalhaes, S., & Santos, H. (2007). A machine learning approach to keystroke dynamics based user authentication. International Journal of Electronic Security and Digital Forensics, 1(1), 55-70.

<a id="4">[4]</a> 
A. Peacock, Xian Ke and M. Wilkerson, "Typing patterns: a key to user identification," in IEEE Security & Privacy, vol. 2, no. 5, pp. 40-47, Sept.-Oct. 2004, doi: 10.1109/MSP.2004.89.

<a id="5">[5]</a> 
Monrose, F., & Rubin, A. (1997). Proceedings of the 4th ACM conference on Computer and communications security.

<a id="6">[6]</a> 
Longi, K., Leinonen, J., Nygren, H., Salmi, J., Klami, A., & Vihavainen, A. (2015, November). Identification of programmers from typing patterns. In Proceedings of the 15th Koli Calling conference on computing education research (pp. 60-67).

<a id="7">[7]</a>
A brief history of user verification & Online identity - Arengu Blog. (n.d.). https://www.arengu.com/blog/a-brief-history-of-user-verification-online-identity

<a id="8">[8]</a>
Sultana, M., Paul, P. P., & Gavrilova, M. (2015). Social behavioral biometrics: An emerging trend. International Journal of Pattern Recognition and Artificial Intelligence, 29(08), 1556013.