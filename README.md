# Ponte Retificadora⚡
Uma ponte retificadora é um circuito eletrônico usado para converter corrente alternada (CA) em corrente contínua (CC). Ela é formada por quatro diodos dispostos em configuração de ponte, 
permitindo que tanto o semiciclo positivo quanto o negativo da onda senoidal sejam aproveitados. Isso resulta em uma saída pulsante, mas sempre no mesmo sentido, que pode ser suavizada com 
capacitores ou outros filtros.

No contexto prático, é um dos blocos mais básicos de fontes de alimentação: a rede elétrica (AC) passa pela ponte retificadora, vira corrente contínua 
(DC), e depois pode ser regulada para alimentar circuitos eletrônicos.


## Funcionamento

<img width="582" height="367" alt="image" src="https://github.com/user-attachments/assets/f7b16b49-2d59-4b0f-960e-7f1183ae9bbd" />

Aqui está o que acontece no circuito:

* Azul (Entrada AC): a tensão senoidal normal da rede, positiva e negativa.

* Vermelho (Saída da Ponte): a ponte de diodos inverte os semiciclos negativos, deixando a saída sempre positiva, mas ainda com ondulação.

* Verde (Saída com Capacitor): o capacitor carrega nos picos e descarrega devagar, “nivelando” a tensão. O resultado é uma DC quase contínua.

Na prática, quanto maior for o capacitor (em µF) e menor a carga consumindo corrente, mais lisa fica essa linha verde.


## Materiais🛠️

<img width="394" height="318" alt="image" src="https://github.com/user-attachments/assets/716d2cec-64c4-47e5-be13-515f38d83e85" />

* Quatro(4) Borns banana

* Quatro(4) Diodos M4007

* Capacitor de 25V e 1000µF

  OBS: Também é necessário fios de cobre e ferramentas como chaves philips.

  ## Circuito🔌

  <img width="424" height="473" alt="image" src="https://github.com/user-attachments/assets/cd0a46a0-c387-4e7d-ab67-01b89adf9736" />

**Lembrando** que quando for usar este circuito não o ligue em uma tensão de 127V ou 220V como está no diagrama.

### Circuito Montado na Placa

**Vista superior**

<img width="384" height="512" alt="image" src="https://github.com/user-attachments/assets/a281852b-d816-4507-9ff4-ea4144ac1bf0" />

___________________________________________________________________________________________________________________________________________________________________________________

**Vista inferior**

<img width="384" height="512" alt="image" src="https://github.com/user-attachments/assets/d4d8a5fa-5bf7-44b9-88da-bab4d4ad2477" />


Obs: está faltando o capacitor nas fotos.

## Resultados❗


https://github.com/user-attachments/assets/fdcfdbf0-0c8a-4c5a-9844-8bef499734a4

_____________________________________________________________________________________________________________________________________________________________________________________________________________________

<img width="50%" alt="Imagem do WhatsApp de 2025-10-03 à(s) 09 32 58_2a1dab3c" src="https://github.com/user-attachments/assets/d895d2e6-40ac-4ae7-a1ac-bc237670ee15" />

Forma de onda sem retificar.

__________________________________________________________________________________________________________________________________________________________________________________________________________________

<img width="50%" alt="Imagem do WhatsApp de 2025-10-03 à(s) 09 33 01_cddcb55d" src="https://github.com/user-attachments/assets/71436ee0-48e1-4e68-89dd-23112ec1fc70" />

  Forma de onda retificada

  _________________________________________________________________________________________________________________________________________________________________________________________________________________________

<img width="66%" alt="Imagem do WhatsApp de 2025-10-04 à(s) 15 46 08_1555eeb6" src="https://github.com/user-attachments/assets/c9791672-4344-4ac6-8da5-9dad5402cd3f" />

Retificador em um suporte, já conectado nos borns
