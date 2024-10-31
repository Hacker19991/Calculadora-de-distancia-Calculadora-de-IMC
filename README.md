# **AppProva (Calculadora de distancia / Calculadora de IMC)**

> Um aplicativo Android desenvolvido para o usuário calcular a distancia percorrida a pé e o a massa corporica do seu IMC.

## Descrição
O **AppProva** permite ao usuário calcular a distancia percorrida a pé com a adição de porcentagem de corrida e calcular sua massa corporica atual.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Calculadora-de-distancia-Calculadora-de-IMC
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal onde ocorrerra os calculos de distância
   │   │   │   ├── IMCActivity.java # Atividade principal onde ocorrera os calculos de IMC
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela onde o usuário podera fazer o calculo de distância
   │   │   │   │   ├── activity_imc.xml # Layout da tela onde o usuário podera calcular o seu IMC
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela C/Distância

![image](https://github.com/user-attachments/assets/2152846a-e58b-4c6e-af10-05411f72b75e)

Uma tela simples, 1 EditText para ser colocado a quantidade de passos que o usuário procediu, um RadioGroup com três RadioButton para passos curtos, médios e rapido, um CheckBox para caso o usário tiver corrido nesses seus ultimos passos e dois botões para processar a conta e o outro para ir a calculadora IMC, e no final o TextView para mostrar o resultado final do calculo com as informações insiridas de maneira certa e como titulo principal da tela.

> Tela C/IMC

![image](https://github.com/user-attachments/assets/a6388117-fef0-4c8c-a3ff-baf609a7a255)

Uma tela simples, 2 EditText para ser colocado o peso atual e a altura atual do usuário, dois botões para processar a conta e o outro para voltar a calculadora de distancia, e no final o TextView para mostrar o resultado final do calculo com as informações insiridas de maneira certa e como titulo principal da tela.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
