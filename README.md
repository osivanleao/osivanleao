- 👋 Hi, I’m @osivanleao
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
osivanleao/osivanleao is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
#include <string.h>

// Estrutura para armazenar informações de médicos
struct Medico {
    char nome[50];
    char areaAtuacao[50];
    int idade;
};

// Estrutura para armazenar informações de pacientes
struct Paciente {
    char nome[50];
    int idade;
    char planoMedico[50];
};

int main() {
    struct Medico medico;
    struct Paciente paciente;

    // Login do Funcionário
    printf("Login do Funcionário:\n");
    printf("Digite o nome do médico: ");
    scanf("%s", &medico.nome);
    printf("Digite a área de atuação: ");
    scanf("%s", &medico.areaAtuacao);
    printf("Digite a idade do médico: ");
    scanf("%d", &medico.idade);

    // Login do Paciente
    printf("ogin do Paciente:\n");
    printf("Digite o nome do paciente:\n ");
    scanf("%s", &paciente.nome);
    printf("Digite a idade do paciente:\n ");
    scanf("%d", &paciente.idade);
    printf("Digite o plano médico do paciente:\n ");
    scanf("%s", &paciente.planoMedico);

    // Exibindo informações
    printf("Informações do Médico:\n");
    printf("Nome: %s\n", medico.nome);
    printf("Área de Atuação: %s\n", medico.areaAtuacao);
    printf("Idade: %d\n", medico.idade);

    printf("Informações do Paciente:\n");
    printf("Nome: %s\n", paciente.nome);
    printf("Idade: %d\n", paciente.idade);
    printf("Plano Médico: %s\n", paciente.planoMedico);

    return 0;
}
