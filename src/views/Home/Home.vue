<template>
  <div>
    <div class="">
      <h1 class="text-4xl mx-auto flex justify-center w-[100]">Products</h1>
    </div>

    <div
      class="w-[90%] border rounded-md border-gray-400 justify-center mx-auto mt-4"
    >
      <div class="w-[100%] bg-gray-400 p-[10px] border border-gray-600">
        <h1>Add a new products</h1>
      </div>
      <div class="flex mx-auto justify-between items-center mb-[3] w-[90%]">
        <div class="">
          <label for="">ID</label>
          <input type="text" class="mx-4 border border-gray-600 rounded-md" />
        </div>
        <div>
          <label for="">Name</label>
          <input type="text" class="mx-4 border border-gray-600 rounded-md" />
        </div>
        <div>
          <label for="">Price</label>
          <input type="text" class="mx-4 border border-gray-600 rounded-md" />
        </div>
        <div class="bg-sky-500 border rounded-md my-2 hover:bg-sky-600">
          <button class="p-1 tex-white text-[16px] mx-2">Add</button>
        </div>
      </div>
    </div>

    <div class="w-[90%] mx-auto mt-5 border border-gray-400 rounded-md">
      <div class="bg-gray-400 border rounded-md w-[100%] border-gray-800">
        <h1 class="p-3">Product List</h1>
      </div>

      <div class="mt-[20px] p-3">
        <div class="h-[2px] bg-gray-400 mb-2"></div>
        <div class="flex justify-between">
          <div class="w-[230px]">
            <h1 class="">Product ID</h1>
          </div>
          <div class="w-[230px]">
            <h1 class="">Product Name</h1>
          </div>
          <div class="w-[230px]">
            <h1 class="">Product Price</h1>
          </div>
          <div class="w-[230px]">
            <h1 class="">Product Action</h1>
          </div>
        </div>
        <div class="h-[2px] bg-gray-400 mt-1"></div>
        <div class="flex justify-between mt-3">
          <div class="w-[230px]">
            <h1 class="">1</h1>
          </div>
          <div class="w-[230px]">
            <h1 class="">fjewk</h1>
          </div>
          <div class="w-[230px]">
            <h1 class="">456</h1>
          </div>
          <div class="w-[230px] ">
              <a href="#" class="mx-2 text-[18px]"><i class="bx bxs-trash"></i></a>
              <a href="#" class="mx-2 text-[18px]"><i class="bx bxs-edit-alt"></i></a>
            <a href="#" class="mx-2 text-[18px]"><i class='bx bx-show'></i></a>
          </div>
        </div>
        <div class="h-[2px] bg-gray-400 mt-1"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style></style>
