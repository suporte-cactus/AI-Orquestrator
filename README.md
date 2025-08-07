# 💼 Sistema de Gestão de Custos e Produtividade

Sistema web completo para gerenciamento de custos empresariais, controle de produtividade e análise financeira por centros de custo.

## 🎯 Funcionalidades

### 📋 Módulos Principais
- **🏢 Centros de Custo** - Definição das unidades organizacionais
- **👥 Colaboradores** - Gestão de RH e custos de mão de obra  
- **🏭 Equipamentos** - Controle de ativos e depreciação
- **📊 Rateio de Centros** - Distribuição de custos administrativos
- **💰 Custos Mensais** - Consolidação e análise financeira
- **📈 Produtividade** - Registro e acompanhamento de produção

### ⚡ Recursos Avançados
- **Cálculos Automáticos** em tempo real
- **Interface Responsiva** para desktop e mobile
- **Validações Inteligentes** entre tabelas relacionadas
- **Dados Pré-carregados** para demonstração
- **Funciona Offline** após carregamento inicial

## 🧮 Fórmulas Implementadas

### 👥 Colaboradores
```
custo_hora = salario_base ÷ jornada_horas_mensal
```

### 🏭 Equipamentos  
```
deprec_mensal = valor_aquisicao ÷ (vida_util_anos × 12)
```

### 💰 Centros de Custo
```
valor_hora = (custo_total + valor_rateio_administrativo) ÷ horas_disponiveis
```

## 📱 Versões Disponíveis

### 🖥️ Desktop - `index.html`
- Interface completa com todos os recursos
- Ideal para gestão administrativa
- Tabelas expandidas e formulários detalhados

### 📱 Mobile - `sistema-mobile.html`  
- Otimizada para dispositivos móveis
- Navegação touch-friendly
- Formulários simplificados
- Tabelas com scroll horizontal

## 🚀 Como Usar

### 1️⃣ **Acesso Local**
```bash
# Clonar o repositório
git clone https://github.com/suporte-cactus/AI-Orquestrator.git

# Navegar para o diretório
cd AI-Orquestrator

# Iniciar servidor local
python -m http.server 8000

# Acessar no navegador
http://localhost:8000
```

### 2️⃣ **Download Direto**
- Baixe `index.html` ou `sistema-mobile.html`
- Abra diretamente no navegador
- Funciona offline sem servidor

## 📋 Sequência de Cadastro Recomendada

1. **🏢 Centros de Custo** → Base obrigatória do sistema
2. **👥 Colaboradores** → Dependem dos centros cadastrados  
3. **🏭 Equipamentos** → Vinculados aos centros de custo
4. **📊 Rateio** → Distribui custos entre centros
5. **💰 Custos Mensais** → Consolida custos do período
6. **📈 Produtividade** → Registra produção mensal

## 🏗️ Arquitetura do Sistema

### 📊 Estrutura de Dados
Baseado no esquema relacional completo com 6 tabelas principais:

- `centros_custo` - Unidades organizacionais
- `colaboradores` - Recursos humanos  
- `equipamentos` - Ativos e máquinas
- `rateio_centros` - Distribuição de custos
- `custos_mensais` - Consolidação financeira
- `produtividade_mensal` - Registros de produção

### 🔧 Tecnologias
- **Frontend**: HTML5, CSS3, JavaScript vanilla
- **Armazenamento**: Local Storage (navegador)
- **Design**: Responsivo e minimalista
- **Compatibilidade**: Todos os navegadores modernos

## 💡 Exemplos de Uso

### 🎯 Cenário 1: Empresa de Impressão
- **Centro Produtivo**: Impressão Digital (440h/mês)
- **Centro Administrativo**: Escritório (220h/mês)  
- **Colaborador**: Operador (R$ 5.000, 220h) → R$ 22,73/hora
- **Equipamento**: Impressora HP (R$ 120.000, 5 anos) → R$ 2.000/mês depreciação

### 🎯 Cenário 2: Análise de Custos
- **Custo Total Centro**: R$ 30.000/mês
- **Rateio Administrativo**: R$ 5.000/mês
- **Horas Disponíveis**: 440h/mês
- **Resultado**: R$ 79,55/hora de operação

## 🔍 Funcionalidades Detalhadas

### ✅ Validações Implementadas
- Campos obrigatórios marcados com *
- Relacionamentos entre tabelas
- Cálculos automáticos em tempo real
- Prevenção de divisão por zero

### 📊 Relatórios Visuais
- Tabelas organizadas por módulo
- Valores formatados em reais (R$)
- Indicadores de produtividade
- Acompanhamento mensal

## 🔧 Personalização

O sistema pode ser facilmente adaptado para diferentes tipos de negócio:

- **Indústria**: Controle de linhas de produção
- **Serviços**: Gestão de equipes e projetos  
- **Comércio**: Análise de rentabilidade por setor
- **Consultoria**: Controle de horas e custos

## 📈 Roadmap Futuro

- [ ] Exportação para Excel/CSV
- [ ] Gráficos e dashboards  
- [ ] Backup em nuvem
- [ ] API para integração
- [ ] Relatórios personalizados
- [ ] Multi-empresa

## 👥 Contribuição

Contribuições são bem-vindas! Por favor:

1. Faça fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças  
4. Abra um Pull Request

## 📄 Licença

Este projeto está sob licença MIT. Veja LICENSE para mais detalhes.

---

🚀 **Sistema pronto para uso imediato!** 

Desenvolvido com foco na simplicidade e eficiência para gestão empresarial moderna.
