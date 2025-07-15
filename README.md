<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Instituto Akangatu</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-orange-50 text-gray-800">

  <!-- Hero Section -->
  <header class="bg-orange-600 text-white">
    <div class="max-w-7xl mx-auto px-6 py-12 flex flex-col-reverse md:flex-row items-center">
      <div class="md:w-1/2 mt-6 md:mt-0">
        <h1 class="text-4xl font-bold mb-4">Instituto Akangatu</h1>
        <p class="text-lg mb-4">Receba seu TCC com aprovação garantida e em 24 horas!</p>
        <a href="#contato" class="inline-block bg-white text-orange-600 px-6 py-2 rounded-full font-semibold hover:bg-orange-100 transition">Fale Conosco</a>
      </div>
      <div class="md:w-1/2">
        <img src="https://images.unsplash.com/photo-1603570419883-7a9c94c8b5f8?auto=format&fit=crop&w=800&q=80" alt="Jovem negra com livros" class="rounded-xl shadow-lg">
      </div>
    </div>
  </header>

  <!-- Serviços -->
  <section class="py-16 px-6 max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-orange-700 mb-6 text-center">Nossos Serviços</h2>
    <p class="text-center mb-10 max-w-2xl mx-auto text-lg">Oferecemos suporte completo na produção de TCCs, com aprovação garantida, agilidade e atendimento especializado.</p>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
        <h3 class="text-xl font-semibold text-orange-600 mb-2">TCC com aprovação</h3>
        <p>Produzimos seu TCC com qualidade, seguindo as normas da sua instituição.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
        <h3 class="text-xl font-semibold text-orange-600 mb-2">Mentorias Personalizadas</h3>
        <p>Acompanhamento individual para orientar alunos em todas as etapas do TCC.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
        <h3 class="text-xl font-semibold text-orange-600 mb-2">Revisões e Formatações</h3>
        <p>Ajustamos seu trabalho conforme ABNT, APA, ou normas específicas da sua faculdade.</p>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="bg-white py-16 px-6">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl font-bold text-orange-700 mb-8 text-center">Entre em Contato</h2>
      <form action="#" method="POST" class="grid gap-6">
        <input type="text" name="nome" placeholder="Seu nome" required class="p-4 border border-gray-300 rounded-lg">
        <input type="email" name="email" placeholder="Seu e-mail" required class="p-4 border border-gray-300 rounded-lg">
        <textarea name="mensagem" placeholder="Sua mensagem" rows="5" required class="p-4 border border-gray-300 rounded-lg"></textarea>
        <button type="submit" class="bg-orange-600 text-white font-semibold py-3 rounded-lg hover:bg-orange-700 transition">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="bg-orange-600 text-white text-center py-6">
    <p>📍 RS | 📞 WhatsApp: (47) 99726-0888</p>
    <p>📸 Instagram: <a href="https://www.instagram.com/instituto.akangatu" target="_blank" class="underline">/instituto.akangatu</a></p>
    <p class="mt-2 text-sm">&copy; 2025 Instituto Akangatu. Todos os direitos reservados.</p>
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
