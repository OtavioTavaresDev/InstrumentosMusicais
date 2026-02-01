🎹 pianoVirtual

Um piano virtual interativo feito com HTML, CSS e JavaScript, com visual moderno em estilo neon e síntese de áudio em tempo real usando a Web Audio API.

O projeto simula um piano completo no navegador, permitindo tocar notas com o mouse (ou toque em telas touch) e alternar entre diferentes timbres sonoros.

✨ Funcionalidades

🎼 Piano completo com várias oitavas

🎹 Teclas brancas e pretas alinhadas corretamente

🌈 Visual neon estilizado com efeitos de brilho e profundidade

🔊 Síntese de som em tempo real (não usa arquivos de áudio)

🎛️ Múltiplos timbres:

Suave (sine)

Synth (triangle)

8-bit (square)

Agressivo (sawtooth)

Órgão (harmônicos)

Pad ambiente

🖱️ Suporte a clique e segurar

📱 Funciona em desktop e mobile

🧠 Tecnologias usadas
Tecnologia	Função
HTML5	Estrutura do piano
CSS3	Estilo, layout e efeitos visuais
JavaScript	Lógica das teclas e interação
Web Audio API	Geração de som em tempo real
🎵 Como o som é gerado

O áudio é sintetizado diretamente pelo navegador:

Frequência da nota → Oscillator → Gain (volume) → Saída de áudio


Cada tecla cria:

Um ou mais osciladores (dependendo do timbre)

Envelope de ataque e liberação para soar mais natural

🚀 Como usar

Baixe o arquivo pianoVirtual.html

Abra no navegador (Chrome, Edge, Firefox, etc.)

Clique ou toque nas teclas para tocar

Mude o timbre no seletor

📁 Estrutura do projeto
pianoVirtual/
│
├── pianoVirtual.html   # Código completo do piano
└── README.md           # Documentação do projeto

🎨 Design

O visual segue uma estética moderna:

Fundo escuro com gradiente profundo

Teclas brancas com brilho azul ao tocar

Teclas pretas com brilho rosa neon

Sombras para dar sensação de profundidade

🔧 Possíveis melhorias futuras

🎹 Suporte ao teclado físico do computador

🎚️ Controle de volume

🎼 Gravação de melodias

🌊 Efeitos como reverb e delay

🎛️ Mais instrumentos

📜 Licença

Uso livre para estudos, experimentos e projetos pessoais.