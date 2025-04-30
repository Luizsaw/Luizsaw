<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luiz Carlos Machado | Desenvolvedor & Cloud Enthusiast</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0f172a;
            color: #e2e8f0;
        }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #8b5cf6);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(59, 130, 246, 0.3);
        }
        .tech-icon {
            transition: all 0.3s ease;
        }
        .tech-icon:hover {
            transform: scale(1.2);
            filter: drop-shadow(0 0 8px rgba(59, 130, 246, 0.6));
        }
        .social-icon {
            transition: all 0.3s ease;
        }
        .social-icon:hover {
            transform: scale(1.1);
        }
        .typewriter {
            overflow: hidden;
            border-right: .15em solid #3b82f6;
            white-space: nowrap;
            margin: 0 auto;
            letter-spacing: .15em;
            animation: 
                typing 3.5s steps(40, end),
                blink-caret .75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #3b82f6; }
        }
        .pulse {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body class="min-h-screen">
    <div class="container mx-auto px-4 py-12 max-w-6xl">
        <!-- Header Section -->
        <header class="text-center mb-16">
            <div class="flex justify-center mb-6">
                <div class="relative">
                    <img src="https://avatars.githubusercontent.com/u/12345678?v=4" alt="Luiz Carlos Machado" 
                         class="w-40 h-40 rounded-full border-4 border-blue-500 shadow-lg pulse">
                    <span class="absolute bottom-0 right-0 bg-green-500 text-white text-xs font-bold px-2 py-1 rounded-full">ONLINE</span>
                </div>
            </div>
            <h1 class="text-4xl md:text-5xl font-bold mb-2 gradient-text">Luiz Carlos Machado</h1>
            <p class="text-xl text-blue-300 mb-4 typewriter">Desenvolvedor | AWS Enthusiast | IA Aprendiz</p>
            <div class="flex flex-wrap justify-center gap-4 text-sm md:text-base mb-6">
                <span class="flex items-center"><i class="fas fa-map-marker-alt mr-2 text-blue-400"></i> Santos/SP → São Vicente</span>
                <span class="flex items-center"><i class="fas fa-graduation-cap mr-2 text-blue-400"></i> Análise e Desenvolvimento de Sistemas</span>
                <span class="flex items-center"><i class="fas fa-cloud mr-2 text-blue-400"></i> Estudante AWS</span>
            </div>
            <!-- Social Links -->
            <div class="flex justify-center space-x-4 mb-8">
                <a href="https://github.com/Luizsaw" target="_blank" class="social-icon bg-gray-800 hover:bg-gray-700 text-white w-10 h-10 rounded-full flex items-center justify-center">
                    <i class="fab fa-github text-lg"></i>
                </a>
                <a href="https://www.linkedin.com/in/luiz-machado-57366a174/" target="_blank" class="social-icon bg-blue-600 hover:bg-blue-700 text-white w-10 h-10 rounded-full flex items-center justify-center">
                    <i class="fab fa-linkedin-in text-lg"></i>
                </a>
                <a href="https://www.instagram.com/luiz_saw/" target="_blank" class="social-icon bg-pink-600 hover:bg-pink-700 text-white w-10 h-10 rounded-full flex items-center justify-center">
                    <i class="fab fa-instagram text-lg"></i>
                </a>
                <a href="mailto:luizsaw@gmail.com" class="social-icon bg-red-500 hover:bg-red-600 text-white w-10 h-10 rounded-full flex items-center justify-center">
                    <i class="fas fa-envelope text-lg"></i>
                </a>
            </div>
            <div class="flex flex-wrap justify-center gap-4">
                <div class="bg-blue-900/30 px-4 py-2 rounded-full flex items-center">
                    <i class="fas fa-star mr-2 text-yellow-400"></i>
                    <span id="github-stars">Loading...</span>
                </div>
                <div class="bg-blue-900/30 px-4 py-2 rounded-full flex items-center">
                    <i class="fas fa-users mr-2 text-blue-400"></i>
                    <span id="github-followers">Loading...</span>
                </div>
            </div>
        </header>
        <!-- Main Content -->
        <main>
            <!-- About Section -->
            <section class="mb-16">
                <div class="bg-gray-800/50 backdrop-blur-sm rounded-xl p-6 shadow-lg card-hover">
                    <h2 class="text-2xl font-bold mb-4 gradient-text flex items-center">
                        <i class="fas fa-user-astronaut mr-3"></i> Sobre Mim
                    </h2>
                    <p class="mb-4 text-gray-300">
                        Sou um eterno estudante de tecnologia, determinado a transformar teoria em prática e pronto para contribuir com inovação e criatividade. Estou em busca da minha primeira oportunidade profissional na área, onde eu possa aplicar meus conhecimentos, aprender com os melhores e crescer junto à equipe.
                    </p>
                    <p class="text-gray-300">
                        Desde criança, sou fascinado por tecnologia e como ela transforma o mundo. Hoje, mergulho nos estudos de <span class="text-blue-400 font-semibold">computação em nuvem (AWS)</span> e <span class="text-purple-400 font-semibold">IA</span>, buscando me especializar em soluções inovadoras e escaláveis.
                    </p>
                </div>
            </section>
            <!-- Welcome Section -->
            <section class="mb-16">
                <div class="bg-gradient-to-r from-blue-900/30 to-purple-900/30 rounded-xl p-6 shadow-lg card-hover">
                    <h2 class="text-2xl font-bold mb-4 gradient-text flex items-center">
                        <i class="fas fa-rocket mr-3"></i> Bem-vindo ao meu GitHub!
                    </h2>
                    <p class="text-gray-300">
                        Aqui você encontrará projetos de aprendizado, desde os mais simples até soluções estruturadas, que refletem minha evolução contínua nesse universo tech. Cada linha de código representa um passo na minha jornada de conhecimento.
                    </p>
                </div>
            </section>
            <!-- Technologies Section -->
            <section class="mb-16">
                <h2 class="text-2xl font-bold mb-6 gradient-text text-center">
                    <i class="fas fa-code mr-2"></i> Tecnologias & Ferramentas
                </h2>
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-6">
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" 
                             alt="Java" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">Java</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" 
                             alt="Docker" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">Docker</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" 
                             alt="PostgreSQL" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">PostgreSQL</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" 
                             alt="SQL" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">SQL</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" 
                             alt="Linux" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">Linux</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" 
                             alt="C#" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">C#</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" 
                             alt="AWS" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">AWS</span>
                    </div>
                    <div class="flex flex-col items-center">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
                             alt="Git" class="tech-icon w-16 h-16 mb-2">
                        <span class="text-sm text-gray-300">Git</span>
                    </div>
                </div>
            </section> 
            <!-- Projects Section -->
            <section class="mb-16">
                <h2 class="text-2xl font-bold mb-6 gradient-text text-center">
                    <i class="fas fa-project-diagram mr-2"></i> Projetos Destacados
                </h2>
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="bg-gray-800/50 rounded-xl p-6 shadow-lg card-hover">
                        <h3 class="text-xl font-semibold mb-2 text-blue-400">Sistema Folha de Pagamento</h3>
                        <p class="text-gray-400 mb-4">Um sistema completo para gestão de folha de pagamento desenvolvido como projeto acadêmico.</p>
                        <a href="https://github.com/Luizsaw/RHS_Folha_de_Ponto" target="_blank" class="inline-flex items-center text-blue-400 hover:text-blue-300">
                            Ver no GitHub <i class="fas fa-external-link-alt ml-2"></i>
                        </a>
                    </div>
                    <div class="bg-gray-800/50 rounded-xl p-6 shadow-lg card-hover">
                        <h3 class="text-xl font-semibold mb-2 text-purple-400">Game: Inside me</h3>
                        <p class="text-gray-400 mb-4">Jogo educativo sobre depressão na adolescência, desenvolvido com propósito social.</p>
                        <a href="https://github.com/Luizsaw/Projeto-Insideme" target="_blank" class="inline-flex items-center text-purple-400 hover:text-purple-300">
                            Ver no GitHub <i class="fas fa-external-link-alt ml-2"></i>
                        </a>
                    </div>
                </div>
            </section>
            <!-- GitHub Stats Section -->
            <section class="mb-16">
                <h2 class="text-2xl font-bold mb-6 gradient-text text-center">
                    <i class="fas fa-chart-line mr-2"></i> Estatísticas do GitHub
                </h2>
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="bg-gray-800/50 rounded-xl p-6 shadow-lg card-hover">
                        <img src="https://github-readme-stats.vercel.app/api?username=Luizsaw&show_icons=true&theme=tokyonight&include_all_commits=true&locale=pt-br" 
                             alt="GitHub Stats" class="w-full">
                    </div>
                    <div class="bg-gray-800/50 rounded-xl p-6 shadow-lg card-hover">
                        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Luizsaw&theme=tokyonight&layout=compact&custom_title=Tecnologias&langs_count=9" 
                             alt="Top Languages" class="w-full">
                    </div>
                </div>
            </section>
            <!-- Contact CTA -->
            <section class="text-center">
                <div class="bg-gradient-to-r from-blue-900/30 to-purple-900/30 rounded-xl p-8 shadow-lg card-hover">
                    <h2 class="text-2xl font-bold mb-4 gradient-text">Vamos conversar?</h2>
                    <p class="text-gray-300 mb-6">Será um prazer conectar e trocar ideias sobre tecnologia, projetos ou oportunidades!</p>
                    <a href="mailto:luizsaw@gmail.com" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-full transition-all duration-300 transform hover:scale-105">
                        <i class="fas fa-paper-plane mr-2"></i> Enviar Mensagem
                    </a>
                </div>
            </section>
        </main>
        <!-- Footer -->
        <footer class="mt-16 text-center text-gray-500 text-sm">
            <p>© 2023 Luiz Carlos Machado. Todos os direitos reservados.</p>
            <p class="mt-2">Feito com <i class="fas fa-heart text-red-500"></i> e muito código</p>
        </footer>
    </div>
    <script>
        // GitHub API fetch for stars and followers
        async function fetchGitHubStats() {
            try {
                const response = await fetch('https://api.github.com/users/Luizsaw');
                const data = await response.json();
                document.getElementById('github-stars').textContent = `${data.public_repos} Repositórios`;
                document.getElementById('github-followers').textContent = `${data.followers} Seguidores`;
            } catch (error) {
                console.error('Error fetching GitHub stats:', error);
                document.getElementById('github-stars').textContent = 'Repositórios';
                document.getElementById('github-followers').textContent = 'Seguidores';
            }
        }
        // Typewriter effect
        function setupTypewriter() {
            const elements = document.querySelectorAll('.typewriter');
            elements.forEach(el => {
                const text = el.textContent;
                el.textContent = '';
                let i = 0;
                function type() {
                    if (i < text.length) {
                        el.textContent += text.charAt(i);
                        i++;
                        setTimeout(type, 100);
                    } else {
                        el.style.borderRight = 'none';
                    }
                }
                type();
            });
        }
        // Initialize animations
        document.addEventListener('DOMContentLoaded', () => {
            fetchGitHubStats();
            setupTypewriter();
            // Add hover effects to cards
            const cards = document.querySelectorAll('.card-hover');
            cards.forEach(card => {
                card.addEventListener('mouseenter', () => {
                    card.classList.add('shadow-xl');
                });
                card.addEventListener('mouseleave', () => {
                    card.classList.remove('shadow-xl');
                });
            });
        });
    </script>
</body>
</html>
