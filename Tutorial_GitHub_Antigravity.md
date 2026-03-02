# Tutorial do GitHub e Antigravity

## 📋 Pré-requisitos (O que você precisa antes de começar)

Antes de iniciar o desenvolvimento do seu MVP, você precisará:

- **Computador com Windows, Mac ou Linux** (com pelo menos 8GB de RAM recomendado)
- **Conexão com a internet** (estável, para downloads e sincronização)
- **Conta Google** (gratuita - você pode usar seu Gmail)
- **Tempo estimado**: 2-4 horas para configuração inicial

> [!NOTE]
> **MVP** significa "Minimum Viable Product" (Produto Mínimo Viável) - uma versão básica do seu sistema que já pode ser testada por usuários reais.

---

## 🚀 Passo a Passo Completo

### **1. Criar sua conta no GitHub**

O GitHub é onde o código do seu sistema ficará armazenado de forma segura e organizada.

1. Acesse o GitHub: [github.com](https://github.com)
2. Faça login com sua conta (ou clique em **"Sign up"** se precisar criar uma conta)
3. Confirme seu acesso
4. Confirme seu email
5. **Guarde suas credenciais** (usuário e senha) em local seguro

> [!TIP]
> O GitHub é a plataforma de desenvolvimento mais usada no mundo. Funciona como um "Google Drive" para código, com ferramentas de colaboração.

---

### **2. Criar a pasta do projeto no seu PC**

Organize seus arquivos em uma pasta dedicada ao projeto:

1. Crie uma pasta em um local de fácil acesso, exemplo:
   - Windows: `C:\Projetos\MeuSistema`
   - Mac/Linux: `~/Projetos/MeuSistema`
2. **Use nomes sem espaços e sem acentos** (exemplo: `SistemaEstoque` ao invés de `Sistema de Estoque`)
3. Esta pasta será o "lar" de todo o código do seu projeto

---

### **3. Preparar os arquivos de referência**

**Este é o passo mais importante!** A qualidade do sistema depende da clareza das suas instruções.

Crie arquivos de texto (`.txt` ou `.md`) dentro da pasta do projeto com:

- **`requisitos.md`** - O que o sistema precisa fazer
- **`regras-de-negocio.md`** - As regras que o sistema deve seguir
- **`casos-de-uso.md`** - Como os usuários vão usar o sistema

> [!IMPORTANT]
> **Não sabe como escrever esses arquivos?** Consulte o [Guia para Gestores: Como Especificar Demandas de Software](Guia%20para%20Gestores_%20Como%20Especificar%20Demandas%20de%20Software.md) que está nesta mesma pasta. Ele ensina passo a passo como transformar sua ideia em instruções claras.

**Exemplo de conteúdo básico:**

```markdown
# Requisitos do Sistema de Estoque

## Objetivo
Controlar entrada e saída de produtos do estoque

## Funcionalidades Principais
1. Cadastrar produtos (nome, código, quantidade)
2. Registrar entrada de mercadorias
3. Registrar saída de mercadorias
4. Consultar estoque atual
5. Gerar relatório de movimentações
```

---

### **4. Baixar e instalar o Google Antigravity**

O Antigravity é a ferramenta de IA que vai desenvolver o sistema para você.

1. Acesse [https://antigravity.google/](https://antigravity.google/)
2. Clique em "Download" ou "Get Started"
3. Escolha a versão para seu sistema operacional (Windows/Mac/Linux)
4. Execute o instalador e siga as instruções na tela
5. Aguarde a instalação completa (pode levar alguns minutos)

> [!NOTE]
> O Antigravity é uma ferramenta oficial do Google, segura e gratuita para uso.

---

### **5. Fazer login com sua conta Google**

1. Abra o Antigravity
2. Clique em "Sign in" ou "Login"
3. Escolha sua conta Google
4. Autorize as permissões solicitadas
5. Aguarde o carregamento da interface

---

### **6. Abrir a pasta do projeto no Antigravity**

1. No Antigravity, procure a opção "Open Folder" ou "Abrir Pasta"
2. Navegue até a pasta que você criou no Passo 2
3. Selecione a pasta e clique em "Abrir"
4. Você verá os arquivos da pasta aparecerem na barra lateral

> [!TIP]
> Você pode trabalhar em vários projetos diferentes. Basta abrir a pasta de outro projeto quando quiser trocar.

#### 🌐 Como colocar o Antigravity em Português

Por padrão, a interface do Antigravity pode estar em inglês. Para mudar para português:

1. Clique no ícone de **Extensões** na barra lateral esquerda (ícone de quadrados ou atalho `Ctrl+Shift+X`)
2. Na barra de pesquisa, digite **"Portuguese Brazil"**
3. Encontre a extensão **"Portuguese (Brazil) Language Pack for Visual Studio Code"** (da Microsoft) e clique em **Install**
4. O Antigravity será reiniciado automaticamente com a interface em português

> [!NOTE]
> Mesmo que a interface esteja em inglês, você pode conversar com o Antigravity em português sem problemas — ele entende e responde no idioma que você usar. A mudança de idioma afeta apenas os menus e botões da interface.

---

### **7. Instalar o Git e syncronizar Antigravity com o GitHub**

1. No Antigravity digite: Conecte na minha conta do GitHub usando github CLI com autenticação via navegador.
2. Na sequência o agente de IA vai instalar o Git solicitando sua permissão e conectar com sua conta do GitHub abrindo uma janela do navegador para que você possa autenticar.