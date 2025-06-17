<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuis Unik Sosiologi Kelas 10</title>
    <style>
        /* CSS Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
            margin: 0;
            padding: 20px;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        
        .quiz-intro {
            background-color: #e8f4fc;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 25px;
            border-left: 5px solid #3498db;
        }
        
        .question {
            margin-bottom: 25px;
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 5px;
            transition: all 0.3s ease;
        }
        
        .question:hover {
            background-color: #f0f0f0;
            transform: translateY(-2px);
        }
        
        .question h3 {
            color: #2980b9;
            margin-top: 0;
        }
        
        .options {
            margin-left: 20px;
        }
        
        .option {
            margin-bottom: 10px;
            cursor: pointer;
        }
        
        .option input {
            margin-right: 10px;
        }
        
        button {
            background-color: #3498db;
            color: white;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            margin: 30px auto 0;
            transition: background-color 0.3s;
        }
        
        button:hover {
            background-color: #2980b9;
        }
        
        .result {
            display: none;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
        }
        
        .correct {
            background-color: #d4edda;
            color: #155724;
        }
        
        .incorrect {
            background-color: #f8d7da;
            color: #721c24;
        }
        
        .score-display {
            text-align: center;
            font-size: 20px;
            margin-top: 20px;
            font-weight: bold;
            color: #2c3e50;
        }
        
        .fun-fact {
            font-style: italic;
            color: #7f8c8d;
            margin-top: 10px;
            font-size: 14px;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 15px;
            }
            
            .question {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Kuis Unik Sosiologi Kelas 10</h1>
        
        <div class="quiz-intro">
            <p>Selamat datang di kuis sosiologi interaktif! Uji pemahamanmu tentang konsep-konsep dasar sosiologi yang telah dipelajari di kelas 10. Pilihlah jawaban yang paling tepat untuk setiap pertanyaan.</p>
        </div>
        
        <form id="quiz-form">
            <!-- Question 1 -->
            <div class="question">
                <h3>1. Apa yang dimaksud dengan "interaksi sosial" dalam sosiologi?</h3>
                <div class="options">
                    <label class="option">
                        <input type="radio" name="q1" value="a"> Hubungan antara individu dengan lingkungan fisik
                    </label>
                    <label class="option">
                        <input type="radio" name="q1" value="b"> Hubungan timbal balik antara dua orang atau lebih yang saling mempengaruhi
                    </label>
                    <label class="option">
                        <input type="radio" name="q1" value="c"> Komunikasi satu arah dari atasan ke bawahan
                    </label>
                    <label class="option">
                        <input type="radio" name="q1" value="d"> Proses adaptasi manusia terhadap teknologi
                    </label>
                </div>
                <div class="fun-fact">Fakta Unik: Interaksi sosial pertama kali dianalisis secara mendalam oleh Georg Simmel, sosiolog Jerman.</div>
            </div>
            
            <!-- Question 2 -->
            <div class="question">
                <h3>2. Manakah yang termasuk contoh dari nilai sosial?</h3>
                <div class="options">
                    <label class="option">
                        <input type="radio" name="q2" value="a"> Uang Rp50.000
                    </label>
                    <label class="option">
                        <input type="radio" name="q2" value="b"> Kejujuran dalam berbisnis
                    </label>
                    <label class="option">
                        <input type="radio" name="q2" value="c"> Gedung sekolah
                    </label>
                    <label class="option">
                        <input type="radio" name="q2" value="d"> Seragam sekolah
                    </label>
                </div>
                <div class="fun-fact">Fakta Unik: Nilai sosial berbeda antar budaya dan dapat berubah seiring waktu.</div>
            </div>
            
            <!-- Question 3 -->
            <div class="question">
                <h3>3. Apa yang dimaksud dengan "sosialisasi" dalam sosiologi?</h3>
                <div class="options">
                    <label class="option">
                        <input type="radio" name="q3" value="a"> Proses berjualan di media sosial
                    </label>
                    <label class="option">
                        <input type="radio" name="q3" value="b"> Proses belajar untuk menjadi anggota masyarakat
                    </label>
                    <label class="option">
                        <input type="radio" name="q3" value="c"> Kegiatan amal untuk masyarakat
                    </label>
                    <label class="option">
                        <input type="radio" name="q3" value="d"> Pembentukan kelompok sosial baru
                    </label>
                </div>
                <div class="fun-fact">Fakta Unik: Sosialisasi primer terjadi dalam keluarga, sementara sosialisasi sekunder terjadi di sekolah dan lingkungan kerja.</div>
            </div>
            
            <!-- Question 4 -->
            <div class="question">
                <h3>4. Manakah yang merupakan contoh dari kelompok sekunder?</h3>
                <div class="options">
                    <label class="option">
                        <input type="radio" name="q4" value="a"> Keluarga inti
                    </label>
                    <label class="option">
                        <input type="radio" name="q4" value="b"> Kelompok teman bermain masa kecil
                    </label>
                    <label class="option">
                        <input type="radio" name="q4" value="c"> Organisasi siswa di sekolah
                    </label>
                    <label class="option">
                        <input type="radio" name="q4" value="d"> Komunitas tetangga yang sangat akrab
                    </label>
                </div>
                <div class="fun-fact">Fakta Unik: Konsep kelompok primer dan sekunder diperkenalkan oleh Charles Horton Cooley tahun 1909.</div>
            </div>
            
            <!-- Question 5 -->
            <div class="question">
                <h3>5. Apa yang dimaksud dengan "deviasi sosial"?</h3>
                <div class="options">
                    <label class="option">
                        <input type="radio" name="q5" value="a"> Perubahan sosial yang sangat cepat
                    </label>
                    <label class="option">
                        <input type="radio" name="q5" value="b"> Perilaku yang menyimpang dari norma yang berlaku
                    </label>
                    <label class="option">
                        <input type="radio" name="q5" value="c"> Penyimpangan dalam pengukuran statistik sosial
                    </label>
                    <label class="option">
                        <input type="radio" name="q5" value="d"> Perbedaan pendapat dalam masyarakat
                    </label>
                </div>
                <div class="fun-fact">Fakta Unik: Apa yang dianggap menyimpang di satu budaya mungkin dianggap normal di budaya lain.</div>
            </div>
            
            <button type="button" id="submit-btn">Kumpulkan Jawaban</button>
            
            <div id="result" class="result"></div>
            <div id="score" class="score-display"></div>
        </form>
    </div>

    <script>
        document.getElementById('submit-btn').addEventListener('click', function() {
            // Jawaban yang benar
            const correctAnswers = {
                q1: 'b',
                q2: 'b',
                q3: 'b',
                q4: 'c',
                q5: 'b'
            };
            
            let score = 0;
            const resultDiv = document.getElementById('result');
            const scoreDiv = document.getElementById('score');
            
            // Periksa setiap jawaban
            for (let i = 1; i <= 5; i++) {
                const questionName = 'q' + i;
                const selectedOption = document.querySelector(`input[name="${questionName}"]:checked`);
                
                if (selectedOption) {
                    const userAnswer = selectedOption.value;
                    const questionElement = selectedOption.closest('.question');
                    
                    if (userAnswer === correctAnswers[questionName]) {
                        score++;
                        questionElement.classList.add('correct');
                        questionElement.classList.remove('incorrect');
                    } else {
                        questionElement.classList.add('incorrect');
                        questionElement.classList.remove('correct');
                    }
                }
            }
            
            // Tampilkan hasil
            scoreDiv.textContent = `Skor Anda: ${score} dari 5`;
            resultDiv.style.display = 'block';
            
            if (score === 5) {
                resultDiv.textContent = 'Luar biasa! Anda sangat menguasai materi sosiologi!';
                resultDiv.className = 'result correct';
            } else if (score >= 3) {
                resultDiv.textContent = 'Bagus! Anda sudah memahami banyak konsep sosiologi.';
                resultDiv.className = 'result correct';
            } else {
                resultDiv.textContent = 'Masih perlu belajar lagi. Yuk pelajari lebih dalam tentang sosiologi!';
                resultDiv.className = 'result incorrect';
            }
            
            // Scroll ke hasil
            resultDiv.scrollIntoView({ behavior: 'smooth' });
        });
    </script>
</body>
</html>
