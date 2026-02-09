<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corrida da Sisil - 20 Anos | Convite Oficial</title>
    <!-- Importação do Tailwind CSS para o design -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Importação de fontes desportivas e modernas -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Barlow+Condensed:ital,wght@0,700;0,900;1,900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #fdf2f8;
            color: #1f2937;
        }
        .font-sport {
            font-family: 'Barlow Condensed', sans-serif;
            text-transform: uppercase;
            letter-spacing: -0.02em;
        }
        .bg-gradient-pink {
            background: linear-gradient(135deg, #ec4899 0%, #be185d 100%);
        }
        .paper-shadow {
            box-shadow: 
                0 1px 3px rgba(0,0,0,0.1), 
                0 20px 25px -5px rgba(0,0,0,0.1), 
                0 10px 10px -5px rgba(0,0,0,0.04);
        }
        /* Estilo para simular furos de um número de peito real */
        .bib-corner {
            width: 12px;
            height: 12px;
            background-color: #f3f4f6;
            border-radius: 50%;
            position: absolute;
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4 sm:p-6">

    <!-- Content Card -->
    <div class="max-w-md w-full bg-white paper-shadow rounded-3xl overflow-hidden border border-gray-100 relative">
        
        <!-- Header: Identidade Visual de Corrida -->
        <div class="bg-gradient-pink p-8 sm:p-10 text-center relative overflow-hidden">
            <!-- Decoração de fundo -->
            <div class="absolute inset-0 opacity-10 flex flex-wrap gap-4 rotate-12 scale-150 pointer-events-none font-sport font-black text-4xl">
                RUN SISIL RUN SISIL RUN SISIL RUN SISIL RUN SISIL
            </div>
            
            <div class="relative z-10">
                <span class="inline-block px-3 py-1 bg-white text-pink-700 text-[10px] font-black tracking-[0.3em] rounded-full mb-4 uppercase">Evento Exclusivo</span>
                <h1 class="font-sport italic text-white text-5xl sm:text-6xl leading-none">
                    CORRIDA DA <br> <span class="text-6xl sm:text-7xl">SISIL</span>
                </h1>
                <div class="mt-4 flex items-center justify-center gap-2">
                    <div class="h-[2px] w-6 bg-pink-300"></div>
                    <span class="font-sport text-pink-100 text-xl sm:text-2xl tracking-widest italic">Edição Especial 20 Anos</span>
                    <div class="h-[2px] w-6 bg-pink-300"></div>
                </div>
            </div>
        </div>

        <!-- Conteúdo Principal -->
        <div class="p-6 sm:p-8 space-y-6">
            
            <!-- Texto de Convite -->
            <div class="text-center">
                <h3 class="font-sport text-2xl text-gray-900 leading-tight italic font-black">A nossa meta é celebrar!</h3>
                <p class="text-gray-500 text-sm mt-2 leading-relaxed">
                    Vinte anos de história merecem uma largada especial. Junte-se ao nosso pelotão para uma comemoração inesquecível na orla.
                </p>
            </div>

            <!-- Informações do Evento -->
            <div class="flex items-center gap-4 bg-gray-50 p-4 rounded-2xl border border-gray-100">
                <div class="flex flex-col items-center justify-center border-r border-gray-200 pr-4">
                    <span class="font-sport text-3xl text-pink-600 leading-none">25</span>
                    <span class="font-sport text-xs text-gray-400">FEV</span>
                </div>
                <div class="flex-1 text-sm">
                    <div class="flex items-center gap-2 text-gray-800 font-bold">
                        <svg class="w-4 h-4 text-pink-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span>17:00h • Ponta Negra</span>
                    </div>
                    <div class="text-pink-600 font-bold mt-1 uppercase text-[10px] tracking-wider">Traje Sugerido: Esportivo & Rosa 👟</div>
                </div>
            </div>

            <!-- Sugestões de Presente -->
            <div class="bg-pink-50/50 rounded-2xl p-5 border border-pink-100">
                <h4 class="font-sport text-lg text-pink-700 mb-3 flex items-center gap-2 font-bold">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path></svg>
                    Sugestões de Presente
                </h4>
                <ul class="grid grid-cols-1 gap-2 text-sm text-gray-700">
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Acessórios
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Perfumes / Hidratante
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Bolsas
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Itens de beleza
                    </li>
                    <li class="mt-2 text-[11px] italic text-gray-500 border-t border-pink-100 pt-2">
                        Ou um presente de sua preferência
                    </li>
                </ul>
            </div>

            <!-- Interação WhatsApp -->
            <div class="space-y-3 pt-2">
                <label for="guestName" class="text-[10px] font-bold text-gray-400 uppercase tracking-widest ml-1">Confirme sua presença abaixo:</label>
                <input type="text" id="guestName" placeholder="Seu nome completo" 
                    class="w-full px-4 py-4 rounded-xl border border-gray-200 focus:ring-2 focus:ring-pink-500 focus:border-transparent outline-none transition-all text-sm shadow-sm">
                
                <button id="whatsappBtn" class="w-full bg-gray-900 text-white font-sport text-xl py-5 rounded-xl shadow-xl hover:bg-black transition-all flex items-center justify-center gap-3 active:scale-95">
                    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
                    Confirmar Presença
                </button>
            </div>
        </div>

        <!-- Rodapé / Ticket Estilo -->
        <div class="bg-gray-100 border-t border-gray-200 px-8 py-5 flex justify-between items-center italic">
            <span class="text-[10px] font-bold text-gray-400 uppercase tracking-[0.2em]">#Sisil20Anos • B-Day Run 2026</span>
            <div class="flex gap-[3px]">
                <div class="w-[1px] h-3 bg-gray-300"></div>
                <div class="w-[3px] h-3 bg-gray-300"></div>
                <div class="w-[1px] h-3 bg-gray-300"></div>
                <div class="w-[4px] h-3 bg-gray-300"></div>
            </div>
        </div>
    </div>

    <script>
        /**
         * Lógica para capturar o nome e redirecionar para o WhatsApp
         */
        const btn = document.getElementById('whatsappBtn');
        const input = document.getElementById('guestName');

        btn.addEventListener('click', () => {
            const name = input.value.trim();
            if (!name) {
                // Pequeno alerta amigável caso o nome esteja vazio
                alert("Por favor, introduza o seu nome para confirmar a presença.");
                input.focus();
                return;
            }

            const phone = "5592993595954";
            const message = `Olá Sisil! Aqui é ${name}. Confirmo a minha presença no Time da tua Corrida de 20 anos! 🏃‍♀️✨`;
            
            // Criação da URL para o WhatsApp
            const wpUrl = `https://api.whatsapp.com/send?phone=${phone}&text=${encodeURIComponent(message)}`;
            
            // Abrir em nova aba
            window.open(wpUrl, '_blank');
        });

        // Permitir confirmar pressionando 'Enter' no campo de texto
        input.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                btn.click();
            }
        });
    </script>
</body>
</html>
        <!-- Conteúdo Principal -->
        <div class="p-6 sm:p-8 space-y-6">
            
            <!-- Texto de Convite -->
            <div class="text-center">
                <h3 class="font-sport text-2xl text-gray-900 leading-tight italic font-black">A nossa meta é celebrar!</h3>
                <p class="text-gray-500 text-sm mt-2 leading-relaxed">
                    Vinte anos de história merecem uma largada especial. Junte-se ao nosso pelotão para uma comemoração inesquecível na orla.
                </p>
            </div>

            <!-- Informações do Evento -->
            <div class="flex items-center gap-4 bg-gray-50 p-4 rounded-2xl border border-gray-100">
                <div class="flex flex-col items-center justify-center border-r border-gray-200 pr-4">
                    <span class="font-sport text-3xl text-pink-600 leading-none">25</span>
                    <span class="font-sport text-xs text-gray-400">FEV</span>
                </div>
                <div class="flex-1 text-sm">
                    <div class="flex items-center gap-2 text-gray-800 font-bold">
                        <svg class="w-4 h-4 text-pink-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span>17:00h • Ponta Negra</span>
                    </div>
                    <div class="text-pink-600 font-bold mt-1 uppercase text-[10px] tracking-wider italic">Traje Sugerido: Esportivo & Rosa 👟</div>
                </div>
            </div>

            <!-- Sugestões de Presente -->
            <div class="bg-pink-50/50 rounded-2xl p-5 border border-pink-100">
                <h4 class="font-sport text-lg text-pink-700 mb-3 flex items-center gap-2 font-bold">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path></svg>
                    Sugestões de Presente
                </h4>
                <ul class="grid grid-cols-1 gap-2 text-sm text-gray-700">
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Acessórios
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Perfumes / Hidratante
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Bolsas
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Itens de beleza
                    </li>
                    <li class="mt-2 text-[11px] italic text-gray-500 border-t border-pink-100 pt-2">
                        Ou um presente de sua preferência
                    </li>
                </ul>
            </div>

            <!-- Interação WhatsApp -->
            <div class="space-y-3 pt-2">
                <label for="guestName" class="text-[10px] font-bold text-gray-400 uppercase tracking-widest ml-1">Confirme sua presença abaixo:</label>
                <input type="text" id="guestName" placeholder="Seu nome completo" 
                    class="w-full px-4 py-4 rounded-xl border border-gray-200 focus:ring-2 focus:ring-pink-500 focus:border-transparent outline-none transition-all text-sm shadow-sm">
                
                <button id="whatsappBtn" class="w-full bg-gray-900 text-white font-sport text-xl py-5 rounded-xl shadow-xl hover:bg-black transition-all flex items-center justify-center gap-3 active:scale-95">
                    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
                    Confirmar Presença
                </button>
            </div>
        </div>

        <!-- Rodapé / Estilo Ticket -->
        <div class="bg-gray-100 border-t border-gray-200 px-8 py-5 flex justify-between items-center italic">
            <span class="text-[10px] font-bold text-gray-400 uppercase tracking-[0.2em]">#Sisil20Anos • B-Day Run 2026</span>
            <div class="flex gap-[3px]">
                <div class="w-[1px] h-3 bg-gray-300"></div>
                <div class="w-[3px] h-3 bg-gray-300"></div>
                <div class="w-[1px] h-3 bg-gray-300"></div>
                <div class="w-[4px] h-3 bg-gray-300"></div>
            </div>
        </div>
    </div>

    <script>
        /**
         * Lógica para capturar o nome e redirecionar para o WhatsApp (PT-BR)
         */
        const btn = document.getElementById('whatsappBtn');
        const input = document.getElementById('guestName');

        btn.addEventListener('click', () => {
            const name = input.value.trim();
            if (!name) {
                alert("Por favor, digite seu nome para confirmar a presença.");
                input.focus();
                return;
            }

            const phone = "5592993595954";
            const message = `Olá Sisil! Aqui é ${name}. Confirmo minha presença no Time da sua Corrida de 20 anos! 🏃‍♀️✨`;
            
            // Criação da URL para o WhatsApp
            const wpUrl = `https://api.whatsapp.com/send?phone=${phone}&text=${encodeURIComponent(message)}`;
            
            // Abrir em nova aba
            window.open(wpUrl, '_blank');
        });

        // Permitir confirmar pressionando 'Enter' no campo de texto
        input.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                btn.click();
            }
        });
    </script>
</body>
</html>                    <span class="font-sport text-pink-100 text-xl sm:text-2xl tracking-widest italic">Edição Especial 20 Anos</span>
                    <div class="h-[2px] w-6 bg-pink-300"></div>
                </div>
            </div>
        </div>

        <!-- Conteúdo Principal -->
        <div class="p-6 sm:p-8 space-y-6">
            
            <!-- Texto de Convite -->
            <div class="text-center">
                <h3 class="font-sport text-2xl text-gray-900 leading-tight italic font-black">A nossa meta é celebrar!</h3>
                <p class="text-gray-500 text-sm mt-2 leading-relaxed">
                    Vinte anos de história merecem uma largada especial. Junte-se ao nosso pelotão para uma comemoração inesquecível na orla.
                </p>
            </div>

            <!-- Informações do Evento -->
            <div class="flex items-center gap-4 bg-gray-50 p-4 rounded-2xl border border-gray-100">
                <div class="flex flex-col items-center justify-center border-r border-gray-200 pr-4">
                    <span class="font-sport text-3xl text-pink-600 leading-none">25</span>
                    <span class="font-sport text-xs text-gray-400">FEV</span>
                </div>
                <div class="flex-1 text-sm">
                    <div class="flex items-center gap-2 text-gray-800 font-bold">
                        <svg class="w-4 h-4 text-pink-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span>17:00h • Ponta Negra</span>
                    </div>
                    <div class="text-pink-600 font-bold mt-1 uppercase text-[10px] tracking-wider">Traje Sugerido: Esportivo & Rosa 👟</div>
                </div>
            </div>

            <!-- Sugestões de Presente -->
            <div class="bg-pink-50/50 rounded-2xl p-5 border border-pink-100">
                <h4 class="font-sport text-lg text-pink-700 mb-3 flex items-center gap-2 font-bold">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path></svg>
                    Sugestões de Presente
                </h4>
                <ul class="grid grid-cols-1 gap-2 text-sm text-gray-700">
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Acessórios
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Perfumes / Hidratante
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Bolsas
                    </li>
                    <li class="flex items-center gap-2 font-semibold">
                        <span class="text-pink-400 text-lg leading-none">•</span> Itens de beleza
                    </li>
                    <li class="mt-2 text-[11px] italic text-gray-500 border-t border-pink-100 pt-2">
                        Ou um presente de sua preferência
                    </li>
                </ul>
            </div>

            <!-- Interação WhatsApp -->
            <div class="space-y-3 pt-2">
                <label for="guestName" class="text-[10px] font-bold text-gray-400 uppercase tracking-widest ml-1">Confirme sua presença abaixo:</label>
                <input type="text" id="guestName" placeholder="Seu nome completo" 
                    class="w-full px-4 py-4 rounded-xl border border-gray-200 focus:ring-2 focus:ring-pink-500 focus:border-transparent outline-none transition-all text-sm shadow-sm">
                
                <button id="whatsappBtn" class="w-full bg-gray-900 text-white font-sport text-xl py-5 rounded-xl shadow-xl hover:bg-black transition-all flex items-center justify-center gap-3 active:scale-95">
                    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
                    Confirmar Presença
                </button>
            </div>
        </div>

        <!-- Rodapé / Ticket Estilo -->
        <div class="bg-gray-100 border-t border-gray-200 px-8 py-5 flex justify-between items-center italic">
            <span class="text-[10px] font-bold text-gray-400 uppercase tracking-[0.2em]">#Sisil20Anos • B-Day Run 2026</span>
            <div class="flex gap-[3px]">
                <div class="w-[1px] h-3 bg-gray-300"></div>
                <div class="w-[3px] h-3 bg-gray-300"></div>
                <div class="w-[1px] h-3 bg-gray-300"></div>
                <div class="w-[4px] h-3 bg-gray-300"></div>
            </div>
        </div>
    </div>

    <script>
        /**
         * Lógica para capturar o nome e redirecionar para o WhatsApp
         */
        const btn = document.getElementById('whatsappBtn');
        const input = document.getElementById('guestName');

        btn.addEventListener('click', () => {
            const name = input.value.trim();
            if (!name) {
                // Pequeno alerta amigável caso o nome esteja vazio
                alert("Por favor, introduza o seu nome para confirmar a presença.");
                input.focus();
                return;
            }

            const phone = "5592993595954";
            const message = `Olá Sisil! Aqui é ${name}. Confirmo a minha presença no Time da tua Corrida de 20 anos! 🏃‍♀️✨`;
            
            // Criação da URL para o WhatsApp
            const wpUrl = `https://api.whatsapp.com/send?phone=${phone}&text=${encodeURIComponent(message)}`;
            
            // Abrir em nova aba
            window.open(wpUrl, '_blank');
        });

        // Permitir confirmar pressionando 'Enter' no campo de texto
        input.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                btn.click();
            }
        });
    </script>
</body>
</html>
