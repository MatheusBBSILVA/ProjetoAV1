#include<iostream>
using namespace std;

struct Lista {
	int num;
	Lista *prox, *ant;
	sexo, idade e CPF
};

int leiaValor() {
	int num idade, CPF;
	cout<<"\n Valor:"<<endl;
	cin>>num;
	return num;
}
int main() {
		
	Lista *inicio = NULL, *fim=NULL, *aux = NULL;
	int op=0, numero=0, achou = 0;
	
	while(op != 8) {
		cout<<"\n\t 1-Qual sua idade?";
		cout<<"\n\t 2-Digite seu CPF";
		cout<<"\n\t 3-Qual seu sexo?";
		cout<<"\n\t 4-esta gravida?";
		cout<<"\n\t 5-consultar fila";
		cout<<"\n\t 6-Proximo atendimento";
                cout<<"\n\t 7-Esvaziar lista";
                cout<<"\n\t 8-Sair do menu";
		cout<<"\n\t Escolha Opcao:"<<endl;
		cin>>op;
		if (op==1) {
			Lista *novo = new Lista;
			novo->num = leiaValor();
			cin>>idade
			}
		}fim op=1
		if (op==2) {		
			Lista *novo = new Lista;
			novo->num = leiaValor();
			cin>> CPF
			}
		}fim op=2
		
		if(op ==3 ) { //inicio/fim
			if (num == 1) {
				cout<<"\nfeminino"<<endl;
			}else {
				while (aux != NULL){
					cout<<"\nmasculino:"<< aux->num <<endl;
					aux=aux->prox;
				}
			}
		}fim if op=3
		
		if (op==4) {
			if (inicio == NULL) {
				cout<<"\nLista Vazia"<<endl;
			}else {
				aux = fim;//*
				while (aux != NULL){
					cout<<"\n\tValor:"<< aux->num <<endl;
					aux=aux->ant;//*
				}
			}
		}fim op=4
		if (op==5)  {
			if (inicio == NULL) {
				cout<<"\nLista Vazia"<<endl;
			}else {
				aux = fim;//*
				while (aux != NULL){
					cout<<"\n\tValor:"<< aux->num <<endl;
					aux=aux->ant;//*
				}
			}
		if (op==6)
                                Pessoa saiu(Pessoa **primeiro, Pessoa **ultimo){
                               if((*primeiro)==(*ultimo)){
                                   (*ultimo) = 0;
                          }
                              Pessoa *aux = *primeiro;
                                     *primeiro = *primeiro->proximo;
                                         aux->proximo = 0;
                               return aux;
                             }
 
                 if (op==7) {
		       if (inicio == NULL) {
				cout<<"\nLista Vazia"<<endl;
			}else {
				aux = inicio;
				while (aux != NULL){
					inicio=inicio->prox;
					delete(aux);
					aux=inicio;
					
				}
			}
		}
	}fim while
	
	return 1;
}
