//exemplo de declaração de estrutra
struct horario agora, agora[20], *agoraPtr; 

struct horario {
  int a;
  int b;
}


//exemplo 2 de declaração de estrutura
struct horario {
  int a;
  int b;
} agora, agora[20], *agoraPtr;

//exemplo 3 inicializando uma estrutura
struct card {
  char *a;
  char *b;
} aCard;

struct card Acard = {"Tres", "Copas"}; //As estruturas podem ser inicializadas através de listas inicializadoras como os arrays

//exemplo 4 acessando algum dado da estrutra
struct card {
  char *a;
  char *b;
} aCard;

struct card Acard = {"Tres", "Copas"}; 
printf("%c", Acard.a); //coloca o nome da estrura ponto nome da variável dentro da estrutura.

//exemplo 5 acessando membros da estrutra por meio de ponteiros
struct horario {
  char *texto;
}*agoraPtr;

pritnf ("%s", agoraPtr -> texto); 
