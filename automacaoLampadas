//ARRAY DE PINOS UTILIZADOS PELOS CANAIS DO MÓDULO RELÉ (LEMBRE-SE QUE A PRIMEIRA POSIÇÃO DO VETOR É 0)
const int releChPos[16] = {2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, A0, A1, A2, A3, A4};
 
int statusCh01 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh02 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh03 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh04 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh05 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh06 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh07 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh08 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh09 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh10 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh11 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh12 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh13 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh14 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh15 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
int statusCh16 = 0; //VARIÁVEL QUE CONTROLA O ESTADO DO CANAL (LIGADO / DESLIGADO)
 
void setup(){
  Serial.begin(9600); //INICIALIZA A SERIAL
  for(int i=0; i<16; i++){ //PARA i IGUAL A 0, ENQUANTO i MENOR QUE 16, INCREMENTA i
    pinMode(releChPos[i], OUTPUT); //DEFINE TODOS OS CANAIS COMO SAÍDA
    digitalWrite(releChPos[i], HIGH); //TODOS OS CANAIS INICIAM DESLIGADOS
  }
}
 
void loop() {
 
  char c = Serial.read(); //VARIÁVEL RESPONSÁVEL POR RECEBER O CARACTERE DIGITADO NO MONITOR SERIAL
 
  /* TRATAMENTO DO CANAL 01 */
  
  if (c == 'a'){ //SE CARACTER DIGITADO FOR IGUAL A "a", FAZ
    if(statusCh01 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[0], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh01 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[0], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh01 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 01 */
 
  /* TRATAMENTO DO CANAL 02 */
  
  if (c == 'b'){ //SE CARACTER DIGITADO FOR IGUAL A "b", FAZ
    if(statusCh02 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[1], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh02 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[1], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh02 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 02 */
 
  /* TRATAMENTO DO CANAL 03 */
  
  if (c == 'c'){ //SE CARACTER DIGITADO FOR IGUAL A "c", FAZ
    if(statusCh03 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[2], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh03 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[2], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh03 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 03 */
 
  /* TRATAMENTO DO CANAL 04 */
  
  if (c == 'd'){ //SE CARACTER DIGITADO FOR IGUAL A "d", FAZ
    if(statusCh04 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[3], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh04 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[3], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh04 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 04 */
 
  /* TRATAMENTO DO CANAL 05 */
  
  if (c == 'e'){ //SE CARACTER DIGITADO FOR IGUAL A "e", FAZ
    if(statusCh05 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[4], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh05 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[4], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh05 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 05 */
 
  /* TRATAMENTO DO CANAL 06 */
  
  if (c == 'f'){ //SE CARACTER DIGITADO FOR IGUAL A "f", FAZ
    if(statusCh06 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[5], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh06 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[5], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh06 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 06 */
 
  /* TRATAMENTO DO CANAL 07 */
  
  if (c == 'g'){ //SE CARACTER DIGITADO FOR IGUAL A "g", FAZ
    if(statusCh07 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[6], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh07 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[6], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh07 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 07 */
 
  /* TRATAMENTO DO CANAL 08 */
  
  if (c == 'h'){ //SE CARACTER DIGITADO FOR IGUAL A "h", FAZ
    if(statusCh08 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[7], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh08 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[7], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh08 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 08 */
 
  /* TRATAMENTO DO CANAL 09 */
  
  if (c == 'i'){ //SE CARACTER DIGITADO FOR IGUAL A "i", FAZ
    if(statusCh09 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[8], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh09 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[8], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh09 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 09 */
 
  /* TRATAMENTO DO CANAL 10 */
  
  if (c == 'j'){ //SE CARACTER DIGITADO FOR IGUAL A "j", FAZ
    if(statusCh10 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[9], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh10 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[9], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh10 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 10 */
 
  /* TRATAMENTO DO CANAL 11 */
  
  if (c == 'k'){ //SE CARACTER DIGITADO FOR IGUAL A "k", FAZ
    if(statusCh11 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[10], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh11 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[10], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh11 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 11 */
 
  /* TRATAMENTO DO CANAL 12 */
  
  if (c == 'l'){ //SE CARACTER DIGITADO FOR IGUAL A "l", FAZ
    if(statusCh12 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[11], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh12 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[11], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh12 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 12*/
 
  /* TRATAMENTO DO CANAL 13 */
  
  if (c == 'm'){ //SE CARACTER DIGITADO FOR IGUAL A "m", FAZ
    if(statusCh13 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[12], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh13 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[12], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh13 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 13 */
 
  /* TRATAMENTO DO CANAL 14 */
  
  if (c == 'n'){ //SE CARACTER DIGITADO FOR IGUAL A "n", FAZ
    if(statusCh14 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[13], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh14 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[13], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh14 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 14 */
 
  /* TRATAMENTO DO CANAL 15 */
  
  if (c == 'o'){ //SE CARACTER DIGITADO FOR IGUAL A "o", FAZ
    if(statusCh15 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[14], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh15 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[14], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh15 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 15 */
 
  /* TRATAMENTO DO CANAL 16 */
  
  if (c == 'p'){ //SE CARACTER DIGITADO FOR IGUAL A "p", FAZ
    if(statusCh16 == 0){ //SE VARIÁVEL FOR IGUAL A 0, FAZ
      digitalWrite(releChPos[15], LOW); //RELÉ ACIONADO (LIGADO)
      statusCh16 = 1; //VARIÁVEL RECEBE O VALOR 1
    }else{ //SENÃO, FAZ
      digitalWrite(releChPos[15], HIGH); //RELÉ ACIONADO (DESLIGADO)
      statusCh16 = 0; //VARIÁVEL RECEBE O VALOR 0
    }
  }
 
  /* TRATAMENTO DO CANAL 16 */
}
