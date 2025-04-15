<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Création de Planning UE</title>
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@3.4.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      .bg-custom {
        background-color: #f1f5f9;
      }
    </style>
  </head>
  <body class="bg-custom min-h-screen">
    <header class="bg-white py-4 px-6 shadow-md flex justify-between items-center">
      <h1 class="text-2xl font-bold text-gray-800">Création de Planning UE</h1>
      <button
        class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700 transition duration-300"
      >
        Enregistrer
      </button>
    </header>

    <main class="p-6">
      <div class="overflow-x-auto">
        <table class="min-w-full border border-gray-300">
          <thead>
            <tr class="bg-gray-200">
              <th class="border border-gray-300 px-4 py-2">Heures</th>
              <th class="border border-gray-300 px-4 py-2">Lundi</th>
              <th class="border border-gray-300 px-4 py-2">Mardi</th>
              <th class="border border-gray-300 px-4 py-2">Mercredi</th>
              <th class="border border-gray-300 px-4 py-2">Jeudi</th>
              <th class="border border-gray-300 px-4 py-2">Vendredi</th>
              <th class="border border-gray-300 px-4 py-2">Samedi</th>
            </tr>
          </thead>
          <tbody>
            <!-- Exemples de lignes, vous pouvez en ajouter ou modifier -->
            <tr>
              <td class="border border-gray-300 px-4 py-2">08:00 - 09:00</td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
            </tr>
            <tr class="bg-white">
              <td class="border border-gray-300 px-4 py-2">09:00 - 10:00</td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
              <td class="border border-gray-300 px-4 py-2" contenteditable="true"></td>
            </tr>
            <!-- Ajoutez plus de lignes ici -->
          </tbody>
        </table>
      </div>
    </main>

    <footer class="text-center text-gray-500 text-sm mt-6">
      &copy; 2024 - Créé par Tristan
    </footer>
  </body>
</html>
