<template>
  <div class="p-4 w-20">
    <div class="dropdown inline-block relative w-6">
      <button class="py-2 px-4 rounded">
        <p
          class="
            bg-gray-500
            p-0.1
            mr-auto
            ml-auto
            m-1
            rounded-xl
            w-2
            h-2
            content-center
          "
        >
          <br />
        </p>
        <p
          class="
            bg-gray-500
            p-0.1
            mr-auto
            ml-auto
            m-1
            rounded-xl
            w-2
            h-2
            content-center
          "
        >
          <br />
        </p>
        <p
          class="
            bg-gray-500
            p-0.1
            mr-auto
            ml-auto
            m-1
            rounded-xl
            w-2
            h-2
            content-center
          "
        >
          <br />
        </p>
      </button>

      <ul
        class="
          dropdown-menu
          absolute
          hidden
          text-gray-700
          pt-1
          transform
          translate-x-8
          -translate-y-5
        "
      >
        <li class="">
          <a
            class="rounded-t bg-gray-200 hover:bg-gray-400 py-2 px-4 block"
            href="#"
            >Re-Run</a
          >
        </li>
        <li class="">
          <a class="bg-gray-200 hover:bg-gray-400 py-2 px-4 block" href="#"
            >Job Log</a
          >
        </li>
        <li class="">
          <a
            class="rounded-b bg-gray-200 hover:bg-gray-400 py-2 px-4 block"
            href="#"
            >Stop</a
          >
        </li>
        <li class="">
          <a
            class="
              rounded-b
              text-red-500
              bg-gray-200
              hover:bg-gray-400
              py-2
              px-4
              block
            "
            href="#"
            ><b>Delete</b></a
          >
        </li>
      </ul>
    </div>
  </div>
</template>

<style>
.dropdown:hover .dropdown-menu {
  display: block;
  width: 180px;
}
</style>
