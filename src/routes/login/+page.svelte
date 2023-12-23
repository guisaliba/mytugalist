<script>
  import DefaultInput from '../../components/inputs/DefaultInput.svelte';
</script>

<div class="main">
  <div class="login--wrapper">
    <h1>Login</h1>
    <DefaultInput label="username" type="text" />
    <DefaultInput label="password" type="password" />
    <button>Login</button>
  </div>
</div>

<style>
  .main {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background-color: #f0f0f0;
  }

  .login--wrapper {
    display: flex;
    flex-direction: column;
    gap: 12px;
    background: #fff;
    border-radius: 12px;
    padding: 32px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 400px;
  }

  h1 {
    margin-bottom: 16px;
    color: #333;
  }

  button {
    background-color: #4caf50;
    color: #fff;
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  button:hover {
    background-color: #45a049;
  }
</style>
