<script></script>

<template>
  <footer>
    <section class="primarySection">
      <nav>
        <ul>
          <li>Contato</li>
          <li>Termos de seviço</li>
          <li>Política de privacidade</li>
          <li>Cancelamento, troca e reembolso</li>
        </ul>
      </nav>
      <div>
        <h4>Newsletter</h4>
        <div>
          <input type="text" placeholder="Digite seu melhor e-mail" />
          <button>Inscrever</button>
        </div>
      </div>
    </section>
   <section class="secondSection">
    <figure>
        <img src="" alt="Logo Instagram">
        <img src="" alt="Logo Facebook">
    </figure>
     <figure>
          <img src="" alt="Logo mastercard">
          <img src="" alt="Logo Paypal">
          <img src="" alt="Logo Visa">
     </figure>
   </section>
  </footer>
</template>

<style scoped lang="scss">
@mixin flex{
  display: flex;
    justify-content: space-between;
    align-items: center;
}
footer{
    background-color: #F9F9F9;
    padding:0 2%;
}
.primarySection{
  @include flex();
    height: 20vh;
    border-bottom: 0.2px #A5A1A1 solid;
}

ul{
    list-style: none;
}

button{
    background-color: #5CA720;
    color: white;
    border: none;
    padding: 9px 20px;
}

input{
    padding: 9px;
    border: none;
}

.secondSection{
  @include flex();
  height: 12vh;
}
</style>