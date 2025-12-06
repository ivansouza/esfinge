🦁 Esfinge de Gizé
> "Decifra-me, ou te devoro!"
> 
Uma aplicação web inteligente que utiliza a IA do Google Gemini para transcrever e resumir áudios em tempo real ou através de upload de arquivos. Projetada com foco em dispositivos móveis ("Mobile First") e com uma interface temática imersiva.
✨ Funcionalidades
A Esfinge de Gizé resolve o problema de áudios longos e desconexos através de duas modalidades principais:
1. 🎤 Modo Microfone (Ao Vivo)
 * Transcrição em Tempo Real: Utiliza a Web Speech API para converter voz em texto instantaneamente.
 * Algoritmo Anti-Duplicação: Implementa uma lógica customizada de "costura de texto" que detecta e remove repetições de frases comuns causadas por correções do navegador (ex: "Era uma vez... uma vez uma menina").
 * Edição Manual: A caixa de transcrição é editável caso você queira fazer correções manuais antes de enviar para a IA.
2. 📂 Modo Arquivo (Upload)
 * Processamento Multimodal: Envia o áudio bruto (MP3, WAV, AAC) diretamente para o Gemini 1.5/2.5 Flash.
 * Player Integrado: Permite pré-visualizar o áudio antes do envio.
 * Alta Capacidade: Suporta arquivos de até 10MB (processamento direto no cliente).
3. 🧠 Inteligência Artificial (O "Decifrador")
 * Resumo Inteligente: Gera um parágrafo conciso capturando o contexto principal.
 * Correção Gramatical: No modo microfone, a IA reescreve a transcrição corrigindo pontuação e erros de concordância.
 * Saída Estruturada: Retorna os dados em JSON para separar visualmente o Resumo da Transcrição Completa.
4. 🛠️ Utilitários de UX
 * Cópia Rápida: Botões dedicados para copiar o resumo ou a transcrição para a área de transferência.
 * Persistência de Chave: Salva a API Key no localStorage do navegador para facilitar o uso recorrente.
 * Design Responsivo: Interface otimizada para celulares e desktops com tema escuro/egípcio.
🚀 Como Usar
Pré-requisitos
 * Um navegador moderno (Chrome, Edge, Safari). Nota: O suporte à Web Speech API varia entre navegadores, funcionando melhor em base Chromium.
 * Uma API Key do Google Gemini (Gratuita via Google AI Studio).
Instalação
Este projeto é uma Single Page Application (SPA) contida em um único arquivo HTML, facilitando a implantação.
 * Clone este repositório:
   git clone [https://github.com/seu-usuario/esfinge-de-gize.git](https://github.com/seu-usuario/esfinge-de-gize.git)

