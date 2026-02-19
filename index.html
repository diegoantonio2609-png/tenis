<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>🎾 Tennis Tracker</title>
  <style>
    /* =============================================
       VARIABLES & RESET
    ============================================= */
    :root {
      --bg: #0d0d0f;
      --surface: #18181c;
      --surface2: #22222a;
      --border: #2e2e38;
      --accent: #c8f250;
      --accent-dim: #8aaa30;
      --text: #e8e8ec;
      --text-muted: #7a7a8a;
      --danger: #e05555;
      --danger-dim: #a03535;
      --closed: #2a3520;
      --closed-border: #4a6030;
      --radius: 12px;
      --radius-sm: 8px;
      --transition: 0.2s ease;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Courier New', 'Lucida Console', monospace;
      min-height: 100vh;
      padding: 0 0 80px;
      line-height: 1.5;
    }

    /* =============================================
       HEADER
    ============================================= */
    header {
      background: var(--surface);
      border-bottom: 1px solid var(--border);
      padding: 18px 20px 14px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-title {
      font-size: 1.1rem;
      font-weight: 700;
      letter-spacing: 0.08em;
      color: var(--accent);
      text-transform: uppercase;
    }

    .header-title span { color: var(--text-muted); font-weight: 400; }

    /* =============================================
       BUTTONS
    ============================================= */
    button {
      cursor: pointer;
      border: none;
      border-radius: var(--radius-sm);
      font-family: inherit;
      font-weight: 600;
      transition: background var(--transition), opacity var(--transition), transform 0.1s;
      touch-action: manipulation;
    }

    button:active { transform: scale(0.96); }

    .btn-primary {
      background: var(--accent);
      color: #0d0d0f;
      padding: 12px 20px;
      font-size: 0.88rem;
      letter-spacing: 0.05em;
      text-transform: uppercase;
    }

    .btn-primary:hover { background: #d8ff60; }

    .btn-danger {
      background: transparent;
      color: var(--danger);
      border: 1px solid var(--danger-dim);
      padding: 10px 16px;
      font-size: 0.82rem;
    }

    .btn-danger:hover { background: var(--danger-dim); color: #fff; }

    .btn-ghost {
      background: transparent;
      color: var(--text-muted);
      border: 1px solid var(--border);
      padding: 10px 16px;
      font-size: 0.82rem;
    }

    .btn-ghost:hover { color: var(--text); border-color: var(--text-muted); }

    .btn-icon {
      background: transparent;
      color: var(--text-muted);
      padding: 6px 10px;
      font-size: 0.85rem;
      border-radius: 6px;
    }

    .btn-icon:hover { color: var(--danger); }

    /* =============================================
       SECTIONS
    ============================================= */
    .section {
      padding: 20px 16px 0;
      max-width: 680px;
      margin: 0 auto;
    }

    .section-title {
      font-size: 0.72rem;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--text-muted);
      margin-bottom: 12px;
      padding-bottom: 8px;
      border-bottom: 1px solid var(--border);
    }

    /* =============================================
       PLAYERS SECTION
    ============================================= */
    #players-list {
      display: flex;
      flex-direction: column;
      gap: 8px;
      margin-bottom: 12px;
    }

    .player-row {
      display: flex;
      align-items: center;
      gap: 8px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius-sm);
      padding: 8px 10px;
      animation: fadeSlideIn 0.25s ease;
    }

    @keyframes fadeSlideIn {
      from { opacity: 0; transform: translateY(-8px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .player-num {
      color: var(--accent);
      font-size: 0.75rem;
      font-weight: 700;
      min-width: 20px;
    }

    .player-name-input {
      flex: 1;
      background: transparent;
      border: none;
      outline: none;
      color: var(--text);
      font-family: inherit;
      font-size: 0.95rem;
      padding: 4px 0;
    }

    .player-name-input:focus {
      border-bottom: 1px solid var(--accent);
    }

    /* =============================================
       SETS SECTION
    ============================================= */
    #sets-container {
      display: flex;
      flex-direction: column;
      gap: 14px;
      margin-bottom: 14px;
    }

    .set-card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      overflow: hidden;
      animation: fadeSlideIn 0.3s ease;
    }

    .set-card.closed {
      background: var(--closed);
      border-color: var(--closed-border);
      opacity: 0.85;
    }

    .set-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 12px 14px;
      border-bottom: 1px solid var(--border);
      background: var(--surface2);
    }

    .set-card.closed .set-header {
      background: #1e2a14;
      border-color: var(--closed-border);
    }

    .set-title {
      font-size: 0.78rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      font-weight: 700;
      color: var(--accent);
    }

    .set-card.closed .set-title { color: var(--accent-dim); }

    .set-badge-closed {
      font-size: 0.65rem;
      background: var(--accent-dim);
      color: #0d0d0f;
      padding: 2px 8px;
      border-radius: 20px;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    .set-body {
      padding: 10px 14px;
      display: flex;
      flex-direction: column;
      gap: 8px;
    }

    .set-player-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
      padding: 6px 0;
      border-bottom: 1px solid var(--border);
    }

    .set-player-row:last-child { border-bottom: none; }

    .set-player-name {
      flex: 1;
      font-size: 0.9rem;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }

    .score-input {
      width: 64px;
      background: var(--surface2);
      border: 1px solid var(--border);
      border-radius: 6px;
      color: var(--text);
      font-family: inherit;
      font-size: 1rem;
      font-weight: 700;
      text-align: center;
      padding: 7px 6px;
      outline: none;
      -moz-appearance: textfield;
    }

    .score-input::-webkit-outer-spin-button,
    .score-input::-webkit-inner-spin-button { -webkit-appearance: none; }

    .score-input:focus { border-color: var(--accent); }
    .score-input:disabled { opacity: 0.6; cursor: not-allowed; background: transparent; }

    .set-footer {
      padding: 10px 14px;
      border-top: 1px solid var(--border);
    }

    /* =============================================
       RANKING / SUMMARY TABLE
    ============================================= */
    #ranking-section {
      padding: 20px 16px 0;
      max-width: 680px;
      margin: 0 auto;
    }

    .ranking-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.88rem;
    }

    .ranking-table thead tr {
      border-bottom: 2px solid var(--accent);
    }

    .ranking-table th {
      padding: 8px 10px;
      text-align: left;
      font-size: 0.7rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: var(--text-muted);
      font-weight: 600;
    }

    .ranking-table th:last-child,
    .ranking-table td:last-child { text-align: right; }

    .ranking-table td {
      padding: 10px 10px;
      border-bottom: 1px solid var(--border);
      vertical-align: middle;
    }

    .rank-pos {
      font-weight: 700;
      color: var(--text-muted);
      font-size: 0.78rem;
      min-width: 28px;
    }

    .rank-pos.gold   { color: #f5c518; }
    .rank-pos.silver { color: #a0a0b0; }
    .rank-pos.bronze { color: #b87040; }

    .rank-pts {
      font-weight: 700;
      font-size: 1rem;
      color: var(--accent);
    }

    .rank-sets {
      color: var(--text-muted);
      font-size: 0.82rem;
    }

    .ranking-table tbody tr {
      transition: background var(--transition);
    }

    .ranking-table tbody tr.rank-updated {
      animation: rankPulse 0.4s ease;
    }

    @keyframes rankPulse {
      0%   { background: transparent; }
      40%  { background: rgba(200, 242, 80, 0.1); }
      100% { background: transparent; }
    }

    .no-data {
      color: var(--text-muted);
      font-size: 0.85rem;
      padding: 20px 0;
      text-align: center;
    }

    /* =============================================
       ADD PLAYER AREA
    ============================================= */
    .add-player-row {
      display: flex;
      gap: 8px;
      margin-top: 4px;
    }

    .add-player-input {
      flex: 1;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius-sm);
      color: var(--text);
      font-family: inherit;
      font-size: 0.9rem;
      padding: 10px 14px;
      outline: none;
    }

    .add-player-input:focus { border-color: var(--accent); }

    /* =============================================
       BOTTOM BAR (actions)
    ============================================= */
    .bottom-bar {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background: var(--surface);
      border-top: 1px solid var(--border);
      padding: 12px 16px;
      display: flex;
      gap: 10px;
      justify-content: center;
      z-index: 100;
    }

    .bottom-bar button { flex: 1; max-width: 300px; }

    /* =============================================
       MISC
    ============================================= */
    .spacer { height: 20px; }
    .mt-8 { margin-top: 8px; }
    .mt-16 { margin-top: 16px; }
  </style>
</head>
<body>

  <!-- =================== HEADER =================== -->
  <header>
    <div class="header-title">🎾 Tennis <span>Tracker</span></div>
    <button class="btn-danger" onclick="resetDay()" style="padding:8px 12px;font-size:0.75rem;">↺ Reiniciar día</button>
  </header>

  <!-- =================== PLAYERS =================== -->
  <div class="section" id="players-section">
    <div class="section-title">Jugadores</div>
    <div id="players-list"></div>
    <div class="add-player-row">
      <input class="add-player-input" id="new-player-input" type="text" placeholder="Nombre del nuevo jugador…" maxlength="30" />
      <button class="btn-primary" onclick="addPlayer()">+ Agregar</button>
    </div>
  </div>

  <div class="spacer"></div>

  <!-- =================== SETS =================== -->
  <div class="section">
    <div class="section-title">Sets del día</div>
    <div id="sets-container"></div>
    <button class="btn-primary" style="width:100%;margin-top:4px;" onclick="createSet()">+ Nuevo Set</button>
  </div>

  <div class="spacer"></div>

  <!-- =================== RANKING =================== -->
  <div id="ranking-section">
    <div class="section-title">Ranking del día</div>
    <div id="ranking-container"></div>
  </div>

  <div style="height:100px;"></div>

  <!-- =================== BOTTOM BAR =================== -->
  <!-- (empty — actions inline or sticky header) -->

  <!-- =============================================
       JAVASCRIPT
  ============================================= -->
  <script>
    /* ===================================================
       STATE
    =================================================== */
    let state = {
      players: [],   // [{ id, name }]
      sets: []       // [{ id, closed, scores: { playerId: number } }]
    };

    /* ===================================================
       PERSISTENCE
    =================================================== */
    function saveState() {
      try {
        localStorage.setItem('tennis_tracker_v1', JSON.stringify(state));
      } catch (e) {
        console.error('Error al guardar en localStorage:', e);
      }
    }

    function loadState() {
      try {
        const raw = localStorage.getItem('tennis_tracker_v1');
        if (raw) {
          state = JSON.parse(raw);
          return;
        }
      } catch (e) {
        console.error('Error al cargar localStorage:', e);
      }
      // Default state with 6 players
      state = {
        players: [
          { id: uid(), name: 'Jugador 1' },
          { id: uid(), name: 'Jugador 2' },
          { id: uid(), name: 'Jugador 3' },
          { id: uid(), name: 'Jugador 4' },
          { id: uid(), name: 'Jugador 5' },
          { id: uid(), name: 'Jugador 6' },
        ],
        sets: []
      };
      saveState();
    }

    /* ===================================================
       UTILITIES
    =================================================== */
    function uid() {
      return Math.random().toString(36).slice(2, 10);
    }

    /* ===================================================
       PLAYERS
    =================================================== */
    function renderPlayers() {
      const list = document.getElementById('players-list');
      list.innerHTML = '';
      state.players.forEach((player, idx) => {
        const row = document.createElement('div');
        row.className = 'player-row';
        row.innerHTML = `
          <span class="player-num">${idx + 1}</span>
          <input
            class="player-name-input"
            type="text"
            value="${escHtml(player.name)}"
            maxlength="30"
            placeholder="Nombre…"
            onchange="updatePlayerName('${player.id}', this.value)"
            onblur="updatePlayerName('${player.id}', this.value)"
          />
          <button class="btn-icon" onclick="removePlayer('${player.id}')" title="Eliminar jugador">✕</button>
        `;
        list.appendChild(row);
      });
    }

    function addPlayer() {
      const input = document.getElementById('new-player-input');
      const name = input.value.trim();
      if (!name) {
        input.focus();
        input.style.borderColor = 'var(--danger)';
        setTimeout(() => input.style.borderColor = '', 1200);
        return;
      }
      const player = { id: uid(), name };
      state.players.push(player);

      // Add this player to all existing open sets with score 0
      state.sets.forEach(set => {
        if (!set.closed) {
          set.scores[player.id] = 0;
        }
      });

      saveState();
      input.value = '';
      renderAll();
    }

    function updatePlayerName(id, val) {
      const name = val.trim();
      if (!name) {
        // restore old name visually
        renderPlayers();
        return;
      }
      const p = state.players.find(p => p.id === id);
      if (p) {
        p.name = name;
        saveState();
        renderRanking(); // update ranking names
        renderSets();    // update set player names
      }
    }

    function removePlayer(id) {
      if (!confirm('¿Eliminar este jugador? Sus puntos en sets cerrados se mantendrán en el historial.')) return;
      state.players = state.players.filter(p => p.id !== id);
      // Remove from open sets
      state.sets.forEach(set => {
        if (!set.closed) delete set.scores[id];
      });
      saveState();
      renderAll();
    }

    /* ===================================================
       SETS
    =================================================== */
    function createSet() {
      const scores = {};
      state.players.forEach(p => { scores[p.id] = 0; });
      const newSet = { id: uid(), closed: false, scores };
      state.sets.push(newSet);
      saveState();
      renderSets();
      renderRanking();
      // Scroll to new set
      setTimeout(() => {
        const el = document.getElementById('set-' + newSet.id);
        if (el) el.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }, 100);
    }

    function renderSets() {
      const container = document.getElementById('sets-container');
      container.innerHTML = '';
      if (state.sets.length === 0) {
        container.innerHTML = '<p class="no-data">No hay sets. Presiona "+ Nuevo Set" para comenzar.</p>';
        return;
      }
      state.sets.forEach((set, idx) => {
        const card = document.createElement('div');
        card.className = 'set-card' + (set.closed ? ' closed' : '');
        card.id = 'set-' + set.id;

        // Determine all player IDs to show in this set
        // Show current players + any player id that has a score in the set
        const allIds = new Set([...state.players.map(p => p.id), ...Object.keys(set.scores)]);
        const rows = [...allIds].map(pid => {
          const player = state.players.find(p => p.id === pid);
          const name = player ? escHtml(player.name) : '<em style="color:var(--text-muted)">Jugador eliminado</em>';
          const score = set.scores[pid] ?? 0;
          const disabledAttr = set.closed ? 'disabled' : '';
          return `
            <div class="set-player-row">
              <span class="set-player-name">${name}</span>
              <input
                class="score-input"
                type="number"
                min="0"
                value="${score}"
                ${disabledAttr}
                data-setid="${set.id}"
                data-playerid="${pid}"
                oninput="updateScore('${set.id}', '${pid}', this)"
              />
            </div>
          `;
        }).join('');

        const footer = set.closed
          ? ''
          : `<div class="set-footer"><button class="btn-ghost" style="width:100%;color:var(--accent);border-color:var(--accent-dim);" onclick="closeSet('${set.id}')">✔ Cerrar Set ${idx + 1}</button></div>`;

        card.innerHTML = `
          <div class="set-header">
            <span class="set-title">Set ${idx + 1}</span>
            ${set.closed ? '<span class="set-badge-closed">Cerrado</span>' : ''}
          </div>
          <div class="set-body">${rows}</div>
          ${footer}
        `;
        container.appendChild(card);
      });
    }

    function updateScore(setId, playerId, input) {
      let val = parseInt(input.value, 10);

      // Validate: no negative, no NaN
      if (isNaN(val) || val < 0) {
        val = 0;
        input.value = 0;
      }

      const set = state.sets.find(s => s.id === setId);
      if (set && !set.closed) {
        set.scores[playerId] = val;
        saveState();
        renderRanking();
      }
    }

    function closeSet(setId) {
      const set = state.sets.find(s => s.id === setId);
      if (!set) return;
      set.closed = true;
      saveState();
      renderSets();
      renderRanking();
    }

    /* ===================================================
       RANKING
    =================================================== */
    function computeRanking() {
      // { playerId: { name, totalPts, setsPlayed } }
      const map = {};

      // Init with all current players
      state.players.forEach(p => {
        map[p.id] = { name: p.name, totalPts: 0, setsPlayed: 0 };
      });

      // Also include deleted players who appear in sets
      state.sets.forEach(set => {
        Object.entries(set.scores).forEach(([pid, pts]) => {
          if (!map[pid]) {
            const p = state.players.find(pl => pl.id === pid);
            map[pid] = { name: p ? p.name : 'Jugador eliminado', totalPts: 0, setsPlayed: 0 };
          }
          map[pid].totalPts += pts;
          if (pts > 0 || set.closed) map[pid].setsPlayed += 1;
        });
      });

      // Sort: desc points, then alphabetical
      return Object.entries(map)
        .map(([id, data]) => ({ id, ...data }))
        .sort((a, b) => {
          if (b.totalPts !== a.totalPts) return b.totalPts - a.totalPts;
          return a.name.localeCompare(b.name);
        });
    }

    function renderRanking() {
      const container = document.getElementById('ranking-container');
      const ranking = computeRanking();

      if (ranking.length === 0) {
        container.innerHTML = '<p class="no-data">Agrega jugadores y sets para ver el ranking.</p>';
        return;
      }

      const medalClass = (i) => i === 0 ? 'gold' : i === 1 ? 'silver' : i === 2 ? 'bronze' : '';
      const medalEmoji = (i) => i === 0 ? '🥇' : i === 1 ? '🥈' : i === 2 ? '🥉' : (i + 1);

      const rows = ranking.map((p, i) => `
        <tr class="rank-row" data-id="${p.id}">
          <td><span class="rank-pos ${medalClass(i)}">${medalEmoji(i)}</span></td>
          <td>${escHtml(p.name)}</td>
          <td><span class="rank-pts">${p.totalPts}</span></td>
          <td><span class="rank-sets">${p.setsPlayed}</span></td>
        </tr>
      `).join('');

      container.innerHTML = `
        <table class="ranking-table">
          <thead>
            <tr>
              <th>#</th>
              <th>Jugador</th>
              <th>Puntos</th>
              <th>Sets</th>
            </tr>
          </thead>
          <tbody>${rows}</tbody>
        </table>
      `;

      // Pulse animation on update
      container.querySelectorAll('tbody tr').forEach(tr => {
        tr.classList.add('rank-updated');
        setTimeout(() => tr.classList.remove('rank-updated'), 500);
      });
    }

    /* ===================================================
       RESET
    =================================================== */
    function resetDay() {
      if (!confirm('¿Reiniciar el día? Se borrarán todos los sets y puntos. Los jugadores se mantendrán.')) return;
      state.sets = [];
      saveState();
      renderAll();
    }

    /* ===================================================
       HELPERS
    =================================================== */
    function escHtml(str) {
      return String(str)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    function renderAll() {
      renderPlayers();
      renderSets();
      renderRanking();
    }

    /* ===================================================
       KEYBOARD SHORTCUT: Enter to add player
    =================================================== */
    document.getElementById('new-player-input').addEventListener('keydown', (e) => {
      if (e.key === 'Enter') addPlayer();
    });

    /* ===================================================
       INIT
    =================================================== */
    loadState();
    renderAll();
  </script>
</body>
</html>
