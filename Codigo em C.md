// Estoque lanchonete
#includ <studio.h>
int main() {

    float precos[10];       // preço de cada salgado
    int quantidades[10];    // quantidade de cada salgado
    int total = 0;          // quantos salgados já cadastrei
    int opcao = -1;
    int i;
    int posicao;
    float soma, media, valorTotal;
    int estoqueBaixo;       // 0 = não, 1 = sim (booleano)

    // zera os vetores
    i = 0;
    while (i < 10) {
        precos[i] = 0;
        quantidades[i] = 0;
        i = i + 1;
    }

    do {

