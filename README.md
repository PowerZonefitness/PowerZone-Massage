<!DOCTYPE html>
<html lang="mn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Power Zone Fitness | Бариа заслын цаг захиалга</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    .container {
      background: #020617;
      padding: 30px;
      border-radius: 16px;
      width: 100%;
      max-width: 420px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.5);
    }
    h1 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 22px;
    }
    label {
      font-size: 14px;
      margin-top: 12px;
      display: block;
    }
    input, select, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      border-radius: 8px;
      border: none;
      font-size: 14px;
    }
    input, select, textarea {
      background: #1e293b;
      color: #fff;
    }
    button {
      background: #22c55e;
      color: #000;
      font-weight: bold;
      margin-top: 20px;
      cursor: pointer;
    }
    button:hover {
      background: #16a34a;
    }
    .note {
      font-size: 12px;
      opacity: 0.7;
      margin-top: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>💆‍♂️ Бариа заслын цаг захиалга</h1>
    <form>
      <label>Нэр</label>
      <input type="text" placeholder="Таны нэр" required />

      <label>Утасны дугаар</label>
      <input type="tel" placeholder="9911xxxx" required />

      <label>Үйлчилгээний төрөл</label>
      <select required>
        <option value="">Сонгох</option>
        <option>Спорт бариа</option>
        <option>Сэргээх бариа</option>
        <option>Эмчилгээний бариа</option>
      </select>

      <label>Өдөр</label>
      <input type="date" required />

      <label>Цаг</label>
      <input type="time" required />

      <label>Нэмэлт тайлбар (хүсвэл)</label>
      <textarea rows="3" placeholder="Булчингийн зовуурь, анхаарах зүйл"></textarea>

      <button type="submit">Цаг захиалах</button>
    </form>
    <div class="note">Power Zone Fitness © 2026</div>
  </div>
</body>
</html>
