# RLC_Analyzer_Pro_Setup
# ⚛️ RLC Analyzer (v1.0 Beta)

O RLC Analyzer é uma ferramenta desenvolvida para **simulação**, **controle de equipamentos** e **análise de circuitos RLC** (Resistência, Indutância e Capacitância).

Esta é uma versão Beta. Seu **feedback** é inestimável para a estabilidade e aprimoramento contínuo!

---

## ⬇️ Instalação e Download

**Não é necessário ter Python ou instalar bibliotecas!** O instalador é completo. Para começar, siga estes passos:

1.  Vá para a seção **[Releases]** no nosso repositório no GitHub.
2.  Baixe o arquivo do instalador mais recente: `RLC_Analyzer_Setup.exe`.
3.  Execute o instalador e siga as instruções na tela.

---

## 🔒 Compromisso de Privacidade (Versão Beta)

A sua privacidade é uma prioridade. O RLC Analyzer **não coleta, rastreia ou transmite quaisquer dados pessoais ou sensíveis** do seu uso. O software é executado integralmente no ambiente local do seu computador, mantendo seus experimentos e análises estritamente privados.

---

## 🛠️ Modos de Operação

O RLC Analyzer opera em dois modos principais, cada um com diferentes requisitos de hardware:

### 1. 🖥️ Simulador e Análise de Resultados (Sem Equipamento)

* **Requisito:** Apenas o software instalado.
* **Função:** Permite que você execute simulações de circuitos RLC e visualize e analise resultados de experimentos salvos.
* **Recomendação:** Use o simulador para descobrir a **faixa de frequência ideal** que deve ser varrida antes de iniciar o experimento real.

### 2. 🧪 Controle de Experimento (Com Equipamento)

* **Requisito:** Equipamentos de medição conectados ao computador.
* **Conexão Necessária:** Os equipamentos devem estar conectados ao computador via **USB Serial** (usando a funcionalidade $\texttt{pyvisa}$ embutida).
* **Equipamentos Suportados:**
    * Gerador de Função: **Tektronix AFG3021C**
    * Osciloscópio: **Tektronix DPO2012B**

---

## ⚠️ Alerta de Bug Visual (Em Correção)

Estamos cientes e pedimos que fiquem tranquilos a respeito de um bug visual que pode ocorrer durante a realização de experimentos controlados.

* **O Bug:** Algumas vezes, o gráfico pode **parar de plotar os pontos** em tempo real na tela.
* **A Solução:** Enquanto sua barra de progresso estiver avançando, seu experimento está sendo realizado normalmente e **poderá ser salvo com segurança** para análise futura.
* Nossa equipe já está trabalhando para resolver este problema visual o quanto antes!

---

## Dica de Desempenho

Lembre-se, na aba de experimentos, quanto **mais pontos** você configurar para varrer, **mais lento** será o processo de análise e coleta de dados.
