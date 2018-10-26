<template>
  <div id="app" class="container">
    <div class="col-md-6">
      <h1>Formulario</h1>
      <form>
    <div class="form-group">
      <label for="correo">Nombre</label>
      <input type="text" class="form-control" placeholder="Nombre">
    </div>
    <div class="form-group">
      <label for="correo">Correo Electrónico</label>
      <input type="email" class="form-control" placeholder="Correo Electrónico">
    </div>
    <div class="form-group">
      <label for="clave">Contraseña</label>
      <input type="password" class="form-control" placeholder="Contraseña">
    </div>
    <div class="form-group">
      <label for="clave">Edad</label>
      <input type="text" class="form-control" placeholder="Edad">
    </div>
    <div class="form-group">
      <label for="pais">País</label>
      <select class="form-control">
        <option ></option>
      </select>
    </div>

    <div class="form-group">
      <label for="mensaje">Mensaje</label>
      <textarea class="form-control" rows="3"
                ></textarea>
    </div>

    <fieldset class="form-group">
      <legend>Genero</legend>
      <div class="form-check">
        <label class="form-check-label">
          <input type="radio" class="form-check-input" name="optionsRadios"
                value="hombre" checked >
          Hombre
        </label>
      </div>
      <div class="form-check">
      <label class="form-check-label">
          <input type="radio" class="form-check-input" name="optionsRadios"
                value="mujer" >
          Mujer
        </label>
      </div>

      </fieldset>
      <div class="form-check">
        <label class="form-check-label">
          <input type="checkbox" class="form-check-input" value="acepto">
          Acepto las condiciones
        </label>
      </div>
      <div class="form-check">
        <label class="form-check-label">
          <input type="checkbox" class="form-check-input" value="newsletter">
          Recibir la newsletter
        </label>
      </div>
      <button type="submit" class="btn btn-primary">Enviar</button>
    </form>
    </div>
    <div class="resultados col-md-6" >
      <h1>Resultados</h1>
      <p><strong>Nombre: </strong></p>
      <p><strong>Correo Electrónico: </strong></p>
      <p><strong>Contraseña: </strong></p>
      <p><strong>Edad: </strong></p>
      <p><strong>País: </strong></p>
      <p class="mensaje"><strong>Mensaje: </strong></p>
      <p><strong>Genero: </strong></p>
      <p><strong>Condiciones: </strong></p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>
<style>
.mensaje{
  white-space: pre;
}
</style>
