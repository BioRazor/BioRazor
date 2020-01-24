<template>
  <div>
    <b-card no-body>
      <b-tabs card fill>
        <b-tab title="Servicios" active>
          <b-card-text>
            <b-row>
              <b-col>
                <b-card
                  title="Soporte de Red"
                  img-src="https://picsum.photos/600/300/?image=25"
                  img-alt="Image"
                  img-top
                  tag="article"
                  style="max-width: 20rem;"
                  class="mb-2"
                >
                  <b-card-text>
                    Implementación y mantenimiento de
                    <b>redes estructuradas</b>, configuracion y mantenimiento de
                    equipos <b>Mikrotik</b>.
                  </b-card-text>

                  <b-button href="#" variant="primary">Go somewhere</b-button>
                </b-card>
              </b-col>
              <b-col>
                <b-card
                  title="Soporte de TI"
                  img-src="https://picsum.photos/600/300/?image=25"
                  img-alt="Image"
                  img-top
                  tag="article"
                  style="max-width: 20rem;"
                  class="mb-2"
                >
                  <b-card-text>
                    <p>
                      Configuración y mantenimiento de equipos informaticos,
                      PC's, Servidores, Biometricos, Central Telefónica 3CX,
                      entre otros.
                    </p>
                    <p>
                      Implementación y mantenimiento de software, Windows
                      Server, Office, Antivirus.
                    </p>
                  </b-card-text>

                  <b-button href="#" variant="primary">Go somewhere</b-button>
                </b-card>
              </b-col>
              <b-col>
                <b-card
                  title="Desarrollo Web App"
                  img-src="https://picsum.photos/600/300/?image=25"
                  img-alt="Image"
                  img-top
                  tag="article"
                  style="max-width: 20rem;"
                  class="mb-2"
                >
                  <b-card-text>
                    <p>
                      Desarrollo de Aplicaciones web a medida. Experiencia con
                      Wix y manejo de dominios, hosting y CPanel.
                    </p>
                    <p>
                      Experiencia con Framworks Vue.js y DjangoREST. Javascript
                      y Python.
                    </p>
                  </b-card-text>

                  <b-button href="#" variant="primary">Go somewhere</b-button>
                </b-card>
              </b-col>
            </b-row>
          </b-card-text>
        </b-tab>
        <b-tab title="Experiencia">
          <b-card-text>
            <div>
              <b-card
                title="Gerencia"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Centrado en el uso eficiente de la tecnología y el liderazgo
                  de equipos. Aplicando la tecnología a la Inteligencia de
                  Negocios.
                </b-card-text>

                <b-button href="#" variant="primary">Go somewhere</b-button>
              </b-card>
            </div>
          </b-card-text>
        </b-tab>
        <b-tab title="Blog">
          <b-card-text>Tab contents 2</b-card-text>
        </b-tab>
      </b-tabs>
    </b-card>
  </div>
</template>
<script>
export default {
  name: "ContentTabs"
};
</script>
