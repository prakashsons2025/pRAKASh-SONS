# pRAKASh-SON'S
Welcome to our dairy 
Owner- SHREE OM PRAKASH DUBEY 
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Namaskar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    h1 {
      font-size: 48px;
      font-weight: bold;
      color: #2e7d32;
      margin-top: 40px;
    }
    .image-container {
      margin: 30px auto;
      max-width: 90%;
    }
    img {
      width: 90%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    .caption {
      font-size: 20px;
      color: #444;
      margin: 10px 0 40px 0;
    }
  </style>
</head>
<body>
  <h1>Namaskar</h1>

  <div class="image-container">
    <img src="6156635293407626851.jpg" alt="Image 1">
    <div class="caption">थोड़ा स्क्रॉल करें कोई 😊</div>
  </div>

  <div class="image-container">
    <img src="6156635293407626852.jpg" alt="Image 2">
    <div class="caption">थोड़ा स्क्रॉल करें कोई 😊</div>
  </div>

  <div class="image-container">
    <img src="6156635293407626850.jpg" alt="Image 3">const PASSWORD = "chatgptmeradost";

function enableEditing() {
  const userPassword = prompt("Enter password to edit:");
  if (userPassword === PASSWORD) {
    document.querySelectorAll("[data-editable]").forEach(el => {
      const currentText = el.innerText;
      const textarea = document.createElement("textarea");
      textarea.value = currentText;
      textarea.style.width = "100%";
      textarea.style.height = "100px";
      el.innerHTML = "";
      el.appendChild(textarea);
    });

    const saveBtn = document.createElement("button");
    saveBtn.textContent = "Save Changes";
    saveBtn.style.margin = "20px";
    saveBtn.onclick = () => {
      document.querySelectorAll("[data-editable]").forEach(el => {
        const newText = el.querySelector("textarea").value;
        el.innerHTML = newText;
      });
      alert("Changes applied (note: these are not saved permanently without Firebase).");
    };
    document.body.appendChild(saveBtn);
  } else {
    alert("Incorrect password!");
  }
}<button onclick="enableEditing()">✏️ Edit</button>


    <div class="caption">थोड़ा स्क्रॉल करें कोई 😊</div>
  </div>

  <div class="image-container">
    <img src="6156635293407626853.jpg" alt="Image 4">
    <div class="caption">थोड़ा स्क्रॉल करें कोई 😊</div>
  </div><h2 data-editable>यह टेक्स्ट एडिटेबल है।</h2>


  <div class="image-container">
    <img src="6156635293407626849.jpg" alt="Image 5">
    <div class="caption">थोड़ा स्क्रॉल करें कोई 😊</div>
  </div>
</body><script src="admin.js"></script>

</html>
