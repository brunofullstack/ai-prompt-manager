# Prompt Manager - Organizador de Prompts para IA

![Versão](https://img.shields.io/badge/versão-1.0.0-blue.svg)
![Licença](https://img.shields.io/badge/licença-MIT-green.svg)

Uma aplicação web poderosa para organizar, categorizar e gerenciar prompts de IA. Desenvolvida com Tailwind CSS e JavaScript vanilla, esta ferramenta ajuda você a armazenar, buscar e reutilizar seus prompts favoritos em diferentes plataformas de IA.

## 🌟 Funcionalidades

### 🚀 Funcionalidades Principais
- **Gerenciamento de Prompts**: Crie, edite e exclua prompts de IA com facilidade
- **Categorização Inteligente**: Organize prompts em categorias personalizáveis
- **Busca Avançada**: Encontre prompts por título, conteúdo ou tags
- **Múltiplas Opções de Ordenação**: Ordene por título, categoria ou data
- **Modo Escuro/Claro**: Alterne entre temas para uso confortável

### 📁 Gerenciamento de Dados
- **Armazenamento Local**: Todos os dados persistem no seu navegador
- **Importar/Exportar**: Faça backup e restaure seus prompts via arquivos JSON
- **Sistema de Categorias**: Categorias totalmente personalizáveis com código de cores
- **Sistema de Tags**: Adicione múltiplas tags a cada prompt para melhor organização

### 🎨 Experiência do Usuário
- **Design Responsivo**: Funciona perfeitamente em desktop e dispositivos móveis
- **Interface Limpa**: UI intuitiva e moderna construída com Tailwind CSS
- **Ações Rápidas**: Copie prompts para a área de transferência com um clique
- **Filtragem em Tempo Real**: Resultados de busca e filtros instantâneos

## 🏗️ Estrutura do Projeto

```
prompt-manager/
├── index.html          # Arquivo principal da aplicação
├── README.md          # Documentação do projeto
```

## 🚀 Início Rápido

### Pré-requisitos
- Um navegador web moderno (Chrome, Firefox, Safari, Edge)
- Nenhuma dependência adicional necessária!

### Instalação & Uso

1. **Baixe a Aplicação**
   ```bash
   # Clone o repositório ou baixe o arquivo HTML
   git clone https://github.com/brunofullstack/prompt-manager.git
   ```

2. **Execute a Aplicação**
   - Abra `index.html` no seu navegador web
   - Pronto! Não é necessário configuração de servidor

3. **Comece a Usar**
   - Adicione seu primeiro prompt usando o formulário à esquerda
   - Crie categorias personalizadas para melhor organização
   - Use busca e filtros para encontrar prompts rapidamente

## 💡 Como Usar

### Adicionando Prompts
1. Preencha o título do prompt
2. Selecione ou crie uma categoria
3. Escreva o texto do prompt
4. Adicione tags relevantes (separadas por vírgula)
5. Clique em "Adicionar Prompt"

### Gerenciando Categorias
1. Clique no ícone de engrenagem (⚙️) ao lado do menu de categorias
2. Adicione novas categorias com nomes e cores personalizadas
3. Edite ou exclua categorias existentes
4. As categorias são salvas automaticamente

### Importando/Exportando Dados
- **Exportar**: Clique em "Exportar para JSON" para baixar todos os seus dados
- **Importar**: Use "Importar de JSON" para restaurar de backup
- Os dados incluem tanto prompts quanto categorias

### Buscando e Filtrando
- Use a barra de busca para encontrar prompts por conteúdo
- Filtre por categorias específicas
- Ordene por diferentes critérios (título, data, categoria)

## 📊 Categorias Padrão

O aplicativo vem com categorias pré-definidas:
- **Geral**: Prompts para todos os propósitos
- **Configuração de Servidor**: Prompts para configuração de sistema e servidor
- **Criação de Conteúdo**: Escrita e geração de conteúdo
- **Análise de Dados**: Processamento e análise de dados
- **Programação**: Prompts relacionados a código
- **Design**: Prompts de UI/UX e design

## 🛠️ Detalhes Técnicos

### Construído Com
- **Tailwind CSS** - Framework CSS utility-first moderno
- **JavaScript Vanilla** - Sem dependências externas
- **Font Awesome** - Ícones bonitos
- **API Local Storage** - Persistência de dados

### Compatibilidade do Navegador
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Estrutura de Dados
```json
{
  "prompts": [
    {
      "id": "id-único",
      "title": "Título do Prompt",
      "category": "id-da-categoria",
      "prompt": "Texto completo do prompt",
      "tags": ["tag1", "tag2"],
      "date": "2023-12-01T10:30:00.000Z"
    }
  ],
  "categories": [
    {
      "id": "id-da-categoria",
      "name": "Nome da Categoria",
      "color": "blue"
    }
  ]
}
```

## 🔧 Personalização

### Adicionando Novas Cores de Categoria
Edite as funções `getCategoryColorClass()` e `getCategoryColorClassForBadge()` no JavaScript para adicionar novas opções de cores.

### Modificando Categorias Padrão
Atualize o array `categories` na inicialização do JavaScript para alterar as categorias padrão.

## 📱 Suporte Mobile

A aplicação é totalmente responsiva e funciona em:
- Computadores desktop
- Tablets
- Telefones móveis
- Dispositivos com touch

## 🔒 Privacidade de Dados

- Todos os dados são armazenados localmente no seu navegador
- Nenhum dado é enviado para servidores externos
- Você tem controle total sobre seus dados
- Funcionalidade de exportar/importar para backups

## 🐛 Solução de Problemas

### Problemas Comuns

1. **Dados não salvando**
   - Verifique se o localStorage está habilitado no seu navegador
   - Certifique-se de que não está no modo privado/incógnito

2. **Importação não funcionando**
   - Verifique se o formato do arquivo JSON está correto
   - Verifique o console do navegador para mensagens de erro

3. **Categorias não aparecendo**
   - Tente atualizar a página
   - Verifique se as categorias existem no localStorage

### Obtendo Ajuda
- Verifique o console do navegador para mensagens de erro
- Certifique-se de estar usando um navegador suportado
- Verifique a estrutura do arquivo JSON ao importar

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para bugs e solicitações de recursos.

### Desenvolvimento
1. Faça um fork do repositório
2. Crie um branch de feature
3. Faça suas alterações
4. Teste thoroughly
5. Envie um pull request

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.

## 🙏 Agradecimentos

- **Tailwind CSS** pelo incrível framework CSS utility-first
- **Font Awesome** pelos belos ícones
- **Todos os contribuidores** que ajudam a melhorar este projeto

---

**Feliz Prompting!** 🚀

Se você acha esta ferramenta útil, por favor considere dar uma estrela ⭐ no GitHub!

## 📞 Suporte

Se precisar de ajuda ou tiver perguntas:
1. Verifique este README primeiro
2. Abra uma issue no GitHub
3. Verifique issues existentes para soluções

---

<div align="center">

**Feito com ❤️ para a comunidade de IA**

</div>