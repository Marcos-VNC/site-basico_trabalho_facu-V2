<template>
  <div class="content">
    <br />
    <br />
    <div class="container my-5">
      <div
        class="
          row
          p-4
          pb-0
          pe-lg-0
          pt-lg-8
          align-items-center
          rounded-3
          border
          shadow-lg
        "
      >
        <form class="row g-3 needs-validation">
          <div class="col-md-4">
            <label for="validationCustom01" class="form-label">Nome</label>
            <input
              type="text"
              class="form-control"
              id="validationCustom01"
              value=""
              required
            />
            <div class="valid-feedback">OK</div>
          </div>
          <div class="col-md-4">
            <label for="validationCustom02" class="form-label">Sobrenome</label>
            <input
              type="text"
              class="form-control"
              id="validationCustom02"
              value=""
              required
            />
            <div class="valid-feedback">OK</div>
          </div>
          <div class="col-md-4">
            <label for="validationCustomUsername" class="form-label"
              >E-mail</label
            >
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">@</span>
              <input
                type="email"
                class="form-control"
                id="validationCustomUsername"
                aria-describedby="inputGroupPrepend"
                required
              />
              <div class="invalid-feedback">
                Por favor preencha um email válido!
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <label for="validationCustom03" class="form-label">Cidade</label>
            <input
              type="text"
              class="form-control"
              id="validationCustom03"
              required
            />
            <div class="invalid-feedback">
              Por favor preencha com uma Cidade válida!
            </div>
          </div>
          <div class="col-md-3">
            <label for="validationCustom04" class="form-label">Estado</label>
            <select class="form-select" id="validationCustom04" required>
              <option selected disabled value="">Escolha...</option>
              <option>SP</option>
              <option>RJ</option>
              <option>MG</option>
            </select>
            <div class="invalid-feedback">Por favor selecione um estado!</div>
          </div>
          <div class="col-md-3">
            <label for="validationCustom05" class="form-label">CEP</label>
            <input
              type="text"
              class="form-control"
              id="validationCustom05"
              required
            />
            <div class="invalid-feedback">Por favor preencha com um CEP!</div>
          </div>
          <div class="col-12">
            <label for="inputAddress" class="form-label">Bairro</label>
            <input
              type="text"
              class="form-control"
              id="inputAddress"
              placeholder="bairro dos ..."
              required
            />
          </div>
          <div class="col-6">
            <label for="inputAddress" class="form-label">Rua</label>
            <input
              type="text"
              class="form-control"
              id="inputAddress"
              placeholder="rua parque das ..."
              required
            />
          </div>
          <div class="col-md-4">
            <label for="inputcomplemento" class="form-label">Complemento</label>
            <input
              type="text"
              class="form-control"
              id="inputcomplemento"
              required
            />
          </div>
          <div class="col-md-2">
            <label for="inputnumero" class="form-label">Numero</label>
            <input
              type="number"
              class="form-control"
              id="inputnumero"
              required
            />
          </div>
          <div class="col-12">
            <div class="form-check">
              <input
                class="form-check-input"
                type="checkbox"
                value=""
                id="invalidCheck"
                required
              />
              <label class="form-check-label" for="invalidCheck">
                Sou maior de 18 anos!
              </label>
              <div class="invalid-feedback">
                Você precis ser maior de 18 anos!
              </div>
            </div>
          </div>
          <div class="col-12 bootom-div">
            <button class="btn btn-primary" type="submit">Enviar</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.content {
  margin-bottom: 13rem;
}
.content .container .bootom-div {
  margin-bottom: 10px;
}
.content .container form {
  margin-bottom: 50px;
}
.content .container form input:focus {
  box-shadow: 0 0 0 0;
  outline: 0;
  border-color: #ff9b2d;
}
.content .container form select:focus {
  box-shadow: 0 0 0 0;
  outline: 0;
  border-color: #ff9b2d;
}
</style>