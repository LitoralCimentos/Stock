# 🏪 LitoralCimentos - Sistema de Gestão

Sistema completo de gestão para loja de ferragens em arquivo HTML único com integração Firebase.

## 📋 Sobre o Sistema

O **LitoralCimentos** é um sistema de gestão completo desenvolvido especificamente para lojas de ferragens e materiais de construção. Toda a funcionalidade está contida em um único arquivo HTML, tornando-o extremamente portátil e fácil de implementar.

## ⚡ Funcionalidades Principais

### 📦 **Gestão de Produtos**
- Cadastro completo de produtos
- Controle de estoque com alertas automáticos
- Estoque mínimo configurável
- Categorias dinâmicas
- Preços de custo e venda

### 💰 **Gestão de Vendas**
- Registro de vendas no balcão
- Vendas com entrega domiciliar
- Preço de entrega configurável
- Múltiplas formas de pagamento
- Histórico completo de vendas

### 🚚 **Gestão de Entregas**
- Cadastro completo de endereços
- Status de entrega em tempo real
- Integração com WhatsApp para notificações
- Motorista configurado: +55 54 9974-1252

### 📊 **Relatórios e Análises**
- Gráficos de vendas por período
- Produtos mais vendidos
- Análise de tendências
- Dados em tempo real

### 🧮 **Sistema Financeiro Integrado**
- Calculadora de margem integrada no cadastro de produtos
- Controle completo de custos e preços de venda
- Gestão de gastos fixos mensais
- Registro de movimentações (perdas, uso próprio, entradas)
- Análise financeira completa com gráficos
- Cálculo automático de ponto de equilíbrio
- ROI mensal e tempo para cobrir gastos fixos

## 🔧 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript
- **UI Framework**: Bootstrap 5.3
- **Ícones**: Font Awesome 6.4
- **Gráficos**: Chart.js
- **Base de Dados**: Firebase Realtime Database
- **Integração**: WhatsApp API

## 🚀 Como Usar

### 1. **Instalação**
```bash
# Não é necessária instalação
# Apenas abra o arquivo index.html em qualquer navegador
```

### 2. **Configuração Firebase**
1. Acesse o [Firebase Console](https://console.firebase.google.com/)
2. Crie um novo projeto
3. Habilite o Realtime Database
4. Configure as credenciais no arquivo HTML

### 3. **Primeira Utilização**
1. Abra o arquivo `index.html` no navegador
2. Comece cadastrando produtos
3. Configure categorias conforme necessário
4. Registre suas primeiras vendas

## 📱 Funcionalidades Detalhadas

### **Dashboard Principal**
- Resumo de vendas do dia
- Produtos com estoque baixo
- Entregas pendentes
- Alertas importantes

### **Cadastro de Produtos**
- Nome e descrição
- Preço de custo e venda (com cálculo automático de margem)
- Quantidade em estoque
- Estoque mínimo
- Categoria
- Observações
- **Análise automática**: Margem de lucro, markup e lucro por unidade

### **Vendas no Balcão**
- Seleção rápida de produtos
- Cálculo automático de totais
- Múltiplas formas de pagamento
- Impressão de comprovante

### **Vendas com Entrega**
- Cadastro completo de endereço
- Cálculo de preço de entrega
- Dados do cliente
- Status de entrega

### **Relatórios e Análises Disponíveis**
- Vendas por período (7 dias, 30 dias, mês, ano)
- Produtos mais vendidos
- Análise de categorias
- **Movimentações de Estoque**: Entradas, saídas, perdas, uso próprio
- **Análise Financeira Completa**:
  - Receita bruta vs custos dos produtos
  - Gastos fixos e operacionais
  - Perdas e produtos danificados
  - Lucro líquido real
  - Ponto de equilíbrio
  - ROI mensal
  - Gráficos de rentabilidade e distribuição de custos

## 🎯 Vantagens do Sistema

✅ **Portátil**: Funciona em qualquer dispositivo com navegador  
✅ **Offline**: Dados salvos localmente quando necessário  
✅ **Sincronização**: Dados em tempo real via Firebase  
✅ **Responsivo**: Interface adaptada para mobile e desktop  
✅ **Completo**: Todas as funcionalidades em um só lugar  
✅ **Fácil**: Interface intuitiva e user-friendly  
✅ **Controle Total**: Rastreamento completo de custos, receitas e lucros  
✅ **Análise Avançada**: Métricas financeiras em tempo real  

## 📞 Suporte e Contato

Para suporte técnico ou dúvidas sobre o sistema:
- WhatsApp Motorista: +55 54 9974-1252
- Sistema desenvolvido especificamente para LitoralCimentos

## 🔒 Segurança

- Dados armazenados no Firebase (Google)
- Backup automático em nuvem
- Acesso controlado por autenticação
- Dados criptografados

## 📈 Métricas e Analytics

O sistema gera automaticamente:
- Relatórios de vendas
- Análise de produtos
- Tendências de mercado
- Indicadores financeiros

## 🛠️ Personalização

O sistema pode ser facilmente personalizado:
- Adicionar novas categorias
- Configurar preços de entrega
- Personalizar campos de cadastro
- Ajustar relatórios

## 📄 Estrutura do Projeto

```
LitoralCimentos/
├── index.html          # Aplicação completa
├── README.md           # Esta documentação
├── replit.md           # Documentação técnica
└── attached_assets/    # Capturas de tela
```

## 💰 **Controle Financeiro Avançado**

O sistema agora inclui controle financeiro completo:

### **Cadastro Inteligente**
- Ao cadastrar produtos, o sistema calcula automaticamente:
  - Margem de lucro (%)
  - Markup sobre o custo
  - Lucro por unidade vendida

### **Movimentações de Estoque**
- **Entradas**: Compras de mercadorias
- **Perdas**: Produtos danificados ou vencidos
- **Uso Próprio**: Produtos retirados para uso pessoal
- **Ajustes**: Correções de inventário

### **Análise Financeira**
- **Receitas**: Total de vendas
- **Custos**: Custo real dos produtos vendidos
- **Gastos Fixos**: Despesas mensais (aluguel, luz, etc.)
- **Lucro Líquido**: Resultado final após todos os custos
- **Ponto de Equilíbrio**: Valor mínimo para cobrir custos
- **ROI**: Retorno sobre investimento

## 🚀 Deploy

Para colocar o sistema online:

1. **GitHub Pages**: Faça upload do `index.html`
2. **Netlify**: Arraste o arquivo para o site
3. **Firebase Hosting**: Use `firebase deploy`
4. **Servidor próprio**: Copie o arquivo para o servidor

## 📋 Changelog

- **07/07/2025**: Versão inicial completa
- **07/07/2025**: Integração WhatsApp configurada
- **07/07/2025**: Gráficos Chart.js implementados
- **07/07/2025**: Sistema de controle financeiro integrado
- **07/07/2025**: Calculadora de margem no cadastro de produtos
- **07/07/2025**: Seções de movimentações e análise financeira
- **07/07/2025**: Sistema finalizado com controle financeiro completo

---

**Desenvolvido com ❤️ para LitoralCimentos**  
*Sistema de gestão completo em arquivo único*