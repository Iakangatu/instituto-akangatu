<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Instituto Akangatu</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    .fade-in-up {
      animation: fadeInUp 1s ease-out forwards;
    }
  </style>
</head>
<body class="text-white">

  <!-- Seção com Imagem de Fundo -->
  <section class="relative h-screen w-full bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?auto=format&fit=crop&w=1950&q=80');">
    <!-- Overlay escuro -->
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>

    <!-- Conteúdo central -->
    <div class="relative z-10 flex flex-col items-center justify-center h-full text-center px-6 fade-in-up">
      <h1 class="text-4xl md:text-6xl font-bold mb-4">Instituto Akangatu</h1>
      <p class="text-lg md:text-2xl mb-6">Receba seu TCC com aprovação garantida e em 24 horas!</p>
      <a href="#contato" class="bg-orange-500 text-white px-6 py-3 rounded-full font-semibold hover:bg-orange-600 transition">Fale Conosco</a>
    </div>
  </section>

  <!-- Serviços -->
  <section class="bg-gradient-to-b from-purple-300 via-purple-500 to-blue-900 py-16 px-6">
    <div class="max-w-6xl mx-auto text-center fade-in-up">
      <h2 class="text-3xl font-bold mb-6">Nossos Serviços</h2>
      <p class="mb-10 text-white/90 max-w-2xl mx-auto">Produção de TCCs, mentorias e serviços educacionais com foco em aprovação e excelência acadêmica.</p>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white/10 backdrop-blur p-6 rounded-lg border border-white/20 hover:shadow-md transition">
          <h3 class="text-xl font-semibold text-white mb-2">TCC com aprovação</h3>
          <p>Trabalhos acadêmicos completos e aprovados com excelência.</p>
        </div>
        <div class="bg-white/10 backdrop-blur p-6 rounded-lg border border-white/20 hover:shadow-md transition">
          <h3 class="text-xl font-semibold text-white mb-2">Mentorias</h3>
          <p>Suporte individual em todas as etapas do seu TCC.</p>
        </div>
        <div class="bg-white/10 backdrop-blur p-6 rounded-lg border border-white/20 hover:shadow-md transition">
          <h3 class="text-xl font-semibold text-white mb-2">Revisões e Formatação</h3>
          <p>Adequação às normas ABNT, APA, Vancouver e outras exigidas.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="bg-white text-gray-900 py-16 px-6">
    <div class="max-w-3xl mx-auto text-center fade-in-up">
      <h2 class="text-3xl font-bold mb-8">Entre em Contato</h2>
      <form action="#" method="POST" class="grid gap-6 text-left">
        <input type="text" name="nome" placeholder="Seu nome" required class="p-4 border border-gray-300 rounded-lg">
        <input type="email" name="email" placeholder="Seu e-mail" required class="p-4 border border-gray-300 rounded-lg">
        <textarea name="mensagem" placeholder="Sua mensagem" rows="5" required class="p-4 border border-gray-300 rounded-lg"></textarea>
        <button type="submit" class="bg-orange-600 text-white font-semibold py-3 rounded-lg hover:bg-orange-700 transition">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="bg-gray-900 text-white text-center py-6">
    <p>📍 RS | 📞 WhatsApp: (47) 99726-0888</p>
    <p>📸 Instagram: <a href="https://www.instagram.com/instituto.akangatu" target="_blank" class="underline">/instituto.akangatu</a></p>
    <p class="mt-2 text-sm text-white/70">&copy; 2025 Instituto Akangatu. Todos os direitos reservados.</p>
  </footer>

  <!-- Botão WhatsApp Flutuante -->
  <div class="fixed bottom-5 right-5 z-50">
    <a href="https://wa.me/5547997260888" target="_blank"
      class="bg-green-500 text-white px-4 py-3 rounded-full shadow-lg flex items-center gap-2 hover:bg-green-600 transition">
      <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp" class="w-5 h-5">
      WhatsApp
    </a>
  </div>

</body>
</html>

