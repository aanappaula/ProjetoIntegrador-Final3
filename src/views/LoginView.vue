<template>
  <link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet" />

  <link href="signin.css" rel="stylesheet" />

  <div class="forms-teste">
    <form>
      <img id="imglogo" width="90" height="90" src="@/assets/logoo.png" />
      <h1 class="h3 mb-3 fw-normal">Fazer login</h1>

      <div class="form-floating">
        <input
          type="email"
          class="form-control"
          id="floatingInput"
          placeholder="name@example.com"
        />
        <label for="floatingInput">Email</label>
      </div>
      <div class="form-floating">
        <input
          type="password"
          class="form-control"
          id="floatingPassword"
          placeholder="Password"
        />
        <label for="floatingPassword">Login</label>
      </div>

      <div class="checkbox mb-3">
        <label> <input type="checkbox" value="remember-me" /> Salvar </label>
      </div>
      <button class="w-100 btn botao-meu" type="submit">Logar</button>
      <p class="mt-5 mb-3 text-muted">&copy; 2022</p>
    </form>
  </div>
</template>
