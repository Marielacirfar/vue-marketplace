<script setup>
defineProps({
  title: {
    type: String,
    required: false
  },
  description: {
    type: String,
    required: false
  },
  imageUrl: {
    type: String,
    required: false
  },
  factoryUrl: {
    type: String,
    required: false
  },
  types: {
    type: Object,
    required: false
  }
})
</script>

<template>
  <div class="card" style="width: 1000px">
    <div class="card-body d-flex">
      <div class="row">
        <div class="col-2" id="smallImage">
          <img
            src="https://ar-media.hptiendaenlinea.com/catalog/product/8/V/8VW01LA-1_T1615590539.png"
            alt=""
            id="thumbnail"
          />
          <img
            src="https://ar-media.hptiendaenlinea.com/catalog/product/8/V/8VW01LA-1_T1615590539.png"
            alt=""
            id="thumbnail"
          />
          <img
            src="https://ar-media.hptiendaenlinea.com/catalog/product/8/V/8VW01LA-1_T1615590539.png"
            alt=""
            id="thumbnail"
          />
          <img
            src="https://ar-media.hptiendaenlinea.com/catalog/product/8/V/8VW01LA-1_T1615590539.png"
            alt=""
            id="thumbnail"
          />
        </div>
        <div class="col-4 text-center p-2">
          <div class="d-flex justify-content-center align-items-center">
            <img
              src="https://ar-media.hptiendaenlinea.com/catalog/product/8/V/8VW01LA-1_T1615590539.png"
              alt=""
              style="width: 200px; height: 200px"
            />
          </div>
        </div>
        <div class="col-3" style="padding-left: 6px">
          <p>Nuevo | +500 vendidos</p>
          <h2>Notebook HP 14-dq2024la</h2>
          <p>Computadora HP orientado para gama media. Procesador Intel® Core™ i3 de 11.ª generación.  Windows 10 Home 64.  Unidad de estado sólido PCIe® NVMe™ M.2 de 256 GB . Pantalla de 14 pulgadas.</p>
          <strong>Variantes:</strong>
          <ul>
            <li>Variante 1 <strong>$95000</strong></li>
              <li>Variante 2 <strong>$135000</strong></li>
          </ul>
        </div>
        <div class="col-3">
          <div class="card">
            <h1>Producto</h1>
            <h2>Descripcion</h2>
            <ul>
              <li>Variante 1</li>
              <li>Variante 2</li>
            </ul>
            <button type="submit">Comprar o morir</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
#thumbnail {
  width: 100px;
  height: 100px;
  margin: 8px;
  padding: 12px;
  border: solid 1px rgb(145, 145, 145);
  border-radius: 12px;
}
</style>
