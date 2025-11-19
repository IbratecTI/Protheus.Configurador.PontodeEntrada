# Protheus.Configurador.PontodeEntrada
📝 Detalhes da Funcionalidade
ESPNOME.PRW
Objetivo: Personalizar o nome do módulo 97 (Módulo Específico/Customizado) na interface do Protheus. Por padrão, este módulo pode aparecer como "SIGAESP" ou "Específico". Esta rotina altera essa nomenclatura para identificar o departamento ou finalidade específica, neste caso, "T.I. - Configurador".

Fluxo de Execução:

Ao carregar o menu principal ou listas de módulos, o Protheus verifica a existência da função ESPNOME.

A função retorna uma string simples: "T.I. - Configurador".

O sistema exibe este texto como o título do módulo na interface do usuário.

⚙️ Requisitos Técnicos
Módulo: SIGAESP (Módulo 97).

Chamada: Esta é uma User Function que atua como um Ponto de Entrada implícito para a nomenclatura do módulo.

🚀 Instalação e Configuração
Compilação: Compile o arquivo ESPNOME.PRW no seu ambiente (RPO).

Verificação:

Faça login no SmartClient.

Observe a lista de módulos disponíveis.

O módulo 97 deverá apresentar o nome "T.I. - Configurador" em vez do padrão "Livros Fiscais" (caso esteja substituindo) ou "Específico".

⚠️ Observações Importantes

Simplicidade: O código apenas retorna uma string de texto e não executa processamentos de banco de dados ou interfaces.

Impacto Visual: A mudança é puramente visual para organização do menu principal, não afetando a lógica interna dos programas do módulo.