<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SIPUS - Sistem Perpustakaan Digital Kampus</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', 'Roboto', 'Noto Sans', sans-serif;
            background-image: url(radja.jpg);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }

        /* Ghibli Style Background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 50%, rgba(255, 182, 193, 0.3) 0%, transparent 50%),
                radial-gradient(circle at 80% 50%, rgba(173, 216, 230, 0.3) 0%, transparent 50%);
            pointer-events: none;
            z-index: 0;
        }

        .container-auth {
            position: relative;
            z-index: 1;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            align-items: center;
            max-width: 1200px;
            width: 100%;
            padding: 2rem;
        }

        .auth-illustration {
            text-align: center;
            animation: float 3s ease-in-out infinite;
        }

        .auth-illustration-icon {
            font-size: 8rem;
            margin-bottom: 2rem;
            filter: drop-shadow(0 10px 30px rgba(0, 0, 0, 0.2));
        }

        .auth-title {
            font-size: 3rem;
            font-weight: 800;
            background: linear-gradient(135deg, #8B6F47 0%, #D4A574 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 1rem;
        }

        .auth-subtitle {
            font-size: 1.2rem;
            color: white;
            margin-bottom: 2rem;
        }

        .auth-features {
            text-align: left;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }

        .feature-item {
            display: flex;
            align-items: center;
            gap: 1rem;
            font-size: 1.05rem;
            color: white;
        }

        .feature-icon {
            font-size: 1.5rem;
            min-width: 40px;
            text-align: center;
        }

        .auth-form-container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
            border: 2px solid rgba(212, 165, 116, 0.2);
        }

        .form-title {
            font-size: 2rem;
            font-weight: 700;
            color: #8B6F47;
            margin-bottom: 0.5rem;
        }

        .form-subtitle {
            color: #999;
            margin-bottom: 2rem;
            font-size: 0.95rem;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: #8B6F47;
        }

        .form-control {
            width: 100%;
            padding: 0.875rem 1.25rem;
            font-size: 1rem;
            border: 2px solid #E8D5C4;
            border-radius: 12px;
            background: rgba(255, 255, 255, 0.9);
            color: #333;
            transition: all 0.3s ease;
            font-family: inherit;
        }

        .form-control:focus {
            outline: none;
            border-color: #6c0202;
            box-shadow: 0 0 0 4px rgba(136, 1, 1, 0.15);
            background: white;
        }

        .form-control::placeholder {
            color: rgba(0, 0, 0, 0.4);
        }

        .btn-submit {
            width: 100%;
            padding: 0.95rem;
            font-size: 1.05rem;
            font-weight: 700;
            border: none;
            border-radius: 12px;
            background: linear-gradient(135deg, #D4A574, #C9A961);
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(109, 1, 1, 0.3);
            margin-top: 1rem;
        }

        .btn-submit:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(212, 165, 116, 0.4);
        }

        .btn-submit:active {
            transform: translateY(-1px);
        }

        .form-footer {
            text-align: center;
            margin-top: 1.5rem;
            color: #666;
        }

        .form-footer a {
            color: #D4A574;
            font-weight: 600;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .form-footer a:hover {
            color: #8B6F47;
        }

        .alert {
            padding: 1rem;
            border-radius: 12px;
            margin-bottom: 1.5rem;
            border-left: 4px solid;
            animation: slideInDown 0.3s ease-out;
        }

        .alert-error {
            background: rgba(193, 67, 67, 0.1);
            border-left-color: #ac0000;
            color: #ffffff;
        }

        .alert-success {
            background: rgba(39, 174, 96, 0.1);
            border-left-color: #27AE60;
            color: #27AE60;
        }

        @keyframes slideInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0px);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        .form-toggle {
            display: none;
        }

        .form-toggle.active {
            display: block;
        }

        @media (max-width: 768px) {
            .container-auth {
                grid-template-columns: 1fr;
                padding: 1rem;
            }

            .auth-illustration {
                display: none;
            }

            .auth-form-container {
                padding: 2rem;
            }

            .auth-title {
                font-size: 2rem;
            }

            .form-title {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container-auth">
        <!-- LEFT SIDE - Illustration -->
        <div class="auth-illustration">
            <div class="auth-illustration-icon">📚</div>
            <h1 class="auth-title">SIPUS</h1>
            <p class="auth-subtitle">Sistem Perpustakaan Digital Kampus</p>
            
            <div class="auth-features">
                <div class="feature-item">
                    <span class="feature-icon">✨</span>
                    <span>Katalog Buku Digital Modern</span>
                </div>
                <div class="feature-item">
                    <span class="feature-icon">📖</span>
                    <span>Sistem Peminjaman Otomatis</span>
                </div>
                <div class="feature-item">
                    <span class="feature-icon">🎓</span>
                    <span>Rekomendasi Berdasarkan Jurusan</span>
                </div>
                <div class="feature-item">
                    <span class="feature-icon">🔔</span>
                    <span>Notifikasi Keterlambatan Real-time</span>
                </div>
                
            </div>
        </div>

        <!-- RIGHT SIDE - Forms -->
        <div class="auth-form-container">
            <!-- Login Form -->
            <form id="loginForm" class="form-toggle active">
                <h2 class="form-title">Masuk</h2>
                <p class="form-subtitle">Selamat datang kembali! 👋</p>

                <div id="loginAlert"></div>

                <div class="form-group">
                    <label for="loginEmail">Email</label>
                    <input 
                        type="email" 
                        id="loginEmail" 
                        class="form-control" 
                        placeholder="your@email.com"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="loginPassword">Password</label>
                    <input 
                        type="password" 
                        id="loginPassword" 
                        class="form-control" 
                        placeholder="••••••••"
                        required
                    >
                </div>

                <button type="submit" class="btn-submit">Masuk ke SIPUS</button>

                <div class="form-footer">
                    Belum punya akun? 
                    <a href="#" onclick="toggleForms(event)">Daftar di sini</a>
                </div>

                <!-- Test Account Info -->
                <div style="margin-top: 2rem; padding: 1rem; background: #FFF8E7; border-radius: 8px; font-size: 0.9rem; color: #666;">
                    <strong>Akun Percobaan:</strong><br>
                    <small>Admin: admin@sipus.ac.id / admin123456</small><br>
                    <small>Mahasiswa: budi.santoso@student.ac.id / budi123456</small>
                </div>
            </form>

            <!-- Register Form -->
            <form id="registerForm" class="form-toggle">
                <h2 class="form-title">Daftar</h2>
                <p class="form-subtitle">Bergabunglah dengan SIPUS 🎓</p>

                <div id="registerAlert"></div>

                <div class="form-group">
                    <label for="registerNIM">NIM</label>
                    <input 
                        type="text" 
                        id="registerNIM" 
                        class="form-control" 
                        placeholder="23110001"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="registerNama">Nama Lengkap</label>
                    <input 
                        type="text" 
                        id="registerNama" 
                        class="form-control" 
                        placeholder="Nama Anda"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="registerJurusan">Jurusan</label>
                    <select id="registerJurusan" class="form-control" required>
                        <option value="">-- Pilih Jurusan --</option>
                        <option value="Teknologi Informasi">Teknologi Informasi</option>
                        <option value="Sistem Informasi">Sistem Informasi</option>
                        <option value="Bisnis Digital">Bisnis Digital</option>
                        <option value="Agribisnis">Agribisnis</option>
                        <option value="Manajemen">Manajemen</option>
                        <option value="Akuntansi">Akuntansi</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="registerEmail">Email</label>
                    <input 
                        type="email" 
                        id="registerEmail" 
                        class="form-control" 
                        placeholder="your@email.com"
                        required
                    >
                </div>

                <div class="form-group">
                    <label for="registerPassword">Password</label>
                    <input 
                        type="password" 
                        id="registerPassword" 
                        class="form-control" 
                        placeholder="••••••••"
                        required
                    >
                </div>

                <button type="submit" class="btn-submit">Daftar Sekarang</button>

                <div class="form-footer">
                    Sudah punya akun? 
                    <a href="#" onclick="toggleForms(event)">Masuk di sini</a>
                </div>
            </form>
        </div>
    </div>

    <script src="js/app.js"></script>
    <script>
        function toggleForms(e) {
            e.preventDefault();
            document.getElementById('loginForm').classList.toggle('active');
            document.getElementById('registerForm').classList.toggle('active');
        }

        // LOGIN
        document.getElementById('loginForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const email = document.getElementById('loginEmail').value;
            const password = document.getElementById('loginPassword').value;

            const user = authManager.login(email, password);
            const alertDiv = document.getElementById('loginAlert');

            if (user) {
                alertDiv.innerHTML = '<div class="alert alert-success">✓ Login berhasil! Mengalihkan...</div>';
                setTimeout(() => {
                    if (user.role === 'admin') {
                        window.location.href = 'admin/dashboard.html';
                    } else {
                        window.location.href = 'mahasiswa/dashboard.html';
                    }
                }, 1000);
            } else {
                alertDiv.innerHTML = '<div class="alert alert-error">✗ Email atau password salah!</div>';
            }
        });

        // REGISTER
        document.getElementById('registerForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const nim = document.getElementById('registerNIM').value;
            const nama = document.getElementById('registerNama').value;
            const jurusan = document.getElementById('registerJurusan').value;
            const email = document.getElementById('registerEmail').value;
            const password = document.getElementById('registerPassword').value;

            const result = authManager.register({
                nim, nama, jurusan, email, password
            });

            const alertDiv = document.getElementById('registerAlert');

            if (result.error) {
                alertDiv.innerHTML = `<div class="alert alert-error">✗ ${result.error}</div>`;
            } else {
                alertDiv.innerHTML = `<div class="alert alert-success">✓ ${result.message} Silakan login!</div>`;
                setTimeout(() => {
                    document.getElementById('registerForm').reset();
                    document.getElementById('loginForm').classList.add('active');
                    document.getElementById('registerForm').classList.remove('active');
                }, 2000);
            }
        });
    </script>
</body>
</html>
