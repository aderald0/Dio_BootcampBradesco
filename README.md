🎙️ Assistente de Voz Multi-Idiomas com Whisper & Gemini
Este projeto foi desenvolvido como parte de um desafio prático de Inteligência Artificial. Ele consiste em um assistente de voz capaz de ouvir o usuário (em vários idiomas), transcrever a fala, processar a intenção usando modelos de linguagem de última geração e responder por áudio.

🛠️ Tecnologias Utilizadas
Python: Linguagem base para integração de APIs e lógica.

OpenAI Whisper: Utilizado para a transcrição de áudio para texto (STT - Speech-to-Text) com alta precisão.

Google Gemini AI: O "cérebro" do assistente, responsável por processar o contexto e gerar respostas inteligentes.

gTTS (Google Text-to-Speech): Utilizado para converter as respostas de texto do Gemini em fala natural.

Google Colab: Ambiente de desenvolvimento utilizado para execução e testes.

🚀 Funcionalidades
Captura de Áudio: Interface via JavaScript para gravação de voz diretamente no navegador.

Transcrição Robusta: Suporte a múltiplos idiomas com reconhecimento automático via Whisper.

Inteligência Conversacional: Respostas contextuais e precisas alimentadas pelo modelo Gemini da Google.

Resposta Vocal: O assistente não apenas escreve, mas também fala a resposta final.

📋 Como Executar
Chave de API: É necessário possuir uma GOOGLE_API_KEY.

Configuração no Colab:

Vá até o ícone de chave (Secrets) no Google Colab.

Adicione uma nova chave com o nome GOOGLE_API_KEY e cole o seu token no valor.

Execução:

Execute as células de instalação de dependências.

Inicie o bloco de gravação de áudio e fale após o sinal.

O sistema processará sua fala e retornará um player de áudio com a resposta.

👤 Autor
Aderaldo Amaral

Estudante de Análise, Projeto e Gerência de Sistemas na UNOPAR.

Interessado em Automação, Programação e Inteligência Artificial.
