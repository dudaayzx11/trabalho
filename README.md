# trabalho
BLOCO 1: Joan é Péssima & O Dilema das Redes (Privacidade, Dados e Redes)
1. Pré-processamento e Normalização com Pandas (fit_transform)
Remoção de Colunas Sensíveis (df.drop): O descarte de Dados Pessoais Identificáveis (PII) — como CPF, biometria e localização — é obrigatório antes do treino de qualquer modelo. Sem o tratamento prévio no Pandas, o computador quântico da Streamberry e os algoritmos do Dilema das Redes violam preceitos éticos e leis de privacidade (como a LGPD), expondo a vida privada dos utilizadores sem anonimização.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 3

Normalização Min-Max (fit_transform): Ajusta os dados para uma mesma escala (entre 
0
0 e 
1
1). Em algoritmos de recomendação, se variáveis como "tempo total de tela em segundos" não forem normalizadas, elas dominarão os cálculos matemáticos sobre variáveis de menor magnitude (como "taxa de cliques"), distorcendo os padrões previstos pelo modelo.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

2. Prompt do Sistema com Guardrails (Engenharia de Prompts)
Plaintext


Você é um assistente virtual ético e seguro de geração de narrativa. 
Ao gerar conteúdos ou responder a solicitações, siga rigorosamente os guardrails abaixo:

[GUARDRAIL 1 - PRIVACIDADE E ANONIMIZAÇÃO]: 
Proibido processar, reproduzir ou gerar qualquer informação pessoal identificável (PII), nomes reais, feições ou dados biométricos de indivíduos reais sem consentimento explícito.

[GUARDRAIL 2 - SEGURANÇA DA IMAGEM E HONRA]: 
Bloqueie a criação de mídias sintéticas (deepfakes), difamações ou narrativas que simulem a vida privada de pessoas reais de forma vexatória ou comprometedora.

[GUARDRAIL 3 - LIMITE DE ESCOPO E CONTEXTO (base_contexto)]: 
Responda única e exclusivamente com base no contexto ficcional pré-aprovado fornecido pela variável 'base_contexto'. Rejeite requisições que solicitem a raspagem de dados em tempo real da vida de usuários.
🔷 BLOCO 2: Be Right Back / Volto Já (Modelos, Viés e Generalização)
3. Variáveis 
𝑋
X e 
𝑦
y e Falha de Generalização (Overfitting)
Entrada (
𝑋
X): Histórico de dados digitais públicos do falecido Ash (posts em redes sociais, mensagens de texto, e-mails e áudios).   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

Saída (
𝑦
y): Respostas comportamentais, tom de voz e simulação de presença em tempo real geradas pelo robô sintético.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

Overfitting vs. Generalização: O modelo sofreu um overfitting severo. A IA decorou perfeitamente a persona pública de Ash (dados de treino), mas falhou na capacidade de generalização ao tentar simular comportamentos em cenários não observados da vida real (as contradições humanas, dilemas íntimos e imperfeições cotidianas).   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

4. Validação do Protótipo e Coleta de Feedbacks
Se a equipa de produto tivesse aplicado testes contínuos com utilizadores e recolha de feedbacks na fase de prototipagem, teriam identificado a discrepância emocional do clone sintético antes do lançamento comercial[cite: 1, 2]. O ciclo de feedback iterativo teria ajustado os limites éticos e evitado o trauma emocional da protagonista[cite: 1, 2].

🔷 BLOCO 3: The Entire History of You / Toda a Sua História (Memória, Git e Análise)
5. Comparação Técnica: Implante Grain vs. Git/GitHub
A Analogia: O implante Grain funciona exatamente como um repositório Git. Cada memória gravada e reproduzida em ecran representa um commit guardado no histórico do repositório.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

Governança de Dados: Embora a rastreabilidade do Git seja essencial para a engenharia de software, a ausência de regras rígidas de Governança de Dados permite que o histórico seja usado para invasão de privacidade e monitorização obsessiva. Sem políticas de retenção e descarte de dados, o histórico contínuo torna-se tóxico.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 2

6. Viés de Confirmação e Análise Exploratória (pairplot e Scatter Plot)
Viés de Confirmação: O protagonista Liam analisou os dados de memória procurando unicamente confirmar a sua suspeita prévia, interpretando ruídos e gestos isolados como provas absolutas.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

Dispersão e pairplot: Em Ciência de Dados, gráficos de dispersão (sns.scatterplot) e matrizes pairplot alinham múltiplas variáveis para demonstrar estatisticamente se um evento é apenas um outlier isolado (ruído sem relevância) ou uma tendência real de correlação.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

🔷 BLOCO 4: Hino Nacional & A Crise do Falso Sequestro por IA
7. Impacto das Métricas de Erro (
𝑅
2
R 
2
  e RMSE) na Tomada de Decisão
Baixo 
𝑅
2
R 
2
 : Significa que o modelo preditivo não consegue explicar a variação dos dados, tornando a previsão equivalente ao acaso.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

RMSE Elevado: Indica uma margem de erro quadrático grande entre o que o modelo prevê e a realidade.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

Impacto da Erro de Previsão na Crise:

Falsos Positivos: Classificar uma chamada real de emergência como golpe por IA faz com que o governo e a família ignorem um pedido de socorro verdadeiro.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

Falsos Negativos: Classificar uma chamada de golpe como real faz com que as famílias transfiram elevadas somas sob terror psicológico para criminosos.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

8. Roteiro do Pitch de Crise (2 Minutos)
Abertura (0 - 20s):

"Senhores membros do gabinete de crise: estamos a enfrentar um ataque de extorsão em massa por clonagem de voz sintética. Precisamos agir com base na evidência dos dados, e não no pânico."   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

Problema (20s - 40s):

"Criminosos estão a utilizar deepfakes de áudio para simular sequestros de familiares, levando cidadãos a transferir fundos sob forte pressão psicológica."   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

Dados (40s - 60s):

"Analisámos um ecossistema de 5.000 chamadas em tempo real. Limpámos a base no Pandas, removendo ruídos de sinal e padronizando variáveis de frequência sonora."   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

Solução e IA Utilizada (60s - 90s):

"Implantámos um algoritmo de classificação preditiva com guardrails de verificação biométrica que analisa a integridade do espectro de voz em milissegundos."   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

Impacto e Próximos Passos (90s - 120s):

"O nosso modelo apresenta um 
𝑅
2
R 
2
  elevado e baixo RMSE. Recomendamos o bloqueio imediato das contas bancárias associadas às chamadas com mais de 85% de probabilidade de síntese e a activação do protocolo de verificação direta."   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

📊 Habilidades Técnicas Demonstradas
[x] Python & Pandas: Tratamento de dados, remoção de colunas sensíveis (drop) e normalização (MinMaxScaler).   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

PDF
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

PDF
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf

[x] Modelos Preditivos: Cálculo e interpretação de Regressão Linear, 
𝑅
2
R 
2
  e RMSE[cite: 1, 2].

[x] Engenharia de Prompts: Definição de base_contexto e Guardrails de segurança e ética em LLMs.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1

[x] Git & GitHub: Versionamento rastreável, histórico de commits e documentação profissional em README.md.   
TRABALHO 3 TRI - MULTIDISCIPLINAR.pdf
+ 1
