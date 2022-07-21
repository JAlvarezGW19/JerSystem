<script setup>
</script>

<template>
<div class="filtrodeBusqueda">
    <h4 class="titulo-filtro">
            <span class="text-muted"> &nbsp Filtro de búsqueda</span>
          </h4>
          <form action="#" method="POST">
          <ul class="list-group mb-3">

            <li class="list-group-item">
              <div>
                <h5 class="my-0">Rango de precio</h5> <br/>

                  <div class="input-group"> 
                    <input type="number" class="form-control" name="EdadMin" placeholder="Min"> 
                    <input type="number" class="form-control" name="EdadMax" placeholder="Max"> 
                  </div>
              </div>
            </li>

            <li class="list-group-item">
              <div>
                <h5 class="my-0">Condición</h5> <br/>

                  <div class="custom-control custom-checkbox">
                    <input type="checkbox" class="custom-control-input" name="condicion[]" id="Nuevo" value="Nuevo"> 
                      <label class="custom-control-label" for="Nuevo"> <h7> Nuevo </h7> <br/></label>
                  </div>

                  <div class="custom-control custom-checkbox">
                    <input type="checkbox" class="custom-control-input" name="condicion[]" id="Usado" value="Usado"> 
                      <label class="custom-control-label" for="Usado"> <h7> Usado </h7> <br/> </label> 
                  </div>
              </div>
            </li>

            <li class="list-group-item d-flex justify-content-between lh-condensed">
              <button type="submit" name="filtrar" class="btn btn-principal">Filtrar</button>
            </li>

          </ul>
          </form>
</div>
</template>