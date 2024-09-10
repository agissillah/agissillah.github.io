<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesan dengan Suara Google</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Untuk Dwi Cahyani Pramudia Hilda Rahmasari</h1>
        <p>Happy anniversary yang Kedua tahun, Sayang!

<p>Dua tahun yang lalu, hidupku berubah dengan cara yang sangat istimewa ketika kita mulai menjalani perjalanan ini bersama. Seiring berjalannya waktu, aku semakin menyadari betapa berartinya kamu dalam hidupku. Setiap hari bersamamu terasa seperti petualangan yang tak pernah berakhir, penuh dengan kebahagiaan, cinta, dan banyak tawa.

<p>Dua tahun ini telah dipenuhi dengan kenangan indah yang tak terlupakan. Dari momen-momen kecil yang sederhana hingga pengalaman-pengalaman besar yang kita bagikan, setiap detik bersamamu adalah harta yang sangat berharga. Aku merasa beruntung memiliki seseorang sepertimu yang selalu bisa membuatku tersenyum, mendukungku dalam setiap langkah, dan mencintai aku dengan sepenuh hati.

<p>Kamu adalah pacar terbaikku, tempat ceritaku, dan tempatku untuk pulang. Setiap hari aku terinspirasi oleh kekuatanmu, kebaikanmu, dan caramu melihat dunia dengan penuh warna. Kamu membawa kehangatan dan cahaya ke dalam hidupku dengan cara yang tidak bisa diungkapkan dengan kata-kata. Aku sangat menghargai setiap momen yang kita habiskan bersama, setiap percakapan, dan setiap canda tawa yang kita bagi.

<p>Sebagai perayaan untuk dua tahun cinta dan kebahagiaan kita, aku ingin mengucapkan terima kasih atas segala hal yang kamu lakukan dan untuk menjadi dirimu sendiri. Aku menantikan masa depan kita bersama, penuh dengan lebih banyak petualangan, cinta, dan pengalaman yang luar biasa. Aku tahu bahwa kita akan terus tumbuh bersama dan menghadapi apa pun yang datang dengan kekuatan dan cinta yang sama seperti yang telah kita tunjukkan selama ini.

<p>Semoga hari ini spesial untukmu sayang, seperti halnya kamu membuat setiap hari menjadi spesial untukku. Aku mencintaimu lebih dari kata-kata yang bisa diungkapkan dan aku sangat bersemangat untuk melanjutkan perjalanan kita bersama, tidak peduli apa pun yang terjadi.

<p>Happy anniversary, sayangku! Aku mencintaimu lebih dari yang bisa diungkapkan dan aku bersyukur setiap hari karena kamu adalah bagian dari hidupku.

<p>[Muhammad Aghiitsillah]

</p>
        <button onclick="speak()">Putar Pesan</button>
    </div>

    <script>
        function speak() {
            // Membuat instance SpeechSynthesisUtterance
            var utterance = new SpeechSynthesisUtterance('Unuk Pacarku, dwi cahyani pramudia hilda rahmasari, Happy Anniversary Yang Kedua Tahun Sayang');

            // Mengatur bahasa
            utterance.lang = 'id-ID'; // ID untuk Bahasa Indonesia

            // Memulai pemutaran
            window.speechSynthesis.speak(utterance);
        }
    </script>
</body>
</html>
