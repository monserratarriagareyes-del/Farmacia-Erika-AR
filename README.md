<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Farmacia Erika AR</title>

<style>
body { font-family: Arial; margin: 0; background: #f5f7fa; }

header {
    background: linear-gradient(90deg,#2e7d32,#66bb6a);
    color: white;
    padding: 20px;
    text-align: center;
}

h2 { padding-left: 15px; color: #2e7d32; }

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(170px,1fr));
    gap: 15px;
    padding: 15px;
}

.card {
    background: white;
    border-radius: 12px;
    padding: 10px;
    text-align: center;
    box-shadow: 0px 3px 8px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
    height: 120px;
    object-fit: cover;
    border-radius: 8px;
}

.price {
    color: #2e7d32;
    font-weight: bold;
}

.btn {
    background: #25D366;
    color: white;
    padding: 8px;
    border-radius: 8px;
    text-decoration: none;
    display: block;
    margin-top: 5px;
}
</style>
</head>

<body>

<header>
    <h1>💊 Farmacia Erika AR</h1>
    <p>Tu salud es nuestra prioridad</p>
</header>

<h2>🩺 Medicamentos</h2>
<div class="grid">

<script>
const productos = [
["Paracetamol",25,"paracetamol"],
["Ibuprofeno",35,"ibuprofen"],
["Amoxicilina",80,"antibiotic"],
["Omeprazol",40,"medicine"],
["Loratadina",35,"allergy medicine"],
["Azitromicina",120,"antibiotic"],
["Ciprofloxacino",110,"antibiotic"],
["Diclofenaco",40,"pain relief"],
["Naproxeno",45,"painkiller"],
["Ketorolaco",50,"medicine"],
["Metformina",60,"diabetes medicine"],
["Losartán",70,"blood pressure"],
["Amlodipino",65,"blood pressure"],
["Insulina",250,"insulin"],
["Salbutamol",90,"inhaler"],
["Prednisona",55,"medicine"],
["Dexametasona",60,"medicine"],
["Clorfenamina",30,"allergy medicine"],
["Ranitidina",45,"medicine"],
["Meloxicam",50,"pain relief"],
["Tramadol",90,"medicine"],
["Fluoxetina",75,"medicine"],
["Enalapril",65,"medicine"],
["Atorvastatina",85,"medicine"],
["Vitamina C",30,"vitamin"],
["Vitamina D",60,"vitamin"],
["Multivitamínico",90,"vitamins"],
["Jarabe para tos",60,"cough syrup"],
["Ambroxol",55,"cough syrup"],
["Suero oral",20,"oral rehydration"]
];

productos.forEach(p=>{
document.write(`
<div class="card">
<img src="https://source.unsplash.com/300x300/?${p[2]}">
<h3>${p[0]}</h3>
<p class="price">$${p[1]}</p>
<a class="btn" href="https://wa.me/528136429787?text=Hola%20quiero%20${p[0]}">Pedir</a>
</div>
`);
});
</script>

</div>

<h2>🧑‍⚕️ Material de Enfermería</h2>
<div class="grid">

<script>
const enfermeria = [
["Gasas estériles",30,"gauze"],
["Jeringa 1ml",10,"syringe"],
["Jeringa 3ml",12,"syringe"],
["Jeringa 5ml",15,"syringe"],
["Jeringa 10ml",18,"syringe"],
["Guantes",120,"medical gloves"],
["Termómetro",90,"thermometer"],
["Baumanómetro",250,"blood pressure"],
["Estetoscopio",200,"stethoscope"],
["Venda",40,"bandage"],
["Micropore",25,"medical tape"]
];

enfermeria.forEach(p=>{
document.write(`
<div class="card">
<img src="https://source.unsplash.com/300x300/?${p[2]}">
<h3>${p[0]}</h3>
<p class="price">$${p[1]}</p>
<a class="btn" href="https://wa.me/528136429787?text=Hola%20quiero%20${p[0]}">Pedir</a>
</div>
`);
});
</script>

</div>

</body>
</html>
