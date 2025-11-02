# 🏠 Sistema de Inspeção Residencial

Sistema completo para realização de inspeções residenciais com salvamento automático no Google Drive.

## 🌐 Acesso Online

**URL do Sistema:** https://brguma.github.io/Sistema-insp-residencial/

## 📋 Funcionalidades

### 🏁 Inspeção Inicial
- Primeira vistoria do imóvel
- Dados básicos e estruturais
- Identificação de problemas
- Upload de fotos

### 📊 Inspeção Completa
- Vistoria detalhada
- Requer inspeção inicial prévia
- Avaliações de estado geral
- Estimativas de custo e prazo
- Recomendações técnicas

### ✨ Recursos
- ✅ Upload ilimitado de fotos
- ✅ Salvamento automático no Google Drive
- ✅ Geração de relatórios em texto
- ✅ Organização automática em pastas (tipo → data → endereço)
- ✅ Ícones informativos sobre patologias
- ✅ Interface responsiva (funciona em celular)

## 🔧 Tecnologias

- HTML5
- CSS3 (Vanilla)
- JavaScript (Vanilla)
- Google Drive API
- Google Identity Services (OAuth 2.0)

## 📁 Estrutura de Pastas no Google Drive

```
Google Drive/
└── Inspecoes_Residenciais/
    ├── inspecao_inicial/
    │   └── [data]/
    │       └── [endereco]/
    │           ├── inspecao.json
    │           ├── relatorio.txt
    │           └── fotos/
    └── inspecao_completa/
        └── [data]/
            └── [endereco]/
                ├── inspecao.json
                ├── relatorio.txt
                └── fotos/
```

## 🚀 Como Usar

1. Acesse: https://brguma.github.io/Sistema-insp-residencial/
2. Clique em "Conectar com Google Drive"
3. Faça login e autorize o acesso
4. Escolha o tipo de inspeção (Inicial ou Completa)
5. Preencha os dados da vistoria
6. Adicione fotos dos problemas
7. Salve - será sincronizado automaticamente com o Google Drive!

## 📖 Seções de Inspeção

1. **Estrutura** - Fissuras, trincas, danos, recalque
2. **Instalações Elétricas** - Quadro, fiação, tomadas, interruptores
3. **Instalações Hidrossanitárias** - Vazamentos, tubulações, louças
4. **Cobertura** - Goteiras, infiltrações, telhado, impermeabilização
5. **Revestimento** - Paredes, pisos, pintura, azulejos
6. **Esquadrias** - Portas, janelas, vedação
7. **Infraestrutura** - Conexões água, esgoto, energia
8. **Outros Problemas** - Campos livres para observações

## 💡 Ícones Informativos

Passe o mouse sobre os ícones "i" para ver explicações técnicas:
- **Fissuras:** Aberturas < 0,5mm
- **Trincas:** Aberturas > 0,5mm
- **Recalque:** Afundamento da fundação
- E muito mais!

## 🔒 Segurança

- Autenticação via Google OAuth 2.0
- Dados salvos apenas no SEU Google Drive
- Nenhuma informação armazenada em servidores externos
- Código 100% client-side (JavaScript)

## 📱 Compatibilidade

- ✅ Google Chrome (Recomendado)
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Funciona em Desktop, Tablet e Mobile

## 🛠️ Desenvolvimento Local

Para rodar localmente:

```bash
# Clone o repositório
git clone https://github.com/brguma/Sistema-insp-residencial.git

# Entre na pasta
cd Sistema-insp-residencial

# Inicie um servidor local
python -m http.server 8000

# Acesse no navegador
http://localhost:8000/sistema_inspecao_completo.html
```

## 📄 Licença

Este projeto é de uso pessoal/profissional.

## 👤 Autor

**brguma**
- GitHub: [@brguma](https://github.com/brguma)

## 📞 Suporte

Para dúvidas sobre configuração do Google Drive API, consulte:
- [Documentação Google Cloud](https://cloud.google.com/docs)
- [Google Drive API Guide](https://developers.google.com/drive/api/guides/about-sdk)

---

**Versão:** 1.0  
**Última atualização:** Novembro 2025
