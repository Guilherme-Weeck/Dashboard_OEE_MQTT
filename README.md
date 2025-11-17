📊 Dashboard OEE

Monitoramento de máquinas em tempo real via MQTT

📝 Descrição

O Dashboard OEE é uma aplicação web responsiva que permite monitorar:

Disponibilidade

Performance

Qualidade

OEE Total

Cada máquina possui suas próprias configurações MQTT, gráficos independentes e armazenamento persistente no navegador.

🚀 Demo (GitHub Pages)

Após publicar, acesse em:

https://seu-usuario.github.io/dashboard-oee/

✨ Funcionalidades
🏭 Gerenciamento de Máquinas

Criar máquinas ilimitadas

Nome editável (e salvo localmente)

Configurações individuais

Conectar/desconectar por máquina

📡 Configuração MQTT Completa

Broker ws:// ou wss://

Client ID

Username (opcional)

Password (opcional)

Tópicos separados para:

Disponibilidade

Performance

Qualidade

OEE

Multiplicadores individuais

📈 Gráficos Interativos

Donut OEE com texto central

Barras KPIs (Disp / Perf / Qual / OEE)

Atualização instantânea ao receber mensagens MQTT

🎨 Temas (Light / Dark Blue)

Alterna com um clique

Salvo automaticamente em localStorage

Tema dark otimizado para leitura

📱 Totalmente Responsivo

Interface reorganizada no mobile

Cabeçalhos com quebra automática

Gráficos redimensionáveis

🧰 Como Usar

Clique em ➕ Adicionar Máquina

Abra o menu ⚙️ Configurações

Preencha:

Broker

Client ID

Username (opcional)

Password (opcional)

Tópicos

Clique em Conectar

Os gráficos atualizarão em tempo real assim que a máquina publicar no broker.

🌐 Deploy no GitHub Pages
1️⃣ Faça upload destes arquivos:
index.html
README.md
LICENSE
(optional) favicon.ico

2️⃣ Vá para:

Settings → Pages → Build and Deployment → Source → main / root

3️⃣ Acesse:
https://seu-usuario.github.io/dashboard-oee/

🛠️ Tecnologias Utilizadas

HTML5 / CSS3 / JS Vanilla

Chart.js 4.x

MQTT.js

LocalStorage

GitHub Pages
