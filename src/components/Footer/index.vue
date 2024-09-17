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
    <figure class="primaryFigure">
        <img src="../../assets/instagran.png" alt="Logo Instagram">
        <img src="../../assets/facebook.png" alt="Logo Facebook">
    </figure>
     <figure class="secondFigure">
          <img src="../../assets/mastercard.png" alt="Logo mastercard">
          <img src="../../assets/pay.png" alt="Logo Paypal">
          <img src="../../assets/visa.png" alt="Logo Visa">
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

    h4{
      padding-bottom: 10px;
    }
}

ul{
    list-style: none;
    line-height: 1.5;
}

button{
    background-color: #5CA720;
    color: white;
    border: none;
    padding: 9px 20px;
    font-weight: 800;
    cursor: pointer;
}

input{
    padding: 9px;
    border: none;
     width: 20vw;
}

.secondSection{
  @include flex();
  height: 12vh;

  .primaryFigure{
      width: 6vw;
      @include flex();
    
  }
  .secondFigure{
     @include flex();
     width: 12vw;
  }
}
</style>