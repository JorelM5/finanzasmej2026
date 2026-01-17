<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Control Financiero</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .login-container {
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 10px 40px rgba(0,0,0,0.2);
            max-width: 400px;
            width: 90%;
        }
        .login-container h1 {
            color: #2c3e50;
            margin-bottom: 10px;
            text-align: center;
        }
        .login-container p {
            color: #7f8c8d;
            margin-bottom: 30px;
            text-align: center;
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: #2c3e50;
            font-weight: bold;
        }
        .form-group input {
            width: 100%;
            padding: 12px;
            border: 2px solid #ddd;
            border-radius: 6px;
            font-size: 16px;
            transition: border 0.3s;
        }
        .form-group input:focus {
            outline: none;
            border-color: #667eea;
        }
        .btn-login {
            width: 100%;
            padding: 14px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.2s;
        }
        .btn-login:hover {
            transform: translateY(-2px);
        }
        .error-msg {
            background: #f8d7da;
            color: #721c24;
            padding: 12px;
            border-radius: 6px;
            margin-bottom: 20px;
            display: none;
            text-align: center;
        }
        .app-container {
            display: none;
            max-width: 1400px;
            width: 95%;
            margin: 20px auto;
            padding: 20px;
            background: #f5f5f5;
            border-radius: 12px;
        }
        .header {
            background: #2c3e50;
            color: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logout-btn {
            padding: 8px 16px;
            background: #e74c3c;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
        }
        .logout-btn:hover {
            background: #c0392b;
        }
        .tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }
        .tab {
            padding: 12px 24px;
            background: #34495e;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
        }
        .tab.active {
            background: #3498db;
        }
        .content {
            display: none;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .content.active {
            display: block;
        }
        .filtros {
            background: #ecf0f1;
            padding: 15px;
            border-radius: 6px;
            margin-bottom: 20px;
            display: flex;
            gap: 15px;
            align-items: center;
            flex-wrap: wrap;
        }
        .filtros label {
            font-weight: bold;
            color: #2c3e50;
        }
        .filtros select {
            padding: 8px 12px;
            border: 2px solid #bdc3c7;
            border-radius: 6px;
            font-size: 14px;
        }
        .resumen-mensual {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .resumen-mensual h3 {
            margin-bottom: 15px;
        }
        .resumen-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        .resumen-item {
            background: rgba(255,255,255,0.2);
            padding: 15px;
            border-radius: 6px;
            text-align: center;
        }
        .resumen-item .label {
            font-size: 14px;
            opacity: 0.9;
            margin-bottom: 5px;
        }
        .resumen-item .valor {
            font-size: 24px;
            font-weight: bold;
        }
        .chart-container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th {
            background: #34495e;
            color: white;
            padding: 12px;
            text-align: left;
            font-weight: bold;
        }
        td {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        input, select {
            width: 100%;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        .ingreso {
            background: #d4edda;
        }
        .egreso {
            background: #f8d7da;
        }
        .saldo {
            background: #d1ecf1;
            font-weight: bold;
        }
        .add-row {
            margin-top: 15px;
            padding: 10px 20px;
            background: #27ae60;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
        }
        .add-row:hover {
            background: #229954;
        }
        .totales {
            margin-top: 20px;
            padding: 15px;
            background: #ecf0f1;
            border-radius: 6px;
        }
        .totales h3 {
            margin-top: 0;
            color: #2c3e50;
        }
        .total-item {
            display: flex;
            justify-content: space-between;
            padding: 8px 0;
            border-bottom: 1px solid #bdc3c7;
        }
        .total-item:last-child {
            border-bottom: none;
            font-weight: bold;
            font-size: 18px;
            color: #2c3e50;
        }
        .instrucciones {
            background: #fff3cd;
            padding: 15px;
            border-radius: 6px;
            margin-bottom: 20px;
            border-left: 4px solid #ffc107;
        }
        .credentials-info {
            background: #d1ecf1;
            padding: 15px;
            border-radius: 6px;
            margin-top: 20px;
            border-left: 4px solid #17a2b8;
        }
        .credentials-info strong {
            color: #0c5460;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <div class="login-container" id="loginContainer">
        <h1>🔐 Acceso Seguro</h1>
        <p>Control Financiero Personal</p>
        
        <div class="error-msg" id="errorMsg">Usuario o contraseña incorrectos</div>
        
        <form onsubmit="login(event)">
            <div class="form-group">
                <label>Usuario</label>
                <input type="text" id="username" placeholder="Ingresa tu usuario" required>
            </div>
            <div class="form-group">
                <label>Contraseña</label>
                <input type="password" id="password" placeholder="Ingresa tu contraseña" required>
            </div>
            <button type="submit" class="btn-login">Ingresar</button>
        </form>

        <div class="credentials-info">
            <strong>📌 Credenciales por defecto:</strong><br>
            Usuario: <code>admin</code><br>
            Contraseña: <code>finanzas2026</code><br><br>
            <small style="color: #0c5460;">⚠️ Cambia estas credenciales editando el código HTML (línea 485-486)</small>
        </div>
    </div>

    <div class="app-container" id="appContainer">
        <div class="header">
            <div>
                <h1>💰 Control de Ingresos y Egresos</h1>
                <p style="margin: 5px 0 0 0;">Negocio de Video, Fotografía, Web, Redes Sociales e Impresiones</p>
            </div>
            <button class="logout-btn" onclick="logout()">🚪 Cerrar Sesión</button>
        </div>

        <div class="instrucciones">
            <strong>📋 Instrucciones:</strong> Llena la fecha, descripción, categoría y el monto en Ingreso o Egreso. El saldo se calcula automáticamente. Usa los filtros para ver resúmenes mensuales. Tus datos se guardan automáticamente.
        </div>

        <div class="tabs">
            <button class="tab active" onclick="showTab('negocio')">🏢 NEGOCIO</button>
            <button class="tab" onclick="showTab('personal')">👤 PERSONAL</button>
        </div>

        <div id="negocio" class="content active">
            <h2>Control de Negocio</h2>
            
            <div class="filtros">
                <label>📅 Filtrar por mes:</label>
                <select id="mesNegocio" onchange="filtrarNegocio()">
                    <option value="todos">Todos los meses</option>
                </select>
                <select id="anioNegocio" onchange="filtrarNegocio()">
                    <option value="2026">2026</option>
                    <option value="2025">2025</option>
                    <option value="2027">2027</option>
                </select>
            </div>

            <div class="resumen-mensual" id="resumenNegocio">
                <h3>📊 Resumen del Periodo Seleccionado</h3>
                <div class="resumen-grid">
                    <div class="resumen-item">
                        <div class="label">Total Ingresos</div>
                        <div class="valor" id="resumenIngresosNegocio">$0.00</div>
                    </div>
                    <div class="resumen-item">
                        <div class="label">Total Egresos</div>
                        <div class="valor" id="resumenEgresosNegocio">$0.00</div>
                    </div>
                    <div class="resumen-item">
                        <div class="label">Balance</div>
                        <div class="valor" id="resumenBalanceNegocio">$0.00</div>
                    </div>
                    <div class="resumen-item">
                        <div class="label">Saldo Actual</div>
                        <div class="valor" id="resumenSaldoNegocio">$0.00</div>
                    </div>
                </div>
            </div>

            <div class="chart-container">
                <canvas id="chartNegocio"></canvas>
            </div>

            <table id="tablaNegocio">
                <thead>
                    <tr>
                        <th style="width: 12%">Fecha</th>
                        <th style="width: 25%">Descripción</th>
                        <th style="width: 18%">Categoría</th>
                        <th style="width: 15%" class="ingreso">Ingreso</th>
                        <th style="width: 15%" class="egreso">Egreso</th>
                        <th style="width: 15%" class="saldo">Saldo</th>
                    </tr>
                </thead>
                <tbody id="bodyNegocio">
                    <tr>
                        <td><input type="date" value="2026-01-16"></td>
                        <td><input type="text" value="Saldo inicial"></td>
                        <td><select><option>Inicial</option></select></td>
                        <td class="ingreso"><input type="number" value="0" readonly></td>
                        <td class="egreso"><input type="number" value="0" readonly></td>
                        <td class="saldo"><input type="number" value="5000" onchange="calcularNegocio(); guardarDatos()"></td>
                    </tr>
                </tbody>
            </table>
            <button class="add-row" onclick="agregarFilaNegocio()">➕ Agregar fila</button>
            
            <div class="totales">
                <h3>📊 Totales Generales</h3>
                <div class="total-item">
                    <span>Total Ingresos:</span>
                    <span id="totalIngresosNegocio">$0.00</span>
                </div>
                <div class="total-item">
                    <span>Total Egresos:</span>
                    <span id="totalEgresosNegocio">$0.00</span>
                </div>
                <div class="total-item">
                    <span>Saldo Actual:</span>
                    <span id="saldoActualNegocio">$5,000.00</span>
                </div>
            </div>
        </div>

        <div id="personal" class="content">
            <h2>Control Personal</h2>
            
            <div class="filtros">
                <label>📅 Filtrar por mes:</label>
                <select id="mesPersonal" onchange="filtrarPersonal()">
                    <option value="todos">Todos los meses</option>
                </select>
                <select id="anioPersonal" onchange="filtrarPersonal()">
                    <option value="2026">2026</option>
                    <option value="2025">2025</option>
                    <option value="2027">2027</option>
                </select>
            </div>

            <div class="resumen-mensual" id="resumenPersonal">
                <h3>📊 Resumen del Periodo Seleccionado</h3>
                <div class="resumen-grid">
                    <div class="resumen-item">
                        <div class="label">Total Ingresos</div>
                        <div class="valor" id="resumenIngresosPersonal">$0.00</div>
                    </div>
                    <div class="resumen-item">
                        <div class="label">Total Egresos</div>
                        <div class="valor" id="resumenEgresosPersonal">$0.00</div>
                    </div>
                    <div class="resumen-item">
                        <div class="label">Balance</div>
                        <div class="valor" id="resumenBalancePersonal">$0.00</div>
                    </div>
                    <div class="resumen-item">
                        <div class="label">Saldo Actual</div>
                        <div class="valor" id="resumenSaldoPersonal">$0.00</div>
                    </div>
                </div>
            </div>

            <div class="chart-container">
                <canvas id="chartPersonal"></canvas>
            </div>

            <table id="tablaPersonal">
                <thead>
                    <tr>
                        <th style="width: 12%">Fecha</th>
                        <th style="width: 25%">Descripción</th>
                        <th style="width: 18%">Categoría</th>
                        <th style="width: 15%" class="ingreso">Ingreso</th>
                        <th style="width: 15%" class="egreso">Egreso</th>
                        <th style="width: 15%" class="saldo">Saldo</th>
                    </tr>
                </thead>
                <tbody id="bodyPersonal">
                    <tr>
                        <td><input type="date" value="2026-01-16"></td>
                        <td><input type="text" value="Saldo inicial"></td>
                        <td><select><option>Inicial</option></select></td>
                        <td class="ingreso"><input type="number" value="0" readonly></td>
                        <td class="egreso"><input type="number" value="0" readonly></td>
                        <td class="saldo"><input type="number" value="3000" onchange="calcularPersonal(); guardarDatos()"></td>
                    </tr>
                </tbody>
            </table>
            <button class="add-row" onclick="agregarFilaPersonal()">➕ Agregar fila</button>
            
            <div class="totales">
                <h3>📊 Totales Generales</h3>
                <div class="total-item">
                    <span>Total Ingresos:</span>
                    <span id="totalIngresosPersonal">$0.00</span>
                </div>
                <div class="total-item">
                    <span>Total Egresos:</span>
                    <span id="totalEgresosPersonal">$0.00</span>
                </div>
                <div class="total-item">
                    <span>Saldo Actual:</span>
                    <span id="saldoActualPersonal">$3,000.00</span>
                </div>
            </div>
        </div>
    </div>

    <script>
        // CREDENCIALES - CAMBIALAS AQUÍ
        const USUARIO_CORRECTO = 'admin';
        const PASSWORD_CORRECTA = 'finanzas2026';

        const meses = ['Enero', 'Febrero', 'Marzo', 'Abril', 'Mayo', 'Junio', 'Julio', 'Agosto', 'Septiembre', 'Octubre', 'Noviembre', 'Diciembre'];

        let chartNegocioInstance = null;
        let chartPersonalInstance = null;

        const categoriasNegocio = [
            'Inicial', 'Video y Fotografía', 'Páginas Web', 'Redes Sociales', 'Impresiones',
            'Paquetes/Combo', 'Anticipos', 'Equipo', 'Software y Suscripciones', 'Insumos',
            'Subcontratación', 'Gastos operativos', 'Marketing', 'Transporte', 'Capacitación',
            'Mantenimiento', 'Otros'
        ];

        const categoriasPersonal = [
            'Inicial', 'Sueldo', 'Vivienda', 'Servicios', 'Gastos diarios', 'Compras grandes',
            'Deudas', 'Ahorro', 'Salud', 'Entretenimiento', 'Otros'
        ];

        function inicializarFiltrosMeses() {
            const selectMesNegocio = document.getElementById('mesNegocio');
            const selectMesPersonal = document.getElementById('mesPersonal');
            
            meses.forEach((mes, idx) => {
                const opt1 = document.createElement('option');
                opt1.value = idx + 1;
                opt1.textContent = mes;
                selectMesNegocio.appendChild(opt1);

                const opt2 = document.createElement('option');
                opt2.value = idx + 1;
                opt2.textContent = mes;
                selectMesPersonal.appendChild(opt2);
            });
        }

        function login(event) {
            event.preventDefault();
            const usuario = document.getElementById('username').value;
            const password = document.getElementById('password').value;
            
            if (usuario === USUARIO_CORRECTO && password === PASSWORD_CORRECTA) {
                document.getElementById('loginContainer').style.display = 'none';
                document.getElementById('appContainer').style.display = 'block';
                document.body.style.background = '#f5f5f5';
                cargarDatos();
                inicializarFiltrosMeses();
                filtrarNegocio();
                filtrarPersonal();
            } else {
                document.getElementById('errorMsg').style.display = 'block';
                setTimeout(() => {
                    document.getElementById('errorMsg').style.display = 'none';
                }, 3000);
            }
        }

        function logout() {
            guardarDatos();
            document.getElementById('loginContainer').style.display = 'block';
            document.getElementById('appContainer').style.display = 'none';
            document.body.style.background = 'linear-gradient(135deg, #667eea 0%, #764ba2 100%)';
            document.getElementById('username').value = '';
            document.getElementById('password').value = '';
        }

        function showTab(tab) {
            document.querySelectorAll('.content').forEach(c => c.classList.remove('active'));
            document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
            document.getElementById(tab).classList.add('active');
            event.target.classList.add('active');
        }

        function agregarFilaNegocio() {
            const tbody = document.getElementById('bodyNegocio');
            const row = tbody.insertRow();
            const hoy = new Date().toISOString().split('T')[0];
            
            row.innerHTML = `
                <td><input type="date" value="${hoy}" onchange="guardarDatos(); filtrarNegocio()"></td>
                <td><input type="text" placeholder="Descripción del movimiento" onchange="guardarDatos()"></td>
                <td><select onchange="guardarDatos()">${categoriasNegocio.map(c => `<option>${c}</option>`).join('')}</select></td>
                <td class="ingreso"><input type="number" step="0.01" value="0" onchange="calcularNegocio(); guardarDatos(); filtrarNegocio()"></td>
                <td class="egreso"><input type="number" step="0.01" value="0" onchange="calcularNegocio(); guardarDatos(); filtrarNegocio()"></td>
                <td class="saldo"><input type="number" readonly></td>
            `;
            calcularNegocio();
            guardarDatos();
            filtrarNegocio();
        }

        function agregarFilaPersonal() {
            const tbody = document.getElementById('bodyPersonal');
            const row = tbody.insertRow();
            const hoy = new Date().toISOString().split('T')[0];
            
            row.innerHTML = `
                <td><input type="date" value="${hoy}" onchange="guardarDatos(); filtrarPersonal()"></td>
                <td><input type="text" placeholder="Descripción del movimiento" onchange="guardarDatos()"></td>
                <td><select onchange="guardarDatos()">${categoriasPersonal.map(c => `<option>${c}</option>`).join('')}</select></td>
                <td class="ingreso"><input type="number" step="0.01" value="0" onchange="calcularPersonal(); guardarDatos(); filtrarPersonal()"></td>
                <td class="egreso"><input type="number" step="0.01" value="0" onchange="calcularPersonal(); guardarDatos(); filtrarPersonal()"></td>
                <td class="saldo"><input type="number" readonly></td>
            `;
            calcularPersonal();
            guardarDatos();
            filtrarPersonal();
        }

        function calcularNegocio() {
            const tbody = document.getElementById('bodyNegocio');
            const rows = tbody.getElementsByTagName('tr');
            let saldoAnterior = 0;
            let totalIngresos = 0;
            let totalEgresos = 0;

            for (let i = 0; i < rows.length; i++) {
                const inputs = rows[i].getElementsByTagName('input');
                const ingreso = parseFloat(inputs[3].value) || 0;
                const egreso = parseFloat(inputs[4].value) || 0;
                
                if (i === 0) {
                    saldoAnterior = parseFloat(inputs[5].value) || 0;
                    inputs[5].value = saldoAnterior.toFixed(2);
                } else {
                    const saldoActual = saldoAnterior + ingreso - egreso;
                    inputs[5].value = saldoActual.toFixed(2);
                    saldoAnterior = saldoActual;
                    totalIngresos += ingreso;
                    totalEgresos += egreso;
                }
            }

            document.getElementById('totalIngresosNegocio').textContent = '$' + totalIngresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('totalEgresosNegocio').textContent = '$' + totalEgresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('saldoActualNegocio').textContent = '$' + saldoAnterior.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
        }

        function calcularPersonal() {
            const tbody = document.getElementById('bodyPersonal');
            const rows = tbody.getElementsByTagName('tr');
            let saldoAnterior = 0;
            let totalIngresos = 0;
            let totalEgresos = 0;

            for (let i = 0; i < rows.length; i++) {
                const inputs = rows[i].getElementsByTagName('input');
                const ingreso = parseFloat(inputs[3].value) || 0;
                const egreso = parseFloat(inputs[4].value) || 0;
                
                if (i === 0) {
                    saldoAnterior = parseFloat(inputs[5].value) || 0;
                    inputs[5].value = saldoAnterior.toFixed(2);
                } else {
                    const saldoActual = saldoAnterior + ingreso - egreso;
                    inputs[5].value = saldoActual.toFixed(2);
                    saldoAnterior = saldoActual;
                    totalIngresos += ingreso;
                    totalEgresos += egreso;
                }
            }

            document.getElementById('totalIngresosPersonal').textContent = '$' + totalIngresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('totalEgresosPersonal').textContent = '$' + totalEgresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('saldoActualPersonal').textContent = '$' + saldoAnterior.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
        }

        function filtrarNegocio() {
            const mes = document.getElementById('mesNegocio').value;
            const anio = document.getElementById('anioNegocio').value;
            const tbody = document.getElementById('bodyNegocio');
            const rows = tbody.getElementsByTagName('tr');

            let totalIngresos = 0;
            let totalEgresos = 0;
            let saldoFinal = 0;

            for (let i = 1; i < rows.length; i++) {
                const fecha = rows[i].cells[0].querySelector('input').value;
                const [year, month] = fecha.split('-');
                
                if (mes === 'todos' || (month === mes.padStart(2, '0') && year === anio)) {
                    rows[i].style.display = '';
                    const ingreso = parseFloat(rows[i].cells[3].querySelector('input').value) || 0;
                    const egreso = parseFloat(rows[i].cells[4].querySelector('input').value) || 0;
                    totalIngresos += ingreso;
                    totalEgresos += egreso;
                } else {
                    rows[i].style.display = 'none';
                }
            }

            saldoFinal = parseFloat(rows[rows.length - 1].cells[5].querySelector('input').value) || 0;
            const balance = totalIngresos - totalEgresos;

            document.getElementById('resumenIngresosNegocio').textContent = ' + totalIngresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('resumenEgresosNegocio').textContent = ' + totalEgresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('resumenBalanceNegocio').textContent = ' + balance.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('resumenSaldoNegocio').textContent = ' + saldoFinal.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");

            actualizarGraficaNegocio();
        }

        function filtrarPersonal() {
            const mes = document.getElementById('mesPersonal').value;
            const anio = document.getElementById('anioPersonal').value;
            const tbody = document.getElementById('bodyPersonal');
            const rows = tbody.getElementsByTagName('tr');

            let totalIngresos = 0;
            let totalEgresos = 0;
            let saldoFinal = 0;

            for (let i = 1; i < rows.length; i++) {
                const fecha = rows[i].cells[0].querySelector('input').value;
                const [year, month] = fecha.split('-');
                
                if (mes === 'todos' || (month === mes.padStart(2, '0') && year === anio)) {
                    rows[i].style.display = '';
                    const ingreso = parseFloat(rows[i].cells[3].querySelector('input').value) || 0;
                    const egreso = parseFloat(rows[i].cells[4].querySelector('input').value) || 0;
                    totalIngresos += ingreso;
                    totalEgresos += egreso;
                } else {
                    rows[i].style.display = 'none';
                }
            }

            saldoFinal = parseFloat(rows[rows.length - 1].cells[5].querySelector('input').value) || 0;
            const balance = totalIngresos - totalEgresos;

            document.getElementById('resumenIngresosPersonal').textContent = ' + totalIngresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('resumenEgresosPersonal').textContent = ' + totalEgresos.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('resumenBalancePersonal').textContent = ' + balance.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");
            document.getElementById('resumenSaldoPersonal').textContent = ' + saldoFinal.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ",");

            actualizarGraficaPersonal();
        }

        function actualizarGraficaNegocio() {
            const tbody = document.getElementById('bodyNegocio');
            const rows = tbody.getElementsByTagName('tr');
            const datosPorMes = {};

            for (let i = 1; i < rows.length; i++) {
                if (rows[i].style.display === 'none') continue;
                
                const fecha = rows[i].cells[0].querySelector('input').value;
                const [year, month] = fecha.split('-');
                const clave = `${meses[parseInt(month) - 1]} ${year}`;
                
                if (!datosPorMes[clave]) {
                    datosPorMes[clave] = { ingresos: 0, egresos: 0 };
                }
                
                datosPorMes[clave].ingresos += parseFloat(rows[i].cells[3].querySelector('input').value) || 0;
                datosPorMes[clave].egresos += parseFloat(rows[i].cells[4].querySelector('input').value) || 0;
            }

            const labels = Object.keys(datosPorMes);
            const ingresos = labels.map(l => datosPorMes[l].ingresos);
            const egresos = labels.map(l => datosPorMes[l].egresos);

            if (chartNegocioInstance) {
                chartNegocioInstance.destroy();
            }

            const ctx = document.getElementById('chartNegocio').getContext('2d');
            chartNegocioInstance = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Ingresos',
                        data: ingresos,
                        backgroundColor: 'rgba(39, 174, 96, 0.7)',
                        borderColor: 'rgba(39, 174, 96, 1)',
                        borderWidth: 1
                    }, {
                        label: 'Egresos',
                        data: egresos,
                        backgroundColor: 'rgba(231, 76, 60, 0.7)',
                        borderColor: 'rgba(231, 76, 60, 1)',
                        borderWidth: 1
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        title: {
                            display: true,
                            text: 'Ingresos vs Egresos por Mes'
                        },
                        legend: {
                            display: true,
                            position: 'top'
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                callback: function(value) {
                                    return ' + value.toLocaleString();
                                }
                            }
                        }
                    }
                }
            });
        }

        function actualizarGraficaPersonal() {
            const tbody = document.getElementById('bodyPersonal');
            const rows = tbody.getElementsByTagName('tr');
            const datosPorMes = {};

            for (let i = 1; i < rows.length; i++) {
                if (rows[i].style.display === 'none') continue;
                
                const fecha = rows[i].cells[0].querySelector('input').value;
                const [year, month] = fecha.split('-');
                const clave = `${meses[parseInt(month) - 1]} ${year}`;
                
                if (!datosPorMes[clave]) {
                    datosPorMes[clave] = { ingresos: 0, egresos: 0 };
                }
                
                datosPorMes[clave].ingresos += parseFloat(rows[i].cells[3].querySelector('input').value) || 0;
                datosPorMes[clave].egresos += parseFloat(rows[i].cells[4].querySelector('input').value) || 0;
            }

            const labels = Object.keys(datosPorMes);
            const ingresos = labels.map(l => datosPorMes[l].ingresos);
            const egresos = labels.map(l => datosPorMes[l].egresos);

            if (chartPersonalInstance) {
                chartPersonalInstance.destroy();
            }

            const ctx = document.getElementById('chartPersonal').getContext('2d');
            chartPersonalInstance = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Ingresos',
                        data: ingresos,
                        backgroundColor: 'rgba(39, 174, 96, 0.7)',
                        borderColor: 'rgba(39, 174, 96, 1)',
                        borderWidth: 1
                    }, {
                        label: 'Egresos',
                        data: egresos,
                        backgroundColor: 'rgba(231, 76, 60, 0.7)',
                        borderColor: 'rgba(231, 76, 60, 1)',
                        borderWidth: 1
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        title: {
                            display: true,
                            text: 'Ingresos vs Egresos por Mes'
                        },
                        legend: {
                            display: true,
                            position: 'top'
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                callback: function(value) {
                                    return ' + value.toLocaleString();
                                }
                            }
                        }
                    }
                }
            });
        }

        function guardarDatos() {
            const datosNegocio = {
                rows: Array.from(document.getElementById('bodyNegocio').rows).map(row => ({
                    fecha: row.cells[0].querySelector('input').value,
                    descripcion: row.cells[1].querySelector('input').value,
                    categoria: row.cells[2].querySelector('select').value,
                    ingreso: row.cells[3].querySelector('input').value,
                    egreso: row.cells[4].querySelector('input').value,
                    saldo: row.cells[5].querySelector('input').value
                }))
            };

            const datosPersonal = {
                rows: Array.from(document.getElementById('bodyPersonal').rows).map(row => ({
                    fecha: row.cells[0].querySelector('input').value,
                    descripcion: row.cells[1].querySelector('input').value,
                    categoria: row.cells[2].querySelector('select').value,
                    ingreso: row.cells[3].querySelector('input').value,
                    egreso: row.cells[4].querySelector('input').value,
                    saldo: row.cells[5].querySelector('input').value
                }))
            };

            const datos = { negocio: datosNegocio, personal: datosPersonal };
            const datosString = JSON.stringify(datos);
            document.cookie = `finanzasData=${datosString}; path=/; max-age=31536000`;
        }

        function cargarDatos() {
            const cookies = document.cookie.split(';');
            let datosGuardados = null;
            
            for (let cookie of cookies) {
                const [nombre, valor] = cookie.trim().split('=');
                if (nombre === 'finanzasData') {
                    datosGuardados = JSON.parse(decodeURIComponent(valor));
                    break;
                }
            }

            if (datosGuardados) {
                const tbodyNegocio = document.getElementById('bodyNegocio');
                tbodyNegocio.innerHTML = '';
                datosGuardados.negocio.rows.forEach((data, idx) => {
                    const row = tbodyNegocio.insertRow();
                    const isFirst = idx === 0;
                    row.innerHTML = `
                        <td><input type="date" value="${data.fecha}" onchange="guardarDatos(); filtrarNegocio()"></td>
                        <td><input type="text" value="${data.descripcion}" onchange="guardarDatos()"></td>
                        <td><select onchange="guardarDatos()">${categoriasNegocio.map(c => `<option ${c === data.categoria ? 'selected' : ''}>${c}</option>`).join('')}</select></td>
                        <td class="ingreso"><input type="number" step="0.01" value="${data.ingreso}" ${isFirst ? 'readonly' : ''} onchange="calcularNegocio(); guardarDatos(); filtrarNegocio()"></td>
                        <td class="egreso"><input type="number" step="0.01" value="${data.egreso}" ${isFirst ? 'readonly' : ''} onchange="calcularNegocio(); guardarDatos(); filtrarNegocio()"></td>
                        <td class="saldo"><input type="number" value="${data.saldo}" ${!isFirst ? 'readonly' : ''} onchange="calcularNegocio(); guardarDatos()"></td>
                    `;
                });

                const tbodyPersonal = document.getElementById('bodyPersonal');
                tbodyPersonal.innerHTML = '';
                datosGuardados.personal.rows.forEach((data, idx) => {
                    const row = tbodyPersonal.insertRow();
                    const isFirst = idx === 0;
                    row.innerHTML = `
                        <td><input type="date" value="${data.fecha}" onchange="guardarDatos(); filtrarPersonal()"></td>
                        <td><input type="text" value="${data.descripcion}" onchange="guardarDatos()"></td>
                        <td><select onchange="guardarDatos()">${categoriasPersonal.map(c => `<option ${c === data.categoria ? 'selected' : ''}>${c}</option>`).join('')}</select></td>
                        <td class="ingreso"><input type="number" step="0.01" value="${data.ingreso}" ${isFirst ? 'readonly' : ''} onchange="calcularPersonal(); guardarDatos(); filtrarPersonal()"></td>
                        <td class="egreso"><input type="number" step="0.01" value="${data.egreso}" ${isFirst ? 'readonly' : ''} onchange="calcularPersonal(); guardarDatos(); filtrarPersonal()"></td>
                        <td class="saldo"><input type="number" value="${data.saldo}" ${!isFirst ? 'readonly' : ''} onchange="calcularPersonal(); guardarDatos()"></td>
                    `;
                });

                calcularNegocio();
                calcularPersonal();
            }
        }

        calcularNegocio();
        calcularPersonal();
    </script>
</body>
</html>
