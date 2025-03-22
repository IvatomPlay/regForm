<script setup lang="ts">

</script>

<template>
  <div class="registration-form">
    <h2>Форма регистрации</h2>
    <form id="registrationForm" action="#" method="POST">
      <div class="form-group">
        <label for="userName">Имя:</label>
        <input
          type="text"
          id="username"
        />
      </div>
      <div class="form-group">
        <label for="userLastName">Фамилия:</label>
        <input
          type="text"
          id="username"
        />
      </div>
      <div class="form-group">
        <label for="tel">Номер телефона</label>
        <input 
          type="tel"
          id="tel"
          required
          placeholder="+7(999) 999 99-99"
        /> 
      </div>
      <div class="form-group">
        <label for="email">Электронный адрес:</label>
        <input
          type="email"
          id="email"
          required
          placeholder="email@gmail.com"
        />
      </div>
      <div class="form-group">
        <label for="password">Пароль:</label>
        <input
          type="password"
          id="password"
          required
        />
      </div>
      <div class="form-group">
        <label for="confirmPassword">Подтвердите пароль:</label>
        <input
          type="password"
          id="confirmPassword"
          required
        />
      </div>
      <button type="submit">Зарегистрироваться</button>
    </form>
  </div>
</template>

<style scoped>
  .registration-form {
  max-width: 400px;
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.form-group {
  margin-bottom: 15px;
}

label {
  display: block;
  margin-bottom: 5px;
}

input {
  width: 100%;
  padding: 8px;
  box-sizing: border-box;
}

button {
  width: 100%;
  padding: 10px;
  background-color: #42b983;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #369f6e;
}
</style>