<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hyper Elas - Αίτηση Αστυνομίας</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
      color: #333;
    }
    header {
      background: url('https://cdn.discordapp.com/attachments/1366423578941063209/1421531085006835822/hyper_banner_by_design_X_team2.png?ex=68d95f7d&is=68d80dfd&hm=efed9a1c4975b099c2ca934e3dace8aafb0cc6b605eb7c907de1505615293524&') no-repeat center center/cover;
      height: 220px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 6px black;
      font-size: 2.5rem;
      font-weight: bold;
      letter-spacing: 2px;
    }
    form {
      background: white;
      max-width: 850px;
      margin: 30px auto;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 2px 12px rgba(0,0,0,0.15);
    }
    label {
      display: block;
      margin: 15px 0 5px;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }
    textarea {
      resize: vertical;
      min-height: 80px;
    }
    button {
      background: #0073e6;
      color: white;
      padding: 14px 22px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1rem;
      transition: 0.3s;
    }
    button:hover {
      background: #005bb5;
    }
  </style>
</head>
<body>

  <header>
    Hyper Elas - Αίτηση Αστυνομίας
  </header>

  <form>
    <label>Discord Name ή Discord ID ❓</label>
    <input type="text" name="discord" required>

    <label>Ονοματεπώνυμο (in game) ❓</label>
    <input type="text" name="fullname" required>

    <label>Ηλικία (IRL) ❓</label>
    <input type="number" name="age" required>

    <label>Έχεις προϋπηρεσία σε άλλη αστυνομία (Αν ναι, πού) ❓</label>
    <textarea name="experience"></textarea>

    <label>Πόσο συχνά μπορείτε να παίζετε (ώρες ανά εβδομάδα) ❓</label>
    <textarea name="hours"></textarea>

    <label>Γιατί θέλεις να ενταχθείς στην αστυνομία της πόλης μας ❓</label>
    <textarea name="why"></textarea>

    <label>Ποια θεωρείς ότι είναι η δουλειά ενός αστυνομικού ❓</label>
    <textarea name="role"></textarea>

    <label>Ποιο είναι το σημαντικότερο όπλο ενός αστυνομικού ❓</label>
    <textarea name="weapon"></textarea>

    <label>Ένας πολίτης σας βρίζει χωρίς λόγο. Πώς αντιδράτε ❓</label>
    <textarea name="citizen"></textarea>

    <label>Βλέπεις δύο άτομα να τσακώνονται και να χειροδικούν. Τι κάνεις ❓</label>
    <textarea name="fight"></textarea>

    <label>Πώς θα χειριζόσουν μια κατάσταση όπου ένας κρατούμενος αρνείται να συνεργαστεί ❓</label>
    <textarea name="prisoner"></textarea>

    <label>Τι είναι ο διαπραγματευτής ❓</label>
    <textarea name="negotiator"></textarea>

    <label>Ανάμεσα σε μία ζωή δικιά σου και ενός ομήρου ποια θα διασφαλίσεις πρώτη και γιατί ❓</label>
    <textarea name="hostage"></textarea>

    <button type="submit">Υποβολή Αίτησης</button>
  </form>

</body>
</html>
