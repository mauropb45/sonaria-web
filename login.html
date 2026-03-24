<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Login - MejorarIA</title>

<style>
body{
  font-family:Arial;
  background:#08121f;
  color:white;
  text-align:center;
  padding:40px;
}

input{
  display:block;
  margin:10px auto;
  padding:10px;
}

button{
  padding:10px 20px;
  margin-top:10px;
}
</style>
</head>

<body>

<h2>Acceso MejorarIA</h2>

<input type="email" id="email" placeholder="Correo">
<input type="password" id="password" placeholder="Contraseña">

<button onclick="login()">Entrar</button>
<button onclick="register()">Crear cuenta</button>

<p id="msg"></p>

<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>

<script>
const SUPABASE_URL = "https://ibtklkjfpcopzgsrulob.supabase.co";
const SUPABASE_ANON_KEY = "sb_publishable_IwR4ByvxMHbrJPZF4Q4ZKg_ra6ji7HM";

const supabaseClient = supabase.createClient(SUPABASE_URL, SUPABASE_ANON_KEY);

async function login(){
  const email = document.getElementById("email").value;
  const password = document.getElementById("password").value;

  const { error } = await supabaseClient.auth.signInWithPassword({ email, password });

  if(error){
    document.getElementById("msg").innerText = error.message;
    return;
  }

  window.location.href = "panel.html";
}

async function register(){
  const email = document.getElementById("email").value;
  const password = document.getElementById("password").value;

  const { error } = await supabaseClient.auth.signUp({ email, password });

  if(error){
    document.getElementById("msg").innerText = error.message;
    return;
  }

  document.getElementById("msg").innerText = "Cuenta creada. Ahora inicia sesión.";
}
</script>

</body>
</html>
