# Mapas de Habilidades

## Sobre o Projeto
Este repositório apresenta a aplicação prática do **Mapa de Habilidades** desenvolvido a partir do roteiro disponibilizado pela DIO.  
O objetivo é conduzir uma análise estruturada de competências, identificar oportunidades de mercado e propor caminhos de monetização.

---

## Estrutura do Prompt

```
// Identificador de Habilidades
// Uso de cores ANSI para destacar etapas e perguntas

const colors = {
  reset: "\x1b[0m",
  bold: "\x1b[1m",
  cyan: "\x1b[36m",
  yellow: "\x1b[33m",
  green: "\x1b[32m",
  magenta: "\x1b[35m",
};

function intro() {
  console.log(
    `${colors.cyan}${colors.bold}Olá, eu sou seu identificador de habilidades que podem ser remuneradas e estou aqui para te fazer perguntas sobre suas habilidades.${colors.reset}`
  );
  console.log("Me diga como eu posso te ajudar?");
}

// ---------------- ETAPA 1 ----------------
function etapa1() {
  console.log(`\n${colors.yellow}${colors.bold}ETAPA 1 — INVENTÁRIO DE HABILIDADES${colors.reset}`);

  console.log(`\n${colors.green}Habilidades Técnicas${colors.reset}`);
  console.log("• Quais ferramentas você domina atualmente?");
  console.log("• Você utiliza planilhas, edição de vídeo, programação, automações ou outras ferramentas técnicas?");
  console.log("• Qual é seu nível em cada uma delas (básico, intermediário ou avançado)?");
  console.log("• Já resolveu algum problema técnico para alguém? Qual foi o resultado?");
  console.log("• As pessoas costumam solicitar sua ajuda técnica? Em qual contexto?");

  console.log(`\n${colors.green}Habilidades Comportamentais${colors.reset}`);
  console.log("• Você se considera organizado? Como isso se manifesta na prática?");
  console.log("• Já liderou projetos ou equipes?");
  console.log("• Como você descreveria sua comunicação (técnica, didática, estratégica)?");
  console.log("• Como lida com pressão ou prazos curtos?");
  console.log("• Costuma resolver problemas de outras pessoas?");
  console.log("• Já ensinou ou orientou alguém, mesmo informalmente?");

  console.log(`\n${colors.green}Habilidades Criativas${colors.reset}`);
  console.log("• Você já produziu conteúdo (textos, vídeos, apresentações, posts)?");
  console.log("• Gosta de escrever ou estruturar ideias?");
  console.log("• Já criou processos ou organizou algo que estava desestruturado?");
  console.log("• Consegue simplificar assuntos complexos?");
  console.log("• Já recebeu reconhecimento por alguma habilidade criativa específica?");

  console.log(`\n${colors.magenta}Encerramento da Etapa 1:${colors.reset}`);
  console.log("Resumo Estratégico do Perfil: principais forças, diferenciais competitivos e combinações de habilidades com potencial de monetização.");
  console.log("Agora vamos cruzar isso com o mercado.");
}

// ---------------- ETAPA 2 ----------------
function etapa2() {
  console.log(`\n${colors.yellow}${colors.bold}ETAPA 2 — CRUZAMENTO COM NECESSIDADE DE MERCADO${colors.reset}`);

  console.log("• Quem estaria disposto a pagar por essa habilidade?");
  console.log("• Que problema real ela resolve?");
  console.log("• Existe demanda atual por essa solução?");
  console.log("• Que tipo de cliente se beneficiaria mais?");
  console.log("• Pequenas empresas buscariam essa solução?");
  console.log("• É possível transformar isso em serviço?");
  console.log("• Poderia se tornar um produto?");
  console.log("• Existe um nicho específico onde essa habilidade é mais valorizada?");
  console.log("• Quais serviços estão em alta nessa área?");
  console.log("• Como essa habilidade poderia gerar renda prática nos próximos 30 dias?");

  console.log(`\n${colors.magenta}Encerramento da Etapa 2:${colors.reset}`);
  console.log("Mapa de Oportunidades Potenciais.");
  console.log("Agora vamos estruturar os caminhos de monetização.");
}

// ---------------- ETAPA 3 ----------------
function etapa3() {
  console.log(`\n${colors.yellow}${colors.bold}ETAPA 3 — CAMINHOS DE MONETIZAÇÃO${colors.reset}`);

  console.log("Checklist reflexivo:");
  console.log("1 - Você poderia oferecer isso como serviço em plataformas?");
  console.log("2 - Poderia criar conteúdo gratuito para atrair clientes?");
  console.log("3 - Montar um portfólio simples para validação?");
  console.log("4 - Fazer parcerias locais ou estratégicas?");
  console.log("5 - Dar aulas, consultorias ou mentorias?");

  console.log("\nPerguntas:");
  console.log("• Qual faz mais sentido para seu perfil?");
  console.log("• Qual parece mais simples para iniciar?");
  console.log("• Qual pode gerar renda mais rapidamente?");
  console.log("• Qual possui maior potencial de escala?");

  console.log(`\n${colors.magenta}Encerramento Final:${colors.reset}`);
  console.log("• Um caminho recomendado para início");
  console.log("• Uma ação prática a ser executada em até 7 dias");
  console.log("• Uma ação específica para validar o mercado");
}

// ---------------- EXECUÇÃO ----------------
intro();
etapa1();
etapa2();
etapa3();

```

### Etapa 1 — Inventário de Habilidades
Nesta etapa são levantadas informações sobre:
- **Habilidades Técnicas**: ferramentas dominadas, nível de proficiência, experiências práticas e apoio técnico prestado.  
- **Habilidades Comportamentais**: organização, liderança, comunicação, resiliência e colaboração.  
- **Habilidades Criativas**: produção de conteúdo, escrita, organização de processos, simplificação de assuntos complexos e reconhecimento criativo.  

Encerramento: elaboração de um **Resumo Estratégico do Perfil**, destacando forças, diferenciais competitivos e combinações de habilidades com potencial de monetização.

---

### Etapa 2 — Cruzamento com Necessidade de Mercado
Nesta fase, as habilidades identificadas são confrontadas com demandas reais do mercado.  
As perguntas orientam a análise sobre:
- Quem estaria disposto a pagar por determinada habilidade.  
- Problemas reais que podem ser solucionados.  
- Existência de demanda atual.  
- Tipos de clientes beneficiados.  
- Possibilidade de transformar habilidades em serviços ou produtos.  
- Nichos específicos de valorização.  
- Serviços em alta na área.  
- Potencial de geração de renda prática em curto prazo.  

Encerramento: elaboração de um **Mapa de Oportunidades Potenciais**, sem apresentar plano final.

---

### Etapa 3 — Caminhos de Monetização
A última etapa propõe reflexões sobre diferentes formas de transformar habilidades em renda:
1. Oferta de serviços em plataformas.  
2. Criação de conteúdo gratuito para atração de clientes.  
3. Montagem de portfólio simples para validação.  
4. Estabelecimento de parcerias locais ou estratégicas.  
5. Oferta de aulas, consultorias ou mentorias.  

As perguntas conduzem a escolha do caminho mais adequado considerando simplicidade, rapidez de retorno e potencial de escala.  

Encerramento final:  
- Caminho recomendado para início.  
- Ação prática a ser executada em até 7 dias.  
- Ação específica para validação de mercado.

---

## Objetivo
O **Mapa de Habilidades** é uma ferramenta estratégica que organiza competências, cruza-as com demandas de mercado e estrutura possibilidades de monetização.  
Este repositório documenta o processo completo, servindo como guia para evolução profissional e exploração de oportunidades.
