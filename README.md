<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Camisas X Store</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-white">

<header class="p-5 text-center border-b border-red-600">
  <h1 class="text-3xl font-bold text-red-500">Camisas X Store</h1>
  <p class="text-gray-400">Vista sua paixão ⚽</p>
</header>

<section class="text-center py-10">
  <h2 class="text-2xl font-semibold">🔥 Camisas Premium de Futebol</h2>
  <p class="text-gray-400">Entrega para todo o Brasil 🚚</p>
</section>

<section class="grid grid-cols-1 md:grid-cols-3 gap-6 p-6">

  <div class="bg-zinc-900 p-4 rounded-2xl shadow-lg">
    <img src="https://via.placeholder.com/300" class="rounded-xl mb-3">
    <h3 class="text-lg">Camisa Flamengo</h3>
    <p class="text-red-500 font-bold">R$ 129,90</p>
    <button onclick="comprar('Camisa Flamengo')" class="mt-3 bg-red-600 px-4 py-2 rounded-xl w-full">Comprar</button>
  </div>

  <div class="bg-zinc-900 p-4 rounded-2xl shadow-lg">
    <img src="https://via.placeholder.com/300" class="rounded-xl mb-3">
    <h3 class="text-lg">Camisa Barcelona</h3>
    <p class="text-red-500 font-bold">R$ 139,90</p>
    <button onclick="comprar('Camisa Barcelona')" class="mt-3 bg-red-600 px-4 py-2 rounded-xl w-full">Comprar</button>
  </div>

  <div class="bg-zinc-900 p-4 rounded-2xl shadow-lg">
    <img src="https://via.placeholder.com/300" class="rounded-xl mb-3">
