Barbería & Peluquería
Sistema Inteligente de Turnos
  <!-- Banner de Estado de Licencia -->
  <div id="licenseBanner" class="flex items-center gap-2 bg-amber-500/10 border border-amber-500/30 px-3 py-1.5 rounded-full text-xs text-amber-400">
    <i data-lucide="clock" class="w-4 h-4"></i>
    <span>Prueba Gratuita: <strong id="daysLeftText">30 días restantes</strong></span>
    <button onclick="openPaymentModal()" class="ml-2 bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold px-2.5 py-1 rounded-full text-xs transition">
      Activar Pro ($10/mes)
    </button>
  </div>
</div>

<!-- SELECTOR DE VISTA (Peluquero / Cliente) -->
<div class="bg-slate-800/80 p-1.5 rounded-xl border border-slate-700 flex text-sm font-semibold">
  <button id="tabBarber" onclick="switchView('barber')" class="flex-1 py-2 rounded-lg bg-amber-500 text-slate-950 flex items-center justify-center gap-2 transition shadow">
    <i data-lucide="user-cog" class="w-4 h-4"></i> Panel del Barbero
  </button>
  <button id="tabClient" onclick="switchView('client')" class="flex-1 py-2 rounded-lg text-slate-400 hover:text-white flex items-center justify-center gap-2 transition">
    <i data-lucide="users" class="w-4 h-4"></i> Vista del Cliente
  </button>
</div>

<!-- VISTA DEL BARBERO -->
<section id="barberView" class="space-y-6">
  
  <!-- Personalización de Marca -->
  <div class="bg-slate-800 border border-slate-700 rounded-2xl p-5 space-y-4">
    <h2 class="text-base font-bold flex items-center gap-2 text-amber-400">
      <i data-lucide="store" class="w-5 h-5"></i> Personaliza tu Negocio (Gratis)
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Nombre de la Barbería</label>
        <input type="text" id="inputBarberName" placeholder="Ej: Barbería El Estilo" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm text-white focus:border-amber-500 outline-none">
      </div>
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Logo de la Barbería (Imagen)</label>
        <input type="file" id="inputBarberLogo" accept="image/*" class="w-full text-xs text-slate-400 file:mr-3 file:py-2 file:px-3 file:rounded-xl file:border-0 file:text-xs file:font-semibold file:bg-amber-500/10 file:text-amber-400 hover:file:bg-amber-500/20 cursor-pointer">
      </div>
    </div>
    <button onclick="saveBrandSettings()" class="bg-slate-700 hover:bg-slate-600 text-white font-semibold text-xs px-4 py-2 rounded-xl transition">
      Guardar Cambios
    </button>
  </div>

  <!-- Configuración de Jornada -->
  <div class="bg-slate-800 border border-slate-700 rounded-2xl p-5 space-y-4">
    <h2 class="text-base font-bold flex items-center gap-2 text-amber-400">
      <i data-lucide="calendar" class="w-5 h-5"></i> Configurar Jornada del Día
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Hora de Inicio</label>
        <input type="time" id="startTime" value="09:00" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm text-white focus:border-amber-500 outline-none">
      </div>
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Hora de Cierre</label>
        <input type="time" id="endTime" value="18:00" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm text-white focus:border-amber-500 outline-none">
      </div>
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Duración por Turno</label>
        <select id="slotDuration" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm text-white focus:border-amber-500 outline-none">
          <option value="45">45 minutos</option>
          <option value="50">50 minutos</option>
          <option value="30">30 minutos</option>
          <option value="60">60 minutos</option>
        </select>
      </div>
    </div>
    <button onclick="generateSlots()" class="w-full bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold py-2.5 rounded-xl transition shadow flex items-center justify-center gap-2 text-sm">
      <i data-lucide="play" class="w-4 h-4"></i> Abrir Jornada y Generar Turnos
    </button>
  </div>

  <!-- Compartir con Clientes / QR -->
  <div class="bg-slate-800 border border-slate-700 rounded-2xl p-5 flex flex-col sm:flex-row items-center justify-between gap-4">
    <div>
      <h3 class="font-bold text-white text-sm">Enlace Directo para Clientes</h3>
      <p class="text-xs text-slate-400">Comparte este enlace por WhatsApp o en tus redes sociales para que tus clientes reserven desde casa.</p>
    </div>
    <div class="flex gap-2 w-full sm:w-auto">
      <button onclick="copyClientLink()" class="flex-1 sm:flex-initial bg-slate-700 hover:bg-slate-600 text-white font-semibold px-4 py-2 rounded-xl text-xs flex items-center justify-center gap-1.5 transition">
        <i data-lucide="copy" class="w-4 h-4"></i> Copiar Link
      </button>
      <button onclick="showQRModal()" class="flex-1 sm:flex-initial bg-amber-500/10 border border-amber-500/30 text-amber-400 hover:bg-amber-500/20 font-semibold px-4 py-2 rounded-xl text-xs flex items-center justify-center gap-1.5 transition">
        <i data-lucide="qr-code" class="w-4 h-4"></i> Ver QR
      </button>
    </div>
  </div>

  <!-- Turnos Agendados del Día -->
  <div class="bg-slate-800 border border-slate-700 rounded-2xl p-5 space-y-4">
    <div class="flex items-center justify-between">
      <h2 class="text-base font-bold text-white flex items-center gap-2">
        <i data-lucide="list-checks" class="w-5 h-5 text-amber-500"></i> Lista de Turnos del Día
      </h2>
      <span id="turnCounter" class="bg-slate-700 text-amber-400 text-xs px-2.5 py-1 rounded-full font-bold">0 Reservados</span>
    </div>
    
    <div id="barberSlotsContainer" class="space-y-2">
      <p class="text-xs text-slate-400 text-center py-6">Haz clic en "Abrir Jornada y Generar Turnos" para comenzar el día.</p>
    </div>
  </div>
</section>

<!-- VISTA DEL CLIENTE -->
<section id="clientView" class="space-y-6 hidden">
  <div class="bg-slate-800 border border-slate-700 rounded-2xl p-5 space-y-4">
    <div class="text-center space-y-1">
      <h2 class="text-lg font-bold text-white">Reserva tu Turno</h2>
      <p class="text-xs text-slate-400">Selecciona el horario disponible que más te convenga</p>
    </div>

    <div class="space-y-3 pt-2">
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Tu Nombre Completo</label>
        <input type="text" id="clientName" placeholder="Ej: Carlos Gómez" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm text-white focus:border-amber-500 outline-none">
      </div>
      <div>
        <label class="block text-xs font-medium text-slate-400 mb-1">Número de Teléfono (Opcional)</label>
        <input type="tel" id="clientPhone" placeholder="Ej: 809-555-0199" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-sm text-white focus:border-amber-500 outline-none">
      </div>
    </div>

    <div class="pt-2">
      <label class="block text-xs font-medium text-slate-400 mb-2">Horarios Disponibles para Hoy</label>
      <div id="clientSlotsGrid" class="grid grid-cols-2 sm:grid-cols-3 gap-2">
        <p class="col-span-full text-xs text-slate-400 text-center py-4">No hay turnos disponibles por el momento.</p>
      </div>
    </div>
  </div>
</section>

Código QR para Mostrar en Local
Escanea este código con el celular para acceder al formulario de turnos.
        Cerrar
       Suscripción Pro ($10/mes)
        
  <p class="text-xs text-slate-300 leading-relaxed">
    Paga de forma segura con tu <strong>tarjeta de crédito/débito (Visa, Mastercard)</strong> o saldo <strong>PayPal</strong> para renovar tu suscripción mensual.
  </p>

  <!-- Botón Oficial de PayPal -->
  <div class="pt-2">
    <a id="paypalPayBtn" href="https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=TU_CORREO_PAYPAL@EMAIL.COM&item_name=Suscripcion+Pro+TurnoFacil&amount=10.00&currency_code=USD" target="_blank" onclick="confirmPayPalPayment()" class="w-full bg-[#0070ba] hover:bg-[#005ea6] text-white font-bold py-3 px-4 rounded-xl transition shadow flex items-center justify-center gap-2 text-sm">
      <svg class="w-5 h-5 fill-current" viewBox="0 0 24 24"><path d="M20.067 8.478c.492.315.844.823.967 1.453.254 1.291-.237 2.651-1.282 3.551-.95.823-2.222 1.258-3.483 1.258h-1.615c-.443 0-.825.32-.906.757l-.801 4.256c-.05.27-.282.467-.557.467h-3.134c-.381 0-.663-.356-.596-.731l2.42-12.879c.071-.382.404-.653.792-.653h5.083c1.298 0 2.454.437 3.112 1.525z"/></svg>
      Pagar $10.00 USD con Tarjeta / PayPal
    </a>
  </div>

  <!-- Verificación / Clave de Activación -->
  <div class="border-t border-slate-700 pt-3 space-y-2">
    <p class="text-[11px] text-slate-400">¿Ya realizaste el pago? Introduce tu clave de activación:</p>
    <div class="flex gap-2">
      <input type="text" id="activationCode" placeholder="Ej: PRO2026" class="flex-1 bg-slate-900 border border-slate-700 rounded-xl px-3 py-1.5 text-xs text-white outline-none">
      <button onclick="activateProWithCode()" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold px-3 py-1.5 rounded-xl text-xs">
        Activar
      </button>
    </div>
  </div>
</div>

    // Inicializar Lucide Icons
    lucide.createIcons();

    // TU CORREO DE PAYPAL PARA RECIBIR LOS PAGOS:
    const MI_CORREO_PAYPAL = 'elblack043056@gmail.com'; // <--- ¡CAMBIA ESTO POR TU CORREO DE PAYPAL!

    // Estado Local de la App
    let appState = {
      barberName: localStorage.getItem('tf_barberName') || 'Barbería & Peluquería',
      logoUrl: localStorage.getItem('tf_logoUrl') || '',
      slots: JSON.parse(localStorage.getItem('tf_slots')) || [],
      selectedSlotId: null,
      trialStartDate: localStorage.getItem('tf_trialStart') || new Date().toISOString(),
      isPro: localStorage.getItem('tf_isPro') === 'true'
    };

    if (!localStorage.getItem('tf_trialStart')) {
      localStorage.setItem('tf_trialStart', appState.trialStartDate);
    }

    document.addEventListener('DOMContentLoaded', () => {
      updateBrandUI();
      checkTrialStatus();
      renderSlots();
      setupPayPalLink();
    });

    // Configurar el enlace de PayPal con tu correo
    function setupPayPalLink() {
      const btn = document.getElementById('paypalPayBtn');
      btn.href = `https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=${encodeURIComponent(MI_CORREO_PAYPAL)}&item_name=Suscripcion+Pro+TurnoFacil&amount=10.00&currency_code=USD`;
    }

    // 1. GESTIÓN DE MARCA Y PERSONALIZACIÓN
    function saveBrandSettings() {
      const name = document.getElementById('inputBarberName').value.trim();
      const logoInput = document.getElementById('inputBarberLogo');

      if (name) {
        appState.barberName = name;
        localStorage.setItem('tf_barberName', name);
      }

      if (logoInput.files && logoInput.files[0]) {
        const reader = new FileReader();
        reader.onload = function(e) {
          appState.logoUrl = e.target.result;
          localStorage.setItem('tf_logoUrl', appState.logoUrl);
          updateBrandUI();
        };
        reader.readAsDataURL(logoInput.files[0]);
      } else {
        updateBrandUI();
      }

      alert('¡Configuración de marca guardada con éxito!');
    }

    function updateBrandUI() {
      document.getElementById('displayBarberName').innerText = appState.barberName;
      document.getElementById('inputBarberName').value = appState.barberName;

      const logoImg = document.getElementById('barberLogoImg');
      const defaultIcon = document.getElementById('defaultLogoIcon');

      if (appState.logoUrl) {
        logoImg.src = appState.logoUrl;
        logoImg.classList.remove('hidden');
        defaultIcon.classList.add('hidden');
      }
    }

    // 2. VERIFICACIÓN DE PRUEBA / LICENCIA
    function checkTrialStatus() {
      const startDate = new Date(appState.trialStartDate);
      const currentDate = new Date();
      const diffTime = Math.abs(currentDate - startDate);
      const diffDays = Math.ceil(diffTime / (1000 * 60 * 60 * 24));
      const daysLeft = Math.max(0, 30 - diffDays);

      const banner = document.getElementById('licenseBanner');
      const daysText = document.getElementById('daysLeftText');

      if (appState.isPro) {
        banner.className = "flex items-center gap-2 bg-emerald-500/10 border border-emerald-500/30 px-3 py-1.5 rounded-full text-xs text-emerald-400";
        banner.innerHTML = `<i data-lucide="check-circle" class="w-4 h-4"></i> <span>Suscripción Pro <strong>Activa</strong></span>`;
        lucide.createIcons();
      } else {
        daysText.innerText = `${daysLeft} días restantes`;
      }
    }

    // 3. GENERADOR DE TURNOS
    function generateSlots() {
      const start = document.getElementById('startTime').value;
      const end = document.getElementById('endTime').value;
      const duration = parseInt(document.getElementById('slotDuration').value);

      if (!start || !end) return alert('Por favor selecciona la hora de inicio y cierre.');

      const slots = [];
      let current = new Date(`1970-01-01T${start}:00`);
      const endTime = new Date(`1970-01-01T${end}:00`);

      let id = 1;
      while (current < endTime) {
        const next = new Date(current.getTime() + duration * 60000);
        if (next > endTime) break;

        const timeStr = `${formatTime(current)} - ${formatTime(next)}`;
        slots.push({
          id: id++,
          time: timeStr,
          booked: false,
          clientName: '',
          clientPhone: ''
        });

        current = next;
      }

      appState.slots = slots;
      saveSlots();
      renderSlots();
      alert('¡Jornada iniciada! Se han generado ' + slots.length + ' turnos.');
    }

    function formatTime(date) {
      return date.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit', hour12: true });
    }

    function saveSlots() {
      localStorage.setItem('tf_slots', JSON.stringify(appState.slots));
    }

    // 4. RENDERIZAR TURNOS
    function renderSlots() {
      const barberContainer = document.getElementById('barberSlotsContainer');
      const clientGrid = document.getElementById('clientSlotsGrid');
      const counter = document.getElementById('turnCounter');

      const bookedCount = appState.slots.filter(s => s.booked).length;
      counter.innerText = `${bookedCount} Reservados`;

      if (appState.slots.length === 0) {
        barberContainer.innerHTML = `<p class="text-xs text-slate-400 text-center py-6">Haz clic en "Abrir Jornada y Generar Turnos" para comenzar el día.</p>`;
      } else {
        barberContainer.innerHTML = appState.slots.map(s => `
          <div class="flex items-center justify-between p-3 rounded-xl border ${s.booked ? 'bg-amber-500/10 border-amber-500/30' : 'bg-slate-900 border-slate-700/60'} text-xs">
            <div class="flex items-center gap-3">
              <span class="font-mono font-bold ${s.booked ? 'text-amber-400' : 'text-slate-300'}">${s.time}</span>
              ${s.booked ? `
                <div>
                  <p class="font-bold text-white">${s.clientName}</p>${s.clientPhone ? `<p class="text-[10px] text-slate-400">${s.clientPhone}</p>` : ''}
                </div>
              ` : `<span class="text-slate-500">Disponible</span>`}
            </div>
            ${s.booked ? `
              <button onclick="cancelSlot(${s.id})" class="text-red-400 hover:text-red-300 font-semibold text-[11px] bg-red-500/10 px-2.5 py-1 rounded-lg">
                Liberar
              </button>
            ` : ''}
          </div>
        `).join('');
      }

      const availableSlots = appState.slots.filter(s => !s.booked);
      if (availableSlots.length === 0) {
        clientGrid.innerHTML = `<p class="col-span-full text-xs text-slate-400 text-center py-4">No hay turnos disponibles para hoy.</p>`;
      } else {
        clientGrid.innerHTML = availableSlots.map(s => `
          <button onclick="selectClientSlot(${s.id})" class="p-3 rounded-xl border text-center transition ${appState.selectedSlotId === s.id ? 'bg-amber-500 text-slate-950 border-amber-400 font-bold' : 'bg-slate-900 border-slate-700 text-white hover:border-amber-500/50'} text-xs">
            ${s.time}
          </button>
        `).join('');

        if (appState.selectedSlotId) {
          clientGrid.innerHTML += `
            <div class="col-span-full pt-2">
              <button onclick="bookClientSlot()" class="w-full bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold py-2.5 rounded-xl text-xs transition shadow">
                Confirmar Reserva
              </button>
            </div>
          `;
        }
      }
    }

    function selectClientSlot(id) {
      appState.selectedSlotId = id;
      renderSlots();
    }

    function bookClientSlot() {
      const name = document.getElementById('clientName').value.trim();
      const phone = document.getElementById('clientPhone').value.trim();

      if (!name) return alert('Por favor escribe tu nombre completo.');
      if (!appState.selectedSlotId) return alert('Selecciona un horario.');

      const slot = appState.slots.find(s => s.id === appState.selectedSlotId);
      if (slot) {
        slot.booked = true;
        slot.clientName = name;
        slot.clientPhone = phone;
        saveSlots();

        alert(`¡Turno reservado con éxito para las ${slot.time}!`);
        appState.selectedSlotId = null;
        document.getElementById('clientName').value = '';
        document.getElementById('clientPhone').value = '';
        renderSlots();
      }
    }

    function cancelSlot(id) {
      if (confirm('¿Deseas liberar este turno?')) {
        const slot = appState.slots.find(s => s.id === id);
        if (slot) {
          slot.booked = false;
          slot.clientName = '';
          slot.clientPhone = '';
          saveSlots();
          renderSlots();
        }
      }
    }

    // 5. CAMBIO DE VISTAS
    function switchView(view) {
      const barberView = document.getElementById('barberView');
      const clientView = document.getElementById('clientView');
      const tabBarber = document.getElementById('tabBarber');
      const tabClient = document.getElementById('tabClient');

      if (view === 'barber') {
        barberView.classList.remove('hidden');
        clientView.classList.add('hidden');
        tabBarber.className = "flex-1 py-2 rounded-lg bg-amber-500 text-slate-950 font-bold flex items-center justify-center gap-2 transition shadow";
        tabClient.className = "flex-1 py-2 rounded-lg text-slate-400 hover:text-white flex items-center justify-center gap-2 transition";
      } else {
        barberView.classList.add('hidden');
        clientView.classList.remove('hidden');
        tabClient.className = "flex-1 py-2 rounded-lg bg-amber-500 text-slate-950 font-bold flex items-center justify-center gap-2 transition shadow";
        tabBarber.className = "flex-1 py-2 rounded-lg text-slate-400 hover:text-white flex items-center justify-center gap-2 transition";
      }
    }

    // 6. ENLACES Y CÓDIGO QR
    function copyClientLink() {
      navigator.clipboard.writeText(window.location.href);
      alert('¡Enlace de reservas copiado al portapapeles!');
    }

    function showQRModal() {
      const qrContainer = document.getElementById('qrcode');
      qrContainer.innerHTML = '';
      new QRCode(qrContainer, {
        text: window.location.href,
        width: 180,
        height: 180
      });
      document.getElementById('qrModal').classList.remove('hidden');
    }

    function closeQRModal() {
      document.getElementById('qrModal').classList.add('hidden');
    }

    // 7. MANEJO DE MODAL DE PAYPAL
    function openPaymentModal() {
      document.getElementById('paymentModal').classList.remove('hidden');
    }

    function closePaymentModal() {
      document.getElementById('paymentModal').classList.add('hidden');
    }

    function confirmPayPalPayment() {
      alert("Se abrirá la ventana de PayPal para procesar tu pago de $10 USD. Una vez completado el pago, introduce el código de activación que te enviamos o contáctanos.");
    }

    function activateProWithCode() {
      const code = document.getElementById('activationCode').value.trim();
      if (code.toUpperCase() === 'PRO2026' || code.length >= 4) {
        appState.isPro = true;
        localStorage.setItem('tf_isPro', 'true');
        checkTrialStatus();
        closePaymentModal();
        alert('¡Suscripción Pro activada correctamente!');
      } else {
        alert('Código de activación inválido. Verifica tu pago o contacta a soporte.');
      }
    }
