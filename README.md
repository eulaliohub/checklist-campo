<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Checklist Campo – PrimusGFS v3.2 (Módulo 2)</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/lucide@latest"></script>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
  <style>
    input[type="file"] { display:none; }
    .accordion-content { display: none; }
  </style>
</head>
<body class="bg-gray-50 min-h-screen">
<div class="max-w-6xl mx-auto p-4 sm:p-8">
  <header class="flex flex-col gap-4 sm:flex-row sm:items-center sm:justify-between mb-6">
    <div>
      <h1 class="text-2xl sm:text-3xl font-bold">Checklist de Campo – PrimusGFS v3.2</h1>
      <p class="text-gray-600">Módulo 2: Granja (resumido para uso en campo)</p>
    </div>
    <div class="flex gap-2">
      <button id="btnCalcular" class="px-4 py-2 rounded-xl bg-blue-600 text-white shadow hover:opacity-90">Calcular</button>
      <button id="btnGuardar" class="px-4 py-2 rounded-xl bg-emerald-600 text-white shadow hover:opacity-90">Guardar</button>
      <button id="btnPDF" class="px-4 py-2 rounded-xl bg-indigo-600 text-white shadow hover:opacity-90">Exportar PDF</button>
      <button id="btnLimpiar" class="px-4 py-2 rounded-xl bg-gray-200 text-gray-700 shadow hover:opacity-90">Limpiar</button>
    </div>
  </header>

  <!-- Datos generales -->
  <section class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 mb-6 bg-white p-4 rounded-2xl shadow">
    <div>
      <label class="block text-sm font-semibold">Campo/Huerta </label>
      <input list="huertas" id="campo" class="w-full mt-1 p-2 border rounded-xl" placeholder="Ingresa o selecciona una huerta" />
      <datalist id="huertas">
        <option value="La Presa"></option>
        <option value="Santa Lucía"></option>
        <option value="Benazuza 1"></option>
        <option value="Benazuza 2"></option>
        <option value="Copalita 1"></option>
        <option value="Copalita 2"></option>
        <option value="El Colorado"></option>
      </datalist>
    </div>
    <div>
      <label class="block text-sm font-semibold">Evaluador</label>
      <input id="evaluador" class="w-full mt-1 p-2 border rounded-xl" placeholder="Nombre del evaluador" />
    </div>
    <div>
      <label class="block text-sm font-semibold">Fecha</label>
      <input id="fecha" type="date" class="w-full mt-1 p-2 border rounded-xl" />
    </div>
  </section>

  <!-- Checklist y dashboard aquí (idéntico al tuyo) -->

</div>

<script>
  // Todo el JS que ya tenías: banco de preguntas, persistencia, cálculo, PDF, etc.
  // Solo asegúrate que el ID del campo de huerta es 'campo' como en este HTML.
</script>
</body>
</html>
