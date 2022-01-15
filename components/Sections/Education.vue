<template>
  <section class="bg-[#141414]" id="formacao">
    <div
      class="
        max-w-7xl
        mx-auto
        grid grid-cols-1
        md:grid-cols-2
        gap-10
        px-6
        py-[60px]
      "
    >
      <h1
        class="
          text-white
          md:text-black md:max-w-[5ch]
          leading-none
          break-all
          uppercase
          font-bold
          text-4xl
          md:text-9xl
        "
      >
        Formação
      </h1>
      <div>
        <p
          class="
            text-2xl
            leading-[1.33]
            max-w-[40ch]
            mb-[60px]
            text-[#a3a3a3]
            font-medium
          "
        >
          Minha mais recente experiência acadêmica foi o
          <strong class="text-white">Curso Técnico</strong> em TI. Além disso,
          me matenho sempre atualizado com cursos intensivos online
        </p>

        <ul class="flex flex-wrap gap-5 mb-16 text-white">
          <li
            class="
              bg-black
              p-5
              rounded
              flex flex-col flex-1
              border-l-4 border-sky-600
            "
          >
            <span class="text-sm uppercase text-[#a3a3a3] mb-3">Técnico</span>
            <h3 class="text-lg leading-[1.4] mb-10 flex-1">
              Curso Técnico em Informática
            </h3>
            <p class="text-lg text-[#a3a3a3]">
              Leiaut Cariele
              <span class="text-sm block text-right">2017 - 2021 🎓</span>
            </p>
          </li>
          <li
            class="
              bg-black
              p-5
              rounded
              flex flex-col flex-1
              border-l-4 border-sky-600
            "
          >
            <span class="text-sm uppercase text-[#a3a3a3] mb-3">Técnologo</span>
            <h3 class="text-lg leading-[1.4] mb-10 flex-1">
              CST - Analise e Desenvolvimento de Sistemas
            </h3>
            <p class="text-lg text-[#a3a3a3]">
              Descomplica
              <span class="text-sm block text-right">2022 - 2024</span>
            </p>
          </li>
        </ul>

        <div>
          <div>
            <h3
              class="
                font-semibold
                text-sm text-[#8f8f8f]
                leading-[1.4]
                uppercase
                mb-8
                relative
                cap
              "
            >
              Cursos intensivos
            </h3>
            <ul>
              <li class="flex justify-between text-lg text-white mb-5">
                Web Design Completo <span class="text-[#8f8f8f]">44h</span>
              </li>
            </ul>
          </div>
          <div>
            <h3
              class="
                font-semibold
                text-sm text-[#8f8f8f]
                leading-[1.4]
                uppercase
                mb-8
                relative
                idioma
              "
            >
              Idiomas
            </h3>
            <ul>
              <li class="text-lg text-white mb-5">
                Inglês / <span class="text-[#8f8f8f]">Básico</span>
              </li>
              <li class="text-lg text-white mb-5">
                Francês / <span class="text-[#8f8f8f]">Básico</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="postcss" scoped>
.cap::before,
.idioma::before {
  @apply md:absolute mb-2;
  content: "";
  display: block;
  top: -4px;
  left: -36px;
  width: 24px;
  height: 24px;
}

.cap::before {
  background: url("~/static/cap.svg") no-repeat center center;
}

.idioma::before {
  background: url("~/static/idiomas.svg") no-repeat center center;
}
</style>